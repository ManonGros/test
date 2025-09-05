## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/parentEventID

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~parentEventID~ **parentEventID**
* Term label (English, not normative): ~Parent Event ID~ **Parent Event ID**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Event
* New definition of the term (normative): **An identifier for a broader dwc:Event that contains this and potentially other dwc:Events.**
* Previous definition of the term: ~An identifier for the broader dwc:Event that groups this and potentially other dwc:Events.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use a globally unique identifier.** 
* Previous usage comments: ~Use a globally unique identifier for a dwc:Event or an identifier for a dwc:Event that is specific to the data set.~
* New examples (not normative): **`A1` (parentEventID to identify the main Whittaker Plot in nested samples, each with its own eventID - `A1:1`, `A1:2`).**
* Previous examples (not normative): ~`A1` (parentEventID to identify the main Whittaker Plot in nested samples, each with its own eventID - `A1:1`, `A1:2`).~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/parentEventID-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
