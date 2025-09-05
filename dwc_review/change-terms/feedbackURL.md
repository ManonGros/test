## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/feedbackURL

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~feedbackURL~ **feedbackURL**
* Term label (English, not normative): ~Feedback URL~ **Feedback URL**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Provenance
* New definition of the term (normative): **A uniform resource locator (URL) that points to a webpage on which a form may be submitted to gather feedback about the record.**
* Previous definition of the term: ~A uniform resource locator (URL) that points to a webpage on which a form may be submitted to gather feedback about the record.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to optionally include query strings that act to pre-populate web page form elements and communicate the context.** 
* Previous usage comments: ~Recommended best practice is to optionally include query strings that act to pre-populate web page form elements and communicate the context.~
* New examples (not normative): **`https://example.com/new?title=New+issue&body=This+comment+is+about+CAN12345`**
* Previous examples (not normative): ~`https://example.com/new?title=New+issue&body=This+comment+is+about+CAN12345`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/feedbackURL-2025-06-12
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
