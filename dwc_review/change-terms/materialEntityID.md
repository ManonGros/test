**Old term**

**Definition:** An identifier for a particular instance of a dwc:MaterialEntity.
**Label:** Material Entity ID
**Term Name:** dwc:materialEntityID
**Term version IRI:** http://rs.tdwg.org/dwc/terms/version/materialEntityID-2023-09-13
**Version of:** http://rs.tdwg.org/dwc/terms/materialEntityID
**Issued:** 2023-09-13
**Type:** Property
**Status:** recommended


| definitions | context 1 |context 2 |context 3 |context 4 |
|-|-|-|-|-|
| **Context - tables concerned** | <ul><li>identification</li></ul> | <ul><li>nucleotide-analysis</li></ul> | <ul><li>material-agent-role</li><li>material-assertion</li><li>material-geological-context</li><li>material-identifier</li><li>material-media</li><li>material-protocol</li><li>material-provenance</li><li>material-reference</li><li>material-usage-policy</li></ul> | <ul><li>material</li></ul> |
| **key** | fk | fk | fk | pk |
| **title** | Material Entity ID | Material Entity ID | Material Entity ID | Material Entity ID |
| **description** | An identifier for a dwc:MaterialEntity based on which a dwc:Identification was made. | An identifier for a dwc:MaterialEntity. | An identifier for a dwc:MaterialEntity. | An identifier for a dwc:MaterialEntity. |
| **comments** | Recommended best practice is to use a globally unique identifier. | Values of dwc:materialEntityID are intended to uniquely and persistently identify a particular dwc:MaterialEntity within some context. Examples of context include a particular sample collection, an organization, or the worldwide scale. Recommended best practice is to use a persistent, globally unique identifier. The identifier is bound to a physical object (a dwc:MaterialEntity) as opposed to a particular digital record (representation) of that physical object. | Values of dwc:materialEntityID are intended to uniquely and persistently identify a particular dwc:MaterialEntity within some context. Examples of context include a particular sample collection, an organization, or the worldwide scale. Recommended best practice is to use a persistent, globally unique identifier. The identifier is bound to a physical object (a dwc:MaterialEntity) as opposed to a particular digital record (representation) of that physical object. | Recommended best practice is to use a globally unique identifier. |
| **example** | `06809dc5-f143-459a-be1a-6f03e63fc083` |  |  | `06809dc5-f143-459a-be1a-6f03e63fc083` |
| **type** | string | string | string | string |
| **format** | default | default | default | default |
| **unique** | False | False | False | True |
| **required** | False | False | True | True |
| **minimum** |  |  |  |  |
| **maximum** |  |  |  |  |
| **namespace** | dwc | dwc | dwc | dwc |
| **dcterms:isVersionOf** | http://rs.tdwg.org/dwc/terms/materialEntityID | http://rs.tdwg.org/dwc/terms/materialEntityID | http://rs.tdwg.org/dwc/terms/materialEntityID | http://rs.tdwg.org/dwc/terms/materialEntityID |
| **dcterms:references** | http://rs.tdwg.org/dwc/terms/version/materialEntityID-2023-09-13 | http://rs.tdwg.org/dwc/terms/version/materialEntityID-2023-09-13 | http://rs.tdwg.org/dwc/terms/version/materialEntityID-2023-09-13 | http://rs.tdwg.org/dwc/terms/version/materialEntityID-2023-09-13 |
| **rdfs:comment** | An identifier for a particular instance of a dwc:MaterialEntity. | An identifier for a particular instance of a dwc:MaterialEntity. | An identifier for a particular instance of a dwc:MaterialEntity. | An identifier for a particular instance of a dwc:MaterialEntity. |
| **status** | recommended | recommended | recommended | recommended |
