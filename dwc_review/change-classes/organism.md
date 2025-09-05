## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/Organism

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~Organism~ **organism**
* Term label (English, not normative): ~Organism~ **Organism**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Organism
* New definition of the term (normative): **A particular organism or defined group of organisms considered to be taxonomically homogeneous.**
* Previous definition of the term: ~A particular organism or defined group of organisms considered to be taxonomically homogeneous.~
* New usage comments (recommendations regarding content, etc., not normative): **Instances of the dwc:Organism class are intended to facilitate linking one or more dwc:Identification instances to one or more dwc:Occurrence instances. Therefore, things that are typically assigned scientific names (such as viruses, hybrids, and lichens) and aggregates whose dwc:Occurrences are typically recorded (such as packs, clones, and colonies) are included in the scope of this class.** 
* Previous usage comments: ~Instances of the dwc:Organism class are intended to facilitate linking one or more dwc:Identification instances to one or more dwc:Occurrence instances. Therefore, things that are typically assigned scientific names (such as viruses, hybrids, and lichens) and aggregates whose dwc:Occurrences are typically recorded (such as packs, clones, and colonies) are included in the scope of this class.~
* New examples (not normative): **`a specific bird`; `a specific wolf pack`; `a specific instance of a bacterial culture`**
* Previous examples (not normative): ~`a specific bird`; `a specific wolf pack`; `a specific instance of a bacterial culture`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/Organism-2023-09-18
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
