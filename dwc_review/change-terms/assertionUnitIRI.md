## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/iri/measurementUnit

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~measurementUnit~ **assertionUnitIRI**
* Term label (English, not normative): ~Measurement Unit (IRI)~ **Assertion Unit IRI**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Assertion
* New definition of the term (normative): **An IRI of a controlled vocabulary value for the units of a dwc:AssertionValueNumeric.**
* Previous definition of the term: ~The units associated with the dwc:measurementValue.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use an IRI for a term in a controlled vocabulary.** 
* Previous usage comments: ~Recommended best practice is to use a controlled vocabulary such as the Ontology of Units of Measure http://www.wurvoc.org/vocabularies/om-1.8/ of SI units, derived units, or other non-SI units accepted for use within the SI.~
* New examples (not normative): ****
* Previous examples (not normative): 
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/iri/version/measurementUnit-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
