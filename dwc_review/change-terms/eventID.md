**Old term**

**Definition:** An identifier for the set of information associated with a dwc:Event (something that occurs at a place and time). May be a global unique identifier or an identifier specific to the data set.
**Label:** Event ID
**Term Name:** dwc:eventID
**Term version IRI:** http://rs.tdwg.org/dwc/terms/version/eventID-2023-06-28
**Version of:** http://rs.tdwg.org/dwc/terms/eventID
**Issued:** 2023-06-28
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/dwc/terms/version/eventID-2017-10-06


| definitions | context 1 |context 2 |
|-|-|-|
| **Context - tables concerned** | <ul><li>chronometric-age</li><li>event-agent-role</li><li>event-assertion</li><li>event-identifier</li><li>event-media</li><li>event-protocol</li><li>event-provenance</li><li>event-reference</li><li>material</li><li>nucleotide-analysis</li><li>occurrence</li><li>organism-interaction</li><li>survey</li></ul> | <ul><li>event</li></ul> |
| **key** | fk | pk |
| **title** | Event ID | Event ID |
| **description** | An identifier for a dwc:Event. | An identifier for a dwc:Event. |
| **comments** | Recommended best practice is to use a globally unique identifier. | Recommended best practice is to use a globally unique identifier. |
| **example** |  | `INBO:VIS:Ev:00009375` |
| **type** | string | string |
| **format** | default | default |
| **unique** | False | True |
| **required** | True | True |
| **minimum** |  |  |
| **maximum** |  |  |
| **namespace** | dwc | dwc |
| **dcterms:isVersionOf** | http://rs.tdwg.org/dwc/terms/eventID | http://rs.tdwg.org/dwc/terms/eventID |
| **dcterms:references** | http://rs.tdwg.org/dwc/terms/version/eventID-2023-06-28 | http://rs.tdwg.org/dwc/terms/version/eventID-2023-06-28 |
| **rdfs:comment** | An identifier for the set of information associated with a dwc:Event (something that occurs at a place and time). May be a global unique identifier or an identifier specific to the data set. | An identifier for the set of information associated with a dwc:Event (something that occurs at a place and time). May be a global unique identifier or an identifier specific to the data set. |
| **status** | recommended | recommended |
