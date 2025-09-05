## New term

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Proposed attributes of the new term:

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): agentRoleOrder
* Term label (English, not normative): Agent Role Order
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): AgentAgentRole
* Definition of the term (normative): A numerical position of an AgentRole in a set of AgentRoles that have the same combination of dwc:agentRole, dwc:agentRoleIRI, dwc:agentRoleSource and related target.
* Usage comments (recommendations regarding content, etc., not normative): One could use dwc:agentRoleOrder to create an ordered list of collectors (dwc:agentRole = 'collector') for a dwc:MaterialEntity, for example. The first would have agentRoleOrder=1, the second would have agentRoleOrder=2.
* Examples (not normative): 
* Refines (identifier of the broader term this term refines; normative): 
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): 
