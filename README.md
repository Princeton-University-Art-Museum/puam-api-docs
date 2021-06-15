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

* [Objects](https://github.com/princeton-university-art-museum/puam-api-docs/blob/master/objects.md)
* [Makers](https://github.com/princeton-university-art-museum/puam-api-docs/blob/master/makers.md)
* [Packages](https://github.com/princeton-university-art-museum/puam-api-docs/blob/master/packages.md)
* [Search](https://github.com/princeton-university-art-museum/puam-api-docs/blob/master/search.md)

## Usage Notes

The API is generally designed to provide programmatic access to the Museum's collections data for applications that require regular updates and/or the ability to dynamically query and filter the data via the endpoints provided. 

For applications and activities such as data visualization and machine learning projects that do not require such a dynamic data connection, we also offer a set of downloadable static JSON files that represent the entirety of the collections and are identical to the responses provided by the API for the various data types. These downloadable datasets are refreshed on a weekly basis.

* [Objects](https://static.artmuseum.princeton.edu/collection-data-sets/objects.zip)
* [Makers](https://static.artmuseum.princeton.edu/collection-data-sets/makers.zip)
* [Packages](https://static.artmuseum.princeton.edu/collection-data-sets/packages.zip)

## Feedback and Questions

If you have a feature request or find a bug, [please open a GitHub issue](https://github.com/princeton-university-art-museum/puam-api-docs/issues/new).

For more general inquiries regarding the API, [e-mail is preferred](mailto:dbrennan@princeton.edu).   

Finally, if you're building something interesting with the API, please reach out, we'd love to hear about it.

## Responses and data format

All data is in [JSON](http://json.org) format. Here is a typical response, truncated for length:  

```shell
https://data.artmuseum.princeton.edu/objects/32221
```

```json
{
  "displayperiod": "Late Classic",
  "displayculture": "Maya ('Codex' style)",
  "classification": "Ceramic",
  "daterange": "A.D. 500-1000",
  "related": [],
  "texts": [
    {
      "remarks": null,
      "textentryhtml": "\r\nThe masterful calligraphic painting on the Princeton Vase is the finest known example of Maya \"codex style\" ceramic art. Graceful, sure lines painted on a cream slip present a theatrically composed mythological scene, while subtle visual devices encourage the viewer to turn the drinking vessel, adding a temporal unfolding to the visual experience. On one side (seen here), an old, toothless underworld god sits on a throne that is placed within a conventionalized depiction of a palace structure, represented by the pier behind him and what is likely a cornice above. The cornice is adorned with two jawless jaguars framing a frontal shark face. Curtains, which&nbsp;were used as doors among the ancient Maya, have been furled and tied to reveal the old lord seated within. This deity, known among scholars as God L, wears his characteristic open-weave brocaded shawl and broad-brimmed hat bedecked with owl feathers and a stuffed owl with wings outstretched. In addition to ruling Xibalba, the Maya underworld, God L was the patron deity of tobacco and merchants. Five elegant female figures — daughters or concubines — surround him. Each wears a loose, flowing sarong, decorated with batik-like dyed patterns rendered in soft brown wash, and jewelry at the ears, neck, and wrists. One of the women behind God L pours chocolate, frothing the bitter delicacy from a vessel of the same form as the Princeton Vase. A rabbit scribe, who may be spying on God L, sits below, recording the actions of the scene in a book with jaguar-pelt covers. God L delicately ties a bracelet on the woman before him, while another woman taps her foot to draw her attention—and the viewer’s—to the gruesome scene at left, in which two men wearing elaborate masks and wielding axes decapitate a bound and stripped figure. The victim’s serpent-umbilicus curls out to bite one of the executioners. The scene closely parallels a portion of the <I>Popol Vuh</I>, a sixteenth-century K’iche’ Maya mythological narrative wherein the Hero Twins trick the lords of the underworld into requesting their own decapitations. As is common in mythological narratives throughout the Americas, these heroes win the day not through Herculean feats of brute strength, but through cunning, and often humorous, trickery. The formulaic texts at the upper edge of the Princeton Vase serve to consecrate the vessel, to specify that it was intended for drinking \"maize tree\" chocolate, and to designate its owner, a lord named <I>Muwaan K’uk’</I>. The vase would have been used in courtly feasts similar to the scene depicted. </P></SPAN>",
      "textpurpose": "Handbook Entry",
      "texttype": "Online"
    }
  ],
  "accessionyear": "1975-01-01",
  "titles": [
    {
      "titletype": "Primary Title",
      "displayorder": 1,
      "title": "The Princeton Vase"
    }
  ],
  "datecomputed": 710,
  "campuscollections": "false",
  "catalograisonne": "K0511\r\nMS1404\r\n\r\n",
  "nowebuse": "False",
  "makers": [],
  "objectnumber": "y1975-17",
  "hasimage": "true",
  "bibliography": [
    {
      "date": 2007,
      "citation": "<i>Princeton University Art Museum: Handbook of the Collection</i> (New Haven, CT: Yale University Press, 2007)., pp. 106, pp. 124–125 (illus.)",
      "boilertext": "<i>Princeton University Art Museum: Handbook of the Collection</i> (New Haven, CT: Yale University Press, 2007).",
      "id": 474,
      "uri": "http://www.worldcat.org/oclc/191864564"
    },
    {
      "date": 2013,
      "citation": "<i>Princeton University Art Museum: Handbook of the Collections </i>(Princeton, NJ: Princeton University Art Museum,&nbsp;2013)., pp. 128–129 (illus.)",
      "boilertext": "<i>Princeton University Art Museum: Handbook of the Collections </i>(Princeton, NJ: Princeton University Art Museum,&nbsp;2013).",
      "id": 1994,
      "uri": "http://www.worldcat.org/oclc/865020505"
    }
  ],
  "objectid": 32221,
  "media": [
    {
      "mediatypeid": 1,
      "restrictions": null,
      "uri": "https://puam-loris.aws.princeton.edu/loris/y1975-17.jp2",
      "rank": 3,
      "caption": "Bruce White Photo",
      "isprimary": 1,
      "id": 49033
    },
    {
      "mediatypeid": 1,
      "restrictions": null,
      "uri": "https://puam-loris.aws.princeton.edu/loris/y1975-17_ROL.jp2",
      "rank": 4,
      "caption": "PUAM Photo",
      "isprimary": 0,
      "id": 221600
    }
  ],
  "displaymaker": null,
  "periodterms": [
    {
      "id": 2035671,
      "period": "Late Classic"
    }
  ],
  "cultureterms": [
    {
      "culture": "Maya",
      "id": 2036114
    }
  ],
  "department": "Art of the Ancient Americas",
  "cultures": [
    {
      "displayculture": "Maya ('Codex' style)",
      "enddate": 0,
      "alphasort": "Maya",
      "begindate": 0,
      "culture": "Maya",
      "displaydate": null,
      "id": 12497
    }
  ],
  "geography": [
    {
      "city": null,
      "code": "Place made",
      "locale": "Nakbé region",
      "country": "Guatemala",
      "region": "Mirador Basin",
      "geoname": "http://www.geonames.org/maps/wikipedia_17.6828_-89.8331.html",
      "subcontinent": "Mesoamerica",
      "locus": null,
      "county": null,
      "excavation": null,
      "state": "Petén",
      "subregion": "Central lowlands",
      "displaygeography": "Place made: North America, Guatemala, Petén, Mirador Basin, Nakbé region",
      "location": {
        "lat": "",
        "lon": ""
      },
      "river": null,
      "continent": "North America"
    }
  ],
  "medium": "Ceramic with red, cream, and black slip, with remnants of painted stucco",
  "terms": [
    {
      "term": "Late Classic",
      "aatid": 300016986,
      "id": 2035671,
      "termtype": "Period / Style"
    },
    {
      "term": "Maya",
      "aatid": null,
      "id": 2036114,
      "termtype": "Culture"
    },
    {
      "term": "ceramics",
      "aatid": 300151343,
      "id": 2049167,
      "termtype": "Classification"
    },
    {
      "term": "figures (representations)",
      "aatid": 300189808,
      "id": 2055657,
      "termtype": "Subject"
    }
  ],
  "sortnumber": "1975   17y",
  "creditline": "Museum purchase, gift of the Hans A. Widenmann, Class of 1918, and Dorothy Widenmann Foundation",
  "primaryimage": [
    "https://puam-loris.aws.princeton.edu/loris/y1975-17.jp2"
  ],
  "creditlinerepro": "",
  "onview": 1,
  "dateend": 750,
  "dimensionelements": [
    {
      "units": "centimeters",
      "type": "Height",
      "dimension": "21.50",
      "element": "Overall"
    },
    {
      "units": "centimeters",
      "type": "diam.",
      "dimension": "16.60",
      "element": "Overall"
    }
  ],
  "update_count": 106,
  "displaytitle": "The Princeton Vase",
  "datebegin": 670,
  "packages": [
    {
      "name": "web_highlights",
      "packageid": 167646
    },
    {
      "name": "ART100",
      "packageid": 179355
    },
    {
      "name": "CRS_ART100_2017_09-25",
      "packageid": 118480
    }
  ],
  "dimensions": "h. 21.5 cm., diam. 16.6 cm. (8 7/16 x 6 9/16 in.)",
  "inscribed": null,
  "restrictions": null,
  "classifications": [
    {
      "id": 2049167,
      "classification": "ceramics"
    },
    {
      "id": 2073530,
      "classification": "vases"
    },
    {
      "id": 2076085,
      "classification": "drinking vessels"
    }
  ],
  "signed": null,
  "displaydate": "A.D. 670–750",
  "newaccession": 0,
  "published_date": "2018-10-08",
  "secondaryobjectnumber": null,
  "markings": null,
  "periods": [
    {
      "displayperiod": "Late Classic",
      "enddate": 900,
      "alphasort": "Classic",
      "begindate": 200,
      "period": "Classic",
      "displaydate": null,
      "id": 12494
    }
  ]
}
```


