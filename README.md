# Princeton University Art Museum API Documentation

The Princeton University Art Museum API is a REST-style service designed to provide developer access to data about the Museum and its collections.

## Access

All requests to the API begin with:

```shell
https://data.artmuseum.princeton.edu
```

No authentication is currently required to access the API, however this may change in future versions.

## Available Resources

Currently three endpoints providing access to three primary resource types from the Princeton University Art Museum are available via this API, as well as a full-text search endpoint:

- [Objects](https://github.com/princeton-university-art-museum/puam-api-docs/blob/master/objects.md)
- [Makers](https://github.com/princeton-university-art-museum/puam-api-docs/blob/master/makers.md)
- [Packages](https://github.com/princeton-university-art-museum/puam-api-docs/blob/master/packages.md)
- [Search](https://github.com/princeton-university-art-museum/puam-api-docs/blob/master/search.md)

## Usage Notes

The API is generally designed to provide programmatic access to the Museum's collections data for applications that require regular updates and/or the ability to dynamically query and filter the data via the endpoints provided.

For applications and activities such as data visualization and machine learning projects that do not require such a dynamic data connection, we also offer a set of downloadable static JSON files that represent the entirety of the collections and are identical to the responses provided by the API for the various data types. These downloadable datasets are refreshed on a weekly basis.

- [Objects](https://static.artmuseum.princeton.edu/collection-data-sets/objects.zip)
- [Makers](https://static.artmuseum.princeton.edu/collection-data-sets/makers.zip)
- [Packages](https://static.artmuseum.princeton.edu/collection-data-sets/packages.zip)

## Feedback and Questions

If you have a feature request or find a bug, [please open a GitHub issue](https://github.com/princeton-university-art-museum/puam-api-docs/issues/new).

For more general inquiries regarding the API, [e-mail is preferred](mailto:jg4301@princeton.edu).

Finally, if you're building something interesting with the API, please reach out, we'd love to hear about it.

## Responses and data format

All data is in [JSON](http://json.org) format. Here is a typical response, truncated for length:

```shell
https://data.artmuseum.princeton.edu/objects/32221
```

```json
{
  "type": "artobject",
  "objectid": 32221,
  "objectnumber": "y1975-17",
  "sortnumber": "1975   17y",
  "displaytitle": "Uk’ib (drinking cup) depicting a mythological scene",
  "department": "Art of the Ancient Americas",
  "classification": "Ceramic",
  "datebegin": 670,
  "dateend": 750,
  "datecomputed": 710,
  "daterange": "A.D. 500-1000",
  "displaydate": "670–750",
  "medium": "Ceramic with red, cream, and black slip, and remnants of painted stucco",
  "dimensions": "h. 21.5 cm., diam. 16.6 cm. (8 7/16 x 6 9/16 in.)",
  "dimensionsproposed": "",
  "creditline": "Museum purchase, gift of the Hans A. Widenmann, Class of 1918, and Dorothy Widenmann Foundation",
  "markings": null,
  "inscribed": null,
  "signed": null,
  "catalograisonne": "K0511\r\nMS1404\r\n\r\n",
  "creditlinerepro": "",
  "restrictions": null,
  "nowebuse": "False",
  "secondaryobjectnumber": null,
  "campuscollections": "false",
  "on_view": true,
  "accessionyear": "1975-01-01",
  "newaccession": 0,
  "titles": [
    {
      "title": "Uk’ib (drinking cup) depicting a mythological scene",
      "titletype": "Primary Title",
      "displayorder": 1
    }
  ],
  "makers": [
    {
      "id": 24043,
      "displayname": "The Princeton Painter",
      "displaydate": null,
      "datebegin": 0,
      "dateend": 0,
      "prefix": null,
      "suffix": "(name vase)",
      "role": "Artist",
      "displaymaker": "The Princeton Painter (name vase)",
      "displayorder": 1
    }
  ],
  "depicted": [],
  "texts": [
    {
      "texttype": "Online",
      "textpurpose": "Provenance",
      "textentryhtml": "<p>\n\tBy April, 1971, Arte Primitivo, Inc. (William Kaplan), New York [1]; 1975, sold to the Princeton University Art Museum.\n</p>\n<p>\n\tNotes:\n\t<br />\n\t[1] According to Robert Sonin archive, Notebook 3, Rolls 208-210. The slides are date-stamped April 1971. Additionally, the work was exhibited in the exhibition The Maya Scribe and His World at the Grolier Club, New York, from April 20 to June 5, 1971, according to installation photographs in the curatorial files.\n</p>",
      "remarks": null
    },
    {
      "texttype": "Online",
      "textpurpose": "Gallery Label",
      "textentryhtml": "<p>With graceful, sure lines painted on a cream ground, this famous Maya chocolate-drinking cup, known as the Princeton Vase, presents a story that stretches around the entire vessel. Subtle visual devices link the primary scenes and encourage the viewer to rotate the vessel, allowing the story to unfold. Here, for example, a young noblewoman taps the foot of the woman in front of her while turning her head in the opposite direction: She bridges two scenes and encourages her companion, as well as the viewer, to shift her attention around the vase. A thin, meandering line connects the mouth of the old man to the hieroglyphic text that records his speech, just above the woman’s head. Frustratingly, surface accretions in this area of the vessel have hindered decipherment of this key piece of textual information.\n</p><p> </p><p>The dramatic scene of human sacrifice on this side of the drinking cup was long thought to depict a scene recorded in the colonial-period K’iche’ Maya manuscript known as the Popol Vuh, in which the Hero Twins disguise themselves and trick the lords of the underworld into requesting their own decapitations. The elaborately costumed actors do not, however, share features with the Hero Twins as they normally appear in this era. Their victim may be a supernatural scribe, perhaps one whose place in the royal court of God L, the patron deity of trade and tobacco, has been taken by the rabbit scribe portrayed on the other side of the vessel. Some other Maya vase paintings depict moments in the humorous humiliation of God L, in which the rabbit is a key actor on behalf of the Sky God and the Moon Goddess.\n</p><p> </p><p>A woman standing with her head bent in concentration holds a vessel similar in size and shape to the uk’ib on which it is painted. A stream of liquid chocolate pours down from it into another similar vessel, now barely visible. In this method of preparation, chocolate was frothed for drinking in a vessel like this one, as specified by one of the hieroglyphic texts on the vessel. The vertical pier represents the rear wall of a palace structure, marking the boundaries of the overall composition on this vase. This self-referential\n\nvignette, which shows the vessel in use at the end of the narrative, functions as a sort of coda.\n </p><p> </p><p>On this side of the drinking cup, curtains, used as doors by the ancient Maya, have been drawn to reveal an old, toothless underworld god. He sits on a throne within a palace, represented by the pier behind him and a cornice above. This deity, known as God L, wears his characteristic brocaded shawl and a broad-brimmed hat bedecked with owl feathers and a taxidermy owl. In addition to ruling the Maya underworld, God L was the patron deity of tobacco and merchants. Five elegant female figures—possibly concubines—surround him. Each wears a loose, flowing sarong and earrings, necklaces, and wristlets. A rabbit scribe, who might be spying on God L, sits below, writing in a book. God L ties a wristlet on the woman before him, but her attention is about to shift as another woman taps on her heel.\n </p>",
      "remarks": "AAA1_20_CLA_FA_9_17_25.pdf - Day 1 installation"
    }
  ],
  "media": [
    {
      "id": 49033,
      "uri": "https://media.artmuseum.princeton.edu/iiif/3/collection/y1975-17",
      "isprimary": 1,
      "rank": 3,
      "mediatypeid": 1,
      "mediaviewtype": "(not assigned)",
      "restrictions": null,
      "caption": "Bruce White Photo"
    },
    {
      "id": 7485,
      "uri": "https://media.artmuseum.princeton.edu/iiif/3/collection/y1975-17_1",
      "isprimary": 0,
      "rank": 6,
      "mediatypeid": 1,
      "mediaviewtype": "(not assigned)",
      "restrictions": null,
      "caption": "Luna Digitization Project"
    },
    {
      "id": 7486,
      "uri": "https://media.artmuseum.princeton.edu/iiif/3/collection/y1975-17_2",
      "isprimary": 0,
      "rank": 8,
      "mediatypeid": 1,
      "mediaviewtype": "(not assigned)",
      "restrictions": null,
      "caption": "Luna Digitization Project"
    },
    ...truncated
  ],
  "hasimage": "true",
  "bibliography": [
    {
      "boilertext": "Matthew Looper,&nbsp;<em>The Beast Between: Deer in Maya Art and Culture</em> (Austin: University of Texas Press, 2019)<br>",
      "citation": "Matthew Looper,&nbsp;<em>The Beast Between: Deer in Maya Art and Culture</em> (Austin: University of Texas Press, 2019)<br>, Fig. 1.1 (illus.)",
      "date": 2019,
      "id": 9695,
      "uri": "https://search.worldcat.org/title/1110583597"
    },
    {
      "boilertext": "\"Acquisitions of the Art Museum 1975,\" <em>Record of the Art Museum, Princeton University,</em> 35, no. 1 (1976): p. 22-31.",
      "citation": "\"Acquisitions of the Art Museum 1975,\" <em>Record of the Art Museum, Princeton University,</em> 35, no. 1 (1976): p. 22-31., p. 31 (illus.)",
      "date": 1976,
      "id": 3366,
      "uri": "https://www.jstor.org/stable/3774452"
    },
    {
      "boilertext": "Alexandre Tokovinine and Dmitri Beliaev, “People of the Road: Traders and Travelers in Ancient Maya Words and Images,” in <EM>Merchants, Markets, and Exchange in the Pre-Columbian World</EM>, Kenneth G. Hirth and Joanne Pillsbury, eds., (Washington D.C.: Dumbarton Oaks, 2013),&nbsp;pp. 169–200 ",
      "citation": "Alexandre Tokovinine and Dmitri Beliaev, “People of the Road: Traders and Travelers in Ancient Maya Words and Images,” in <EM>Merchants, Markets, and Exchange in the Pre-Columbian World</EM>, Kenneth G. Hirth and Joanne Pillsbury, eds., (Washington D.C.: Dumbarton Oaks, 2013),&nbsp;pp. 169–200 , p. 187",
      "date": 2013,
      "id": 6723,
      "uri": "https://search.worldcat.org/title/795909454"
    },
    ...truncated
  ],
  "exhibitions": [
    {
      "exhibitionid": 1693,
      "citation": "The Maya Scribe and His World (April 20–June 5, 1971)",
      "isvirtual": true,
      "begindate": "1971-04-20",
      "enddate": "1971-06-05",
      "uri": "https://artmuseum.princeton.edu/art/exhibitions/1693"
    },
    {
      "exhibitionid": 1687,
      "citation": "Lords of the Underworld (Saturday, March 04, 1978 - Sunday, June 18, 1978)",
      "isvirtual": true,
      "begindate": "1978-03-04",
      "enddate": "1978-06-18",
      "uri": "https://artmuseum.princeton.edu/art/exhibitions/1687"
    },
    {
      "exhibitionid": 1680,
      "citation": "The Blood of Kings: Dynasty and Ritual in Maya Art (May 17 - December 14, 1986)",
      "isvirtual": true,
      "begindate": "1986-05-17",
      "enddate": "1986-12-14",
      "uri": "https://artmuseum.princeton.edu/art/exhibitions/1680"
    },
    {
      "exhibitionid": 961,
      "citation": "An Educated Eye: The Princeton University Art Museum Collection (Friday, February 22, 2008 - Sunday, June 15, 2008)",
      "isvirtual": true,
      "begindate": "2008-02-22",
      "enddate": "2008-06-15",
      "uri": "https://artmuseum.princeton.edu/art/exhibitions/961"
    },
    {
      "exhibitionid": 559,
      "citation": "Courtly Art of the Ancient Maya (April 4, 2004–January 2, 2005)",
      "isvirtual": true,
      "begindate": "2004-04-04",
      "enddate": "2005-01-02",
      "uri": "https://artmuseum.princeton.edu/art/exhibitions/559"
    }
  ],
  "geography": [
    {
      "displaygeography": "Place made: North America, Guatemala, Petén, Mirador Basin, Nakbé region",
      "code": "Place made",
      "continent": "North America",
      "subcontinent": "Mesoamerica",
      "country": "Guatemala",
      "region": "Mirador Basin",
      "state": "Petén",
      "city": null,
      "county": null,
      "subregion": "Central lowlands",
      "locale": "Nakbé region",
      "locus": null,
      "river": null,
      "excavation": null,
      "geoname": "http://www.geonames.org/maps/wikipedia_17.6828_-89.8331.html",
      "location": {
        "lat": "",
        "lon": ""
      }
    },
    {
      "displaygeography": "Place made: North America, Mexico, Campeche, Kaanu’l",
      "code": "Place made",
      "continent": "North America",
      "subcontinent": "Mesoamerican",
      "country": "Mexico",
      "region": null,
      "state": "Campeche",
      "city": null,
      "county": null,
      "subregion": null,
      "locale": "Kaanu’l",
      "locus": null,
      "river": null,
      "excavation": null,
      "geoname": null,
      "location": {
        "lat": "",
        "lon": ""
      }
    }
  ],
  "terms": [
    {
      "id": 2134667,
      "term": "banquets",
      "aatid": 300247614,
      "termtype": "Subject"
    },
    {
      "id": 2035671,
      "term": "Late Classic",
      "aatid": 300016986,
      "termtype": "Period / Style"
    },
    {
      "id": 2092754,
      "term": "scribes",
      "aatid": 300025580,
      "termtype": "Subject"
    },
    ...truncated
  ],
  "classifications": [
    {
      "id": 2076085,
      "classification": "drinking vessels"
    },
    {
      "id": 2073530,
      "classification": "vases"
    },
    {
      "id": 2049167,
      "classification": "ceramics"
    }
  ],
  "cultures": [
    {
      "id": 12497,
      "culture": "Maya",
      "alphasort": "Maya",
      "begindate": 0,
      "enddate": 0,
      "displayculture": "Maya (Codex style)",
      "displaydate": null
    }
  ],
  "cultureterms": [
    {
      "id": 2036114,
      "culture": "Maya"
    }
  ],
  "periods": [
    {
      "id": 24016,
      "period": "Late Classic Period",
      "alphasort": "Classic Period, Late",
      "begindate": 0,
      "enddate": 0,
      "displayperiod": "Late Classic Period",
      "displaydate": null
    }
  ],
  "periodterms": [
    {
      "id": 2035671,
      "period": "Late Classic"
    }
  ],
  "dimensionelements": [
    {
      "element": "Overall",
      "type": "Height",
      "units": "centimeters",
      "dimension": "21.50"
    },
    {
      "element": "Overall",
      "type": "diam.",
      "units": "centimeters",
      "dimension": "16.60"
    }
  ],
  "packages": [
    {
      "packageid": 206417,
      "name": "image_descriptions_top250"
    },
    {
      "packageid": 182962,
      "name": "Tour_WorldHighlights"
    },
    ...truncated
  ],
  "primaryimage": [
    "https://media.artmuseum.princeton.edu/iiif/3/collection/y1975-17"
  ],
  "displaymaker": "The Princeton Painter (name vase)",
  "displayculture": "Maya (Codex style)",
  "displayperiod": "Late Classic Period",
  "caption": "The Princeton Painter (name vase), Maya (Codex style), Late Classic Period, 670–750, Central lowlands, Petén, Mirador Basin, Guatemala, Mesoamerica, Uk’ib (drinking cup) depicting a mythological scene. Ceramic with red, cream, and black slip, and remnants of painted stucco; 21.5 x 16.6 cm. Museum purchase, gift of the Hans A. Widenmann, Class of 1918, and Dorothy Widenmann Foundation (y1975-17)",
  "captionhtml": "The Princeton Painter (name vase), Maya (Codex style), Late Classic Period, 670–750, Central lowlands, Petén, Mirador Basin, Guatemala, Mesoamerica, <i>Uk’ib (drinking cup) depicting a mythological scene</i>. Ceramic with red, cream, and black slip, and remnants of painted stucco; 21.5 x 16.6 cm. Museum purchase, gift of the Hans A. Widenmann, Class of 1918, and Dorothy Widenmann Foundation (y1975-17)",
  "published_date": "2026-01-08 11:24:22.759281",
  "campusart": [
    {
      "campuscollections": "false",
      "campusart": 0,
      "neighborhood": null,
      "lat": null,
      "lon": null
    }
  ],
  "extended_content": true
}
```
