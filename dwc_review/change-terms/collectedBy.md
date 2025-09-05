## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/recordedBy

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~recordedBy~ **collectedBy**
* Term label (English, not normative): ~Recorded By~ **Collected By**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): MaterialEntity
* New definition of the term (normative): **A list (concatenated and separated) of names of dcterms:Agents responsible for collecting a dwc:MaterialEntity.**
* Previous definition of the term: ~A list (concatenated and separated) of names of people, groups, or organizations responsible for recording the original dwc:Occurrence. The primary collector or observer, especially one who applies a personal identifier (dwc:recordNumber), should be listed first.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to separate the values in a list with space vertical bar space (` | `).** 
* Previous usage comments: ~Recommended best practice is to separate the values in a list with space vertical bar space (` | `). This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.~
* New examples (not normative): **`José E. Crespo`; `Oliver P. Pearson | Anita K. Pearson` (where the value in dwc:collectorNumber `OPP 7101` corresponds to the collector number for the specimen in the field catalog of Oliver P. Pearson)**
* Previous examples (not normative): ~`José E. Crespo`; `Oliver P. Pearson | Anita K. Pearson` (where the value in recordNumber `OPP 7101` corresponds to the collector number for the specimen in the field catalog of Oliver P. Pearson)~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/recordedBy-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Gathering/GatheringAgents/GatheringAgentsText
