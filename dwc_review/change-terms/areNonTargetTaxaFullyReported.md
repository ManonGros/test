**Old term**

**Definition:** Every dwc:Organism that was outside of the target taxonomic scope (the combination of eco:targetTaxonomicScope and eco:excludedTaxonomicScope) and detected during the dwc:Event, and that was detectable using the given protocol (given in eco:protocolDescriptions and dwc:samplingProtocol), was reported.
**Label:** Are Non-target Taxa Fully Reported
**Term Name:** eco:areNonTargetTaxaFullyReported
**Term version IRI:** http://rs.tdwg.org/eco/terms/version/areNonTargetTaxaFullyReported-2025-06-12
**Version of:** http://rs.tdwg.org/eco/terms/areNonTargetTaxaFullyReported
**Issued:** 2025-06-12
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/eco/terms/version/areNonTargetTaxaFullyReported-2024-02-28


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>survey</li></ul> |
| **key** |  |
| **title** | Are Non Target Taxa Fully Reported |
| **description** | Every dwc:Organism that was outside of the target taxonomic scope (the combination of eco:targetTaxonomicScope and eco:excludedTaxonomicScope) and detected during a dwc:Event, and that was detectable using the given protocol (given in eco:protocolDescriptions and dwc:samplingProtocol), was reported. |
| **comments** | This term is meant to inform a user of the data whether there were non-target taxa that were detected, but left unreported. This term is only relevant if a dwc:Event used restricted search or open search methods and if a target taxonomic scope is declared. Taxonomic scope is based on the combination of eco:targetTaxonomicScope and eco:excludedTaxonomicScope. Within dwc:Events that used either a restricted search or an open search method and declared a taxonomic scope, if all dwc:Organisms that are not included within the target taxonomic scope and that were detected during a dwc:Event were reported, the value of this term should be 'true', otherwise the value of this term should be ‘false'. |
| **example** | `true`; `false` |
| **type** | boolean |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** |  |
| **maximum** |  |
| **namespace** | eco |
| **dcterms:isVersionOf** | http://rs.tdwg.org/eco/terms/areNonTargetTaxaFullyReported |
| **dcterms:references** | http://rs.tdwg.org/eco/terms/version/areNonTargetTaxaFullyReported-2025-06-12 |
| **rdfs:comment** | Every dwc:Organism that was outside of the target taxonomic scope (the combination of eco:targetTaxonomicScope and eco:excludedTaxonomicScope) and detected during the dwc:Event, and that was detectable using the given protocol (given in eco:protocolDescriptions and dwc:samplingProtocol), was reported. |
| **status** | recommended |
