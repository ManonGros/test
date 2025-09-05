## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/datasetID

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~datasetID~ **datasetID**
* Term label (English, not normative): ~Dataset ID~ **Dataset ID**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Provenance
* New definition of the term (normative): **An identifier for a dataset from which data originated.**
* Previous definition of the term: ~An identifier for the set of data. May be a global unique identifier or an identifier specific to a collection or institution.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use a globally unique identifier.** 
* Previous usage comments: ~~
* New examples (not normative): **`b15d4952-7d20-46f1-8a3e-556a512b04c5`**
* Previous examples (not normative): ~`b15d4952-7d20-46f1-8a3e-556a512b04c5`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/datasetID-2017-10-06
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/DataSetGUID
