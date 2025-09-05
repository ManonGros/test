## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/verbatimIdentification

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~verbatimIdentification~ **verbatimIdentification**
* Term label (English, not normative): ~Verbatim Identification~ **Verbatim Identification**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Identification
* New definition of the term (normative): **A string representing a taxonomic identification as it appeared in the original record.**
* Previous definition of the term: ~A string representing the taxonomic identification as it appeared in the original record.~
* New usage comments (recommendations regarding content, etc., not normative): **** 
* Previous usage comments: ~This term is meant to allow the capture of an unaltered original identification/determination, including identification qualifiers, hybrid formulas, uncertainties, etc. This term is meant to be used in addition to dwc:scientificName (and dwc:identificationQualifier etc.), not instead of it.~
* New examples (not normative): **`Peromyscus sp.`; `Ministrymon sp. nov. 1`; `Anser anser × Branta canadensis`; `Pachyporidae?`, `Potentilla × pantotricha Soják`; `Aconitum pilipes × A. variegatum; `Lepomis auritus x cyanellus`**
* Previous examples (not normative): ~`Peromyscus sp.`; `Ministrymon sp. nov. 1`; `Anser anser × Branta canadensis`; `Pachyporidae?`; `Potentilla × pantotricha Soják`; `Aconitum pilipes × A. variegatum`; `Lepomis auritus x cyanellus`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/verbatimIdentification-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
