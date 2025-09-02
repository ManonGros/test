**Old term**

**Definition:** An identifier for the Organism instance (as opposed to a particular digital record of the Organism). May be a globally unique identifier or an identifier specific to the data set.
**Label:** Organism ID
**Term Name:** dwc:organismID
**Term version IRI:** http://rs.tdwg.org/dwc/terms/version/organismID-2017-10-06
**Version of:** http://rs.tdwg.org/dwc/terms/organismID
**Issued:** 2017-10-06
**Type:** Property
**Status:** superseded
**Replaces:** http://rs.tdwg.org/dwc/terms/version/organismID-2014-10-23


| definitions | context 1 |context 2 |context 3 |context 4 |
|-|-|-|-|-|
| **Context - tables concerned** | <ul><li>identification</li></ul> | <ul><li>occurrence</li></ul> | <ul><li>organism-assertion</li><li>organism-identifier</li><li>organism-reference</li></ul> | <ul><li>organism</li></ul> |
| **key** | fk | fk | fk | pk |
| **title** | Organism ID | Organism ID | Organism ID | Organism ID |
| **description** | An identifier for a dwc:Organism based on which a dwc:Identification was made. | An identifier for a dwc:Organism. | An identifier for a dwc:Organism. | An identifier for a dwc:Organism. |
| **comments** | Recommended best practice is to use a globally unique identifier. |  | Recommended best practice is to use a persistent, globally unique identifier. | Recommended best practice is to use a persistent, globally unique identifier. |
| **example** |  |  |  |  |
| **type** | string | string | string | string |
| **format** | default | default | default | default |
| **unique** | False | False | False | True |
| **required** | False | False | True | True |
| **minimum** |  |  |  |  |
| **maximum** |  |  |  |  |
| **namespace** | dwc | dwc | dwc | dwc |
| **dcterms:isVersionOf** | http://rs.tdwg.org/dwc/terms/organismID | http://rs.tdwg.org/dwc/terms/organismID | http://rs.tdwg.org/dwc/terms/organismID | http://rs.tdwg.org/dwc/terms/organismID |
| **dcterms:references** | http://rs.tdwg.org/dwc/terms/version/organismID-2017-10-06 | http://rs.tdwg.org/dwc/terms/version/organismID-2023-06-28 | http://rs.tdwg.org/dwc/terms/version/organismID-2023-06-28 | http://rs.tdwg.org/dwc/terms/version/organismID-2023-06-28 |
| **rdfs:comment** | An identifier for the dwc:Organism instance (as opposed to a particular digital record of the dwc:Organism). May be a globally unique identifier or an identifier specific to the data set. | An identifier for the dwc:Organism instance (as opposed to a particular digital record of the dwc:Organism). May be a globally unique identifier or an identifier specific to the data set. | An identifier for the dwc:Organism instance (as opposed to a particular digital record of the dwc:Organism). May be a globally unique identifier or an identifier specific to the data set. | An identifier for the dwc:Organism instance (as opposed to a particular digital record of the dwc:Organism). May be a globally unique identifier or an identifier specific to the data set. |
| **status** | recommended | recommended | recommended | recommended |
