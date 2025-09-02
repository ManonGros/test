**Old term**

**Definition:** An identifier for the dwc:Identification (the body of information associated with the assignment of a scientific name). May be a global unique identifier or an identifier specific to the data set.
**Label:** Identification ID
**Term Name:** dwc:identificationID
**Term version IRI:** http://rs.tdwg.org/dwc/terms/version/identificationID-2023-06-28
**Version of:** http://rs.tdwg.org/dwc/terms/identificationID
**Issued:** 2023-06-28
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/dwc/terms/version/identificationID-2017-10-06


| definitions | context 1 |context 2 |context 3 |context 4 |
|-|-|-|-|-|
| **Context - tables concerned** | <ul><li>identification-agent-role</li></ul> | <ul><li>identification-taxon</li></ul> | <ul><li>identification-reference</li></ul> | <ul><li>identification</li></ul> |
| **key** | fk | fk | fk | pk |
| **title** | Identification ID | Identification ID | Identification ID | Identification ID |
| **description** | An identifier for a dwc:Identification. | An identifier for a dwc:Identification. | An identifier for a dwc:Protocol. | An identifier for a dwc:Identification. |
| **comments** | Recommended best practice is to use a globally unique identifier. | Recommended best practice is to use a globally unique identifier. | Recommended best practice is to use a globally unique identifier. | Recommended best practice is to use a globally unique identifier. |
| **example** |  | `9992` |  | `9992` |
| **type** | string | string | string | string |
| **format** | default | default | default | default |
| **unique** | False | False | False | True |
| **required** | True | True | True | True |
| **minimum** |  |  |  |  |
| **maximum** |  |  |  |  |
| **namespace** | dwc | dwc | dwc | dwc |
| **dcterms:isVersionOf** | http://rs.tdwg.org/dwc/terms/identificationID | http://rs.tdwg.org/dwc/terms/identificationID | http://rs.tdwg.org/dwc/terms/identificationID | http://rs.tdwg.org/dwc/terms/identificationID |
| **dcterms:references** | http://rs.tdwg.org/dwc/terms/version/identificationID-2023-06-28 | http://rs.tdwg.org/dwc/terms/version/identificationID-2023-06-28 | http://rs.tdwg.org/dwc/terms/version/identificationID-2023-06-28 | http://rs.tdwg.org/dwc/terms/version/identificationID-2023-06-28 |
| **rdfs:comment** | An identifier for the dwc:Identification (the body of information associated with the assignment of a scientific name). May be a global unique identifier or an identifier specific to the data set. | An identifier for the dwc:Identification (the body of information associated with the assignment of a scientific name). May be a global unique identifier or an identifier specific to the data set. | An identifier for the dwc:Identification (the body of information associated with the assignment of a scientific name). May be a global unique identifier or an identifier specific to the data set. | An identifier for the dwc:Identification (the body of information associated with the assignment of a scientific name). May be a global unique identifier or an identifier specific to the data set. |
| **status** | recommended | recommended | recommended | recommended |
