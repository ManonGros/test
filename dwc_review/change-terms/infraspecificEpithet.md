## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/infraspecificEpithet

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~infraspecificEpithet~ **infraspecificEpithet**
* Term label (English, not normative): ~Infraspecific Epithet~ **Infraspecific Epithet**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Identification
* New definition of the term (normative): **The name of the lowest or terminal infraspecific epithet of a dwc:scientificName, excluding any rank designation.**
* Previous definition of the term: ~The name of the lowest or terminal infraspecific epithet of the dwc:scientificName, excluding any rank designation.~
* New usage comments (recommendations regarding content, etc., not normative): **In botany, name strings in literature and identifications may have multiple infraspecific ranks. According to the International Code of Nomenclature for algae, fungi, and plants (Schenzhen Code Articles 6.7 & Art. 24.1), valid names only have two epithets, with the lowest rank being the dwc:infraspecificEpithet. For example: the dwc:infraspecificEpithet in the string Indigofera charlieriana subsp. sessilis var. scaberrima is scaberrima and the dwc:scientificName is Indigofera charlieriana var. scaberrima (Schinz) J.B.Gillett. Use dwc:verbatimIdentification for the full name string used in a dwc:Identification.** 
* Previous usage comments: ~In botany, name strings in literature and identifications may have multiple infraspecific ranks. According to the International Code of Nomenclature for algae, fungi, and plants (Schenzhen Code Articles 6.7 & Art. 24.1), valid names only have two epithets, with the lowest rank being the dwc:infraspecificEpithet. For example: the dwc:infraspecificEpithet in the string `Indigofera charlieriana subsp. sessilis var. scaberrima` is `scaberrima` and the dwc:scientificName is `Indigofera charlieriana var. scaberrima (Schinz) J.B.Gillett`. Use dwc:verbatimIdentification for the full name string used in a dwc:Identification.~
* New examples (not normative): **`concolor` (for scientificName `Puma concolor concolor`); `oxyadenia` (for scientificName `Quercus agrifolia var. oxyadenia`); `laxa` (for scientificName `Cheilanthes hirta f. laxa`); `scaberrima` (for scientificName `Indigofera charlieriana var. scaberrima`)**
* Previous examples (not normative): ~`concolor` (for scientificName `Puma concolor concolor (Linnaeus, 1771)`); `oxyadenia` (for scientificName `Quercus agrifolia var. oxyadenia (Torr.) J.T. Howell`); `laxa` (for scientificName `Cheilanthes hirta f. laxa (Kunze) W.Jacobsen & N.Jacobsen`); `scaberrima` (for scientificName `Indigofera charlieriana var. scaberrima (Schinz) J.B.Gillett`)~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/infraspecificEpithet-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Identifications/Identification/TaxonIdentified/ScientificName/NameAtomised/Bacterial/SubspeciesEpithet or DataSets/DataSet/Units/Unit/Identifications/Identification/TaxonIdentified/ScientificName/NameAtomised/Botanical/SecondEpithet or DataSets/DataSet/Units/Unit/Identifications/Identification/TaxonIdentified/ScientificName/NameAtomised/Zoological/SubspeciesEpithet
