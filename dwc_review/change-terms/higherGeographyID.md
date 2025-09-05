## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/higherGeographyID

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~higherGeographyID~ **higherGeographyID**
* Term label (English, not normative): ~Higher Geography ID~ **Higher Geography ID**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Event
* New definition of the term (normative): **An identifier for a geographic region within which a dcterms:Location occurs.**
* Previous definition of the term: ~An identifier for the geographic region within which the dcterms:Location occurred.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use a globally unique identifier.** 
* Previous usage comments: ~Recommended best practice is to use a persistent identifier from a controlled vocabulary such as the Getty Thesaurus of Geographic Names.~
* New examples (not normative): **`http://vocab.getty.edu/tgn/1002002` (Antártida e Islas del Atlántico Sur, Territorio Nacional de la Tierra del Fuego, Argentina)**
* Previous examples (not normative): ~`http://vocab.getty.edu/tgn/1002002` (Antártida e Islas del Atlántico Sur, Territorio Nacional de la Tierra del Fuego, Argentina).~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/higherGeographyID-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
