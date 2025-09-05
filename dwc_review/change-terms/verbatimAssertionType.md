## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/verbatimMeasurementType

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~verbatimMeasurementType~ **verbatimAssertionType**
* Term label (English, not normative): ~Verbatim Measurement Type~ **Verbatim Assertion Type**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Assertion
* New definition of the term (normative): **A string representing the type of dwc:Assertion as it appeared in the original record.**
* Previous definition of the term: ~A string representing the type of measurement or fact as it appeared in the original record.~
* New usage comments (recommendations regarding content, etc., not normative): **This term is meant to allow the capture of an unaltered original name for a dwc:assertionType. This term is meant to be used in addition to dwc:assertionType, not instead of it.** 
* Previous usage comments: ~This term is meant to allow the capture of an unaltered original name for a measurement or fact type. This term is meant to be used in addition to dwc:measurementType, not instead of it.~
* New examples (not normative): **`water_temp`; `Fish biomass`; `sampling net mesh size`**
* Previous examples (not normative): ~`water_temp`; `Fish biomass`; `sampling net mesh size`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/verbatimMeasurementType-2025-06-12
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
