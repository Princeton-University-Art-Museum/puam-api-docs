# Objects

Contains information describing the objects in the Princeton University Art Museum's collection.

## Get single object by ID

`GET /objects/[id]`

#### Example

> http://api.artmuseum.princeton.edu/objects/25277

#### Response

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

Encompassed within the object response is the full public catalog record for this object as determined by the Museum's research and documentation. While many of the fields in the response are self-explanatory as to what they convey, what follows is a description of each with some notes for better understanding and using the data.

**accessionyear**  
Four-digit year indicating the year the object was acquired by the museum.

Note that for some objects in the museum's collection this date may not be known, or may be null. In particular some objects such as long and short-term loans are never formally acquired, and so in those cases this value will be null.

**bibliography**  
A listing of publications in which this object has been published.

`boilertext` - A string citation for the publication, including html formatting for the handling of titles, etc.  
`date` - The four-digit year that the publication was published.

**catalogueraisonne**  
Indicates whether this work has been published in the artist's catalogue raisonné.

**creditline**  
The object's credit line, a statement indicating by what means it was acquired by the Museum.

**creditlinerepro**  
A statement such as a copyright statement that must accompany any reproduction of the object.

**datebegin**  
An integer value expressing the earliest possible date the object was created. Dates before the common era are expressed as negative integers.

**dateend**  
An integer value expressing the latest possible date the object was created. Dates before the common era are expressed as negative integers.

**department**  
The curatorial department of the Museum which is responsible for the object such as European Paintings, Asian Art, etc.

**dimensionelements**  
A list of values representing all available measurements for the object, represented as integers.

`dimension` - The numeric value of the dimension.  
`element` - The aspect of the object that the dimension represents, such as the overall measurement, the frame, etc.  
`type` - The dimension type, such as the height or width.  
`units` - The type of units in which the dimension is recorded, such as centimeters.  

**dimensions**  
A human-readable version of the object's dimensions, more suitable for display purposes.

**displaydate**  
A human-readable version of the object's date, more suitable for display purposes.

**displaytitle**  
The title of the object that should be used for display purposes.

**exhibitions**  
A listing of museum exhibitions in which this object has been included, both at the Princeton University Art Museum and elsewhere.

`begindate` - The date the exhibition began.  
`citation` - A string containing the exhibition's title, dates, and venue(s).  
`enddate` - The date the exhibition ended.  
`exhibitionid` - A unique identifier for the exhibition.  
`isvirtual` - True/false indicating if the exhibition was organized by an institution other than The Princeton University Art Museum.  

**geography**  
A string expressing a geographic location that can be related to the object in any number of ways, but most typically the location that the object was made.

**hasimage**  
Boolean indicating whether the object has an image or not.

**inscribed**  
A string describing any inscriptions on the object.

**makers**  
Describes the artists, cultures, and other entities involved in the creation of the object.

`datebegin` - Integer expressing the earliest date the entity existed (birth date in the case of an individual).  
`dateend` - Integer expressing latest date that the entity existed (death in the case of an individual).  
`displaydate` - A human-readable expression of the dates associated with the entity. In some cases also includes biographical information such as country or city of origin.  
`displayname` - A human-readable expression of the entity, as in a proper name.  
`makerid` - A unique identifier for the entity.  
`prefix` - A prefix indicating information relevant to this particular instance of the entity's relationship to the object, such as "After."  
`role` - Term indicating the entity's relationship to the object, such as Artist.  
`suffix` - A suffix indicating information relevant to this particular instance of the entity's relationship to the object.  

**markings**  
A string describing any markings present on the object.

**media**  
A list of images and other media representing or associated with the object. Note that an object can have many media items, or none at all. The majority of the collection is represented by at least one image.

`mediatypeid` - A numeric code indicating the type of media item. 1 = image.  
`restrictions` - A string indicating any relevant restrictions on image use and display.  
`uri` - An http link that can be used to retrieve the media item. In the case of images this is the base URL to the Museum's IIIF service. IIIF Image API parameters can be appended to this url in order to retrieve a file of a specified size or of other characteristics. [Learn more about IIIF](http://iiif.io).    
`rank` - The sequence in which the media item should appear relative to any others.  
`caption` - A text caption for the media item (not typically suitable for satisfying accessibility requirements).  
`isprimary` - A boolean indicating if a particular media item is to be considered the primary media for the object. In most situations, this is the media item that should be used to represent the object visually.  
`id` - A unique identifier for this media item.  

