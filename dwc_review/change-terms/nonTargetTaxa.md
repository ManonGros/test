**Old term**

**Definition:** A list (concatenated and separated) of taxa reported during the dwc:Event that are outside of the target taxonomic scope (the combination of eco:targetTaxonomicScope and eco:excludedTaxonomicScope).
**Label:** Non-target Taxa
**Term Name:** eco:nonTargetTaxa
**Term version IRI:** http://rs.tdwg.org/eco/terms/version/nonTargetTaxa-2025-07-10
**Version of:** http://rs.tdwg.org/eco/terms/nonTargetTaxa
**Issued:** 2025-07-10
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/eco/terms/version/nonTargetTaxa-2024-03-26


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>survey</li></ul> |
| **key** |  |
| **title** | Non Target Taxa |
| **description** | A list (concatenated and separated) of taxa reported during a dwc:Event that are outside of the target taxonomic scope (the combination of eco:targetTaxonomicScope and eco:excludedTaxonomicScope). |
| **comments** | This term is meant to allow the full list of taxa that are considered outside of the taxonomic scope and yet were reported in the dataset to be shared. This term is relevant only if a target taxonomic scope is declared and eco:hasNonTargetTaxa is ‘true’. Taxonomic scope is based on the combination of eco:targetTaxonomicScope and eco:excludedTaxonomicScope. Non-target taxa (in some disciplines called “bycatch”) can be reported at any taxonomic level. Recommended best practice is to separate multiple values in a list with space vertical bar space ( | ). This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value. |
| **example** | `Parabuteo unicinctus | Geranoaetus melanoleucus`; `Cetoniinae | Aclopinae | Cyclocephala modesta` |
| **type** | string |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** |  |
| **maximum** |  |
| **namespace** | eco |
| **dcterms:isVersionOf** | http://rs.tdwg.org/eco/terms/nonTargetTaxa |
| **dcterms:references** | http://rs.tdwg.org/eco/terms/version/nonTargetTaxa-2025-07-10 |
| **rdfs:comment** | A list (concatenated and separated) of taxa reported during the dwc:Event that are outside of the target taxonomic scope (the combination of eco:targetTaxonomicScope and eco:excludedTaxonomicScope). |
| **status** | recommended |
