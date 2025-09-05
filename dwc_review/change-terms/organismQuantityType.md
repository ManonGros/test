## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/organismQuantity

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~organismQuantityType~ **organismQuantityType**
* Term label (English, not normative): ~Organism Quantity Type~ **Organism Quantity Type**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Occurrence
* New definition of the term (normative): **A type of quantification system used for the quantity of dwc:Organisms.**
* Previous definition of the term: ~The type of quantification system used for the quantity of dwc:Organisms.~
* New usage comments (recommendations regarding content, etc., not normative): **A dwc:organismQuantityType must have a corresponding dwc:organismQuantity. This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.** 
* Previous usage comments: ~A dwc:organismQuantityType must have a corresponding dwc:organismQuantity. This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.~
* New examples (not normative): **`27` (organismQuantity) with `individuals` (organismQuantityType); `12.5` (organismQuantity) with `% biomass` (organismQuantityType); `r` (organismQuantity) with `Braun-Blanquet Scale` (organismQuantityType); `many` (organismQuantity) with `individuals` (organismQuantityType)**
* Previous examples (not normative): ~`27` (organismQuantity) with `individuals` (organismQuantityType); `12.5` (organismQuantity) with `% biomass` (organismQuantityType); `r` (organismQuantity) with `Braun-Blanquet Scale` (organismQuantityType); `many` (organismQuantity) with `individuals` (organismQuantityType)~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/organismQuantityType-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
