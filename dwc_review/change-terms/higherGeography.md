## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/higherGeography

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~higherGeography~ **higherGeography**
* Term label (English, not normative): ~Higher Geography~ **Higher Geography**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Event
* New definition of the term (normative): **A list (concatenated and separated) of geographic names less specific than the information captured in dwc:locality.**
* Previous definition of the term: ~A list (concatenated and separated) of geographic names less specific than the information captured in the dwc:locality term.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to separate the values in a list with space vertical bar space (` | `), with terms in order from least specific to most specific.** 
* Previous usage comments: ~Recommended best practice is to separate the values in a list with space vertical bar space (` | `), with terms in order from least specific to most specific.~
* New examples (not normative): **`North Atlantic Ocean`; `South America | Argentina | Patagonia | Parque Nacional Nahuel Huapi | Neuquén | Los Lagos` with accompanying values `South America` (continent) `Argentina` (country), `Neuquén` (first order division), and `Los Lagos` (second order division)**
* Previous examples (not normative): ~`North Atlantic Ocean`; `South America | Argentina | Patagonia | Parque Nacional Nahuel Huapi | Neuquén | Los Lagos` with accompanying values `South America` (continent) `Argentina` (country), `Neuquén` (first order division), and `Los Lagos` (second order division)~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/higherGeography-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): {DataSets/DataSet/Units/Unit/Gathering/LocalityText or DataSets/DataSet/Units/Unit/Gathering/NamedAreas/NamedArea/AreaName}
