## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/relationshipRemarks

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~relationshipRemarks~ **relationshipRemarks**
* Term label (English, not normative): ~Relationship Remarks~ **Relationship Remarks**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): ResourceRelationship
* New definition of the term (normative): **Comments or notes about a dwc:ResourceRelationship.**
* Previous definition of the term: ~Comments or notes about the relationship between the two resources.~
* New usage comments (recommendations regarding content, etc., not normative): **** 
* Previous usage comments: ~~
* New examples (not normative): **`mother and offspring collected from the same nest`; `pollinator captured in the act`**
* Previous examples (not normative): ~`mother and offspring collected from the same nest`; `pollinator captured in the act`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/relationshipRemarks-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Associations/UnitAssociation/Comments
