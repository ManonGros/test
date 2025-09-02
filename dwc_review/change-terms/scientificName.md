**Old term**

**Definition:** The full scientific name, with authorship and date information if known. When forming part of a dwc:Identification, this should be the name in lowest level taxonomic rank that can be determined. This term should not contain identification qualifications, which should instead be supplied in the dwc:identificationQualifier term.
**Label:** Scientific Name
**Term Name:** dwc:scientificName
**Term version IRI:** http://rs.tdwg.org/dwc/terms/version/scientificName-2023-06-28
**Version of:** http://rs.tdwg.org/dwc/terms/scientificName
**Issued:** 2023-06-28
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/dwc/terms/version/scientificName-2021-07-15


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>identification</li><li>identification-taxon</li><li>material</li><li>occurrence</li></ul> |
| **key** |  |
| **title** | Scientific Name |
| **description** | A scientific name string, not including authorship, date or identification qualifiers. |
| **comments** |  |
| **example** | `Coleoptera` (order); `Vespertilionidae` (family); `Manis` (genus); `Ctenomys sociabilis` (genus + specificEpithet); `Ambystoma tigrinum diaboli` (genus + specificEpithet + infraspecificEpithet); `Quercus agrifolia var. oxyadenia` (genus + specificEpithet + taxonRank + infraspecificEpithet); `×Agropogon littoralis`; `Mentha ×smithiana`; `Agrostis stolonifera L. × Polypogon monspeliensis` |
| **type** | string |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** |  |
| **maximum** |  |
| **namespace** | dwc |
| **dcterms:isVersionOf** | http://rs.tdwg.org/dwc/terms/scientificName |
| **dcterms:references** | http://rs.tdwg.org/dwc/terms/version/scientificName-2023-06-28 |
| **rdfs:comment** | The full scientific name, with authorship and date information if known. When forming part of a dwc:Identification, this should be the name in lowest level taxonomic rank that can be determined. This term should not contain identification qualifications, which should instead be supplied in the dwc:identificationQualifier term. |
| **status** | recommended |
