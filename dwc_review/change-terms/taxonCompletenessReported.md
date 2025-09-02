**Old term**

**Definition:** Statement about whether the taxonomic completeness of the dwc:Event was assessed.
**Label:** Taxon Completeness Reported
**Term Name:** eco:taxonCompletenessReported
**Term version IRI:** http://rs.tdwg.org/eco/terms/version/taxonCompletenessReported-2025-07-10
**Version of:** http://rs.tdwg.org/eco/terms/taxonCompletenessReported
**Issued:** 2025-07-10
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/eco/terms/version/taxonCompletenessReported-2024-03-26


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>survey</li></ul> |
| **key** |  |
| **title** | Taxon Completeness Reported |
| **description** | Statement about whether the taxonomic completeness of a dwc:Event was assessed. |
| **comments** | This term is meant to alert users that the inventory was conducted in such a way that all of the target taxa (the combination of eco:targetTaxonomicScope and eco:excludedTaxonomicScope) should have been detectable if they were present during a dwc:Event. This term can provide data users with a qualitative measure of how comprehensively an area has been surveyed, which assists in interpreting species populations, areas of occupancy, inferring species absences, etc. This term is only relevant if a dwc:Event used restricted search or open search methods. If taxonomic completeness was assessed, the methods used or an explanation of the basis of the completeness should be stated in eco:taxonCompletenessProtocols. Recommended best practice is to use controlled value strings from the controlled vocabulary designated for use with this term, listed at http://rs.tdwg.org/dwc/doc/tcr/. This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value. |
| **example** | `notReported`; `reportedComplete`; `reportedIncomplete` |
| **type** | string |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** |  |
| **maximum** |  |
| **namespace** | eco |
| **dcterms:isVersionOf** | http://rs.tdwg.org/eco/terms/taxonCompletenessReported |
| **dcterms:references** | http://rs.tdwg.org/eco/terms/version/taxonCompletenessReported-2025-07-10 |
| **rdfs:comment** | Statement about whether the taxonomic completeness of the dwc:Event was assessed. |
| **status** | recommended |
