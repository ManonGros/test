## New term

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Proposed attributes of the new term:

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): isSurveyTargetFullyReported
* Term label (English, not normative): Is Survey Target Fully Reported
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): SurveyTarget
* Definition of the term (normative): A declaration of whether the counts for an instance of the dwc:SurveyTarget report everything that matches the declared dwc:SurveyTarget. If they do, this enables inference of absence of detection for everything in that dwc:SurveyTarget that is included but that does not appear in the count.
* Usage comments (recommendations regarding content, etc., not normative): 
* Examples (not normative): `true`; `false`
* Refines (identifier of the broader term this term refines; normative): 
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): 
