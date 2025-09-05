## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/lifeStage

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~lifeStage~ **lifeStage**
* Term label (English, not normative): ~Life Stage~ **Life Stage**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Occurrence
* New definition of the term (normative): **An age class or life stage of a dwc:Organism.**
* Previous definition of the term: ~The age class or life stage of the dwc:Organism(s) at the time the dwc:Occurrence was recorded.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use a controlled vocabulary. This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.** 
* Previous usage comments: ~Recommended best practice is to use a controlled vocabulary. This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.~
* New examples (not normative): **`zygote`; `larva`; `juvenile`; `adult`; `seedling`; `flowering`; `fruiting`**
* Previous examples (not normative): ~`zygote`; `larva`; `juvenile`; `adult`; `seedling`; `flowering`; `fruiting`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/lifeStage-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/MycologicalUnit/MycologicalSexualStage or DataSets/DataSet/Units/Unit/MycologicalUnit/MycologicalLiveStages/MycologicalLiveStage or DataSets/DataSet/Units/Unit/ZoologicalUnit/PhasesOrStages/PhaseOrStage
