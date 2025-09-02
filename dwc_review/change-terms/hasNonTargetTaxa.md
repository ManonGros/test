**Old term**

**Definition:** One or more dwc:Organisms of taxa outside the target taxonomic scope (the combination of eco:targetTaxonomicScope and eco:excludedTaxonomicScope) were detected and reported for this dwc:Event.
**Label:** Has Non-target Taxa
**Term Name:** eco:hasNonTargetTaxa
**Term version IRI:** http://rs.tdwg.org/eco/terms/version/hasNonTargetTaxa-2024-02-28
**Version of:** http://rs.tdwg.org/eco/terms/hasNonTargetTaxa
**Issued:** 2024-02-28
**Type:** Property
**Status:** recommended


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>survey</li></ul> |
| **key** |  |
| **title** | Has Non Target Taxa |
| **description** | One or more dwc:Organisms of taxa outside the target taxonomic scope (the combination of eco:targetTaxonomicScope and eco:excludedTaxonomicScope) were detected and reported for this dwc:Event. |
| **comments** | This term is meant to alert users to the presence of non-target taxa (in some disciplines called “bycatch”) reported in this dwc:Event. This term is relevant only if a target taxonomic scope is declared. Taxonomic scope is based on the combination of eco:targetTaxonomicScope and eco:excludedTaxonomicScope. Examination of the taxonomic scope is needed in order to identify the non-target taxa. It should be possible to confirm the expectations by investigating a dwc:Occurrences in this dwc:Event and in its child dwc:Events (if available) or by exploring eco:nonTargetTaxa for this dwc:Event (if populated). The value of this term should be 'true' if dwc:Occurrences of taxa outside the taxonomic scope as defined at the time of a dwc:Event are reported, otherwise the value of this term should be 'false'. |
| **example** | `true`; `false` |
| **type** | boolean |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** |  |
| **maximum** |  |
| **namespace** | eco |
| **dcterms:isVersionOf** | http://rs.tdwg.org/eco/terms/hasNonTargetTaxa |
| **dcterms:references** | http://rs.tdwg.org/eco/terms/version/hasNonTargetTaxa-2024-02-28 |
| **rdfs:comment** | One or more dwc:Organisms of taxa outside the target taxonomic scope (the combination of eco:targetTaxonomicScope and eco:excludedTaxonomicScope) were detected and reported for this dwc:Event. |
| **status** | recommended |
