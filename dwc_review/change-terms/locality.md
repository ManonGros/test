## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/locality

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~locality~ **locality**
* Term label (English, not normative): ~Locality~ **Locality**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Event
* New definition of the term (normative): **A specific description of a place.**
* Previous definition of the term: ~The specific description of the place.~
* New usage comments (recommendations regarding content, etc., not normative): **Less specific geographic information can be provided in other geographic terms (dwc:higherGeography, dwc:continent, dwc:country, dwc:stateProvince, dwc:county, dwc:municipality, dwc:waterBody, dwc:island, dwc:islandGroup). This term may contain information modified from the original to correct perceived errors or standardize the description.** 
* Previous usage comments: ~Less specific geographic information can be provided in other geographic terms (dwc:higherGeography, dwc:continent, dwc:country, dwc:stateProvince, dwc:county, dwc:municipality, dwc:waterBody, dwc:island, dwc:islandGroup). This term may contain information modified from the original to correct perceived errors or standardize the description.~
* New examples (not normative): **`Bariloche, 25 km NNE via Ruta Nacional 40 (=Ruta 237)`; `Queets Rainforest, Olympic National Park`**
* Previous examples (not normative): ~`Bariloche, 25 km NNE via Ruta Nacional 40 (=Ruta 237)`; `Queets Rainforest, Olympic National Park`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/locality-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Gathering/NamedAreas/NamedArea/AreaName
