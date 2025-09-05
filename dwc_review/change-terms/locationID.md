## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/locationID

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~locationID~ **locationID**
* Term label (English, not normative): ~Location ID~ **Location ID**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Event
* New definition of the term (normative): **An identifier for a dcterms:Location.**
* Previous definition of the term: ~An identifier for the set of dcterms:Location information. May be a global unique identifier or an identifier specific to the data set.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use a globally unique identifier.** 
* Previous usage comments: ~~
* New examples (not normative): **`https://opencontext.org/subjects/768A875F-E205-4D0B-DE55-BAB7598D0FD1`**
* Previous examples (not normative): ~`https://opencontext.org/subjects/768A875F-E205-4D0B-DE55-BAB7598D0FD1`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/locationID-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
