## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/measurementUnit

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~measurementUnit~ **assertionUnit**
* Term label (English, not normative): ~Measurement Unit~ **Assertion Unit**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Assertion
* New definition of the term (normative): **Units associated with the value in dwc:assertionValueNumeric.**
* Previous definition of the term: ~The units associated with the dwc:measurementValue.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use a controlled vocabulary such as the Ontology of Units of Measure http://www.wurvoc.org/vocabularies/om-1.8/ of SI units, derived units, or other non-SI units accepted for use within the SI. For units that are composed of multiple parts, use the patterns as given in "A Primer for Communicating Mathematics via Plain Text" (https://cse.sc.edu/~fenner/latex-ASCII.pdf) by Stephen Fenner (e.g., `g/cm^3` for grams per cubic centimeter). For other units, provide the value as a recognizable standard (e.g., '%') or written out in full and in the plural (e.g., `individuals`). It is fine to provide non-SI units in the original language of the dataset.** 
* Previous usage comments: ~Recommended best practice is to use the International System of Units (SI). This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.~
* New examples (not normative): **`m`; `g`; `l`; `°C`; `mm`; `km²`; `%`; `hh:mm:ss`**
* Previous examples (not normative): ~`m`; `g`; `l`; `°C`; `mm`; `km²`; `%`; `hh:mm:ss`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/measurementUnit-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Gathering/SiteMeasurementsOrFacts/MeasurementOrFact/MeasurementOrFactAtomised/UnitOfMeasurement or DataSets/DataSet/Units/Unit/Gathering/SiteMeasurementsOrFacts/MeasurementOrFact/MeasurementOrFactAtomised/UnitOfMeasurement
