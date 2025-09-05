## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/measurementMethod

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~measurementMethod~ **assertionProtocols**
* Term label (English, not normative): ~Measurement Method~ **Assertion Protocols**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Assertion
* New definition of the term (normative): **Names of, references to, or descriptions of dwc:Protocols used in making a dwc:Assertion.**
* Previous definition of the term: ~A description of or reference to (publication, URI) the method or protocol used to determine the measurement, fact, characteristic, or assertion.~
* New usage comments (recommendations regarding content, etc., not normative): **** 
* Previous usage comments: ~This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.~
* New examples (not normative): **`minimum convex polygon around burrow entrances` (for a home range area); `barometric altimeter` (for an elevation)**
* Previous examples (not normative): ~`minimum convex polygon around burrow entrances` (for a home range area); `barometric altimeter` (for an elevation)~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/measurementMethod-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): /DataSets/DataSet/Units/Unit/MeasurementsOrFacts/MeasurementOrFact/MeasurementOrFactAtomised/Method or /DataSets/DataSet/Units/Unit/Gathering/Biotope/MeasurementsOrFacts/MeasurementOrFactAtomised/Method or /DataSets/DataSet/Units/Unit/Gathering/SiteMeasurementsOrFacts/SiteMeasurementOrFact/MeasurementOrFactAtomised/Method
