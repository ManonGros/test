## New term

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Proposed attributes of the new term:

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): includeOrExclude
* Term label (English, not normative): Include Or Exclude
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): SurveyTarget
* Definition of the term (normative): A term to declare whether an instance of a dwc:SurveyTarget is an included scope or an excluded scope. Combinations of dwc:SurveyTarget records of inclusions and exclusions can define complex scopes such as all flying adult Aves except Passeriformes.
* Usage comments (recommendations regarding content, etc., not normative): Recommended best practice is use a controlled vocabulary consisting of 'include' and 'exclude' only.
* Examples (not normative): `include`; `exclude`
* Refines (identifier of the broader term this term refines; normative): 
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): 
