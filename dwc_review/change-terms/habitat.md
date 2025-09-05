## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/habitat

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~habitat~ **habitat**
* Term label (English, not normative): ~Habitat~ **Habitat**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Event
* New definition of the term (normative): **A category or description of the habitat in which a dwc:Event occurred.**
* Previous definition of the term: ~A category or description of the habitat in which the dwc:Event occurred.~
* New usage comments (recommendations regarding content, etc., not normative): **** 
* Previous usage comments: ~This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.~
* New examples (not normative): **`oak savanna`; `pre-cordilleran steppe`**
* Previous examples (not normative): ~`oak savanna`; `pre-cordilleran steppe`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/habitat-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Gathering/Biotope/Text
