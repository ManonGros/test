## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/subgenus

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~subgenus~ **subgenus**
* Term label (English, not normative): ~Subgenus~ **Subgenus**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Identification
* New definition of the term (normative): **A dwc:scientificName of a subgenus in which a dwc:Taxon is classified.**
* Previous definition of the term: ~The full scientific name of the subgenus in which the dwc:Taxon is classified.~
* New usage comments (recommendations regarding content, etc., not normative): **A value for this term should be a complete subgenus name as required by the appropriate nomenclatural code.** 
* Previous usage comments: ~A value for this term should be a complete subgenus name as required by the appropriate nomenclatural code.~
* New examples (not normative): **`Abacetus (Parastygis)`; `Dicranum subgen. Orthodicranum`**
* Previous examples (not normative): ~`Abacetus (Parastygis)`; `Dicranum subgen. Orthodicranum`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/subgenus-2025-06-12
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
