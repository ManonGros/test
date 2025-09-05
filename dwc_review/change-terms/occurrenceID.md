## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/occurrenceID

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~occurrenceID~ **occurrenceID**
* Term label (English, not normative): ~Occurrence ID~ **Occurrence ID**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Occurrence
* New definition of the term (normative): **An identifier for a dwc:Occurrence.**
* Previous definition of the term: ~An identifier for the dwc:Occurrence (as opposed to a particular digital record of the dwc:Occurrence). In the absence of a persistent global unique identifier, construct one from a combination of identifiers in the record that will most closely make the dwc:occurrenceID globally unique.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use a globally unique identifier.** 
* Previous usage comments: ~Recommended best practice is to use a persistent, globally unique identifier.~
* New examples (not normative): **`http://arctos.database.museum/guid/MSB:Mamm:233627`; `000866d2-c177-4648-a200-ead4007051b9`; `urn:catalog:UWBM:Bird:89776`**
* Previous examples (not normative): ~`http://arctos.database.museum/guid/MSB:Mamm:233627`; `000866d2-c177-4648-a200-ead4007051b9`; `urn:catalog:UWBM:Bird:89776`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/occurrenceID-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/UnitGUID
