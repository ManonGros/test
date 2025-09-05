## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/organismScope

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~organismScope~ **organismScope**
* Term label (English, not normative): ~Organism Scope~ **Organism Scope**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Organism
* New definition of the term (normative): **A description of the type of a dwc:Organism instance.**
* Previous definition of the term: ~A description of the kind of dwc:Organism instance. Can be used to indicate whether the dwc:Organism instance represents a discrete organism or if it represents a particular type of aggregation.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use a controlled vocabulary. Can be used to indicate whether a dwc:Organism instance represents a discrete organism or if it represents a particular type of aggregation.** 
* Previous usage comments: ~Recommended best practice is to use a controlled vocabulary. This term is not intended to be used to specify a type of dwc:Taxon. To describe the kind of dwc:Organism using a URI object in RDF, use rdf:type (http://www.w3.org/1999/02/22-rdf-syntax-ns#type) instead.~
* New examples (not normative): **`multicellular organism`; `virus`; `clone`; `pack`; `colony`**
* Previous examples (not normative): ~`multicellular organism`; `virus`; `clone`; `pack`; `colony`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/organismScope-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
