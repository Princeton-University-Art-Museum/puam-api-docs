# Search

Provides access to a full-text search against the Museum's data.

## Search across all data types for a term

`GET /search?q=""[term(s)]"&type=all`

#### Example

> http://data.artmuseum.princeton.edu/search?q=blue&type=all

#### Response

```json

{
  "took": 3,
  "timed_out": false,
  "_shards": {
    "total": 5,
    "successful": 5,
    "failed": 0
  },
  "hits": {
    "total": 2309,
    "max_score": 5.5395494,
    "hits": [
      {
        "_index": "2017-11-28",
        "_type": "artobjects",
        "_id": "23711",
        "_score": 5.5395494,
        "_source": {
          "displaymaker": "German , Rhenish",
          "objectnumber": "y1949-123",
          "creditline": "Museum purchase, gift of Gordon McCormick, Class of 1917",
          "displaydate": "12th century",
          "primaryimage": [
            "http://puam-lori-ElasticL-W22FK7028HD9-1675803086.us-east-1.elb.amazonaws.com/loris/y1949-123.jp2"
          ],
          "medium": "Copper with gilding and champlevé enamel",
          "displaytitle": "Champlevé border strip",
          "objectid": 23711,
          "dimensions": "2.7 × 17.7 × 0.4 cm (1 1/16 × 6 15/16 × 3/16 in.)"
        }
      },
      {
        "_index": "2017-11-28",
        "_type": "artobjects",
        "_id": "20561",
        "_score": 5.357977,
        "_source": {
          "displaymaker": "Chinese | Qing dynasty, Qianlong reign period, 1736–1795",
          "objectnumber": "y1936-665",
          "creditline": "Bequest of Col. James A. Blair",
          "displaydate": null,
          "primaryimage": [
            "http://puam-lori-ElasticL-W22FK7028HD9-1675803086.us-east-1.elb.amazonaws.com/loris/INV021004.jp2"
          ],
          "medium": "Porcelain with underglaze blue",
          "displaytitle": "Snuff bottle",
          "objectid": 20561,
          "dimensions": "h. without stopper 6.8 cm., diam. 2.8 cm. (2 11/16 x 1 1/8 in.)"
        }
      },
      {
        "_index": "2017-11-28",
        "_type": "artobjects",
        "_id": "20165",
        "_score": 5.357977,
        "_source": {
          "displaymaker": "Chinese | Qing dynasty, Qianlong reign period, 1736–1795",
          "objectnumber": "y1936-548",
          "creditline": "Bequest of Col. James A. Blair",
          "displaydate": null,
          "primaryimage": [
            "http://puam-lori-ElasticL-W22FK7028HD9-1675803086.us-east-1.elb.amazonaws.com/loris/INV020669.jp2"
          ],
          "medium": "Porcelain with underglaze blue",
          "displaytitle": "Snuff bottle",
          "objectid": 20165,
          "dimensions": "h. with stopper 5.6 cm., w. 2.8 cm., d. 1.7 cm. (2 3/16 x 1 1/8 x 11/16 in.)"
        }
      },
      {
        "_index": "2017-11-28",
        "_type": "artobjects",
        "_id": "18563",
        "_score": 5.357977,
        "_source": {
          "displaymaker": "Italian",
          "objectnumber": "y130.2",
          "creditline": "Prime Fund",
          "displaydate": "ca. 1507",
          "primaryimage": [
            "http://puam-lori-ElasticL-W22FK7028HD9-1675803086.us-east-1.elb.amazonaws.com/loris/INV59521.jp2"
          ],
          "medium": "Glazed earthenware",
          "displaytitle": "Triangular Majolica Tile with Crescent Moon on a Blue Field",
          "objectid": 18563,
          "dimensions": "13.5 × 15.5 × 2.3 cm (5 5/16 × 6 1/8 × 7/8 in.)"
        }
      },
      {
        "_index": "2017-11-28",
        "_type": "artobjects",
        "_id": "18565",
        "_score": 5.357977,
        "_source": {
          "displaymaker": "Italian",
          "objectnumber": "y130.4",
          "creditline": "Prime Fund",
          "displaydate": "ca. 1507",
          "primaryimage": [
            "http://puam-lori-ElasticL-W22FK7028HD9-1675803086.us-east-1.elb.amazonaws.com/loris/INV59523.jp2"
          ],
          "medium": "Glazed earthenware",
          "displaytitle": "Triangular Majolica Tile with Crescent Moon on a Blue Field",
          "objectid": 18565,
          "dimensions": "13.5 × 15.3 × 2.2 cm (5 5/16 × 6 × 7/8 in.)"
        }
      },
      {
        "_index": "2017-11-28",
        "_type": "artobjects",
        "_id": "18566",
        "_score": 5.357977,
        "_source": {
          "displaymaker": "Italian",
          "objectnumber": "y130.5",
          "creditline": "Prime Fund",
          "displaydate": "ca. 1507",
          "primaryimage": [
            "http://puam-lori-ElasticL-W22FK7028HD9-1675803086.us-east-1.elb.amazonaws.com/loris/INV59524.jp2"
          ],
          "medium": "Glazed earthenware",
          "displaytitle": "Triangular Majolica Tile with Crescent Moon on a Blue Field",
          "objectid": 18566,
          "dimensions": "13.5 × 15.5 × 2.2 cm (5 5/16 × 6 1/8 × 7/8 in.)"
        }
      },
      {
        "_index": "2017-11-28",
        "_type": "artobjects",
        "_id": "41398",
        "_score": 5.357977,
        "_source": {
          "displaymaker": "Robert Natkin, American, 1930–2010",
          "objectnumber": "2002-341",
          "creditline": "Gift of Lillian Heidenberg",
          "displaydate": "1974",
          "primaryimage": [
            "http://puam-lori-ElasticL-W22FK7028HD9-1675803086.us-east-1.elb.amazonaws.com/loris/INV63530.jp2"
          ],
          "medium": "Serigraph",
          "displaytitle": "Intimate Lighting: Blue",
          "objectid": 41398,
          "dimensions": "image: 91.4 x 66.6 cm (36 x 26 1/4 in.)\r\nsheet: 103.2 × 78.9 cm (40 5/8 × 31 1/16 in.)"
        }
      },
      {
        "_index": "2017-11-28",
        "_type": "artobjects",
        "_id": "3662",
        "_score": 5.356955,
        "_source": {
          "displaymaker": "George Constant, American, 1892-1978",
          "objectnumber": "x1941-18",
          "creditline": "Federal Art Project, W.P.A. Loan",
          "displaydate": "1939",
          "primaryimage": [
            "http://puam-lori-ElasticL-W22FK7028HD9-1675803086.us-east-1.elb.amazonaws.com/loris/INV26681.jp2"
          ],
          "medium": "Etching",
          "displaytitle": "Blue Crabs",
          "objectid": 3662,
          "dimensions": "plate: 30.2 x 28 cm. (11 7/8 x 11 in.)\r\nsheet: 35.6 x 44.2 cm. (14 x 17 3/8 in.)"
        }
      },
      {
        "_index": "2017-11-28",
        "_type": "artobjects",
        "_id": "20897",
        "_score": 5.356955,
        "_source": {
          "displaymaker": "Chinese | Qing dynasty, Qianlong reign period, 1736–1795",
          "objectnumber": "y1936-938",
          "creditline": "Bequest of Col. James A. Blair",
          "displaydate": "1730–90",
          "primaryimage": [
            "http://puam-lori-ElasticL-W22FK7028HD9-1675803086.us-east-1.elb.amazonaws.com/loris/INV020106.jp2"
          ],
          "medium": "Glass with blue overlay",
          "displaytitle": "Glass snuff bottle with blue overlay carved with pearl-chasing dragons",
          "objectid": 20897,
          "dimensions": "h. with stopper 8.0 cm., diam. 3.4 cm. (3 1/8 x 1 3/8 in.)"
        }
      },
      {
        "_index": "2017-11-28",
        "_type": "artobjects",
        "_id": "19822",
        "_score": 5.351532,
        "_source": {
          "displaymaker": "Hellenistic to Roman Imperial",
          "objectnumber": "y1930-502 e",
          "creditline": "Museum purchase",
          "displaydate": "1st century B.C.–1st century A.D.",
          "primaryimage": [
            "http://puam-lori-ElasticL-W22FK7028HD9-1675803086.us-east-1.elb.amazonaws.com/loris/y1930-502e.jp2"
          ],
          "medium": "Opaque white, red, blue, yellow, and black glass; translucent purple glass",
          "displaytitle": "Fragment of an inlay",
          "objectid": 19822,
          "dimensions": "pres. 2.8 x 3.4 cm (1 1/8 x 1 5/16 in.)"
        }
      }
    ]
  }
}

```



In order to facilitate searching across multiple data types, the type must be included within the query string as a parameter.

> http://data.artmuseum.princeton.edu/search?q="blue"&type=artobjects

Valid data types are:  

- [artobjects](https://github.com/danieltbrennan/puam-api-docs/blob/master/objects.md)
- [makers](https://github.com/danieltbrennan/puam-api-docs/blob/master/makers.md)
- [packages](https://github.com/danieltbrennan/puam-api-docs/blob/master/packages.md)
- all - This value will search across all data types  

Note that in order to limit response sizes, the artobjects data type will always return the abbreviated "tombstone" profile when returned via a search query.

Additional query parameters can be appended to any search query to control sorting and pagination of results. The available parameters are:

`size` - establishes the maximum number of records to be retrieved at once (integer, defaults to 10, up to a maximum of 500).  
`from` - offset position of the first result to be retrieved. This can effectively be used to paginate through large result sets via repeated requests (integer, defaults to 0)  
`sort` - field on which to sort results (field name, defaults to Lucene query score)  
`sortorder` - order in which results are sorted ('ASC' or 'DESC', defaults to DESC)  
