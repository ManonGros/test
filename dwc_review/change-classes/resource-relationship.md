## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/ResourceRelationship

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~ResourceRelationship~ **resource-relationship**
* Term label (English, not normative): ~Resource Relationship~ **Resource Relationship**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): ResourceRelationship
* New definition of the term (normative): **A relationship of one rdfs:Resource (http://www.w3.org/2000/01/rdf-schema#Resource) to another.**
* Previous definition of the term: ~A relationship of one rdfs:Resource (http://www.w3.org/2000/01/rdf-schema#Resource) to another.~
* New usage comments (recommendations regarding content, etc., not normative): **** 
* Previous usage comments: ~Resources can be thought of as identifiable records or instances of classes and may include, but need not be limited to instances of dwc:Occurrence, dwc:Organism, dwc:MaterialEntity, dwc:Event, dcterms:Location, dwc:GeologicalContext, dwc:Identification, or dwc:Taxon.~
* New examples (not normative): **`an instance of a dwc:Organism is the mother of another instance of a dwc:Organism`; `a uniquely identified dwc:Occurrence represents the same dwc:Occurrence as another uniquely identified dwc:Occurrence`; `a dwc:MaterialEntity is a subsample of another dwc:MaterialEntity`**
* Previous examples (not normative): ~`an instance of a dwc:Organism is the mother of another instance of a dwc:Organism`; `a uniquely identified dwc:Occurrence represents the same dwc:Occurrence as another uniquely identified dwc:Occurrence`; `a dwc:MaterialEntity is a subsample of another dwc:MaterialEntity`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/ResourceRelationship-2023-09-13
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Associations
