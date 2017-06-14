# Princeton University Art Museum API Documentation

The Princeton University Art Museum API is a REST-style service designed to provide developer access to data about the Museum and its collections.

## Access

All requests to the API begin with:

```shell
http://api.artmuseum.princeton.edu
```

## Responses and data format

All data is in [JSON](http://json.org) format. Here is a typical response:

```json
{
  "exhibitions": [
    {
      "isvirtual": true,
      "exhibitionid": 1086,
      "begindate": "1970-06-10",
      "citation": "Impressionism, Post-Impressionism, Expressionism: The Mr. & Mrs. Henry Pearlman Collection of Works by Cézanne, Van Gogh, Degas, Tolouse-Lautrec, Manet, Modigliani, Soutine, and Others: Wadsworth Atheneum Museum of Art (10 Jun 1970 – ?)",
      "enddate": "1970-10-04"
    },
    {
      "isvirtual": true,
      "exhibitionid": 1087,
      "begindate": "1971-07-13",
      "citation": "Summer Loan 1971: Paintings from New York Collections: Collection of Mr. and Mrs. Henry Pearlman and the Henry and Rose Pearlman Foundation: The Metropolitan Museum of Art (13 Jul 1971 – 7 Sep 1971)",
      "enddate": "1971-09-07"
    },
    {
      "isvirtual": true,
      "exhibitionid": 1098,
      "begindate": "1968-07-03",
      "citation": "New York Collects, 1968: The Metropolitan Museum of Art (3 Jul 1968 – 2 Sep 1968)",
      "enddate": "1968-09-02"
    },
    {
      "isvirtual": true,
      "exhibitionid": 1346,
      "begindate": "1974-05-22",
      "citation": "An Exhibition of Paintings, Watercolors, Sculpture and Drawings from the Collection of Mr. and Mrs. Henry Pearlman and the Henry and Rose Pearlman Foundation: Brooklyn Museum (22 May 1974 – 29 Sep 1974); Princeton University Art Museum (8 Dec 1974 – 14 Ma",
      "enddate": "1974-09-29"
    },
    {
      "isvirtual": true,
      "exhibitionid": 1542,
      "begindate": "1982-06-26",
      "citation": "Paul Cézanne: The Collection of Mr. and Mrs. Henry Pearlman: Fine Arts Museums of San Francisco, California (26 Jun 1982 – 29 Aug 1982)",
      "enddate": "1982-08-29"
    },
    {
      "isvirtual": true,
      "exhibitionid": 1541,
      "begindate": "1986-05-02",
      "citation": "Art of Cézanne from the Henry & Rose Pearlman Foundation: Brooklyn Museum (2 May 1986 – 14 Jul 1986)",
      "enddate": "1986-07-14"
    }
  ],
  "objectid": 25277,
  "texts": [],
  "accessionyear": "",
  "titles": [
    {
      "titletype": "Primary Title",
      "displayorder": 1,
      "title": "Study of Trees"
    }
  ],
  "catalograisonne": "Chappuis 1973: No. 920",
  "makers": [
    {
      "makerid": 6353,
      "displayname": "Paul Cézanne",
      "suffix": null,
      "prefix": null,
      "dateend": 1906,
      "displaydate": "French, 1839–1906",
      "role": "Artist",
      "datebegin": 1839
    }
  ],
  "objectnumber": "L.1988.62.54",
  "hasimage": "true",
  "bibliography": [
    {
      "date": 1973,
      "boilertext": "Adrien Chappuis, <EM>The Drawings of Paul Cézanne:&nbsp;A Catalogue Raisonné</EM> (Greenwich, Conn., 1973)"
    },
    {
      "date": 1974,
      "boilertext": "<I>An Exhibition of Paintings, Watercolors, Sculpture and Drawings from the Collection of Mr. and Mrs. Henry Pearlman and Henry and Rose Pearlman Foundation </I>(New York, 1974)"
    },
    {
      "date": 1971,
      "boilertext": "<I>Summer Loan 1971: Paintings from New York Collections: Collection of Mr. and Mrs. Henry Pearlman and The Henry and Rose Pearlman Foundation </I>(New York, 1971)"
    },
    {
      "date": 1968,
      "boilertext": "<I>New York Collects</I> (New York, 1968)"
    },
    {
      "date": 2002,
      "boilertext": "Laura M. Giles and Carol Armstrong, eds.,&nbsp;<EM>Cézanne in Focus: Watercolors from the Henry and Rose Pearlman Collection</EM> (Princeton, 2002)"
    }
  ],
  "dimensions": "48.3 x 31.7 cm. (19 x 12 1/2 in.)",
  "media": [
    {
      "mediatypeid": 1,
      "restrictions": "Restricted",
      "uri": "http://puam-loris.aws.princeton.edu/loris/L1988-62-54_REC.jp2",
      "rank": 1,
      "caption": "Bruce White Photography",
      "isprimary": 1,
      "id": 74665
    },
    {
      "mediatypeid": 1,
      "restrictions": "Restricted",
      "uri": "http://puam-loris.aws.princeton.edu/loris/L1988-62-54_VER.jp2",
      "rank": 2,
      "caption": "Bruce White Photography",
      "isprimary": 0,
      "id": 74666
    }
  ],
  "department": "Prints and Drawings",
  "geography": [],
  "medium": "Pencil",
  "terms": [],
  "sortnumber": "1988   62L   54",
  "creditline": "The Henry and Rose Pearlman Foundation on long term loan to the Princeton University Art Museum",
  "creditlinerepro": "",
  "dateend": 1888,
  "dimensionelements": [
    {
      "units": "centimeters",
      "type": "Height",
      "dimension": "48.25",
      "element": "Overall"
    },
    {
      "units": "centimeters",
      "type": "Width",
      "dimension": "31.74",
      "element": "Overall"
    }
  ],
  "datebegin": 1886,
  "displaytitle": "Study of Trees",
  "signed": null,
  "displaydate": "1886–88",
  "published_date": "2017-06-11 11:46:05.571752",
  "inscribed": null,
  "markings": null
}
```

## Available resources

Currently data describing two primary resources from the Princeton University Art Museum are available via this API:

* [Objects](https://github.com/danieltbrennan/puam-api-docs/blob/master/objects.md)
* [Makers](https://github.com/danieltbrennan/puam-api-docs/blob/master/objects.md)

## Feedback and Questions

If you have a feature request or find a bug, [please open a GitHub issue](https://github.com/danieltbrennan/puam-api-docs/issues/new).

For more general inquiries regarding the API, [e-mail is preferred](mailto:dbrennan@princeton.edu).
