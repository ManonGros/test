## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/collectionID

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~collectionID~ **collectionID**
* Term label (English, not normative): ~Collection ID~ **Collection ID**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): MaterialEntity
* New definition of the term (normative): **An identifier for a collection.**
* Previous definition of the term: ~An identifier for the collection or dataset from which the record was derived.~
* New usage comments (recommendations regarding content, etc., not normative): **For physical specimens, the recommended best practice is to use a globally unique and resolvable identifier from a collections registry such as the Global Registry of Scientific Collections (https://scientific-collections.gbif.org/).** 
* Previous usage comments: ~For physical specimens, the recommended best practice is to use a globally unique and resolvable identifier from a collections registry such as the Global Registry of Scientific Collections (https://scientific-collections.gbif.org/).~
* New examples (not normative): **`https://scientific-collections.gbif.org/collection/fbd3ed74-5a21-4e01-b86a-33d36f032d9c`**
* Previous examples (not normative): ~`https://scientific-collections.gbif.org/collection/fbd3ed74-5a21-4e01-b86a-33d36f032d9c`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/collectionID-2025-06-12
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/SourceID
