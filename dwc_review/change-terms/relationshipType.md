## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/relationshipOfResource

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~relationshipOfResource~ **relationshipType**
* Term label (English, not normative): ~Relationship Of Resource~ **Relationship Type**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): ResourceRelationship
* New definition of the term (normative): **A relationship of a subject resource (identified by dwc:subjectResourceID) to a related resource (identified by dwc:relatedResourceID).**
* Previous definition of the term: ~The relationship of the subject (identified by dwc:resourceID) to the object (identified by dwc:relatedResourceID).~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use a controlled vocabulary.** 
* Previous usage comments: ~Recommended best practice is to use a controlled vocabulary.~
* New examples (not normative): **`same as`; `duplicate of`; `mother of`; `offspring of`; `sibling of`; `parasite of`; `host of`; `valid synonym of`; `located within`; `pollinator of members of taxon`; `pollinated specific plant`; `pollinated by members of taxon`; `on slab with`**
* Previous examples (not normative): ~`same as`; `duplicate of`; `mother of`; `offspring of`; `sibling of`; `parasite of`; `host of`; `valid synonym of`; `located within`; `pollinator of members of taxon`; `pollinated specific plant`; `pollinated by members of taxon`; `on slab with`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/relationshipOfResource-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Associations/UnitAssociation/AssociationType
