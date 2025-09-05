## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/relationshipOfResourceID

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~relationshipOfResourceID~ **relationshipTypeIRI**
* Term label (English, not normative): ~Relationship Of Resource ID~ **Relationship Type IRI**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): ResourceRelationship
* New definition of the term (normative): **An IRI of a controlled vocabulary value for the type of a dwc:ResourceRelationship.**
* Previous definition of the term: ~An identifier for the relationship type (predicate) that connects the subject identified by dwc:resourceID to its object identified by dwc:relatedResourceID.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use an IRI for a term in a controlled vocabulary.** 
* Previous usage comments: ~Recommended best practice is to use the identifiers of the terms in a controlled vocabulary, such as the OBO Relation Ontology.~
* New examples (not normative): **`http://purl.obolibrary.org/obo/RO_0002456` (for the relation pollinated by); `http://purl.obolibrary.org/obo/RO_0002455` (for the relation pollinates); `https://www.inaturalist.org/observation_fields/879` (for the relation eaten by)**
* Previous examples (not normative): ~`http://purl.obolibrary.org/obo/RO_0002456` (for the relation `pollinated by`); `http://purl.obolibrary.org/obo/RO_0002455` (for the relation `pollinates`); `https://www.inaturalist.org/observation_fields/879` (for the relation `eaten by`)~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/relationshipOfResourceID-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
