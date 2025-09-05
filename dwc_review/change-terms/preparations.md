## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/preparations

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~preparations~ **preparations**
* Term label (English, not normative): ~Preparations~ **Preparations**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): MaterialEntity
* New definition of the term (normative): **A list (concatenated and separated) of preparations and preservation methods for a dwc:MaterialEntity.**
* Previous definition of the term: ~A list (concatenated and separated) of preparations and preservation methods for a dwc:MaterialEntity.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to separate the values in a list with space vertical bar space (` | `).** 
* Previous usage comments: ~Recommended best practice is to separate the values in a list with space vertical bar space ( | ). This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.~
* New examples (not normative): **`fossil`; `cast`; `photograph`; `DNA extract`; `skin | skull | skeleton`; `whole animal (EtOH) | tissue (EDTA)`**
* Previous examples (not normative): ~`fossil`; `cast`; `photograph`; `DNA extract`; `skin | skull | skeleton`; `whole animal (EtOH) | tissue (EDTA)`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/preparations-2025-06-12
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/SpecimenUnit/Preparations/PreparationsText
