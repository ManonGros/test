## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/iri/georeferencedBy

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~georeferencedBy~ **georeferencedByID**
* Term label (English, not normative): ~Georeferenced By (IRI)~ **Georeferenced By ID**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Event
* New definition of the term (normative): **An identifier for a dcterms:Agent responsible for determining a georeference for a dwc:Event.**
* Previous definition of the term: ~A person, group, or organization who determined the georeference (spatial representation) for the dcterms:Location.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use a globally unique identifier.** 
* Previous usage comments: ~Terms in the dwciri namespace are intended to be used in RDF with non-literal objects.~
* New examples (not normative): **`https://orcid.org/0000-0002-1825-0097`**
* Previous examples (not normative): 
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/iri/version/georeferencedBy-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
