## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/taxonID

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~taxonID~ **taxonID**
* Term label (English, not normative): ~Taxon ID~ **Taxon ID**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Identification
* New definition of the term (normative): **An identifier for a dwc:Taxon.**
* Previous definition of the term: ~An identifier for the set of dwc:Taxon information. May be a global unique identifier or an identifier specific to the data set.~
* New usage comments (recommendations regarding content, etc., not normative): **In DwC-DP, the dwc:taxonID is always an external link to a taxon record. As such, if present, it should be a resolvable globally unique identifier. See the Identifiers section of https://github.com/CatalogueOfLife/coldp/blob/master/README.md.** 
* Previous usage comments: ~~
* New examples (not normative): **`8fa58e08-08de-4ac1-b69c-1235340b7001`; `32567`; `https://www.gbif.org/species/212`**
* Previous examples (not normative): ~`8fa58e08-08de-4ac1-b69c-1235340b7001`; `32567`; `https://www.gbif.org/species/212`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/taxonID-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