**medium**  
A string describing the materials and processes used to create the object.

**objectid**  
The Museum's numeric unique machine-readable identifier for the object. Note that by appending this id to the url string [http://artmuseum.princeton.edu/collections/objects/](http://artmuseum.princeton.edu/collections/objects/) one can also construct a link to the object's page in the Museum's online collection.  

**objectnumber**  
The museum's internal identifier for the object, most commonly expressed as a combination of a four-digit year and various prefixes/suffixes meant to indicate characteristics about the object. In the museum lexicon this is also commonly referred to as an accession number, however loans and other objects not formally accessioned by the Museum receive these numbers as well.

**published_date**  
The date that the object record was last updated.

**signed**  
A string describing the presence of a signature on the object.

**sortnumber**  
A version of the object number that has been algorithmically processed to enable intelligent sorting. By doing so one can use this value to reasonably sort objects in the order in which they have been acquired by the museum.

**terms**  
Terms from the Museum's own controlled taxonomy that describe the object.

`id` - A unique identifier for the term.  
`term` - The term.  

**texts**  
A listing of pieces of interpretive content related to the object that have been produced by the museum in the form of gallery labels, online web features, publications, etc.

`remarks` - A string describing the origin of the text such as an exhibition or a publication.  
`textentryhtml` - The text itself, including html formatting for online display.  
`texttype` - The type of text, such as gallery label.  

**titles**  
A listing of titles of the work and information about their origin and intended use. Will include any title described in the displaytitle field.

`displayorder` - The order in which this title should be displayed relative to any others.  
`title` - The title.  
`titletype` - A string describing the nature of the title. "Primary title" is by far the most common value, though others can include "Translation" or "Title of Origin."

## Get object tombstone by ID

`GET /objects/[id]/tombstone`

#### Example

> http://api.artmuseum.princeton.edu/objects/25277/tombstone

#### Response

```json

{
  "displaymaker": "Paul Cézanne, French, 1839–1906",
  "objectnumber": "L.1988.62.54",
  "creditline": "The Henry and Rose Pearlman Foundation on long term loan to the Princeton University Art Museum",
  "displaydate": "1886–88",
  "primaryimage": "http://puam-loris.aws.princeton.edu/loris/L1988-62-54_REC.jp2",
  "medium": "Pencil",
  "displaytitle": "Study of Trees",
  "objectid": 25277,
  "dimensions": "48.3 x 31.7 cm. (19 x 12 1/2 in.)"
}

```

The tombstone response offers a much simplified subset of the full object record, suitable for situations in which only the basic data needed to identify the object is required.

## Get multiple objects

`GET /objects?[param]=[value]`

In order to facilitate the retrieval of multiple objects, select criteria have been exposed as parameters. A multi-object response consists of all object records that match the selected criteria as a list object.

Available parameters are:  

- maker (ID)
- department (Exact Name)
- term (ID)

#### Example

> http://api.artmuseum.princeton.edu/objects?maker=6353

Additional query parameters can be appended to any multi-record request to control filtering, sorting, and pagination of results. The available query parameters are:

`size` - establishes the maximum number of records to be retrieved at once (integer, defaults to 10, up to a maximum of 500).  
`from` - offset position of the first result to be retrieved which can effectively be used to paginate through large result sets via multiple repeated requests (integer, defaults to 0)  
`sort` - field on which to sort results (field name, defaults to Lucene query score)  
`sortorder` - order in which to sort results ('ASC' or 'DESC', defaults to DESC)  

#### Example

> http://api.artmuseum.princeton.edu/objects?maker=6353&sort=ObjectID&sortorder=ASC

## Get all objects

Records for the entire collection can be retrieved by not specifying an endpoint. 

> http://api.artmuseum.princeton.edu/objects/
