## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/genericName

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~genericName~ **genericName**
* Term label (English, not normative): ~Generic Name~ **Generic Name**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Identification
* New definition of the term (normative): **The genus part of a dwc:scientificName.**
* Previous definition of the term: ~The genus part of the dwc:scientificName without authorship.~
* New usage comments (recommendations regarding content, etc., not normative): **For synonyms the accepted genus and the genus part of the name may be different. The term dwc:genericName should be used together with dwc:specificEpithet to form a binomial and with dwc:infraspecificEpithet to form a trinomial. The term dwc:genericName should only be used for combinations. Uninomials of generic rank do not have a dwc:genericName.** 
* Previous usage comments: ~For synonyms the accepted genus and the genus part of the name may be different. The term dwc:genericName should be used together with dwc:specificEpithet to form a binomial and with dwc:infraspecificEpithet to form a trinomial. The term dwc:genericName should only be used for combinations. Uninomials of generic rank do not have a dwc:genericName.~
* New examples (not normative): **`Felis` (for scientificName `Felis concolor`, with accompanying values of `Puma concolor` in acceptedNameUsage and `Puma` in genus)**
* Previous examples (not normative): ~`Felis` (for scientificName `Felis concolor`, with accompanying values of `Puma concolor` in acceptedNameUsage and `Puma` in genus)~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/genericName-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
