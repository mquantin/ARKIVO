# ARKIVO Ontology

## Overview

* **This Version:** Arkivo 0.3
* **Authors:** [Laura Pandolfo](mailto:lpandolfo@uniss.it), [Luca Pulina](mailto:lpulina@uniss.it) and [Marek Zielinski](mailto:MZielinski@pilsudski.org)
* **Contributors:** Pilsudski Institute of America and University of Sassari.
* **Issued:** 2020-07-09
* **Document Status:** 0.3
* **License:** This work is licensed under a [Creative Commons CC BY 4.0 license](https://creativecommons.org/licenses/by/4.0/). This copyright applies to the ARKIVO Ontology and accompanying documentation.

## What is ARKIVO ontology?

**arkivo** ontology is designed to accomodate archival description, including collection hierarchy (for archives typically as Fonds, Series, Files, Items etc.) as well as metadata of the digitized and born-digital items. It provides the way to represent historical events, people, places, organizations and other entities in archival items, as well as relationships between them. arkivo ontology is intended for presentation of archival objects and relationships in Linked Open Data environment. Regarding underlying technology, arkivo uses [OWL 2 DL](http://www.w3.org/TR/owl2-overview/) profile.

## Classes and Properties

[Latest version](https://github.com/ArkivoTeam/ARKIVO/blob/master/arkivo_0.2.owl) of the ontology.
See [documentation.pdf](https://github.com/ArkivoTeam/ARKIVO/blob/master/documentation1.2.pdf) file.

## Core Ontologies 

**arkivo** ontology has been integrated with several core ontologies and vocabularies, such as [Dublin Core metadata elements (DCMI)](http://dublincore.org/documents/dcmi-terms/), [Friend Of A Friend Vocaboluary (FOAF)](http://xmlns.com/foaf/spec/), [schema.org](http://schema.org), [the Bibliographic Ontology (BIBO)](http://bibliontology.com), [GeoNames Ontology](http://www.geonames.org/ontology/documentation.html) and [LODE](http://linkedevents.org/ontology/). 

## Application & Dataset

**arkivo** ontology has been used to model the archival collections of the **Józef Piłsudski Institute of America**.
The [RDF dataset](https://github.com/ArkivoTeam/ARKIVO/blob/master/Jo%CC%81zef_Pi%C5%82sudski_data.rdf.zip) is available under a [Creative Commons CC BY 4.0 license](https://creativecommons.org/licenses/by/4.0/) for you to download in .zip* format. 

## How to cite
Please consider citing our papers if you find the ontology and dataset useful:
```markdown
@inproceedings{arkivo19,
  author    = {Laura Pandolfo and
               Luca Pulina and
               Marek Zielinski},
  editor    = {Paolo Manghi and
               Leonardo Candela and
               Gianmaria Silvello},
  title     = {Exploring Semantic Archival Collections: The Case of Pi{\l}sudski
               Institute of America},
  booktitle = {Digital Libraries: Supporting Open Science - 15th Italian Research
               Conference on Digital Libraries, {IRCDL} 2019, Pisa, Italy, January
               31 - February 1, 2019, Proceedings},
  series    = {Communications in Computer and Information Science},
  volume    = {988},
  pages     = {107--121},
  publisher = {Springer},
  year      = {2019},
  url       = {https://doi.org/10.1007/978-3-030-11226-4\_9},
  doi       = {10.1007/978-3-030-11226-4\_9}
}
```
```markdown
@inproceedings{arkivo17,
  author    = {Laura Pandolfo and
               Luca Pulina and
               Marek Zielinski},
  editor    = {Alessandro Adamou and
               Enrico Daga and
               Leif Isaksen},
  title     = {Towards an Ontology for Describing Archival Resources},
  booktitle = {Proceedings of the Second Workshop on Humanities in the Semantic Web
               (WHiSe {II)} co-located with 16th International Semantic Web Conference
               {(ISWC} 2017), Vienna, Austria, October 22, 2017},
  series    = {{CEUR} Workshop Proceedings},
  volume    = {2014},
  pages     = {111--116},
  publisher = {CEUR-WS.org},
  year      = {2017},
  url       = {http://ceur-ws.org/Vol-2014/paper-12.pdf}
}
```
