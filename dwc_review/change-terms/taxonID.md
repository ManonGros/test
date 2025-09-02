**Old term**

**Definition:** An identifier for the set of dwc:Taxon information. May be a global unique identifier or an identifier specific to the data set.
**Label:** Taxon ID
**Term Name:** dwc:taxonID
**Term version IRI:** http://rs.tdwg.org/dwc/terms/version/taxonID-2023-06-28
**Version of:** http://rs.tdwg.org/dwc/terms/taxonID
**Issued:** 2023-06-28
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/dwc/terms/version/taxonID-2017-10-06


| definitions | context 1 |context 2 |
|-|-|-|
| **Context - tables concerned** | <ul><li>identification</li><li>identification-taxon</li><li>material</li></ul> | <ul><li>occurrence</li></ul> |
| **key** |  |  |
| **title** | Taxon ID | Taxon ID |
| **description** | An identifier for a dwc:Taxon. | An identifier for a dwc:Taxon. |
| **comments** | In DwC-DP, the dwc:taxonID is always an external link to a taxon record. As such, if present, it should be a resolvable globally unique identifier. See the Identifiers section of https://github.com/CatalogueOfLife/coldp/blob/master/README.md. | In DwC-DP, the taxonID is always an external link to a taxon record. As such, if present, it should be a resolvable globally unique identifier. See the Identifiers section of https://github.com/CatalogueOfLife/coldp/blob/master/README.md. |
| **example** | `8fa58e08-08de-4ac1-b69c-1235340b7001`; `32567`; `https://www.gbif.org/species/212` | `8fa58e08-08de-4ac1-b69c-1235340b7001`; `32567`; `https://www.gbif.org/species/212` |
| **type** | string | string |
| **format** | default | default |
| **unique** |  |  |
| **required** |  |  |
| **minimum** |  |  |
| **maximum** |  |  |
| **namespace** | dwc | dwc |
| **dcterms:isVersionOf** | http://rs.tdwg.org/dwc/terms/taxonID | http://rs.tdwg.org/dwc/terms/taxonID |
| **dcterms:references** | http://rs.tdwg.org/dwc/terms/version/taxonID-2023-06-28 | http://rs.tdwg.org/dwc/terms/version/taxonID-2023-06-28 |
| **rdfs:comment** | An identifier for the set of dwc:Taxon information. May be a global unique identifier or an identifier specific to the data set. | An identifier for the set of dwc:Taxon information. May be a global unique identifier or an identifier specific to the data set. |
| **status** | recommended | recommended |
