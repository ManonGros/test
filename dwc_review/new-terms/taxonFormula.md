## New term

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Proposed attributes of the new term:

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): taxonFormula
* Term label (English, not normative): Taxon Formula
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Identification
* Definition of the term (normative): A string representing the pattern to use to construct a dwc:Identification from dwc:Taxon names and identification qualifiers.
* Usage comments (recommendations regarding content, etc., not normative): Recommended best practice is to use a controlled vocabulary such as https://arctos.database.museum/info/ctDocumentation.cfm?table=cttaxa_formula.
* Examples (not normative): `A`; `A ?`; `A or B`; `A and B`; `A x B`; `A cf.`; `A aff.`
* Refines (identifier of the broader term this term refines; normative): 
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): 
