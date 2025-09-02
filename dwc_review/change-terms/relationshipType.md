**Old term**

**Definition:** The relationship of the subject (identified by dwc:resourceID) to the object (identified by dwc:relatedResourceID).
**Label:** Relationship Of Resource
**Term Name:** dwc:relationshipOfResource
**Term version IRI:** http://rs.tdwg.org/dwc/terms/version/relationshipOfResource-2023-06-28
**Version of:** http://rs.tdwg.org/dwc/terms/relationshipOfResource
**Issued:** 2023-06-28
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/dwc/terms/version/relationshipOfResource-2021-07-15


| definitions | context 1 |context 2 |context 3 |
|-|-|-|-|
| **Context - tables concerned** | <ul><li>organism-relationship</li></ul> | <ul><li>resource-relationship</li></ul> | <ul><li>chronometric-age-reference</li><li>event-reference</li><li>identification-reference</li><li>material-reference</li><li>molecular-protocol-reference</li><li>occurrence-reference</li><li>organism-interaction-reference</li><li>organism-reference</li><li>protocol-reference</li><li>survey-reference</li></ul> |
| **key** |  |  |  |
| **title** | Relationship Type | Relationship Type | Relationship Type |
| **description** | A relationship of a subject resource (identified by dwc:subjectOrganismID) to a related resource (identified by dwc:relatedOrganismID). | A relationship of a subject resource (identified by dwc:subjectResourceID) to a related resource (identified by dwc:relatedResourceID). | A relationship of a subject resource to a dcterms:BibliographicResource. |
| **comments** | Recommended best practice is to use a controlled vocabulary. | Recommended best practice is to use a controlled vocabulary. | Recommended best practice is to use a controlled vocabulary. |
| **example** | `same as`; `duplicate of`; `mother of`; `offspring of`; `sibling of`; `parasite of`; `host of`; `valid synonym of`; `located within`; `pollinator of members of taxon`; `pollinated specific plant`; `pollinated by members of taxon`; `on slab with` | `same as`; `duplicate of`; `mother of`; `offspring of`; `sibling of`; `parasite of`; `host of`; `valid synonym of`; `located within`; `pollinator of members of taxon`; `pollinated specific plant`; `pollinated by members of taxon`; `on slab with` | `cited in`; `referenced` |
| **type** | string | string | string |
| **format** | default | default | default |
| **unique** |  |  |  |
| **required** |  |  |  |
| **minimum** |  |  |  |
| **maximum** |  |  |  |
| **namespace** | dwc | dwc | dwc |
| **dcterms:isVersionOf** | http://rs.tdwg.org/dwc/terms/relationshipOfResource | http://rs.tdwg.org/dwc/terms/relationshipOfResource | http://rs.tdwg.org/dwc/terms/relationshipOfResource |
| **dcterms:references** | http://rs.tdwg.org/dwc/terms/version/relationshipOfResource-2023-06-28 | http://rs.tdwg.org/dwc/terms/version/relationshipOfResource-2023-06-28 | http://rs.tdwg.org/dwc/terms/version/relationshipOfResource-2023-06-28 |
| **rdfs:comment** | The relationship of the subject (identified by dwc:resourceID) to the object (identified by dwc:relatedResourceID). | The relationship of the subject (identified by dwc:resourceID) to the object (identified by dwc:relatedResourceID). | The relationship of the subject (identified by dwc:resourceID) to the object (identified by dwc:relatedResourceID). |
| **status** | recommended | recommended | recommended |
