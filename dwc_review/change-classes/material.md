## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/MaterialEntity

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~MaterialEntity~ **material**
* Term label (English, not normative): ~Material Entity~ **Material**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): MaterialEntity
* New definition of the term (normative): **An entity that can be identified, exist for some period of time, and consist in whole or in part of physical matter while it exists.**
* Previous definition of the term: ~An entity that can be identified, exists for some period of time, and consists in whole or in part of physical matter while it exists.~
* New usage comments (recommendations regarding content, etc., not normative): **The term is defined at the most general level to admit descriptions of any subtype of material entity within the scope of Darwin Core. In particular, any kind of material sample, preserved specimen, fossil, or exemplar from living collections is intended to be subsumed under this term.** 
* Previous usage comments: ~The term is defined at the most general level to admit descriptions of any subtype of material entity within the scope of Darwin Core. In particular, any kind of material sample, preserved specimen, fossil, or exemplar from living collections is intended to be subsumed under this term.~
* New examples (not normative): **`the entire contents of a trawl`; `a subset of the contents of a trawl`; `the body of a fish`; `the stomach contents of a fish`; `a rock containing fossils`; `a fossil within a rock`; `an herbarium sheet with its attached plant specimen`; `a flower on a plant specimen`; `a pollen grain`; `a specific water sample`; `an isolated molecule of DNA`**
* Previous examples (not normative): ~`an instance of a fossil`; `an instance of a herbarium sheet with its attached plant specimen`; `a particular part of the plant-derived material affixed to a herbarium sheet`; `an instance of a frozen tissue sample`; `a specific water sample`; `an instance of a meteorite fragment`; `a particular wolf in a zoo`; `a particular pack of wolves in the wild`; `an isolated molecule of DNA`; `a specific deep-frozen DNA sample`; `a particular field notebook`; `a particular paper page from a field notebook`; `an instance of a printed photograph`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/MaterialEntity-2023-09-13
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): None (Specimen Unit, when used to denote a class of things, appears to be a broadly construed subclass.)
