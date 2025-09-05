## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/nomenclaturalCode

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~nomenclaturalCode~ **nomenclaturalCode**
* Term label (English, not normative): ~Nomenclatural Code~ **Nomenclatural Code**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Identification
* New definition of the term (normative): **A nomenclatural code (or codes in the case of an ambiregnal name) under which a dwc:scientificName is constructed.**
* Previous definition of the term: ~The nomenclatural code (or codes in the case of an ambiregnal name) under which the dwc:scientificName is constructed.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use a controlled vocabulary.** 
* Previous usage comments: ~Recommended best practice is to use a controlled vocabulary.~
* New examples (not normative): **`ICN`; `ICZN`; `BC`; `ICNCP`; `BioCode`**
* Previous examples (not normative): ~`ICN`; `ICZN`; `BC`; `ICNCP`; `BioCode`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/nomenclaturalCode-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Identifications/Identification/TaxonIdentified/Code
