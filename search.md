# Search

Provides access to a full-text search against the Museum's data.

## Get single object by ID

`GET /search?q=""[term(s)]"&type=all`

#### Example

> http://data.artmuseum.princeton.edu/search?q=blue&type:all

#### Response

```json

{
  "took": 8,
  "timed_out": false,
  "_shards": {
    "total": 5,
    "successful": 5,
    "failed": 0
  },
  "hits": {
    "total": 87,
    "max_score": 9.750915,
    "hits": [
      {
        "_index": "puam",
        "_type": "artobjects",
        "_id": "45438",
        "_score": 9.750915,
        "_source": {
          "exhibitions": [],
          "objectid": 45438,
          "texts": [],
          "accessionyear": "",
          "titles": [
            {
              "titletype": "Primary Title",
              "displayorder": 1,
              "title": "Blue Green Algae Pools"
            }
          ],
          "periods": [],
          "catalograisonne": null,
          "makers": [
            {
              "makerid": 4334,
              "displayname": "Charles R. Knight",
              "suffix": null,
              "prefix": null,
              "dateend": 1953,
              "displaydate": "American, 1874–1953",
              "role": "Artist",
              "datebegin": 1874
            }
          ],
          "objectnumber": "PP370",
          "hasimage": "true",
          "bibliography": [],
          "dimensions": "38.3 x 45.8 cm (15 1/16 x 18 1/16 in.)\r\nframe: 44.5 × 52.1 cm (17 1/2 × 20 1/2 in.)",
          "media": [
            {
              "mediatypeid": 1,
              "restrictions": null,
              "uri": "http://puam-loris.aws.princeton.edu/loris/PP370.jp2",
              "rank": 1,
              "caption": "PUAM Photo",
              "isprimary": 1,
              "id": 19181
            }
          ],
          "displaymaker": "Charles R. Knight, American, 1874–1953",
          "department": "American Art",
          "cultures": [
            {
              "culture": "American",
              "id": 2038492
            }
          ],
          "geography": [],
          "medium": "Oil on canvas",
          "terms": [
            {
              "term": "American",
              "id": 2038492
            },
            {
              "term": "oil paintings",
              "id": 2053145
            },
            {
              "term": "landscapes (representations)",
              "id": 2055694
            },
            {
              "term": "algae",
              "id": 2120414
            }
          ],
          "sortnumber": "P       370P",
          "creditline": "Princeton University",
          "primaryimage": "PP370.jpg",
          "creditlinerepro": "© 1948 Trustees of Princeton University",
          "dateend": 1927,
          "dimensionelements": [
            {
              "units": "centimeters",
              "type": "Height",
              "dimension": "38.30",
              "element": "Overall"
            },
            {
              "units": "centimeters",
              "type": "Width",
              "dimension": "45.80",
              "element": "Overall"
            },
            {
              "units": "centimeters",
              "type": "Height",
              "dimension": "44.50",
              "element": "frame"
            },
            {
              "units": "centimeters",
              "type": "Width",
              "dimension": "52.10",
              "element": "frame"
            }
          ],
          "datebegin": 1927,
          "displaytitle": "Blue Green Algae Pools",
          "signed": "Signed and dated lower right: CHAS. R. KNIGHT / 27",
          "displaydate": "1927",
          "published_date": "2017-08-09 14:59:22.648874",
          "inscribed": null,
          "markings": "Typed paper label inserted in lower right frame corner: Proterzoic Era / Charles R. Knight"
        }
      },
      {
        "_index": "puam",
        "_type": "artobjects",
        "_id": "33888",
        "_score": 9.743227,
        "_source": {
          "exhibitions": [],
          "objectid": 33888,
          "texts": [],
          "accessionyear": "1994",
          "titles": [
            {
              "titletype": "Primary Title",
              "displayorder": 1,
              "title": "Woven fragment with bird head designs in yellow, red, blue, green, white, black, and gold"
            }
          ],
          "periods": [],
          "catalograisonne": null,
          "makers": [
            {
              "makerid": 13511,
              "displayname": "Wari",
              "suffix": null,
              "prefix": null,
              "dateend": 0,
              "displaydate": null,
              "role": "Culture",
              "datebegin": 0
            },
            {
              "makerid": 13507,
              "displayname": "Middle Horizon",
              "suffix": null,
              "prefix": null,
              "dateend": 1000,
              "displaydate": null,
              "role": "Period",
              "datebegin": 550
            }
          ],
          "objectnumber": "y1994-107",
          "hasimage": "true",
          "bibliography": [],
          "dimensions": "l. 27.0 cm., w. 6.0 cm. (10 5/8 x 2 3/8 in.)",
          "media": [
            {
              "mediatypeid": 1,
              "restrictions": null,
              "uri": "http://puam-loris.aws.princeton.edu/loris/INV011021.jp2",
              "rank": 1,
              "caption": "Inventory Project",
              "isprimary": 1,
              "id": 46039
            }
          ],
          "displaymaker": "Middle Horizon | Wari",
          "department": "Art of the Ancient Americas",
          "cultures": [
            {
              "culture": "Huari",
              "id": 2036029
            }
          ],
          "geography": [
            {
              "city": null,
              "code": "Place made",
              "locale": null,
              "country": "Peru",
              "region": "South coast",
              "geoname": "http://www.geonames.org/3932488/republic-of-peru.html",
              "subcontinent": "Andes",
              "locus": null,
              "county": null,
              "excavation": null,
              "state": null,
              "subregion": null,
              "displaygeography": "Place made: South coast, Peru",
              "longitude": "-75.25",
              "latitude": "-10",
              "river": null,
              "continent": "South America"
            }
          ],
          "medium": "Textile",
          "terms": [
            {
              "term": "Huari",
              "id": 2036029
            },
            {
              "term": "fragments",
              "id": 2048603
            },
            {
              "term": "textiles",
              "id": 2049610
            },
            {
              "term": "weaving",
              "id": 2151271
            },
            {
              "term": "dyeing",
              "id": 2151290
            },
            {
              "term": "birds",
              "id": 2158039
            }
          ],
          "sortnumber": "1994  107y",
          "creditline": "Anonymous gift",
          "primaryimage": "INV011021.jpg",
          "creditlinerepro": null,
          "dateend": 1200,
          "dimensionelements": [
            {
              "units": "centimeters",
              "type": "Width",
              "dimension": "6.00",
              "element": "Overall"
            },
            {
              "units": "centimeters",
              "type": "Length",
              "dimension": "27.00",
              "element": "Overall"
            }
          ],
          "datebegin": 1000,
          "displaytitle": "Woven fragment with bird head designs in yellow, red, blue, green, white, black, and gold",
          "signed": null,
          "displaydate": "A.D. 1000–1200",
          "published_date": "2017-08-09 14:18:31.144176",
          "inscribed": null,
          "markings": null
        }
      },
      {
        "_index": "puam",
        "_type": "artobjects",
        "_id": "32070",
        "_score": 8.264614,
        "_source": {
          "exhibitions": [],
          "objectid": 32070,
          "texts": [],
          "accessionyear": "1973",
          "titles": [
            {
              "titletype": "Primary Title",
              "displayorder": 1,
              "title": "Thatched Huts Between Trees and Rocks in the \"blue-green\" style"
            }
          ],
          "periods": [],
          "catalograisonne": null,
          "makers": [
            {
              "makerid": 2987,
              "displayname": "Wang Hui 王翬",
              "suffix": null,
              "prefix": null,
              "dateend": 1717,
              "displaydate": "1632–1717",
              "role": "Artist",
              "datebegin": 1632
            },
            {
              "makerid": 13592,
              "displayname": "Chinese",
              "suffix": null,
              "prefix": null,
              "dateend": 0,
              "displaydate": null,
              "role": "Culture",
              "datebegin": 0
            },
            {
              "makerid": 15366,
              "displayname": "Qing dynasty",
              "suffix": null,
              "prefix": null,
              "dateend": 1912,
              "displaydate": "1644–1912",
              "role": "Period",
              "datebegin": 1644
            }
          ],
          "objectnumber": "y1973-67 h",
          "hasimage": "true",
          "bibliography": [],
          "dimensions": "Painting: 21.9 x 30.9 cm. (8 5/8 x 12 3/16 in.)\r\nLeaf: 63 x 48.5 cm. (24 13/16 x 19 1/8 in.)",
          "media": [
            {
              "mediatypeid": 1,
              "restrictions": null,
              "uri": "http://puam-loris.aws.princeton.edu/loris/y1973-67H_SL.jp2",
              "rank": 1,
              "caption": "Luna Digitization Project",
              "isprimary": 1,
              "id": 7475
            }
          ],
          "displaymaker": "Chinese | Qing dynasty, 1644–1912 | Wang Hui 王翬, 1632–1717",
          "department": "Asian Art",
          "cultures": [
            {
              "culture": "Qing",
              "id": 2033603
            }
          ],
          "geography": [
            {
              "city": null,
              "code": "Place made",
              "locale": null,
              "country": "China",
              "region": null,
              "geoname": null,
              "subcontinent": null,
              "locus": null,
              "county": null,
              "excavation": null,
              "state": null,
              "subregion": null,
              "displaygeography": "Place made: China",
              "longitude": null,
              "latitude": "NULL",
              "river": null,
              "continent": "Asia"
            }
          ],
          "medium": "Album leaf; ink and light colors on paper",
          "terms": [
            {
              "term": "Qing",
              "id": 2033603
            },
            {
              "term": "Chinese painting styles",
              "id": 2033673
            },
            {
              "term": "paintings",
              "id": 2052977
            },
            {
              "term": "landscapes (representations)",
              "id": 2055694
            },
            {
              "term": "autumn",
              "id": 2098550
            },
            {
              "term": "trees",
              "id": 2103928
            },
            {
              "term": "albums",
              "id": 2125788
            },
            {
              "term": "rock (inorganic material)",
              "id": 2163203
            }
          ],
          "sortnumber": "1973   67yh",
          "creditline": "Gift of Mr. and Mrs. Earl Morse",
          "primaryimage": "y1973-67H_SL.jpg",
          "creditlinerepro": "",
          "dateend": 1673,
          "dimensionelements": [
            {
              "units": "centimeters",
              "type": "Height",
              "dimension": "63.00",
              "element": "Leaf"
            },
            {
              "units": "centimeters",
              "type": "Width",
              "dimension": "48.50",
              "element": "Leaf"
            },
            {
              "units": "centimeters",
              "type": "Height",
              "dimension": "21.90",
              "element": "Painting"
            },
            {
              "units": "centimeters",
              "type": "Width",
              "dimension": "30.90",
              "element": "Painting"
            }
          ],
          "datebegin": 1673,
          "displaytitle": "Thatched Huts Between Trees and Rocks in the \"blue-green\" style",
          "signed": "signed",
          "displaydate": "1673",
          "published_date": "2017-08-09 14:08:30.973946",
          "inscribed": "dated 1673",
          "markings": null
        }
      },
      {
        "_index": "puam",
        "_type": "artobjects",
        "_id": "34123",
        "_score": 8.250535,
        "_source": {
          "exhibitions": [],
          "objectid": 34123,
          "texts": [
            {
              "remarks": null,
              "textentryhtml": "Rounded, fire-polished, flaring rim; short cylindrical neck, widening into a bag-shaped body; pushed-in base forming a spreading foot; slightly convex bottom. Ribbed strap handle of blue-green glass from shoulder to rim. Two threads of the same material wound below the rim and at the neck. At the center of the bottom is a solid, circular pontil mark, 1.2 cm. wide.",
              "texttype": "Online"
            },
            {
              "remarks": "Migrated from 9.35 12/2013",
              "textentryhtml": "Mount Carmel",
              "texttype": "Online"
            }
          ],
          "accessionyear": "",
          "titles": [
            {
              "titletype": "Primary Title",
              "displayorder": 1,
              "title": "Jug"
            }
          ],
          "periods": [],
          "catalograisonne": null,
          "makers": [
            {
              "makerid": 17030,
              "displayname": "Late Antique",
              "suffix": null,
              "prefix": null,
              "dateend": 641,
              "displaydate": null,
              "role": "Period",
              "datebegin": 284
            }
          ],
          "objectnumber": "y215",
          "hasimage": "true",
          "bibliography": [
            {
              "date": 2012,
              "boilertext": "Anastassios Antonaras,<EM> Fire and sand: ancient glass in the Princeton University Art Museum, </EM>(Princeton, NJ: Princeton University Art Museum, 2012)."
            }
          ],
          "dimensions": "h. 18.4 cm, diam. rim 6.1 cm, diam. base 6 cm (7 1/4 x 2 3/8 x 2 3/8 in.)",
          "media": [
            {
              "mediatypeid": 1,
              "restrictions": null,
              "uri": "http://puam-loris.aws.princeton.edu/loris/y215_1.jp2",
              "rank": 1,
              "caption": "Bruce White Photography",
              "isprimary": 1,
              "id": 74496
            }
          ],
          "displaymaker": "Late Antique",
          "department": "Ancient, Byzantine, and Islamic Art",
          "cultures": [
            {
              "culture": "Roman (style or period)",
              "id": 2036723
            }
          ],
          "geography": [
            {
              "city": null,
              "code": "Place made",
              "locale": "Mount Carmel",
              "country": null,
              "region": "Eastern Mediterranean",
              "geoname": "http://www.geonames.org/maps/google_32.721_35.031.html",
              "subcontinent": null,
              "locus": null,
              "county": null,
              "excavation": null,
              "state": null,
              "subregion": null,
              "displaygeography": "Place made: Mount Carmel, Eastern Mediterranean",
              "longitude": null,
              "latitude": "NULL",
              "river": null,
              "continent": null
            }
          ],
          "medium": "Transparent light green and blue-green glass; no impurities",
          "terms": [
            {
              "term": "Roman (style or period)",
              "id": 2036723
            },
            {
              "term": "light green",
              "id": 2058680
            },
            {
              "term": "ewers",
              "id": 2073185
            },
            {
              "term": "pontil marks",
              "id": 2117162
            },
            {
              "term": "glass",
              "id": 2161148
            }
          ],
          "sortnumber": "215     y",
          "creditline": "Gift of W. L. Bogert",
          "primaryimage": "y215_1.jpg",
          "creditlinerepro": "",
          "dateend": 399,
          "dimensionelements": [
            {
              "units": "centimeters",
              "type": "Height",
              "dimension": "18.40",
              "element": "Overall"
            },
            {
              "units": "centimeters",
              "type": "diam. rim",
              "dimension": "6.10",
              "element": "Overall"
            },
            {
              "units": "centimeters",
              "type": "diam. base",
              "dimension": "6.00",
              "element": "Overall"
            }
          ],
          "datebegin": 300,
          "displaytitle": "Jug",
          "signed": null,
          "displaydate": "4th century A.D.",
          "published_date": "2017-08-09 14:19:30.933258",
          "inscribed": null,
          "markings": null
        }
      },
      {
        "_index": "puam",
        "_type": "artobjects",
        "_id": "19271",
        "_score": 8.22445,
        "_source": {
          "exhibitions": [],
          "objectid": 19271,
          "texts": [],
          "accessionyear": "1929",
          "titles": [
            {
              "titletype": "Primary Title",
              "displayorder": 1,
              "title": "Lamp"
            }
          ],
          "periods": [],
          "catalograisonne": null,
          "makers": [],
          "objectnumber": "y1929-276",
          "hasimage": "true",
          "bibliography": [],
          "dimensions": "4.5 × 10.7 × 11.2 cm (1 3/4 × 4 3/16 × 4 7/16 in.)",
          "media": [
            {
              "mediatypeid": 1,
              "restrictions": null,
              "uri": "http://puam-loris.aws.princeton.edu/loris/INV65665.jp2",
              "rank": 3,
              "caption": "Inventory Project",
              "isprimary": 0,
              "id": 147905
            },
            {
              "mediatypeid": 1,
              "restrictions": null,
              "uri": "http://puam-loris.aws.princeton.edu/loris/INV65666.jp2",
              "rank": 2,
              "caption": "Inventory Project",
              "isprimary": 0,
              "id": 147906
            },
            {
              "mediatypeid": 1,
              "restrictions": null,
              "uri": "http://puam-loris.aws.princeton.edu/loris/INV65667.jp2",
              "rank": 1,
              "caption": "Inventory Project",
              "isprimary": 1,
              "id": 147907
            }
          ],
          "displaymaker": null,
          "department": "Ancient, Byzantine, and Islamic Art",
          "cultures": [
            {
              "culture": "Arabian",
              "id": 2037249
            }
          ],
          "geography": [],
          "medium": "Terracotta; granular, buff clay; vitreous blue-green glaze",
          "terms": [
            {
              "term": "Arabian",
              "id": 2037249
            },
            {
              "term": "oil lamps",
              "id": 2071641
            }
          ],
          "sortnumber": "1929  276y",
          "creditline": "Trumbull Prime Collection",
          "primaryimage": "INV65667.jpg",
          "creditlinerepro": null,
          "dateend": 0,
          "dimensionelements": [
            {
              "units": "centimeters",
              "type": "Height",
              "dimension": "4.50",
              "element": "Overall"
            },
            {
              "units": "centimeters",
              "type": "Width",
              "dimension": "10.70",
              "element": "Overall"
            },
            {
              "units": "centimeters",
              "type": "Length",
              "dimension": "11.20",
              "element": "Overall"
            }
          ],
          "datebegin": 0,
          "displaytitle": "Lamp",
          "signed": null,
          "displaydate": null,
          "published_date": "2017-08-09 13:11:15.258081",
          "inscribed": null,
          "markings": null
        }
      },
      {
        "_index": "puam",
        "_type": "artobjects",
        "_id": "38015",
        "_score": 8.22445,
        "_source": {
          "exhibitions": [],
          "objectid": 38015,
          "texts": [],
          "accessionyear": "1959",
          "titles": [
            {
              "titletype": "Primary Title",
              "displayorder": 1,
              "title": "Ushabti"
            }
          ],
          "periods": [
            {
              "id": 2037044,
              "period": "Twenty-sixth Dynasty"
            }
          ],
          "catalograisonne": null,
          "makers": [
            {
              "makerid": 12860,
              "displayname": "Late Period",
              "suffix": "(Saitic)",
              "prefix": null,
              "dateend": -332,
              "displaydate": null,
              "role": "Period",
              "datebegin": -712
            },
            {
              "makerid": 15181,
              "displayname": "Egyptian",
              "suffix": null,
              "prefix": null,
              "dateend": 0,
              "displaydate": null,
              "role": "Culture",
              "datebegin": 0
            }
          ],
          "objectnumber": "y1959-143",
          "hasimage": "true",
          "bibliography": [],
          "dimensions": "14.0 x 4.1 x 2.6 cm (5 1/2 x 1 5/8 x 1 in.)",
          "media": [
            {
              "mediatypeid": 1,
              "restrictions": null,
              "uri": "http://puam-loris.aws.princeton.edu/loris/INV003041.jp2",
              "rank": 1,
              "caption": "Inventory Project",
              "isprimary": 1,
              "id": 34835
            }
          ],
          "displaymaker": "Egyptian | Late Period (Saitic)",
          "department": "Ancient, Byzantine, and Islamic Art",
          "cultures": [
            {
              "culture": "Egyptian",
              "id": 2036860
            }
          ],
          "geography": [],
          "medium": "Blue-green faience",
          "terms": [
            {
              "term": "Egyptian",
              "id": 2036860
            },
            {
              "term": "Twenty-sixth Dynasty",
              "id": 2037044
            },
            {
              "term": "funerary objects",
              "id": 2048783
            },
            {
              "term": "faience",
              "id": 2049250
            },
            {
              "term": "ushabti",
              "id": 2055000
            },
            {
              "term": "hieroglyphics",
              "id": 2118718
            }
          ],
          "sortnumber": "1959  143y",
          "creditline": "Gift of Horace Mayer",
          "primaryimage": "INV003041.jpg",
          "creditlinerepro": null,
          "dateend": -525,
          "dimensionelements": [
            {
              "units": "centimeters",
              "type": "Height",
              "dimension": "14.00",
              "element": "Overall"
            },
            {
              "units": "centimeters",
              "type": "Width",
              "dimension": "4.12",
              "element": "Overall"
            },
            {
              "units": "centimeters",
              "type": "Depth",
              "dimension": "2.60",
              "element": "Overall"
            }
          ],
          "datebegin": -672,
          "displaytitle": "Ushabti",
          "signed": null,
          "displaydate": null,
          "published_date": "2017-08-09 14:32:48.317810",
          "inscribed": null,
          "markings": null
        }
      },
      {
        "_index": "puam",
        "_type": "artobjects",
        "_id": "6511",
        "_score": 8.22445,
        "_source": {
          "exhibitions": [],
          "objectid": 6511,
          "texts": [],
          "accessionyear": "1948",
          "titles": [
            {
              "titletype": "Primary Title",
              "displayorder": 1,
              "title": "Couple Wrestling"
            }
          ],
          "periods": [],
          "catalograisonne": null,
          "makers": [
            {
              "makerid": 4353,
              "displayname": "Georg Kolbe",
              "suffix": null,
              "prefix": null,
              "dateend": 1947,
              "displaydate": "German, 1877 – 1947",
              "role": "Artist",
              "datebegin": 1877
            }
          ],
          "objectnumber": "x1948-1249",
          "hasimage": "true",
          "bibliography": [],
          "dimensions": "Overall: 46.7 x 37 cm (18 3/8 x 14 9/16 in.)",
          "media": [
            {
              "mediatypeid": 1,
              "restrictions": "Restricted",
              "uri": "http://puam-loris.aws.princeton.edu/loris/INV35787.jp2",
              "rank": 1,
              "caption": "Inventory Project",
              "isprimary": 1,
              "id": 112699
            }
          ],
          "displaymaker": "Georg Kolbe, German, 1877 – 1947",
          "department": "Prints and Drawings",
          "cultures": [],
          "geography": [],
          "medium": "Pen and blue-gray ink, blue-green-gray wash",
          "terms": [],
          "sortnumber": "1948 1249x",
          "creditline": "Bequest of Dan Fellows Platt, Class of 1895",
          "primaryimage": "INV35787.jpg",
          "creditlinerepro": "© Georg Kolbe / Artists Rights Society (ARS), New York / VG Bild-Kunst, Germany",
          "dateend": 1947,
          "dimensionelements": [
            {
              "units": "centimeters",
              "type": "Height",
              "dimension": "46.70",
              "element": "Overall"
            },
            {
              "units": "centimeters",
              "type": "Width",
              "dimension": "37.00",
              "element": "Overall"
            }
          ],
          "datebegin": 1877,
          "displaytitle": "Couple Wrestling",
          "signed": null,
          "displaydate": null,
          "published_date": "2017-08-09 11:53:38.970090",
          "inscribed": "right: monogram",
          "markings": null
        }
      },
      {
        "_index": "puam",
        "_type": "artobjects",
        "_id": "23033",
        "_score": 8.074817,
        "_source": {
          "exhibitions": [],
          "objectid": 23033,
          "texts": [],
          "accessionyear": "1946",
          "titles": [
            {
              "titletype": "Primary Title",
              "displayorder": 1,
              "title": "Unguentarium"
            }
          ],
          "periods": [],
          "catalograisonne": null,
          "makers": [
            {
              "makerid": 13442,
              "displayname": "Roman",
              "suffix": null,
              "prefix": null,
              "dateend": 0,
              "displaydate": null,
              "role": "Culture",
              "datebegin": 0
            }
          ],
          "objectnumber": "y1946-308",
          "hasimage": "true",
          "bibliography": [],
          "dimensions": "h. 14.9 cm, diam. 7.8 cm (5 7/8 x 3 1/16 in.)",
          "media": [
            {
              "mediatypeid": 1,
              "restrictions": null,
              "uri": "http://puam-loris.aws.princeton.edu/loris/INV003966.jp2",
              "rank": 1,
              "caption": "Inventory Project",
              "isprimary": 1,
              "id": 35691
            }
          ],
          "displaymaker": "Roman",
          "department": "Ancient, Byzantine, and Islamic Art",
          "cultures": [
            {
              "culture": "Roman (style or period)",
              "id": 2036723
            }
          ],
          "geography": [],
          "medium": "Pale blue-green glass",
          "terms": [
            {
              "term": "Roman (style or period)",
              "id": 2036723
            },
            {
              "term": "bottles",
              "id": 2072893
            },
            {
              "term": "glass",
              "id": 2161148
            },
            {
              "term": "unguentaria",
              "id": 2171812
            }
          ],
          "sortnumber": "1946  308y",
          "creditline": "Gift of Mrs. Platt from the bequest of Dan Fellows Platt, Class of 1895",
          "primaryimage": "INV003966.jpg",
          "creditlinerepro": null,
          "dateend": 499,
          "dimensionelements": [
            {
              "units": "centimeters",
              "type": "Height",
              "dimension": "14.90",
              "element": "Overall"
            },
            {
              "units": "centimeters",
              "type": "diam.",
              "dimension": "7.80",
              "element": "Overall"
            }
          ],
          "datebegin": 300,
          "displaytitle": "Unguentarium",
          "signed": null,
          "displaydate": "4th–5th century",
          "published_date": "2017-08-09 13:32:41.126271",
          "inscribed": null,
          "markings": null
        }
      },
      {
        "_index": "puam",
        "_type": "artobjects",
        "_id": "30235",
        "_score": 8.074817,
        "_source": {
          "exhibitions": [],
          "objectid": 30235,
          "texts": [],
          "accessionyear": "1966",
          "titles": [
            {
              "titletype": "Primary Title",
              "displayorder": 1,
              "title": "Miniature Unguentarium"
            }
          ],
          "periods": [],
          "catalograisonne": null,
          "makers": [
            {
              "makerid": 13442,
              "displayname": "Roman",
              "suffix": null,
              "prefix": null,
              "dateend": 0,
              "displaydate": null,
              "role": "Culture",
              "datebegin": 0
            }
          ],
          "objectnumber": "y1966-177",
          "hasimage": "true",
          "bibliography": [],
          "dimensions": "h. 3.7 cm, diam. 2.9 cm (1 7/16 x 1 1/8 in.)",
          "media": [
            {
              "mediatypeid": 1,
              "restrictions": null,
              "uri": "http://puam-loris.aws.princeton.edu/loris/INV004214.jp2",
              "rank": 1,
              "caption": "Inventory Project",
              "isprimary": 1,
              "id": 37447
            }
          ],
          "displaymaker": "Roman",
          "department": "Ancient, Byzantine, and Islamic Art",
          "cultures": [
            {
              "culture": "Roman (style or period)",
              "id": 2036723
            }
          ],
          "geography": [],
          "medium": "Pale blue-green glass",
          "terms": [
            {
              "term": "Roman (style or period)",
              "id": 2036723
            },
            {
              "term": "bottles",
              "id": 2072893
            },
            {
              "term": "glass",
              "id": 2161148
            },
            {
              "term": "unguentaria",
              "id": 2171812
            }
          ],
          "sortnumber": "1966  177y",
          "creditline": "Gift of Dr. Louis C. West",
          "primaryimage": "INV004214.jpg",
          "creditlinerepro": null,
          "dateend": 299,
          "dimensionelements": [
            {
              "units": "centimeters",
              "type": "Height",
              "dimension": "3.70",
              "element": "Overall"
            },
            {
              "units": "centimeters",
              "type": "diam.",
              "dimension": "2.90",
              "element": "Overall"
            }
          ],
          "datebegin": 100,
          "displaytitle": "Miniature Unguentarium",
          "signed": null,
          "displaydate": "2nd–3rd century A.D.",
          "published_date": "2017-08-09 14:00:37.758244",
          "inscribed": null,
          "markings": null
        }
      },
      {
        "_index": "puam",
        "_type": "artobjects",
        "_id": "36358",
        "_score": 8.074817,
        "_source": {
          "exhibitions": [],
          "objectid": 36358,
          "texts": [],
          "accessionyear": "1998",
          "titles": [
            {
              "titletype": "Primary Title",
              "displayorder": 1,
              "title": "Bowl"
            }
          ],
          "periods": [
            {
              "id": 2036906,
              "period": "Early Dynastic (Egyptian)"
            }
          ],
          "catalograisonne": null,
          "makers": [
            {
              "makerid": 15181,
              "displayname": "Egyptian",
              "suffix": null,
              "prefix": null,
              "dateend": 0,
              "displaydate": null,
              "role": "Culture",
              "datebegin": 0
            },
            {
              "makerid": 12853,
              "displayname": "Early Dynastic",
              "suffix": ", 1st - 3rd Dynasties",
              "prefix": null,
              "dateend": -2750,
              "displaydate": null,
              "role": "Period",
              "datebegin": -3100
            }
          ],
          "objectnumber": "1998-428",
          "hasimage": "true",
          "bibliography": [],
          "dimensions": "h. 12.4 cm, diam. 17.8 cm (4 7/8 x 7 in.)",
          "media": [
            {
              "mediatypeid": 1,
              "restrictions": null,
              "uri": "http://puam-loris.aws.princeton.edu/loris/INV002364.jp2",
              "rank": 1,
              "caption": "Inventory Project",
              "isprimary": 1,
              "id": 34604
            }
          ],
          "displaymaker": "Egyptian | Early Dynastic , 1st - 3rd Dynasties",
          "department": "Ancient, Byzantine, and Islamic Art",
          "cultures": [
            {
              "culture": "Egyptian",
              "id": 2036860
            }
          ],
          "geography": [],
          "medium": "Blue-green stone",
          "terms": [
            {
              "term": "Egyptian",
              "id": 2036860
            },
            {
              "term": "Early Dynastic (Egyptian)",
              "id": 2036906
            },
            {
              "term": "bowls (vessels)",
              "id": 2073090
            }
          ],
          "sortnumber": "1998  428",
          "creditline": "Bequest of John B. Elliott, Class of 1951",
          "primaryimage": "INV002364.jpg",
          "creditlinerepro": null,
          "dateend": -2613,
          "dimensionelements": [
            {
              "units": "centimeters",
              "type": "Height",
              "dimension": "12.40",
              "element": "Overall"
            },
            {
              "units": "centimeters",
              "type": "diam.",
              "dimension": "17.80",
              "element": "Overall"
            }
          ],
          "datebegin": -3100,
          "displaytitle": "Bowl",
          "signed": null,
          "displaydate": "ca. 3100–2613 B.C.",
          "published_date": "2017-08-09 14:25:43.938523",
          "inscribed": null,
          "markings": null
        }
      }
    ]
  }
}

```

In order to facilitate searching across multiple data types, the data type must be included within the query string as a parameter. A multi-object response consists of all object records that match the selected criteria as a list object.

> http://data.artmuseum.princeton.edu/search?q="blue"&type=artobjects

Valid type values are:  

- [artobjects](https://github.com/danieltbrennan/puam-api-docs/blob/master/objects.md)
- [makers](https://github.com/danieltbrennan/puam-api-docs/blob/master/makers.md)
- [packages]((https://github.com/danieltbrennan/puam-api-docs/blob/master/packages.md)
- all - This value will search across all data types

Additional parameters can be appended to any search query to control filtering, sorting, and pagination of results. The available query parameters are:

`size` - establishes the maximum number of records to be retrieved at once (integer, defaults to 10, up to a maximum of 500).  
`from` - offset position of the first result to be retrieved which can effectively be used to paginate through large result sets via multiple repeated requests (integer, defaults to 0)  
`sort` - field on which to sort results (field name, defaults to Lucene query score descending)  
`sortorder` - order in which to sort results ('ASC' or 'DESC', defaults to DESC)  

#### Example

> http://data.artmuseum.princeton.edu/objects?maker=6353&size=25sort=ObjectID&sortorder=ASC
