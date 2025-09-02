**Old term**

**Definition:** An identifier for the broader dwc:Event that groups this and potentially other dwc:Events.
**Label:** Parent Event ID
**Term Name:** dwc:parentEventID
**Term version IRI:** http://rs.tdwg.org/dwc/terms/version/parentEventID-2023-06-28
**Version of:** http://rs.tdwg.org/dwc/terms/parentEventID
**Issued:** 2023-06-28
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/dwc/terms/version/parentEventID-2017-10-06


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>event</li></ul> |
| **key** | fk |
| **title** | Parent Event ID |
| **description** | An identifier for a broader dwc:Event that contains this and potentially other dwc:Events. |
| **comments** | Recommended best practice is to use a globally unique identifier. |
| **example** | `A1` (parentEventID to identify the main Whittaker Plot in nested samples, each with its own eventID - `A1:1`, `A1:2`). |
| **type** | string |
| **format** | default |
| **unique** | False |
| **required** | False |
| **minimum** |  |
| **maximum** |  |
| **namespace** | dwc |
| **dcterms:isVersionOf** | http://rs.tdwg.org/dwc/terms/parentEventID |
| **dcterms:references** | http://rs.tdwg.org/dwc/terms/version/parentEventID-2023-06-28 |
| **rdfs:comment** | An identifier for the broader dwc:Event that groups this and potentially other dwc:Events. |
| **status** | recommended |
