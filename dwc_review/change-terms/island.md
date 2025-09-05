## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/island

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~island~ **island**
* Term label (English, not normative): ~Island~ **Island**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Event
* New definition of the term (normative): **A name of an island on or near which a dcterms:Location occurs.**
* Previous definition of the term: ~The name of the island on or near which the dcterms:Location occurs.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use a controlled vocabulary such as the Getty Thesaurus of Geographic Names.** 
* Previous usage comments: ~Recommended best practice is to use a controlled vocabulary such as the Getty Thesaurus of Geographic Names.~
* New examples (not normative): **`Nosy Be`; `Bikini Atoll`; `Vancouver`; `Viti Levu`; `Zanzibar`**
* Previous examples (not normative): ~`Nosy Be`; `Bikini Atoll`; `Vancouver`; `Viti Levu`; `Zanzibar`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/island-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Gathering/NamedAreas/NamedArea/AreaName with NamedAreas/NamedArea/AreaClass= Island
