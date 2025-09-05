## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/measurementValue

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~measurementValue~ **assertionValue**
* Term label (English, not normative): ~Measurement Value~ **Assertion Value**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Assertion
* New definition of the term (normative): **An asserted value, if it is not numeric.**
* Previous definition of the term: ~The value of the measurement, fact, characteristic, or assertion.~
* New usage comments (recommendations regarding content, etc., not normative): **** 
* Previous usage comments: ~This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.~
* New examples (not normative): **`45`; `20`; `1`; `14.5`; `UV-light`**
* Previous examples (not normative): ~`45`; `20`; `1`; `14.5`; `UV-light`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/measurementValue-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/MeasurementsOrFacts/MeasurementOrFact/MeasurementOrFactAtomised/LowerValue or DataSets/DataSet/Units/Unit/MeasurementsOrFacts/MeasurementOrFact/MeasurementOrFactAtomised/UpperValue or DataSets/DataSet/Units/Unit/Gathering/SiteMeasurementsOrFacts/SiteMeasurementOrFact/MeasurementOrFactAtomised/LowerValue or DataSets/DataSet/Units/Unit/Gathering/SiteMeasurementsOrFacts/SiteMeasurementOrFact/MeasurementOrFactAtomised/UpperValue or DataSets/DataSet/Units/Unit/Gathering/Altitude/MeasurementOrFactAtomised/LowerValue or DataSets/DataSet/Units/Unit/Gathering/Altitude/MeasurementOrFactAtomised/UpperValue or DataSets/DataSet/Units/Unit/Gathering/Depth/MeasurementOrFactAtomised/LowerValue or DataSets/DataSet/Units/Unit/Gathering/Depth/MeasurementOrFactAtomised/UpperValue or DataSets/DataSet/Units/Unit/Gathering/Biotope/MeasurementsOrFacts/MeasurementOrFactAtomised/LowerValue or DataSets/DataSet/Units/Unit/Gathering/Biotope/MeasurementsOrFacts/MeasurementOrFactAtomised/UpperValue or DataSets/DataSet/Units/Unit/Gathering/Height/MeasurementOrFactAtomised/LowerValue or DataSets/DataSet/Units/Unit/Gathering/Height/MeasurementOrFactAtomised/UpperValue
