**Old term**

**Definition:** One or more dwc:Organisms outside the target organismal scopes (eco:targetDegreeOfEstablishmentScope, eco:targetGrowthFormScope, and eco:targetLifeStageScope) were detected and reported for this dwc:Event.
**Label:** Has Non-target Organisms
**Term Name:** eco:hasNonTargetOrganisms
**Term version IRI:** http://rs.tdwg.org/eco/terms/version/hasNonTargetOrganisms-2024-02-28
**Version of:** http://rs.tdwg.org/eco/terms/hasNonTargetOrganisms
**Issued:** 2024-02-28
**Type:** Property
**Status:** recommended


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>survey</li></ul> |
| **key** |  |
| **title** | Has Non Target Organisms |
| **description** | One or more dwc:Organisms outside the target organismal scopes (eco:targetDegreeOfEstablishmentScope, eco:targetGrowthFormScope, and eco:targetLifeStageScope) were detected and reported for this dwc:Event. |
| **comments** | This term is meant to alert users to the presence of non-target organisms (in some disciplines called “bycatch”) reported in this dwc:Event. This term is relevant only if a target organismal scope is declared. Organismal scope is based on the combination of all of the following terms: eco:targetLifeStageScope, eco:excludedLifeStageScope, eco:targetDegreeOfEstablishmentScope, eco:excludedDegreeOfEstablishmentScope, eco:targetGrowthFormScope, and eco:excludedGrowthFormScope. Examination of the organismal scope is needed in order to identify the non-target dwc:Organisms. It should be possible to confirm the expectations by investigating a dwc:Occurrences in this dwc:Event and in its child dwc:Events (if available). The value of this term should be 'true' if dwc:Occurrences of dwc:Organisms outside the organismal scope(s) as defined at the time of a dwc:Event are reported, otherwise the value of this term should be 'false'. |
| **example** | `true`; `false` |
| **type** | boolean |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** |  |
| **maximum** |  |
| **namespace** | eco |
| **dcterms:isVersionOf** | http://rs.tdwg.org/eco/terms/hasNonTargetOrganisms |
| **dcterms:references** | http://rs.tdwg.org/eco/terms/version/hasNonTargetOrganisms-2024-02-28 |
| **rdfs:comment** | One or more dwc:Organisms outside the target organismal scopes (eco:targetDegreeOfEstablishmentScope, eco:targetGrowthFormScope, and eco:targetLifeStageScope) were detected and reported for this dwc:Event. |
| **status** | recommended |
