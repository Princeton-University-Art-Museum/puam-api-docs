# Packages

Contains information describing a group of works that are related for a generic reason, along with basic information regarding the rationale for that grouping.

## Get single package by ID

`GET /packages/[id]`

#### Example

> http://data.artmuseum.princeton.edu/packages/123

#### Response

```json

{
  "objects": [
    {
      "id": 4557,
      "sortorder": 10
    },
    {
      "id": 8626,
      "sortorder": 12
    },
    {
      "id": 10487,
      "sortorder": 11
    },
    {
      "id": 12928,
      "sortorder": 13
    },
    {
      "id": 20105,
      "sortorder": 1
    },
    {
      "id": 20106,
      "sortorder": 2
    },
    {
      "id": 20288,
      "sortorder": 3
    },
    {
      "id": 20391,
      "sortorder": 5
    },
    {
      "id": 20394,
      "sortorder": 4
    },
    {
      "id": 21063,
      "sortorder": 6
    },
    {
      "id": 21083,
      "sortorder": 7
    },
    {
      "id": 21096,
      "sortorder": 8
    },
    {
      "id": 21336,
      "sortorder": 9
    }
  ],
  "name": "Web_Provenance",
  "packageid": 123,
  "published_date": "2017-07-13 16:04:51.035552"
}

```

Encompassed within this response is lightweight data describing this group of objects as well as a unique identifier for each object and corresponding data describing the order in which the objects should appear when presented in the context of the group.

**name**  
A string describing the package of objects.  

**objects**  
A listing of the objects included in this grouping.  

`id` - The Object ID of the object. This can be used to retrieve additional data about the object using the [objects](https://github.com/danieltbrennan/puam-api-docs/blob/master/objects.md) endpoint.  
`sortorder` - An integer describing the position in which the object should appear relative to the others in the grouping when displayed in a collective context.

**packageid**  
A unique numeric identifier for the package of objects.  

**published_date**  
The date that the package of objects was most recently updated.  
