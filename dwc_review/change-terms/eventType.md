## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/eventType

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~eventType~ **eventType**
* Term label (English, not normative): ~Event Type~ **Event Type**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Event
* New definition of the term (normative): **A narrow category that best matches the nature of a dwc:Event.**
* Previous definition of the term: ~The nature of the dwc:Event.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use a controlled vocabulary.** 
* Previous usage comments: ~Recommended best practice is to use a controlled vocabulary. Regardless of the dwc:eventType, the interval of the dwc:Event can be captured in dwc:eventDate. This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.~
* New examples (not normative): **`BioBlitz`; `camera trap deployment`; `expedition`; `project`; `site visit`; `trawl`**
* Previous examples (not normative): ~`Sample`; `Observation`; `Site Visit`; `Biotic Interaction`; `Bioblitz`; `Expedition`; `Survey`; `Project`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/eventType-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
