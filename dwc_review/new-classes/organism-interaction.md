## New term

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Proposed attributes of the new term:

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): organism-interaction
* Term label (English, not normative): Organism Interaction
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): OrganismInteraction
* Definition of the term (normative): An interaction between two dwc:Organisms during a dwc:Event.
* Usage comments (recommendations regarding content, etc., not normative): Supports only primary observed interactions, not habitual or derived taxon-level interactions. Pairwise interactions must be used to represent multi-organism interactions. When possible, typify the action rather than the state from which an action is inferred, with the actor as the subject dwc:Occurrence and the acted-upon as the related dwc:Occurrence. Only one direction of a two-way interaction is necessary, though both are permissible as distinct OrganismInteractions with distint subject dwc:Occurrences.
* Examples (not normative): `a bee visiting a flower`; `a Mallophora ruficauda hunting an Apis mellifera in flight`; `a viral infection in a plant`; `a female spider mating with a male spider`; `a lion cub nursing from its mother`; `a mosquito sucking blood from a chimpanzee's arm`; `a slug eating a fungus growing on decomposing stump (2 interactions)`
* Refines (identifier of the broader term this term refines; normative): 
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): 
