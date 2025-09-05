## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/fundingAttributionID

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~fundingAttributionID~ **fundingAttributionID**
* Term label (English, not normative): ~Funding Attribution ID~ **Funding Attribution ID**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Provenance
* New definition of the term (normative): **A list (concatenated and separated) of globally unique identifiers for funding organizations or agencies that supported a project.**
* Previous definition of the term: ~A list (concatenated and separated) of the globally unique identifiers for the funding organizations or agencies that supported the project.~
* New usage comments (recommendations regarding content, etc., not normative): **Provide a unique identifier for the funding body, such as an identifier used in governmental or international databases. If no official identifier exists, use a persistent and unique identifier within your organization or dataset. The Recommended best practice is to separate the values in a list with space vertical bar space (` | `).** 
* Previous usage comments: ~Provide a unique identifier for the funding body, such as an identifier used in governmental or international databases. If no official identifier exists, use a persistent and unique identifier within your organization or dataset. The recommended best practice is to separate the values in a list with space vertical bar space ( | ).~
* New examples (not normative): **`https://ror.org/00epmv149`; `https://ror.org/00epmv149 | https://ror.org/04jnzhb65`; `https://www.wikidata.org/wiki/Q13102615`**
* Previous examples (not normative): ~`https://ror.org/00epmv149`; `https://ror.org/00epmv149 | https://ror.org/04jnzhb65`; `https://www.wikidata.org/wiki/Q13102615`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/fundingAttributionID-2025-06-12
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
