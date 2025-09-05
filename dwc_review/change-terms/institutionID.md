## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/institutionID

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~institutionID~ **institutionID**
* Term label (English, not normative): ~Institution ID~ **Institution ID**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): MaterialEntity
* New definition of the term (normative): **An identifier for an institution.**
* Previous definition of the term: ~An identifier for the institution having custody of the object(s) or information referred to in the record.~
* New usage comments (recommendations regarding content, etc., not normative): **For physical specimens, the recommended best practice is to use a globally unique and resolvable identifier from a collections registry such as the Research Organization Registry (ROR) or the Global Registry of Scientific Collections (https://scientific-collections.gbif.org/).** 
* Previous usage comments: ~For physical specimens, the recommended best practice is to use a globally unique and resolvable identifier from a collections registry such as the Research Organization Registry (ROR) or the Global Registry of Scientific Collections (https://scientific-collections.gbif.org/)~
* New examples (not normative): **`https://ror.org/015hz7p22`; `http://grscicoll.org/institution/museum-southwestern-biology`; `https://scientific-collections.gbif.org/institution/e3d4dcc4-81e2-444c-8a5c-41d1044b5381`**
* Previous examples (not normative): ~`https://ror.org/015hz7p22`; `http://grscicoll.org/institution/museum-southwestern-biology`; `https://www.gbif.org/grscicoll/institution/e3d4dcc4-81e2-444c-8a5c-41d1044b5381`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/institutionID-2025-06-12
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/SourceInstitutionID
