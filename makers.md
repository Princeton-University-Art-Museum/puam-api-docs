# Makers

Contains information describing artists, cultural groups, and other makers of objects in the Princeton University Art Museum's collection.

## Get single maker by ID

`GET /makers/[id]`

#### Example

> http://api.artmuseum.princeton.edu/makers/6353

#### Response

```json

{
    "makerid": 6353,
    "displaybio": "French, 1839–1906",
    "culturegroup": null,
    "displayname": "Paul Cézanne",
    "firstname": "Paul",
    "middlename": null,
    "alphasort": "Cézanne, Paul",
    "begindate": 1839,
    "altnames": [
      {
        "nametype": "Primary Name",
        "displayname": "Paul Cézanne",
        "firstname": "Paul",
        "middlename": null,
        "alphasort": "Cézanne, Paul",
        "culturegroup": null,
        "lastname": "Cézanne",
        "nametitle": null
      }
    ],
    "published_date": "2017-06-14 05:01:55.395427",
    "lastname": "Cézanne",
    "nametitle": null,
    "enddate": 1906,
    "nationality": "French",
    "makertype": "Individual",
    "biography": "Cézanne modulated warm and cool hues to depict depth and surface and used his constructive brushstroke, rather than perspective or foreshortening, to build up form and structure. Since 1890, his complex painting has influenced nearly every avant-garde movement in painting, including Cubism and abstract art. In his early career, he was strongly influenced by Delacroix and Courbet, using thick slabs of paint to give his early works a sculptural presence and intensity. He exhibited with the Impressionists, but eventually rejected what he considered the Impressionists' lack of structure, declaring his intention to make Impressionism into \"something solid and durable, like the art of museums.\" French artist (ULAN).",
    "identifiers": [
      {
        "source": "ULAN",
        "id": "500004793"
      },
      {
        "source": "VIAF",
        "id": "http://viaf.org/viaf/39374836"
      }
    ]
  }

```

Encompassed within this response is the full public catalog record for this maker as determined by the Museum's research and documentation. While many of the fields in the response are self-explanatory as to what they convey, what follows is a description of each with some notes for better understanding and using the data.

**alphasort**  
A version of the maker's name or title ordered in such a manner as to facilitate alphabetical sorting.

**altnames**  
A listing of names by which this maker may be referred.

`nametype` - A categorization describing the nature of this name, most commonly 'Primary Name'
`displayname`- A rendering of this name or title of the maker that is suitable for display purposes.  
`firstname` - The maker's first name.
`middlename` - The maker's middle name.
`alphasort` - A version of the maker's name or title ordered in such a manner as to facilitate alphabetical sorting.
`culturegroup` - Describes the cultural group to which this maker can be associated, if applicable.
`lastname` - The maker's last name.
`nametitle` - A title such as 'Rev.' or 'Major' that is associated with the maker.

**begindate**  
Integer representation of the earliest possible date associated with the maker (birth, as in the case of an individual). Dates before the Common Era are represented as negative values.

**culturegroup**  
Describes the cultural group to which this maker can be associated, if applicable.

**displaybio**  
A brief biographical note describing the maker, most typically containing life or period dates and place of origin if applicable.  

**displayname**  
A rendering of the name or title of the maker that is suitable for display purposes.  

**enddate**
Integer representation of the latest possible date associated with the maker (death, as in the case of an individual). Dates before the Common Era are represented as negative values.

**firstname**  
The maker's first name.

**identifiers**  
A listing of web resources such as biographical dictionaries or name authorities in which this maker can be found.

`id` - An identifier, often a URI, that can be used to retrieve this particular maker from the resource in question.  
`source` - The name of the web resource.

**lastname**  
The maker's last name.

**makerid**  
The numeric identifier for this maker record.

**makertype**  
A categorization describing the nature of the maker, such as 'individual' or 'organization'.  

**middlename**  
The maker's middle name.

**nametitle**  
A title such as 'Rev.' or 'Major' that is associated with the maker.

**nationality**
The nationality associated with the maker.

**published_date**
The date this maker record was last updated.
