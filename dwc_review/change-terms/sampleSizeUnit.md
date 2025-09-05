## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/sampleSizeUnit

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~sampleSizeUnit~ **sampleSizeUnit**
* Term label (English, not normative): ~Sample Size Unit~ **Sample Size Unit**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Survey
* New definition of the term (normative): **A unit of measurement of the size (time duration, length, area, or volume) of a sample in a sampling dwc:Event.**
* Previous definition of the term: ~The unit of measurement of the size (time duration, length, area, or volume) of a sample in a sampling dwc:Event.~
* New usage comments (recommendations regarding content, etc., not normative): **A dwc:sampleSizeUnit must have a corresponding dwc:sampleSizeValue, e.g., `5` for dwc:sampleSizeValue with `metre` for dwc:sampleSizeUnit.** 
* Previous usage comments: ~A dwc:sampleSizeUnit must have a corresponding dwc:sampleSizeValue, e.g., `5` for dwc:sampleSizeValue with `m` for dwc:sampleSizeUnit. This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.~
* New examples (not normative): **`minute`; `hour`; `day`; `metre`; `square metre`; `cubic metre`**
* Previous examples (not normative): ~`minute`; `hour`; `day`; `metre`; `square metre`; `cubic metre`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/sampleSizeUnit-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
