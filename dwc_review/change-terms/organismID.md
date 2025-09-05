## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/organismID

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~organismID~ **organismID**
* Term label (English, not normative): ~Organism ID~ **Organism ID**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Organism
* New definition of the term (normative): **An identifier for a dwc:Organism.**
* Previous definition of the term: ~An identifier for the dwc:Organism instance (as opposed to a particular digital record of the dwc:Organism). May be a globally unique identifier or an identifier specific to the data set.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use a persistent, globally unique identifier.** 
* Previous usage comments: ~~
* New examples (not normative): **`http://arctos.database.museum/guid/WNMU:Mamm:1249`**
* Previous examples (not normative): ~`http://arctos.database.museum/guid/WNMU:Mamm:1249`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/organismID-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
