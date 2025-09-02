**Old term**

**Definition:** An identifier for the dwc:Occurrence (as opposed to a particular digital record of the dwc:Occurrence). In the absence of a persistent global unique identifier, construct one from a combination of identifiers in the record that will most closely make the dwc:occurrenceID globally unique.
**Label:** Occurrence ID
**Term Name:** dwc:occurrenceID
**Term version IRI:** http://rs.tdwg.org/dwc/terms/version/occurrenceID-2023-06-28
**Version of:** http://rs.tdwg.org/dwc/terms/occurrenceID
**Issued:** 2023-06-28
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/dwc/terms/version/occurrenceID-2017-10-06


| definitions | context 1 |context 2 |context 3 |
|-|-|-|-|
| **Context - tables concerned** | <ul><li>identification</li></ul> | <ul><li>occurrence-agent-role</li><li>occurrence-assertion</li><li>occurrence-identifier</li><li>occurrence-media</li><li>occurrence-protocol</li><li>occurrence-reference</li></ul> | <ul><li>occurrence</li></ul> |
| **key** | fk | fk | pk |
| **title** | Occurrence ID | Occurrence ID | Occurrence ID |
| **description** | An identifier for a dwc:Occurrence based on which a dwc:Identification was made. | An identifier for a dwc:Occurrence. | An identifier for a dwc:Occurrence. |
| **comments** | Recommended best practice is to use a globally unique identifier. | Recommended best practice is to use a persistent, globally unique identifier. In the absence of a persistent global unique identifier, construct one from a combination of identifiers in the record that will most closely make a dwc:occurrenceID globally unique. | Recommended best practice is to use a globally unique identifier. |
| **example** | `http://arctos.database.museum/guid/MSB:Mamm:233627`; `000866d2-c177-4648-a200-ead4007051b9`; `urn:catalog:UWBM:Bird:89776` |  | `http://arctos.database.museum/guid/MSB:Mamm:233627`; `000866d2-c177-4648-a200-ead4007051b9`; `urn:catalog:UWBM:Bird:89776` |
| **type** | string | string | string |
| **format** | default | default | default |
| **unique** | False | False | True |
| **required** | False | True | True |
| **minimum** |  |  |  |
| **maximum** |  |  |  |
| **namespace** | dwc | dwc | dwc |
| **dcterms:isVersionOf** | http://rs.tdwg.org/dwc/terms/occurrenceID | http://rs.tdwg.org/dwc/terms/occurrenceID | http://rs.tdwg.org/dwc/terms/occurrenceID |
| **dcterms:references** | http://rs.tdwg.org/dwc/terms/version/occurrenceID-2023-06-28 | http://rs.tdwg.org/dwc/terms/version/occurrenceID-2023-06-28 | http://rs.tdwg.org/dwc/terms/version/occurrenceID-2023-06-28 |
| **rdfs:comment** | An identifier for the dwc:Occurrence (as opposed to a particular digital record of the dwc:Occurrence). In the absence of a persistent global unique identifier, construct one from a combination of identifiers in the record that will most closely make the dwc:occurrenceID globally unique. | An identifier for the dwc:Occurrence (as opposed to a particular digital record of the dwc:Occurrence). In the absence of a persistent global unique identifier, construct one from a combination of identifiers in the record that will most closely make the dwc:occurrenceID globally unique. | An identifier for the dwc:Occurrence (as opposed to a particular digital record of the dwc:Occurrence). In the absence of a persistent global unique identifier, construct one from a combination of identifiers in the record that will most closely make the dwc:occurrenceID globally unique. |
| **status** | recommended | recommended | recommended |
