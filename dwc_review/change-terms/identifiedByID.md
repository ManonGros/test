## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/iri/identifiedBy

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~identifiedBy~ **identifiedByID**
* Term label (English, not normative): ~Identified By (IRI)~ **Identified By ID**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Identification
* New definition of the term (normative): **An identifier for a dcterms:Agent responsible for making a taxonomic determination of a dwc:Organism.**
* Previous definition of the term: ~A person, group, or organization who assigned the dwc:Taxon to the subject.~
* New usage comments (recommendations regarding content, etc., not normative): **When used in the context of a dwc:Survey, the subject consists of all of the dwc:Identifications related to the dwc:Survey. Recommended best practice is to provide a single identifier that disambiguates the details of the identifying dcterma:Agent. If a list is used, the order of the identifiers on the list should not be assumed to convey any semantics. Recommended best practice is to separate the values in a list with space vertical bar space (` | `).** 
* Previous usage comments: ~When used in the context of an Event (such as in the Humboldt Extension), the subject consists of all of the dwc:Organisms related to the Event. Terms in the dwciri namespace are intended to be used in RDF with non-literal objects.~
* New examples (not normative): **`https://orcid.org/0000-0002-1825-0097` (for an individual); `https://orcid.org/0000-0002-1825-0097 | https://orcid.org/0000-0002-1825-0098` (for a list of people)**
* Previous examples (not normative): 
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/iri/version/identifiedBy-2025-06-12
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
