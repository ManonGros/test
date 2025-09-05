## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/namePublishedIn

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~namePublishedIn~ **namePublishedIn**
* Term label (English, not normative): ~Name Published In~ **Name Published In**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Identification
* New definition of the term (normative): **A reference for the publication in which a dwc:scientificName was originally established under the rules of an associated dwc:nomenclaturalCode.**
* Previous definition of the term: ~A reference for the publication in which the dwc:scientificName was originally established under the rules of the associated dwc:nomenclaturalCode.~
* New usage comments (recommendations regarding content, etc., not normative): **A citation of the first publication of the name in its given combination, not the basionym / original name. Recombinations are often not published in zoology, in which case dwc:namePublishedIn should be empty.** 
* Previous usage comments: ~A citation of the first publication of the name in its given combination, not the basionym / original name. Recombinations are often not published in zoology, in which case dwc:namePublishedIn should be empty.~
* New examples (not normative): **`Pearson O. P., and M. I. Christie. 1985. Historia Natural, 5(37):388`; `Forel, Auguste, Diagnosies provisoires de quelques espèces nouvelles de fourmis de Madagascar, récoltées par M. Grandidier., Annales de la Societe Entomologique de Belgique, Comptes-rendus des Seances 30, 1886`**
* Previous examples (not normative): ~`Pearson O. P., and M. I. Christie. 1985. Historia Natural, 5(37):388`; `Forel, Auguste, Diagnosies provisoires de quelques espèces nouvelles de fourmis de Madagascar, récoltées par M. Grandidier., Annales de la Societe Entomologique de Belgique, Comptes-rendus des Seances 30, 1886`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/namePublishedIn-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/SpecimenUnit/NomenclaturalTypeDesignations/NomenclaturalTypeDesignation/NomenclaturalReference/TitleCitation
