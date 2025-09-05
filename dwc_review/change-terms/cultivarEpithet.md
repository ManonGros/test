## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/cultivarEpithet

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~cultivarEpithet~ **cultivarEpithet**
* Term label (English, not normative): ~Cultivar Epithet~ **Cultivar Epithet**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Identification
* New definition of the term (normative): **Part of the name of a cultivar, cultivar group or grex that follows a dwc:scientificName.**
* Previous definition of the term: ~Part of the name of a cultivar, cultivar group or grex that follows the dwc:scientificName.~
* New usage comments (recommendations regarding content, etc., not normative): **According to the Rules of the Cultivated Plant Code, a cultivar name consists of a botanical name followed by a cultivar epithet. The value given as the dwc:cultivarEpithet should exclude any quotes. The term dwc:taxonRank should be used to indicate which type of cultivated plant name (e.g. cultivar, cultivar group, grex) is concerned. This epithet, including any enclosing apostrophes or suffix, should be provided in dwc:scientificName as well.** 
* Previous usage comments: ~According to the Rules of the Cultivated Plant Code, a cultivar name consists of a botanical name followed by a cultivar epithet. The value given as the dwc:cultivarEpithet should exclude any quotes. The term dwc:taxonRank should be used to indicate which type of cultivated plant name (e.g. cultivar, cultivar group, grex) is concerned. This epithet, including any enclosing apostrophes or suffix, should be provided in dwc:scientificName as well.~
* New examples (not normative): **`King Edward` (for scientificName `Solanum tuberosum 'King Edward'` and taxonRank `cultivar`); `Mishmiense` (for scientificName `Rhododendron boothii Mishmiense Group` and taxonRank `cultivar group`); `Atlantis` (for scientificName `Paphiopedilum Atlantis grex` and taxonRank `grex`)**
* Previous examples (not normative): ~`King Edward` (for scientificName `Solanum tuberosum 'King Edward'` and taxonRank `cultivar`); `Mishmiense` (for scientificName `Rhododendron boothii Mishmiense Group` and taxonRank `cultivar group`); `Atlantis` (for scientificName `Paphiopedilum Atlantis grex` and taxonRank `grex`)~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/cultivarEpithet-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): http://rs.tdwg.org/abcd/terms/cultivarName or http://rs.tdwg.org/abcd/terms/cultivarGroupName or http://rs.tdwg.org/abcd/terms/breed (ABCD 3.0)
