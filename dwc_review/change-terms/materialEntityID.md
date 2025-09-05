## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/materialEntityID

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~materialEntityID~ **materialEntityID**
* Term label (English, not normative): ~Material Entity ID~ **Material Entity ID**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): MaterialEntity
* New definition of the term (normative): **An identifier for a dwc:MaterialEntity.**
* Previous definition of the term: ~An identifier for a particular instance of a dwc:MaterialEntity.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use a globally unique identifier.** 
* Previous usage comments: ~Values of dwc:materialEntityID are intended to uniquely and persistently identify a particular dwc:MaterialEntity within some context. Examples of context include a particular sample collection, an organization, or the worldwide scale. Recommended best practice is to use a persistent, globally unique identifier. The identifier is bound to a physical object (the dwc:MaterialEntity) as opposed to a particular digital record (representation) of that physical object.~
* New examples (not normative): **`06809dc5-f143-459a-be1a-6f03e63fc083`**
* Previous examples (not normative): ~`06809dc5-f143-459a-be1a-6f03e63fc083`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/materialEntityID-2023-09-13
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): Unit/UnitGUID or Unit/UnitID
