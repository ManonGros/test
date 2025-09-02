| definitions | context 1 |context 2 |
|-|-|-|
| **Context - tables concerned** | <ul><li>organism-relationship</li></ul> | <ul><li>resource-relationship</li></ul> |
| **key** |  |  |
| **title** | Relationship Order | Relationship Order |
| **description** | A numerical position of a dwc:ResourceRelationship in a set of dwc:ResourceRelationships that have the same combination of dwc:organismID, dwc:relatedOrganismID, dwc:relationshipType, dwc:relationshipTypeIRI, and dwc:relationshipTypeSource. | A numerical position of a dwc:ResourceRelationship in a set of dwc:ResourceRelationships that have the same combination of dwc:subjectResourceID, dwc:relatedResourceID, dwc:relationshipType, dwc:relationshipTypeIRI, and dwc:relationshipTypeSource. |
| **comments** | One could use relationshipOrder to create an ordered list of authors for a Reference, for example. The first would have relationshipOrder=1, the second would have relationshipOrder=2. | One could use this term to create an ordered list of authors for a dcterms:BibliographicResource, for example. The first would have relationshipOrder=1, the second would have relationshipOrder=2. |
| **example** |  |  |
| **type** | integer | integer |
| **format** | default | default |
| **unique** |  |  |
| **required** |  |  |
| **minimum** | 1.0 | 1.0 |
| **maximum** |  |  |
| **namespace** | dwcdp | dwcdp |
| **dcterms:isVersionOf** |  |  |
| **dcterms:references** |  |  |
| **rdfs:comment** |  |  |
| **status** | recommended | recommended |
