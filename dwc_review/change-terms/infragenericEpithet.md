## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/infragenericEpithet

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~infragenericEpithet~ **infragenericEpithet**
* Term label (English, not normative): ~Infrageneric Epithet~ **Infrageneric Epithet**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Identification
* New definition of the term (normative): **The infrageneric part of a binomial name at ranks above species but below genus.**
* Previous definition of the term: ~The infrageneric part of a binomial name at ranks above species but below genus.~
* New usage comments (recommendations regarding content, etc., not normative): **** 
* Previous usage comments: ~The term dwc:infragenericEpithet should be used in conjunction with dwc:genericName, dwc:specificEpithet, dwc:infraspecificEpithet, dwc:taxonRank and dwc:scientificNameAuthorship to represent the individual elements of the complete dwc:scientificName. It can be used to indicate the subgenus placement of a species, which in zoology is often given in parentheses. Can also be used to share infrageneric names such as botanical sections (e.g., `Vicia sect. Cracca`).~
* New examples (not normative): **`Abacetillus` (for scientificName `Abacetus (Abacetillus) ambiguus`); `Cracca` (for scientificName `Vicia sect. Cracca`)**
* Previous examples (not normative): ~`Abacetillus` (for scientificName `Abacetus (Abacetillus) ambiguus`); `Cracca` (for scientificName `Vicia sect. Cracca`)~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/infragenericEpithet-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Identifications/Identification/Result/TaxonIdentified/ScientificName/NameAtomised/Bacterial/Subgenus (for bacterial names) or  DataSets/DataSet/Units/Unit/Identifications/Identification/Result/TaxonIdentified/ScientificName/NameAtomised/Zoological/Subgenus (for zoological names) or DataSets/DataSet/Units/Unit/Identifications/Identification/Result/TaxonIdentified/ScientificName/NameAtomised/Botanical/FirstEpithet (for botanical names)
