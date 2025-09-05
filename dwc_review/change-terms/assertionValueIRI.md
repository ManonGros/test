## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/iri/measurementValue

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~measurementValue~ **assertionValueIRI**
* Term label (English, not normative): ~Measurement Value (IRI)~ **Assertion Value IRI**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Assertion
* New definition of the term (normative): **An IRI of the controlled vocabulary value for a value of a dwc:Assertion.**
* Previous definition of the term: ~The value of the measurement, fact, characteristic, or assertion.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use an IRI for a term in a controlled vocabulary.** 
* Previous usage comments: ~Terms in the dwciri namespace are intended to be used in RDF with non-literal objects.~
* New examples (not normative): **`http://vocab.nerc.ac.uk/collection/L22/current/TOOL0960/`**
* Previous examples (not normative): ~`http://vocab.nerc.ac.uk/collection/L22/current/TOOL0960/`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/iri/version/measurementValue-2021-07-15
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
