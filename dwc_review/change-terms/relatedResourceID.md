## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/relatedResourceID

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~relatedResourceID~ **relatedResourceID**
* Term label (English, not normative): ~Related Resource ID~ **Related Resource ID**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): ResourceRelationship
* New definition of the term (normative): **An identifier for the related resource (the object) of a dwc:ResourceRelationship.**
* Previous definition of the term: ~An identifier for a related resource (the object, rather than the subject of the relationship).~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use a globally unique identifier.** 
* Previous usage comments: ~~
* New examples (not normative): **`dc609808-b09b-11e8-96f8-529269fb1459`**
* Previous examples (not normative): ~`dc609808-b09b-11e8-96f8-529269fb1459`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/relatedResourceID-2018-09-06
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Associations/UnitAssociation/AssociatedUnitSourceInstitutionCode + DataSets/DataSet/Units/Unit/Associations/UnitAssociation/AssociatedUnitSourceName + DataSets/DataSet/Units/Unit/Associations/UnitAssociation/AssociatedUnitID
