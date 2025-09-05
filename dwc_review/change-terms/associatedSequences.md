## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/associatedSequences

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~associatedSequences~ **associatedSequences**
* Term label (English, not normative): ~Associated Sequences~ **Associated Sequences**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): MaterialEntity
* New definition of the term (normative): **A list (concatenated and separated) of dcterms:BibiographicResources for dwc:NucleotideSequences associated with a dwc:MaterialEntity.**
* Previous definition of the term: ~A list (concatenated and separated) of identifiers (publication, global unique identifier, URI) of genetic sequence information associated with the dwc:MaterialEntity.~
* New usage comments (recommendations regarding content, etc., not normative): **** 
* Previous usage comments: ~~
* New examples (not normative): **`http://www.ncbi.nlm.nih.gov/nuccore/U34853.1`; `http://www.ncbi.nlm.nih.gov/nuccore/GU328060 | http://www.ncbi.nlm.nih.gov/nuccore/AF326093`**
* Previous examples (not normative): ~`http://www.ncbi.nlm.nih.gov/nuccore/U34853.1`; `http://www.ncbi.nlm.nih.gov/nuccore/GU328060 | http://www.ncbi.nlm.nih.gov/nuccore/AF326093`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/associatedSequences-2023-09-13
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Sequences/Sequence/ID-in-Database + constant
