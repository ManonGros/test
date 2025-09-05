## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/measurementAccuracy

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~measurementAccuracy~ **assertionError**
* Term label (English, not normative): ~Measurement Accuracy~ **Assertion Error**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Assertion
* New definition of the term (normative): **The description of the potential error associated with dwc:assertionValueNumeric.**
* Previous definition of the term: ~The description of the potential error associated with the dwc:measurementValue.~
* New usage comments (recommendations regarding content, etc., not normative): **** 
* Previous usage comments: ~~
* New examples (not normative): **`0.01`; `normal distribution with variation of 2 m`**
* Previous examples (not normative): ~`0.01`; `normal distribution with variation of 2 m`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/measurementAccuracy-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/MeasurementsOrFacts/MeasurementOrFact/MeasurementOrFactAtomised/Accuracy or DataSet/Units/Unit/Gathering/SiteMeasurementsOrFacts/SiteMeasurementOrFact/MeasurementOrFactAtomised/Accuracy or DataSets/DataSet/Units/Unit/Gathering/Aspect/Accuracy or DataSets/DataSet/Units/Unit/Gathering/Altitude/MeasurementOrFactAtomised/Accuracy or DataSets/DataSet/Units/Unit/Gathering/Depth/MeasurementOrFactAtomised/Accuracy or DataSets/DataSet/Units/Unit/Gathering/Biotope/MeasurementsOrFacts/MeasurementOrFactAtomised/Accuracy or DataSets/DataSet/Units/Unit/MeasurementsOrFacts/MeasurementOrFact/MeasurementOrFactAtomised/Accuracy
