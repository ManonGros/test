**Old term**

**Definition:** The genus part of the dwc:scientificName without authorship.
**Label:** Generic Name
**Term Name:** dwc:genericName
**Term version IRI:** http://rs.tdwg.org/dwc/terms/version/genericName-2023-06-28
**Version of:** http://rs.tdwg.org/dwc/terms/genericName
**Issued:** 2023-06-28
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/dwc/terms/version/genericName-2021-07-15


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>identification</li><li>identification-taxon</li></ul> |
| **key** |  |
| **title** | Generic Name |
| **description** | The genus part of a dwc:scientificName. |
| **comments** | For synonyms the accepted genus and the genus part of the name may be different. The term dwc:genericName should be used together with dwc:specificEpithet to form a binomial and with dwc:infraspecificEpithet to form a trinomial. The term dwc:genericName should only be used for combinations. Uninomials of generic rank do not have a dwc:genericName. |
| **example** | `Felis` (for scientificName `Felis concolor`, with accompanying values of `Puma concolor` in acceptedNameUsage and `Puma` in genus) |
| **type** | string |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** |  |
| **maximum** |  |
| **namespace** | dwc |
| **dcterms:isVersionOf** | http://rs.tdwg.org/dwc/terms/genericName |
| **dcterms:references** | http://rs.tdwg.org/dwc/terms/version/genericName-2023-06-28 |
| **rdfs:comment** | The genus part of the dwc:scientificName without authorship. For synonyms the accepted genus and the genus part of the name may be different. The term dwc:genericName should be used together with dwc:specificEpithet to form a binomial and with dwc:infraspecificEpithet to form a trinomial. The term dwc:genericName should only be used for combinations. Uninomials of generic rank do not have a dwc:genericName. |
| **status** | recommended |
