# Princeton University Art Museum API Documentation

The Princeton University Art Museum API is a REST-style service designed to provide developer access to data about the Museum and it's collection. This API

## Access

All requests to the API begin with:

```shell
http://api.artmuseum.princeton.edu
```

## Responses and data format

All data is in [JSON](http://json.org) format. Here is a typical response:

```json
{
  "exhibitions": [],
  "objectid": 12345,
  "texts": [],
  "accessionyear": "1974",
  "titles": [
    {
      "titletype": "Primary Title",
      "displayorder": 1,
      "title": "Woman from Bern"
    }
  ],
  "catalograisonne": null,
  "makers": [
    {
      "makerid": 3526,
      "displayname": "Schroeder and Company",
      "suffix": null,
      "prefix": null,
      "dateend": 1900,
      "displaydate": "Swiss, active 1870–1900",
      "role": "Artist",
      "datebegin": 1870
    }
  ],
  "objectnumber": "x1974-40",
  "hasimage": "true",
  "bibliography": [],
  "dimensions": "26.9 x 21 cm (10 9/16 x 8 1/4 in.)\r\nmount: 45.5 x 35.6 cm. (17 15/16 x 14 in.)",
  "media": [
    {
      "mediatypeid": 1,
      "restrictions": null,
      "uri": "http://puam-loris.aws.princeton.edu/loris/INV12165.jp2",
      "rank": 1,
      "caption": "Inventory Project",
      "isprimary": 1,
      "id": 85575
    }
  ],
  "department": "Photography",
  "geography": [],
  "medium": "Gold toned albumen print",
  "terms": [
    {
      "term": "Swiss",
      "id": 2031678
    },
    {
      "term": "photographs",
      "id": 2053200
    },
    {
      "term": "black-and-white photographs",
      "id": 2053728
    },
    {
      "term": "portraits",
      "id": 2055723
    },
    {
      "term": "women",
      "id": 2088280
    },
    {
      "term": "black-and-white photography",
      "id": 2154270
    }
  ],
  "sortnumber": "1974   40x",
  "creditline": "Museum purchase, David H. McAlpin, Class of 1920, Fund",
  "creditlinerepro": null,
  "dateend": 1895,
  "dimensionelements": [
    {
      "units": "centimeters",
      "type": "Height",
      "dimension": "26.90",
      "element": "Overall"
    },
    {
      "units": "centimeters",
      "type": "Width",
      "dimension": "21.00",
      "element": "Overall"
    },
    {
      "units": "centimeters",
      "type": "Height",
      "dimension": "45.50",
      "element": "mount"
    },
    {
      "units": "centimeters",
      "type": "Width",
      "dimension": "35.60",
      "element": "mount"
    }
  ],
  "datebegin": 1885,
  "displaytitle": "Woman from Bern",
  "signed": null,
  "displaydate": "ca. 1890",
  "published_date": "2017-06-04 11:18:10.842055",
  "inscribed": null,
  "markings": null
}
```

## Images

Some of the datasets include image URLs as part of a block of image information in each record. Our images are served to you by an image server that supports a number of interfaces including [IIIF](http://iiif.io).


## Resources that are available

Several primary museum resources are accessible in this API. They include the following:

* [Object](https://github.com/harvardartmuseums/api-docs/blob/master/object.md)
* [Maker](https://github.com/harvardartmuseums/api-docs/blob/master/person.md)

## Feedback

Have you tried the API? [Let us know what you think.](https://docs.google.com/forms/d/118WjSPgKEYBjLU3B3iUkELwHbgeWryVb_5hw3o6_3K8/viewform)  

If you have a specific feature request or find a bug, [please open a GitHub issue](https://github.com/harvardartmuseums/api-docs/issues/new).

## About the API

#### Technical specs

The two core pieces of software behind the API are [Node.js](https://nodejs.org/en/) and [Elasticsearch](http://www.elastic.co).

#### The data

About the data...

## Terms of use

Terms...
