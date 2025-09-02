**Old term**

**Definition:** The reference to the source in which the specific taxon concept circumscription is defined or implied - traditionally signified by the Latin "sensu" or "sec." (from secundum, meaning "according to"). For taxa that result from identifications, a reference to the keys, monographs, experts and other sources should be given.
**Label:** Name According To
**Term Name:** dwc:nameAccordingTo
**Term version IRI:** http://rs.tdwg.org/dwc/terms/version/nameAccordingTo-2023-06-28
**Version of:** http://rs.tdwg.org/dwc/terms/nameAccordingTo
**Issued:** 2023-06-28
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/dwc/terms/version/nameAccordingTo-2021-07-15


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>identification</li><li>identification-taxon</li></ul> |
| **key** |  |
| **title** | Name According To |
| **description** | A reference to the source in which a specific taxon concept circumscription is defined or implied - traditionally signified by the Latin "sensu" or "sec." (from secundum, meaning "according to"). For taxa that result from identifications, a reference to the keys, monographs, experts and other sources should be given. |
| **comments** | This term provides context to the dwc:scientificName. Together with the dwc:scientificName, separated by sensu or sec., it forms the taxon concept label, which may be seen as having the same relationship to dwc:taxonConceptID as, for example, dwc:acceptedNameUsage has to dwc:acceptedNameUsageID. When not provided, in Taxon Core data sets the dwc:nameAccordingTo can be taken to be the data set. In this case the data set mostly provides sufficient context to infer the delimitation of the taxon and its relationship with other taxa. In Occurrence Core data sets, when not provided, dwc:nameAccordingTo can be an underlying taxonomy of the data set, e.g. Plants of the World Online (http://powo.science.kew.org/) for vascular plant records in iNaturalist (in which case it should be provided), or, which is the case for most dwc:PreservedSpecimen data sets, the dwc:Identification, in which case there is no further context. |
| **example** | `Franz NM, Cardona-Duque J (2013) Description of two new species and phylogenetic reassessment of Perelleschus Wibmer & O’Brien, 1986 (Coleoptera: Curculionidae), with a complete taxonomic concept history of Perelleschus sec. Franz & Cardona-Duque, 2013. Syst Biodivers. 11: 209–236.` (as the full citation of the Franz & Cardona-Duque (2013) in Perelleschus splendida sec. Franz & Cardona-Duque (2013)) |
| **type** | string |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** |  |
| **maximum** |  |
| **namespace** | dwc |
| **dcterms:isVersionOf** | http://rs.tdwg.org/dwc/terms/nameAccordingTo |
| **dcterms:references** | http://rs.tdwg.org/dwc/terms/version/nameAccordingTo-2023-06-28 |
| **rdfs:comment** | The reference to the source in which the specific taxon concept circumscription is defined or implied - traditionally signified by the Latin "sensu" or "sec." (from secundum, meaning "according to"). For taxa that result from identifications, a reference to the keys, monographs, experts and other sources should be given. |
| **status** | recommended |
