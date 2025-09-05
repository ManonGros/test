## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/scientificName

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~scientificName~ **scientificName**
* Term label (English, not normative): ~Scientific Name~ **Scientific Name**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Identification
* New definition of the term (normative): **A scientific name string, not including authorship, date or identification qualifiers.**
* Previous definition of the term: ~The full scientific name, with authorship and date information if known. When forming part of a dwc:Identification, this should be the name in lowest level taxonomic rank that can be determined. This term should not contain identification qualifications, which should instead be supplied in the dwc:identificationQualifier term.~
* New usage comments (recommendations regarding content, etc., not normative): **** 
* Previous usage comments: ~This term should not contain identification qualifications, which should instead be supplied in the IdentificationQualifier term. When applied to an Organism or Occurrence, this term should be used to represent the scientific name that was applied to the associated Organism in accordance with the Taxon to which it was or is currently identified. Names should be compliant to the most recent nomenclatural code. For example, names of hybrids for algae, fungi and plants should follow the rules of the International Code of Nomenclature for algae, fungi, and plants (Schenzhen Code Articles H.1, H.2 and H.3). Thus, use the multiplication sign `×` (Unicode `U+00D7`, HTML `&times;`) to identify a hybrid, not `x` or `X`, if possible.~
* New examples (not normative): **`Coleoptera` (order); `Vespertilionidae` (family); `Manis` (genus); `Ctenomys sociabilis` (genus + specificEpithet); `Ambystoma tigrinum diaboli` (genus + specificEpithet + infraspecificEpithet); `Quercus agrifolia var. oxyadenia` (genus + specificEpithet + taxonRank + infraspecificEpithet); `×Agropogon littoralis`; `Mentha ×smithiana`; `Agrostis stolonifera L. × Polypogon monspeliensis`**
* Previous examples (not normative): ~`Coleoptera` (order); `Vespertilionidae` (family); `Manis` (genus); `Ctenomys sociabilis` (genus + specificEpithet); `Ambystoma tigrinum diaboli` (genus + specificEpithet + infraspecificEpithet); `Roptrocerus typographi (Györfi, 1952)` (genus + specificEpithet + scientificNameAuthorship); `Quercus agrifolia var. oxyadenia (Torr.) J.T. Howell` (genus + specificEpithet + taxonRank + infraspecificEpithet + scientificNameAuthorship); `×Agropogon littoralis (Sm.) C. E. Hubb.`; `Mentha ×smithiana R. A. Graham`; `Agrostis stolonifera L. × Polypogon monspeliensis (L.) Desf.`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/scientificName-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Identifications/Identification/TaxonIdentified/ScientificName/FullScientificNameString
