# Princeton University Art Museum API Documentation

The Princeton University Art Museum API is a REST-style service designed to provide developer access to data about the Museum and its collections.

## Access

All requests to the API begin with:

```shell
https://data.artmuseum.princeton.edu
```

## Responses and data format

All data is in [JSON](http://json.org) format. Here is a typical response:

```json
{
  "displayperiod": "Late Classic",
  "displayculture": "Maya ('Codex' style)",
  "exhibitions": [
    {
      "enddate": "2005-01-02",
      "isvirtual": true,
      "begindate": "2004-04-04",
      "citation": "Courtly Art of the Ancient Maya (April 4, 2004–January 2, 2005)",
      "uri": "https://artmuseum.princeton.edu/art/exhibitions/559",
      "exhibitionid": 559
    },
    {
      "enddate": "2008-06-15",
      "isvirtual": true,
      "begindate": "2008-02-22",
      "citation": "An Educated Eye: The Princeton University Art Museum Collection (Friday, February 22, 2008 - Sunday, June 15, 2008)",
      "uri": "https://artmuseum.princeton.edu/art/exhibitions/961",
      "exhibitionid": 961
    },
    {
      "enddate": "1986-12-14",
      "isvirtual": true,
      "begindate": "1986-05-17",
      "citation": "The Blood of Kings: Dynasty and Ritual in Maya Art (May 17 - December 14, 1986)",
      "uri": "https://artmuseum.princeton.edu/art/exhibitions/1680",
      "exhibitionid": 1680
    },
    {
      "enddate": "1978-06-18",
      "isvirtual": true,
      "begindate": "1978-03-04",
      "citation": "Lords of the Underworld (Saturday, March 04, 1978 - Sunday, June 18, 1978)",
      "uri": "https://artmuseum.princeton.edu/art/exhibitions/1687",
      "exhibitionid": 1687
    },
    {
      "enddate": "1971-06-05",
      "isvirtual": true,
      "begindate": "1971-04-20",
      "citation": "The Maya Scribe and His World (April 20–June 5, 1971)",
      "uri": "https://artmuseum.princeton.edu/art/exhibitions/1693",
      "exhibitionid": 1693
    }
  ],
  "classification": "Ceramic",
  "daterange": "A.D. 500-1000",
  "related": [],
  "place_politic": [
    {
      "ancestors": [],
      "value": "North America",
      "level": 1
    },
    {
      "ancestors": [
        "North America"
      ],
      "value": "Guatemala",
      "level": 2
    },
    {
      "ancestors": [
        "North America",
        "Guatemala"
      ],
      "value": "Petén",
      "level": 3
    },
    {
      "ancestors": [
        "North America",
        "Guatemala",
        "Petén"
      ],
      "value": null,
      "level": 4
    }
  ],
  "texts": [
    {
      "remarks": null,
      "textentryhtml": "\r\nThe masterful calligraphic painting on the Princeton Vase is the finest known example of Maya \"codex style\" ceramic art. Graceful, sure lines painted on a cream slip present a theatrically composed mythological scene, while subtle visual devices encourage the viewer to turn the drinking vessel, adding a temporal unfolding to the visual experience. On one side (seen here), an old, toothless underworld god sits on a throne that is placed within a conventionalized depiction of a palace structure, represented by the pier behind him and what is likely a cornice above. The cornice is adorned with two jawless jaguars framing a frontal shark face. Curtains, which&nbsp;were used as doors among the ancient Maya, have been furled and tied to reveal the old lord seated within. This deity, known among scholars as God L, wears his characteristic open-weave brocaded shawl and broad-brimmed hat bedecked with owl feathers and a stuffed owl with wings outstretched. In addition to ruling Xibalba, the Maya underworld, God L was the patron deity of tobacco and merchants. Five elegant female figures — daughters or concubines — surround him. Each wears a loose, flowing sarong, decorated with batik-like dyed patterns rendered in soft brown wash, and jewelry at the ears, neck, and wrists. One of the women behind God L pours chocolate, frothing the bitter delicacy from a vessel of the same form as the Princeton Vase. A rabbit scribe, who may be spying on God L, sits below, recording the actions of the scene in a book with jaguar-pelt covers. God L delicately ties a bracelet on the woman before him, while another woman taps her foot to draw her attention—and the viewer’s—to the gruesome scene at left, in which two men wearing elaborate masks and wielding axes decapitate a bound and stripped figure. The victim’s serpent-umbilicus curls out to bite one of the executioners. The scene closely parallels a portion of the <I>Popol Vuh</I>, a sixteenth-century K’iche’ Maya mythological narrative wherein the Hero Twins trick the lords of the underworld into requesting their own decapitations. As is common in mythological narratives throughout the Americas, these heroes win the day not through Herculean feats of brute strength, but through cunning, and often humorous, trickery. The formulaic texts at the upper edge of the Princeton Vase serve to consecrate the vessel, to specify that it was intended for drinking \"maize tree\" chocolate, and to designate its owner, a lord named <I>Muwaan K’uk’</I>. The vase would have been used in courtly feasts similar to the scene depicted. </P></SPAN>",
      "textpurpose": "Handbook Entry",
      "texttype": "Online"
    },
    {
      "remarks": "2015 AAA Reinstallation - Princeton Vase",
      "textentryhtml": "<P>On this side of the famous Maya chocolate-drinking cup known as the Princeton Vase, an old, toothless underworld god sits on a throne within a palace, represented by the pier behind him and a cornice above. Curtains, which were used as doors among the ancient Maya, have been pulled up to reveal the interior scene. This deity, known among scholars as God L, wears his characteristic shawl and a broadbrimmed hat bedecked with owl feathers and an owl. In addition to ruling the Maya underworld, God L was the patron deity of tobacco and merchants. Five elegant female figures—possibly concubines— surround him. A rabbit scribe, who might be spying on God L, sits below, writing in a book. </P>\r\n<P>A standing woman with her head bent in concentration suggests that the viewer rotate the vase to the left. She holds a vessel similar in size and shape to the Princeton Vase, and a stream of liquid pours down from it, presumably into a vessel whose rendering has eroded. This method of preparation likely frothed the bitter chocolate beverage that this vessel was made to serve. The vertical pier or rear wall of a palace structure marks the boundaries of the overall composition on this vase, placing the selfreferential vignette of vessel use at the end of the scene, as a sort of addendum. </P>\r\n<P>The most important moment in the narrative of the Princeton Vase appears on this side of the vessel. Two men wearing elaborate masks and wielding axes decapitate a bound and stripped figure, seen at the lower left; the victim’s serpent-umbilicus curls out to bite one of the executioners. The scene closely parallels a portion of the Popol Vuh, a sixteenth-century K’iche’ Maya mythological narrative in which the Hero Twins trick the lords of the underworld into requesting their own decapitations. As is common in mythological narratives throughout the Americas, these heroes win the day not through feats of brute strength but through cunning, and often humorous, trickery. </P>\r\n<P>With graceful, sure lines painted on a cream slip, the Princeton Vase presents a story that stretches around the entire object. Because passing or turning the drinking cup is necessary for full comprehension of the narrative, subtle visual devices between the primary scenes encourage the viewer to rotate the vessel, creating a temporal unfolding of the visual experience. Here, for example, a young noblewoman taps the foot of the woman in front of her while turning her head in the opposite direction: she is between two scenes and encourages her companion (and thus the viewer) to shift her attention around the vase. </P>",
      "textpurpose": "Gallery Label",
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
    },
    {
      "date": 2009,
      "citation": "\"Los Codices Mayas<EM>\",</EM>&nbsp;in <EM>Códices prehispánicos y coloniales tempranos</EM>, (Mexico, D.F.: Instituto Nacional de Antropología e Historia, 2009). , p. 10-11 (illus.)",
      "boilertext": "\"Los Codices Mayas<EM>\",</EM>&nbsp;in <EM>Códices prehispánicos y coloniales tempranos</EM>, (Mexico, D.F.: Instituto Nacional de Antropología e Historia, 2009). ",
      "id": 2520,
      "uri": "http://www.worldcat.org/oclc/29789840"
    },
    {
      "date": 1993,
      "citation": "Gregorio Arribas and Manuel Pijoan, trans., <I>Los Reinos Perdidos de los Mayas</I> (Barcelona/Washington D.C.: RBA Publications/National Geographic Society, 1993)., pp. 56–57 (illus.)",
      "boilertext": "Gregorio Arribas and Manuel Pijoan, trans., <I>Los Reinos Perdidos de los Mayas</I> (Barcelona/Washington D.C.: RBA Publications/National Geographic Society, 1993).",
      "id": 2522,
      "uri": "http://www.worldcat.org/oclc/48103441"
    },
    {
      "date": 1973,
      "citation": "Michael D. Coe, <I>The Maya Scribe and His World</I> (New York: The Grolier Club, 1973). , cat. no. 42, pp. 90–93",
      "boilertext": "Michael D. Coe, <I>The Maya Scribe and His World</I> (New York: The Grolier Club, 1973). ",
      "id": 2567,
      "uri": "http://www.worldcat.org/oclc/804680"
    },
    {
      "date": 1978,
      "citation": "Michael D. Coe,<I> Lords of the Underworld: Masterpieces of Classic Maya Ceramics</I> (Princeton: Princeton University Art Museum, 1978), cat. no. 1, 16–21 (illus.); cover",
      "boilertext": "Michael D. Coe,<I> Lords of the Underworld: Masterpieces of Classic Maya Ceramics</I> (Princeton: Princeton University Art Museum, 1978)",
      "id": 2568,
      "uri": "http://www.worldcat.org/oclc/3928095"
    },
    {
      "date": 1997,
      "citation": "Michael D. Coe and Justin Kerr,<I> The Art of the Maya Scribe </I>(New York: Harry N. Abrams, 1997)., fig. 84, p. 110 (illus.)",
      "boilertext": "Michael D. Coe and Justin Kerr,<I> The Art of the Maya Scribe </I>(New York: Harry N. Abrams, 1997).",
      "id": 2570,
      "uri": "http://www.worldcat.org/oclc/38068915"
    },
    {
      "date": 1994,
      "citation": "Sophie D. Coe,<I> America's First Cuisines</I> (Austin: University of Texas Press, 1994)., cover (illus.), p. 142",
      "boilertext": "Sophie D. Coe,<I> America's First Cuisines</I> (Austin: University of Texas Press, 1994).",
      "id": 2571,
      "uri": "http://www.worldcat.org/oclc/28294829"
    },
    {
      "date": 1989,
      "citation": "Marvin Cohodas, \"Transformations: Relationships between Image and Text in the Ceramic Paintings of the Metropolitan Master,\" in <i>Word and Image in Maya Culture: Explorations in Language, Writing, and Representation,</i> ed. William F. Hanks and Don S. R (Salt Lake City: University of Utah Press, 1989)., fig. 14.3, pp. 198–231 (illus. rollout)",
      "boilertext": "Marvin Cohodas, \"Transformations: Relationships between Image and Text in the Ceramic Paintings of the Metropolitan Master,\" in <i>Word and Image in Maya Culture: Explorations in Language, Writing, and Representation,</i> ed. William F. Hanks and Don S. R (Salt Lake City: University of Utah Press, 1989).",
      "id": 2574,
      "uri": "http://www.worldcat.org/oclc/19921358"
    },
    {
      "date": 1980,
      "citation": "Jill Leslie McKeever Furst and Peter T. Furst, <I>Pre-Columbian Art of Mexico </I>(New York: Abbeville Press, 1980)., pp. 82–87 (illus.)",
      "boilertext": "Jill Leslie McKeever Furst and Peter T. Furst, <I>Pre-Columbian Art of Mexico </I>(New York: Abbeville Press, 1980).",
      "id": 2594,
      "uri": "http://www.worldcat.org/oclc/5940951"
    },
    {
      "date": 1997,
      "citation": "Adam Herring, \"A Royal Artist at Naranjo: Notes on a Late Classic Maya Cylinder Vessel,\" <I>Yale University Art Gallery Bulletin</I> (1995-1996): 34-47., fig. 3, pp. 34–47 (illus. rollout)",
      "boilertext": "Adam Herring, \"A Royal Artist at Naranjo: Notes on a Late Classic Maya Cylinder Vessel,\" <I>Yale University Art Gallery Bulletin</I> (1995-1996): 34-47.",
      "id": 2611,
      "uri": "http://www.worldcat.org/oclc/5542981498"
    },
    {
      "date": 2010,
      "citation": "Stephen D. Houston and Karl A. Taube, \"La sexualidad entre los antiguos mayas,\" <EM>Arqueología Mexicana</EM> 18, no. 104 (Jul.-Aug., 2010): p. 38-45., p. 43 (illus.)",
      "boilertext": "Stephen D. Houston and Karl A. Taube, \"La sexualidad entre los antiguos mayas,\" <EM>Arqueología Mexicana</EM> 18, no. 104 (Jul.-Aug., 2010): p. 38-45.",
      "id": 2614,
      "uri": "http://www.worldcat.org/oclc/29789840"
    },
    {
      "date": 2006,
      "citation": "Stephen D. Houston, David Stuart, and Karl Taube, <I>The Memory of Bones: Body, Being, and Experience among the Classic Maya</I> (Austin: University of Texas Press, 2006)., p. 108",
      "boilertext": "Stephen D. Houston, David Stuart, and Karl Taube, <I>The Memory of Bones: Body, Being, and Experience among the Classic Maya</I> (Austin: University of Texas Press, 2006).",
      "id": 2616,
      "uri": "http://www.worldcat.org/oclc/61660268"
    },
    {
      "date": 2009,
      "citation": "Stephen D. Houston et al., <I>Veiled Brightness: A History of Ancient Maya Color</I> (Austin, University of Texas Press, 2009)., fig. 1.1b (illus. rollout)",
      "boilertext": "Stephen D. Houston et al., <I>Veiled Brightness: A History of Ancient Maya Color</I> (Austin, University of Texas Press, 2009).",
      "id": 2617,
      "uri": "http://www.worldcat.org/oclc/230730263"
    },
    {
      "date": 2009,
      "citation": "Sarah E. Jackson, \"Imagining Courtly Communities: An Exploration of Classic Maya Experiences of Status and Identity through Painted Ceramic Vessels,\" <i>Ancient Mesoamerica</i>&nbsp;20,&nbsp;no. 1&nbsp;(Spring, 2009): p. 71-85., fig. 7, pp. 71–85 (illus. rollout line drawing)",
      "boilertext": "Sarah E. Jackson, \"Imagining Courtly Communities: An Exploration of Classic Maya Experiences of Status and Identity through Painted Ceramic Vessels,\" <i>Ancient Mesoamerica</i>&nbsp;20,&nbsp;no. 1&nbsp;(Spring, 2009): p. 71-85.",
      "id": 2620,
      "uri": "http://www.worldcat.org/oclc/658198379"
    },
    {
      "date": 2012,
      "citation": "Bryan R. Just, <I>Dancing into Dreams: Maya Vase Painting of the Ik' Kingdom </I>(Princeton, Princeton University Art Museum, 2012)., fig. 71b, p. 137",
      "boilertext": "Bryan R. Just, <I>Dancing into Dreams: Maya Vase Painting of the Ik' Kingdom </I>(Princeton, Princeton University Art Museum, 2012).",
      "id": 2627,
      "uri": "http://www.worldcat.org/oclc/810947235"
    },
    {
      "date": 2010,
      "citation": "Justin Kerr, \"The Maya Cylinder: A Short History Unrolled,\" in <I>Adventures in Pre-Columbian Studies: Essays in Honor of Elizabeth P. Benson</I>, ed. Julie Jones (Washington D.C.: Pre-Columbian Society of Washington, D.C.): 99-118., fig. 2",
      "boilertext": "Justin Kerr, \"The Maya Cylinder: A Short History Unrolled,\" in <I>Adventures in Pre-Columbian Studies: Essays in Honor of Elizabeth P. Benson</I>, ed. Julie Jones (Washington D.C.: Pre-Columbian Society of Washington, D.C.): 99-118.",
      "id": 2637,
      "uri": "http://www.worldcat.org/oclc/839045723"
    },
    {
      "date": 1988,
      "citation": "Barbara Kerr and Justin Kerr, \"Some Observations on Maya Vase Painters,\" in <I>Maya Iconography</I>, eds. Elizabeth P. Benson and Gillett G. Griffin (Princeton: Princeton University Press, 1988)., figs. 7.1, 7.3a, 7.4a, 7.5a, 7.6a, 7.7a, 7.8a and 7.9a, pp. 236–259 (illus.)",
      "boilertext": "Barbara Kerr and Justin Kerr, \"Some Observations on Maya Vase Painters,\" in <I>Maya Iconography</I>, eds. Elizabeth P. Benson and Gillett G. Griffin (Princeton: Princeton University Press, 1988).",
      "id": 2639,
      "uri": "http://www.worldcat.org/oclc/77851364"
    },
    {
      "date": 1986,
      "citation": "Mary Ellen Miller, <I>The Murals of Bonampak</I> (Princeton: Princeton University Press, 1986)., fig. 38 (illus.)",
      "boilertext": "Mary Ellen Miller, <I>The Murals of Bonampak</I> (Princeton: Princeton University Press, 1986).",
      "id": 2645,
      "uri": "http://www.worldcat.org/oclc/11623862"
    },
    {
      "date": 2002,
      "citation": "Terry G. Powis et al., \"Spouted Vessels and Cacao Use among the Preclassic Maya,\" <I>Latin American antiquity </I>13, no. 1 (2002): 85-106., fig. 8b, pp. 85–106 (illus.)",
      "boilertext": "Terry G. Powis et al., \"Spouted Vessels and Cacao Use among the Preclassic Maya,\" <I>Latin American antiquity </I>13, no. 1 (2002): 85-106.",
      "id": 2659,
      "uri": "http://www.worldcat.org/oclc/5546400390"
    },
    {
      "date": 1994,
      "citation": "Dorie Reents-Budet,<I> Painting the Maya Universe: Royal Ceramics of the Classic Period</I> (Durham and London: Duke University Press, 1994)., fig. 2.4, cat. no. 89, p. 39 (illus.); pp. 356–357 (illus.); fig. 2.26, pp. 57 (illus.)",
      "boilertext": "Dorie Reents-Budet,<I> Painting the Maya Universe: Royal Ceramics of the Classic Period</I> (Durham and London: Duke University Press, 1994).",
      "id": 2665,
      "uri": "http://www.worldcat.org/oclc/28632069"
    },
    {
      "date": 1981,
      "citation": "Francis Robiscek, <I>The Maya Book of the Dead: The Ceramic Codex</I> (Charlottesville: University of Virginia Art Museum, 1981)., Vessel 1 (illus.)",
      "boilertext": "Francis Robiscek, <I>The Maya Book of the Dead: The Ceramic Codex</I> (Charlottesville: University of Virginia Art Museum, 1981).",
      "id": 2672,
      "uri": "http://www.worldcat.org/oclc/9073379"
    },
    {
      "date": 2004,
      "citation": "Daniel Schávelzon, <EM>Treinta siglos de imágenes : maquetas y representaciones de arquitectura en México y América Central prehispánica</EM> (Buenos Aires: Ediciones Fundación CEPPA, 2004)., p. 192 (illus. rollout drawing)",
      "boilertext": "Daniel Schávelzon, <EM>Treinta siglos de imágenes : maquetas y representaciones de arquitectura en México y América Central prehispánica</EM> (Buenos Aires: Ediciones Fundación CEPPA, 2004).",
      "id": 2677,
      "uri": "http://www.worldcat.org/oclc/61710274"
    },
    {
      "date": 1986,
      "citation": "Linda Schele and Mary E. Miller,<i> The Blood of Kings: Dynasty and Ritual in Maya Art</i> (New York and Fort Worth, George Braziller, Inc. and Kimbell Art Museum, 1986)., pls. 115 and 115a, pp. 286–287, p. 296 (illus.)",
      "boilertext": "Linda Schele and Mary E. Miller,<i> The Blood of Kings: Dynasty and Ritual in Maya Art</i> (New York and Fort Worth, George Braziller, Inc. and Kimbell Art Museum, 1986).",
      "id": 2678,
      "uri": "http://www.worldcat.org/oclc/13327308"
    },
    {
      "date": 2013,
      "citation": "Daniela Soleri, Marcus Winter, Steven R. Bozarth, and W. Jeffrey Hurst, \"Archaeological Residues and Recipes: Exploratory Testing for Evidence of Maize and Cacao Beverages in Postclassic Vessels from the Valley of Oaxaca,\" <em>Latin American antiquity </em>24, no. 3 (2013): p. 345-362., fig. 1, p. 348 (illus. detail drawing)",
      "boilertext": "Daniela Soleri, Marcus Winter, Steven R. Bozarth, and W. Jeffrey Hurst, \"Archaeological Residues and Recipes: Exploratory Testing for Evidence of Maize and Cacao Beverages in Postclassic Vessels from the Valley of Oaxaca,\" <em>Latin American antiquity </em>24, no. 3 (2013): p. 345-362.",
      "id": 2689,
      "uri": "http://www.worldcat.org/oclc/862152372"
    },
    {
      "date": 1993,
      "citation": "Gene S. Stuart and George E. Stuart,<I> Lost Kingdoms of the Maya</I> (Washington, D.C.: National Geographic Society, 1993)., pp. 56–57 (illus. rollout)",
      "boilertext": "Gene S. Stuart and George E. Stuart,<I> Lost Kingdoms of the Maya</I> (Washington, D.C.: National Geographic Society, 1993).",
      "id": 2703,
      "uri": "http://www.worldcat.org/oclc/27012239"
    },
    {
      "date": 1999,
      "citation": "Caroline E. Tate, \"Writing on the face of the moon: Women's products, archetypes, and power in ancient Maya civilization,\" in <I>Manifesting Power: Gender and the Interpretation of Power in Archaeology</I>, ed. Tracey Sweely (London; New York: Routledge, 1999)., fig. 5.2, pp. 81–102 (illus.)",
      "boilertext": "Caroline E. Tate, \"Writing on the face of the moon: Women's products, archetypes, and power in ancient Maya civilization,\" in <I>Manifesting Power: Gender and the Interpretation of Power in Archaeology</I>, ed. Tracey Sweely (London; New York: Routledge, 1999).",
      "id": 2705,
      "uri": "http://www.worldcat.org/oclc/39706906"
    },
    {
      "date": 2008,
      "citation": "Erik Velásquez García, \"El Vaso de Princeton: Un ejemplo del estilo códice,\" <em>Arqueología Mexicana</em> 16, no. 93 (Oct., 2008): 51-59., pp. 51–59 (illus.)",
      "boilertext": "Erik Velásquez García, \"El Vaso de Princeton: Un ejemplo del estilo códice,\" <em>Arqueología Mexicana</em> 16, no. 93 (Oct., 2008): 51-59.",
      "id": 2720,
      "uri": "http://www.worldcat.org/oclc/29789840"
    },
    {
      "date": 2009,
      "citation": "Erik Velásquez García, \"Reflections on the Codex Style and the Princeton Vessel,\" <i>The PARI Journal</i> 10, no. 1 (2009): 1-16., p. 1–16",
      "boilertext": "Erik Velásquez García, \"Reflections on the Codex Style and the Princeton Vessel,\" <i>The PARI Journal</i> 10, no. 1 (2009): 1-16.",
      "id": 2721,
      "uri": "http://www.worldcat.org/oclc/44780248"
    },
    {
      "date": 2010,
      "citation": "Marc Zender, \"Baj 'Hammer' and Related Affective Verbs in Classic Mayan,\" <i>The PARI Journal</i> 11, no. 2 (2010): 1-16., fig. 3b, pp. 10–16 (illus. line detail drawing)",
      "boilertext": "Marc Zender, \"Baj 'Hammer' and Related Affective Verbs in Classic Mayan,\" <i>The PARI Journal</i> 11, no. 2 (2010): 1-16.",
      "id": 2733,
      "uri": "http://www.worldcat.org/oclc/720374055"
    },
    {
      "date": 2005,
      "citation": "Allen Rosenbaum, \"'Gillett and Me': How a Eurocentric Museum Director Learned to Love Pre-Columbian Art,\"&nbsp;<em>Record of the Princeton University Art Museum</em> 64 (2005): 8-19., fig. 1, p. 8; fig. 2, p. 9; fig. 3, p. 10",
      "boilertext": "Allen Rosenbaum, \"'Gillett and Me': How a Eurocentric Museum Director Learned to Love Pre-Columbian Art,\"&nbsp;<em>Record of the Princeton University Art Museum</em> 64 (2005): 8-19.",
      "id": 2745,
      "uri": "http://www.worldcat.org/oclc/5546635691"
    },
    {
      "date": 2005,
      "citation": "Barbara Kerr and Justin Kerr, \"The Way of God L: The Princeton Vase Revisited,\"&nbsp;<EM>Record of the Princeton University Art Museum</EM> 64 (2005): 71-79., p. 71, figs. 1–2; p. 72, fig. 3; p. 74, fig. 6; p. 78, fig. 15",
      "boilertext": "Barbara Kerr and Justin Kerr, \"The Way of God L: The Princeton Vase Revisited,\"&nbsp;<EM>Record of the Princeton University Art Museum</EM> 64 (2005): 71-79.",
      "id": 2747,
      "uri": "http://www.worldcat.org/oclc/5546709519"
    },
    {
      "date": 2000,
      "citation": "Nikolai Grube, ed., <EM>Maya: Gottkönige im Regenwald</EM> (Köln: Könemann Verlagsgesellschaft, 2000)., Appendix title page (illus.)",
      "boilertext": "Nikolai Grube, ed., <EM>Maya: Gottkönige im Regenwald</EM> (Köln: Könemann Verlagsgesellschaft, 2000).",
      "id": 2955,
      "uri": "http://www.worldcat.org/oclc/45989737"
    },
    {
      "date": 2008,
      "citation": "Ana García Barrios, \"Chaahk, el Dios de la Lluvia, en el Periodo Clásico Maya: Aspectos Religiosos y Políticos\" (PhD diss. unpublished, Universidad Compultense de Madrid, 2008)., fig. 1.55 (illus.)",
      "boilertext": "Ana García Barrios, \"Chaahk, el Dios de la Lluvia, en el Periodo Clásico Maya: Aspectos Religiosos y Políticos\" (PhD diss. unpublished, Universidad Compultense de Madrid, 2008).",
      "id": 2947,
      "uri": "http://www.worldcat.org/oclc/847466857"
    },
    {
      "date": 2004,
      "citation": "Mary E. Miller and Simon Martin, <EM>Courtly Art of the Ancient Maya</EM> (San Francisco: Fine Arts Museum of San Fransisco, 2004)., pl. 32 (and rollout), 76–77 (illus.)",
      "boilertext": "Mary E. Miller and Simon Martin, <EM>Courtly Art of the Ancient Maya</EM> (San Francisco: Fine Arts Museum of San Fransisco, 2004).",
      "id": 2924,
      "uri": "http://www.worldcat.org/oclc/54799516"
    },
    {
      "date": 2008,
      "citation": "\"Mysteries of the Maya: the rise, glory and collapse of an ancient civilization,\" National Geographic Collector's Edition (Washington, D.C.: National Geographic Society, 2008)., p. 95 (illus.)",
      "boilertext": "\"Mysteries of the Maya: the rise, glory and collapse of an ancient civilization,\" National Geographic Collector's Edition (Washington, D.C.: National Geographic Society, 2008).",
      "id": 2927,
      "uri": "http://www.worldcat.org/oclc/271452657"
    },
    {
      "date": 1986,
      "citation": "Gillett G. Griffin, \"In Defense of the Collector,\" <i>National Geographic</i> vol. 169, no. 4 (April 1986): 462-465., pp. 462–465, p. 464 (illus.)",
      "boilertext": "Gillett G. Griffin, \"In Defense of the Collector,\" <i>National Geographic</i> vol. 169, no. 4 (April 1986): 462-465.",
      "id": 2784,
      "uri": "http://www.worldcat.org/oclc/6451257"
    },
    {
      "date": 1992,
      "citation": "Michael Olmert, <I>Smithsonian Book of Books</I> (Washington: Smithsonian Books, 1992)., pp. 34–35",
      "boilertext": "Michael Olmert, <I>Smithsonian Book of Books</I> (Washington: Smithsonian Books, 1992).",
      "id": 2785,
      "uri": "http://www.worldcat.org/oclc/24907462"
    },
    {
      "date": 1990,
      "citation": "Terence Grieder, <I>Artist and Audience </I>(New York: Holt, Rinehart, and Winston, 1990)., fig. 421, p. 300 (illus.)",
      "boilertext": "Terence Grieder, <I>Artist and Audience </I>(New York: Holt, Rinehart, and Winston, 1990).",
      "id": 2786,
      "uri": "http://www.worldcat.org/oclc/19922701"
    },
    {
      "date": 1996,
      "citation": "Steve J. Stern, \"The Tricks of Time: Colonial Legacies and Historical Sensibilities inLatin America,\" <I>Princeton University Library Chronicle</I>, vol. LVII, no. 3, (Spring 1996): 373., p. 353 (illus.)",
      "boilertext": "Steve J. Stern, \"The Tricks of Time: Colonial Legacies and Historical Sensibilities inLatin America,\" <I>Princeton University Library Chronicle</I>, vol. LVII, no. 3, (Spring 1996): 373.",
      "id": 2787,
      "uri": "http://www.worldcat.org/oclc/1695247"
    },
    {
      "date": 2015,
      "citation": "Alejandra Martínez de Velasco Cotrina and María Elena Vega Villalobos, eds. <I>The Maya: Voices in Stone</I>, 2nd ed.&nbsp;(Mexico City; Madrid: Turner/Ámbar Diseño, A´mbar Disen~o: Universidad Nacional Auto´noma de Me´xico: Turner, 2015)., fig. 193 (illus.)",
      "boilertext": "Alejandra Martínez de Velasco Cotrina and María Elena Vega Villalobos, eds. <I>The Maya: Voices in Stone</I>, 2nd ed.&nbsp;(Mexico City; Madrid: Turner/Ámbar Diseño, A´mbar Disen~o: Universidad Nacional Auto´noma de Me´xico: Turner, 2015).",
      "id": 6331,
      "uri": "http://www.worldcat.org/oclc/919237012"
    },
    {
      "date": 1976,
      "citation": "\"Acquisitions of the Art Museum 1975,\" <em>Record of the Art Museum, Princeton University,</em> 35, no. 1 (1976): p. 22-31., p. 31 (illus.)",
      "boilertext": "\"Acquisitions of the Art Museum 1975,\" <em>Record of the Art Museum, Princeton University,</em> 35, no. 1 (1976): p. 22-31.",
      "id": 3366,
      "uri": "http://www.worldcat.org/oclc/5546667988"
    },
    {
      "date": 1986,
      "citation": "Allen Rosenbaum and Francis F. Jones,<em> Selections from The Art Museum, Princeton University, </em>(Princeton,&nbsp;NJ: The Art Museum, Princeton University, 1986)., p. 255 (illus.)",
      "boilertext": "Allen Rosenbaum and Francis F. Jones,<em> Selections from The Art Museum, Princeton University, </em>(Princeton,&nbsp;NJ: The Art Museum, Princeton University, 1986).",
      "id": 1899,
      "uri": "http://www.worldcat.org/oclc/14244748"
    },
    {
      "date": 2013,
      "citation": "Alexandre Tokovinine and Dmitri Beliaev, “People of the Road: Traders and Travelers in Ancient Maya Words and Images,” in <EM>Merchants, Markets, and Exchange in the Pre-Columbian World</EM>, Kenneth G. Hirth and Joanne Pillsbury, eds., (Washington D.C.: Dumbarton Oaks, 2013),&nbsp;pp. 169–200 , p. 187",
      "boilertext": "Alexandre Tokovinine and Dmitri Beliaev, “People of the Road: Traders and Travelers in Ancient Maya Words and Images,” in <EM>Merchants, Markets, and Exchange in the Pre-Columbian World</EM>, Kenneth G. Hirth and Joanne Pillsbury, eds., (Washington D.C.: Dumbarton Oaks, 2013),&nbsp;pp. 169–200 ",
      "id": 6723,
      "uri": "http://www.worldcat.org/oclc/795909454"
    },
    {
      "date": 2016,
      "citation": "<p>Stephen D. Houston,&nbsp;\"Kill All the Lawyers,\" <em>Maya Decipherment</em> (blog),&nbsp;December 28, 2016, <a href=\"https://decipherment.wordpress.com/2016/12/28/kill-all-the-lawyers/\">https://decipherment.wordpress.com/2016/12/28/kill-all-the-lawyers/</a></p>, fig. 3a",
      "boilertext": "<p>Stephen D. Houston,&nbsp;\"Kill All the Lawyers,\" <em>Maya Decipherment</em> (blog),&nbsp;December 28, 2016, <a href=\"https://decipherment.wordpress.com/2016/12/28/kill-all-the-lawyers/\">https://decipherment.wordpress.com/2016/12/28/kill-all-the-lawyers/</a></p>",
      "id": 6809,
      "uri": null
    },
    {
      "date": 2018,
      "citation": "<font face=\"Times New Roman\" size=\"3\">\n\n</font><p style=\"margin: 0in 0in 8pt;\"><span style='line-height: 107%; font-family: \"Arial\",sans-serif; font-size: 9pt; mso-bidi-font-style: italic;'><span style='line-height: 107%; font-family: \"Arial\",sans-serif; font-size: 9pt; mso-bidi-font-style: italic;'>Stephen Houston. “What Writing\nLooks Like.” Maya Decipherment: Ideas on Ancient Maya Writing and Iconography,\nJune 28, 2018. <a href=\"https://decipherment.wordpress.com/2018/06/28/what-writing-looks-like/\"><font color=\"#0563c1\">https://decipherment.wordpress.com/2018/06/28/what-writing-looks-like/</font></a></span></span></p><font face=\"Times New Roman\" size=\"3\">\n\n</font>",
      "boilertext": "<font face=\"Times New Roman\" size=\"3\">\n\n</font><p style=\"margin: 0in 0in 8pt;\"><span style='line-height: 107%; font-family: \"Arial\",sans-serif; font-size: 9pt; mso-bidi-font-style: italic;'><span style='line-height: 107%; font-family: \"Arial\",sans-serif; font-size: 9pt; mso-bidi-font-style: italic;'>Stephen Houston. “What Writing\nLooks Like.” Maya Decipherment: Ideas on Ancient Maya Writing and Iconography,\nJune 28, 2018. <a href=\"https://decipherment.wordpress.com/2018/06/28/what-writing-looks-like/\"><font color=\"#0563c1\">https://decipherment.wordpress.com/2018/06/28/what-writing-looks-like/</font></a></span></span></p><font face=\"Times New Roman\" size=\"3\">\n\n</font>",
      "id": 9261,
      "uri": null
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
    },
    {
      "mediatypeid": 1,
      "restrictions": null,
      "uri": "https://puam-loris.aws.princeton.edu/loris/y1975-17_A.jp2",
      "rank": 5,
      "caption": "Luna Digitization Project",
      "isprimary": 0,
      "id": 7488
    },
    {
      "mediatypeid": 1,
      "restrictions": null,
      "uri": "https://puam-loris.aws.princeton.edu/loris/y1975-17_1.jp2",
      "rank": 6,
      "caption": "Luna Digitization Project",
      "isprimary": 0,
      "id": 7485
    },
    {
      "mediatypeid": 1,
      "restrictions": null,
      "uri": "https://puam-loris.aws.princeton.edu/loris/y1975-17_DET.jp2",
      "rank": 7,
      "caption": "Luna Digitization Project",
      "isprimary": 0,
      "id": 7489
    },
    {
      "mediatypeid": 1,
      "restrictions": null,
      "uri": "https://puam-loris.aws.princeton.edu/loris/y1975-17_2.jp2",
      "rank": 8,
      "caption": "Luna Digitization Project",
      "isprimary": 0,
      "id": 7486
    },
    {
      "mediatypeid": 1,
      "restrictions": null,
      "uri": "https://puam-loris.aws.princeton.edu/loris/y1975-17_3.jp2",
      "rank": 9,
      "caption": "Luna Digitization Project",
      "isprimary": 0,
      "id": 7487
    },
    {
      "mediatypeid": 1,
      "restrictions": null,
      "uri": "https://puam-loris.aws.princeton.edu/loris/y1975-17_1A.jp2",
      "rank": 10,
      "caption": "Contract Photographer",
      "isprimary": 0,
      "id": 15425
    },
    {
      "mediatypeid": 1,
      "restrictions": null,
      "uri": "https://puam-loris.aws.princeton.edu/loris/y1975-17_DETX.jp2",
      "rank": 11,
      "caption": "Contract Photographer",
      "isprimary": 0,
      "id": 15426
    },
    {
      "mediatypeid": 7,
      "restrictions": null,
      "uri": "https://puam-loris.aws.princeton.edu/loris/research.mayavase.com/kerrmaya_list.php?_allSearch",
      "rank": 12,
      "caption": "Kerr Maya Vase Database",
      "isprimary": 0,
      "id": 15219
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
    },
    {
      "term": "vases",
      "aatid": 300132254,
      "id": 2073530,
      "termtype": "Classification"
    },
    {
      "term": "drinking vessels",
      "aatid": 300194567,
      "id": 2076085,
      "termtype": "Classification"
    },
    {
      "term": "courts (social groups)",
      "aatid": 300236519,
      "id": 2087878,
      "termtype": "Subject"
    },
    {
      "term": "men",
      "aatid": 300025928,
      "id": 2088270,
      "termtype": "Subject"
    },
    {
      "term": "women",
      "aatid": 300025943,
      "id": 2088280,
      "termtype": "Subject"
    },
    {
      "term": "scribes",
      "aatid": 300025580,
      "id": 2092754,
      "termtype": "Subject"
    },
    {
      "term": "heroes",
      "aatid": 300236801,
      "id": 2095051,
      "termtype": "Subject"
    },
    {
      "term": "mythology",
      "aatid": 300055985,
      "id": 2096051,
      "termtype": "Subject"
    },
    {
      "term": "iconography",
      "aatid": 300055859,
      "id": 2096251,
      "termtype": "Subject"
    },
    {
      "term": "hieroglyphics",
      "aatid": 300028721,
      "id": 2118718,
      "termtype": "Subject"
    },
    {
      "term": "banquets",
      "aatid": 300247614,
      "id": 2134667,
      "termtype": "Subject"
    },
    {
      "term": "mythical or legendary beings",
      "aatid": null,
      "id": 2147420,
      "termtype": "Subject"
    },
    {
      "term": "rabbits",
      "aatid": null,
      "id": 2158063,
      "termtype": "Subject"
    },
    {
      "term": "jaguars",
      "aatid": null,
      "id": 2158072,
      "termtype": "Subject"
    },
    {
      "term": "gods",
      "aatid": null,
      "id": 2171856,
      "termtype": "Subject"
    },
    {
      "term": "slip",
      "aatid": 300010459,
      "id": 2160397,
      "termtype": "Materials"
    },
    {
      "term": "ceramic",
      "aatid": 300235507,
      "id": 2160750,
      "termtype": "Materials"
    },
    {
      "term": "stucco",
      "aatid": 300014966,
      "id": 2167544,
      "termtype": "Materials"
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
  "place_geo": [
    {
      "ancestors": [],
      "value": "North America",
      "level": 1
    },
    {
      "ancestors": [
        "North America"
      ],
      "value": "Mesoamerica",
      "level": 2
    },
    {
      "ancestors": [
        "North America",
        "Mesoamerica"
      ],
      "value": "Mirador Basin",
      "level": 3
    },
    {
      "ancestors": [
        "North America",
        "Mesoamerica",
        "Mirador Basin"
      ],
      "value": "Central lowlands",
      "level": 4
    }
  ],
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

## Available resources

Currently three endpoints providing access to three primary resource types from the Princeton University Art Museum are available via this API, as well as a full-text search endpoint:

* [Objects](https://github.com/danieltbrennan/puam-api-docs/blob/master/objects.md)
* [Makers](https://github.com/danieltbrennan/puam-api-docs/blob/master/makers.md)
* [Packages](https://github.com/danieltbrennan/puam-api-docs/blob/master/packages.md)
* [Search](https://github.com/danieltbrennan/puam-api-docs/blob/master/search.md)

## Feedback and Questions

If you have a feature request or find a bug, [please open a GitHub issue](https://github.com/danieltbrennan/puam-api-docs/issues/new).

For more general inquiries regarding the API, [e-mail is preferred](mailto:dbrennan@princeton.edu).
