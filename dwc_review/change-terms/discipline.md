## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/discipline

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~discipline~ **discipline**
* Term label (English, not normative): ~Discipline~ **Discipline**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): MaterialEntity
* New definition of the term (normative): **The primary branch or branches of knowledge represented by the dwc:MaterialEntity.**
* Previous definition of the term: ~The primary branch or branches of knowledge represented by the record.~
* New usage comments (recommendations regarding content, etc., not normative): **This term can be used to classify records according to branches of knowledge. Recommended best practice is to use a controlled vocabulary and to separate the values in a list with space vertical bar space ( | ). It is also recommended to use this field to describe specimenType in MIDS.** 
* Previous usage comments: ~This term can be used to classify records according to branches of knowledge. Recommended best practice is to use a controlled vocabulary and to separate the values in a list with space vertical bar space ( | ).This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.  It is also recommended to use this field to describe specimenType in MIDS.~
* New examples (not normative): **`Botany`; `Botany | Virology | Taxonomy`**
* Previous examples (not normative): ~`Botany`; `Botany | Virology | Taxonomy`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/discipline-2025-06-12
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
