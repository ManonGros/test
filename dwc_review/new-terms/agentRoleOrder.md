| definitions | context 1 |context 2 |context 3 |
|-|-|-|-|
| **Context - tables concerned** | <ul><li>media-agent-role</li><li>organism-interaction-agent-role</li></ul> | <ul><li>chronometric-age-agent-role</li><li>event-agent-role</li><li>identification-agent-role</li><li>material-agent-role</li><li>molecular-protocol-agent-role</li><li>occurrence-agent-role</li><li>survey-agent-role</li></ul> | <ul><li>agent-agent-role</li></ul> |
| **key** |  |  |  |
| **title** | Agent Role Order | Agent Role Order | Agent Role Order |
| **description** | A numerical position of a dcterms:AgentRole in a set of dcterms:AgentRoles that have the same combination of dwc:agentRole, dwc:agentRoleIRI, dwc:agentRoleSource and related target. | A numerical position of a dcterms:AgentRole in a set of dcterms:AgentRoles that have the same combination of dwc:agentRole, dwc:agentRoleIRI, dwc:agentRoleSource and related target. | A numerical position of an AgentRole in a set of AgentRoles that have the same combination of dwc:agentRole, dwc:agentRoleIRI, dwc:agentRoleSource and related target. |
| **comments** | One could use dwc:agentRoleOrder to create an ordered list of collectors (dwc:agentRole = 'collector') for a dwc:MaterialEntity, for example. The first would have dwc:agentRoleOrder=1, the second would have dwc:agentRoleOrder=2. | One could use dwc:agentRoleOrder to create an ordered list of collectors (dwc:agentRole = 'collector') for a dwc:MaterialEntity, for example. The first would have dwc:agentRoleOrder=1, the second would have dwc:agentRoleOrder=2. | One could use dwc:agentRoleOrder to create an ordered list of collectors (dwc:agentRole = 'collector') for a dwc:MaterialEntity, for example. The first would have agentRoleOrder=1, the second would have agentRoleOrder=2. |
| **example** |  |  |  |
| **type** | integer | integer | integer |
| **format** | default | default | default |
| **unique** |  |  |  |
| **required** | False |  |  |
| **minimum** | 1.0 | 1.0 | 1.0 |
| **maximum** |  |  |  |
| **namespace** | dwcdp | dwcdp | dwcdp |
| **dcterms:isVersionOf** |  |  |  |
| **dcterms:references** |  |  |  |
| **rdfs:comment** |  |  |  |
| **status** | recommended | recommended | recommended |
