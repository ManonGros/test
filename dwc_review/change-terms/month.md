## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/month

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~month~ **month**
* Term label (English, not normative): ~Month~ **Month**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Event
* New definition of the term (normative): **An integer month in which a dwc:Event occurred.**
* Previous definition of the term: ~The integer month in which the dwc:Event occurred.~
* New usage comments (recommendations regarding content, etc., not normative): **** 
* Previous usage comments: ~~
* New examples (not normative): **`1` (January); `10` (October)**
* Previous examples (not normative): ~`1` (January); `10` (October)~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/month-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): accessible from DataSets/DataSet/Units/Unit/Gathering/ISODateTimeBegin
