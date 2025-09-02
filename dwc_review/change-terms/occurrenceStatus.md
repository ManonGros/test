**Old term**

**Definition:** A statement about the presence or absence of a dwc:Taxon at a dcterms:Location.
**Label:** Occurrence Status
**Term Name:** dwc:occurrenceStatus
**Term version IRI:** http://rs.tdwg.org/dwc/terms/version/occurrenceStatus-2023-06-28
**Version of:** http://rs.tdwg.org/dwc/terms/occurrenceStatus
**Issued:** 2023-06-28
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/dwc/terms/version/occurrenceStatus-2021-07-15


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>occurrence</li></ul> |
| **key** |  |
| **title** | Occurrence Status |
| **description** | A statement about the detection or non-detection of a dwc:Organism. |
| **comments** | For dwc:Occurrences, the default vocabulary is recommended to consist of 'detected' and 'notDetected', but can be extended by implementers with good justification. This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value. |
| **example** | `detected`; `notDetected` |
| **type** | string |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** |  |
| **maximum** |  |
| **namespace** | dwc |
| **dcterms:isVersionOf** | http://rs.tdwg.org/dwc/terms/occurrenceStatus |
| **dcterms:references** | http://rs.tdwg.org/dwc/terms/version/occurrenceStatus-2023-06-28 |
| **rdfs:comment** | A statement about the presence or absence of a dwc:Taxon at a dcterms:Location. |
| **status** | recommended |
