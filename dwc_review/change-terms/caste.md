## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/caste

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~caste~ **caste**
* Term label (English, not normative): ~Caste~ **Caste**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Occurrence
* New definition of the term (normative): **A social caste of a dwc:Organism.**
* Previous definition of the term: ~Categorisation of individuals for eusocial species (including some mammals and arthropods).~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use a controlled vocabulary that aligns best with a dwc:Taxon. This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.** 
* Previous usage comments: ~Recommended best practice is to use a controlled vocabulary that aligns best with the dwc:Taxon. This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.~
* New examples (not normative): **`queen`; `male alate`; `intercaste`; `soldier`; `ergatoid`**
* Previous examples (not normative): ~`queen`; `male alate`; `intercaste`; `minor worker`; `soldier`; `ergatoid`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/caste-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
