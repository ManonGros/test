## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/projectID

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~projectID~ **projectID**
* Term label (English, not normative): ~Project ID~ **Project ID**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Provenance
* New definition of the term (normative): **A list (concatenated and separated) of identifiers for projects that contributed to a dwc:Event.**
* Previous definition of the term: ~A list (concatenated and separated) of identifiers for projects that contributed to a dwc:Event.~
* New usage comments (recommendations regarding content, etc., not normative): **A projectID can be may be shared in multiple distinct datasets. The nature of the association can be described in the metadata project description element. This term should be used to provide a globally unique identifier (GUID) for a project, if available. This could be a DOI, URI, or any other persistent identifier that ensures a project can be uniquely distinguished from others. The Recommended best practice is to separate the values in a list with space vertical bar space (` | `).** 
* Previous usage comments: ~A projectID may be shared in multiple distinct datasets. The nature of the association can be described in the metadata project description element. This term should be used to provide a globally unique identifier (GUID) for a project, if available. This could be a DOI, URI, or any other persistent identifier that ensures a project can be uniquely distinguished from others. The recommended best practice is to separate the values in a list with space vertical bar space ( | ).~
* New examples (not normative): **`https://arvenetternansen.com/`; `https://doi.org/10.26259/3b15eca7`; `https://doi.org/10.3030/101180559`; `OC202405`; `RCN276730`; `RCN276730 | Artsproject_7-24`**
* Previous examples (not normative): ~`RCN276730`; `RCN276730 | Artsproject_7-24`; `OC202405`; `https://arvenetternansen.com/`; `https://doi.org/10.3030/101180559`; `https://doi.org/10.26259/3b15eca7`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/projectID-2025-06-12
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Gathering/Project
