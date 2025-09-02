**Old term**

**Definition:** An identifier for the set of information associated with a dwc:GeologicalContext (the location within a geological context, such as stratigraphy). May be a global unique identifier or an identifier specific to the data set.
**Label:** Geological Context ID
**Term Name:** dwc:geologicalContextID
**Term version IRI:** http://rs.tdwg.org/dwc/terms/version/geologicalContextID-2023-06-28
**Version of:** http://rs.tdwg.org/dwc/terms/geologicalContextID
**Issued:** 2023-06-28
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/dwc/terms/version/geologicalContextID-2017-10-06


| definitions | context 1 |context 2 |context 3 |context 4 |
|-|-|-|-|-|
| **Context - tables concerned** | <ul><li>geological-context-media</li></ul> | <ul><li>material-geological-context</li></ul> | <ul><li>event</li></ul> | <ul><li>geological-context</li></ul> |
| **key** | fk | fk | fk | pk |
| **title** | Geological Context ID | Geological Context ID | Geological Context ID | Geological Context ID |
| **description** | An identifier for a dwc:GeologicalContext. | An identifier for a dwc:GeologicalContext. | An identifier for a dwc:GeologicalContext. | An identifier for a dwc:GeologicalContext. |
| **comments** | Recommended best practice is to use a globally unique identifier. | Recommended best practice is to use a globally unique identifier. | Recommended best practice is to use a globally unique identifier. | Recommended best practice is to use a globally unique identifier. |
| **example** |  |  | `https://opencontext.org/subjects/e54377f7-4452-4315-b676-40679b10c4d9` | `https://opencontext.org/subjects/e54377f7-4452-4315-b676-40679b10c4d9` |
| **type** | string | string | string | string |
| **format** | default | default | default | default |
| **unique** | False | False | False | True |
| **required** | True | True | False | True |
| **minimum** |  |  |  |  |
| **maximum** |  |  |  |  |
| **namespace** | dwc | dwc | dwc | dwc |
| **dcterms:isVersionOf** | http://rs.tdwg.org/dwc/terms/geologicalContextID | http://rs.tdwg.org/dwc/terms/geologicalContextID | http://rs.tdwg.org/dwc/terms/geologicalContextID | http://rs.tdwg.org/dwc/terms/geologicalContextID |
| **dcterms:references** |  | http://rs.tdwg.org/dwc/terms/version/geologicalContextID-2023-06-28 | http://rs.tdwg.org/dwc/terms/version/geologicalContextID-2023-06-28 | http://rs.tdwg.org/dwc/terms/version/geologicalContextID-2023-06-28 |
| **rdfs:comment** |  | An identifier for the set of information associated with a dwc:GeologicalContext (the location within a geological context, such as stratigraphy). May be a globally unique identifier or an identifier specific to the data set. | An identifier for the set of information associated with a dwc:GeologicalContext (the location within a geological context, such as stratigraphy). May be a global unique identifier or an identifier specific to the data set. | An identifier for the set of information associated with a dwc:GeologicalContext (the location within a geological context, such as stratigraphy). May be a globally unique identifier or an identifier specific to the data set. |
| **status** | recommended | recommended | recommended | recommended |
