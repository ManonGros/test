## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/identificationReferences

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~identificationReferences~ **identificationReferences**
* Term label (English, not normative): ~Identification References~ **Identification References**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Identification
* New definition of the term (normative): **A list (concatenated and separated) of dcterms:BibliographicResources used in the dwc:Identification.**
* Previous definition of the term: ~A list (concatenated and separated) of references (publication, global unique identifier, URI) used in the dwc:Identification.~
* New usage comments (recommendations regarding content, etc., not normative): **When used in the context of a dwc:Survey, the subject consists of all of the dwc:Identifications related to the dwc:Survey. Recommended best practice is to separate the values in a list with space vertical bar space (` | `).** 
* Previous usage comments: ~When used in the context of an Event (such as in the Humboldt Extension), the subject consists of all of the dwc:Organisms related to the Event. Recommended best practice is to separate the values in a list with space vertical bar space ( | ).~
* New examples (not normative): **`Aves del Noroeste Patagonico. Christie et al. 2004.`; `Stebbins, R. Field Guide to Western Reptiles and Amphibians. 3rd Edition. 2003. | Irschick, D.J. and Shaffer, H.B. (1997). The polytypic species revisited: Morphological differentiation among tiger salamanders (Ambystoma tigrinum) (Amphibia: Caudata). Herpetologica, 53(1), 30-49.`**
* Previous examples (not normative): ~`Aves del Noroeste Patagonico. Christie et al. 2004.`; `Stebbins, R. Field Guide to Western Reptiles and Amphibians. 3rd Edition. 2003. | Irschick, D.J. and Shaffer, H.B. (1997). The polytypic species revisited: Morphological differentiation among tiger salamanders (Ambystoma tigrinum) (Amphibia: Caudata). Herpetologica, 53(1), 30-49.`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/identificationReferences-2025-06-12
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Identifications/Identification/References
