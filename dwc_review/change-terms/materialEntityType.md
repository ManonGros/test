## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/materialEntityType

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~materialEntityType~ **materialEntityType**
* Term label (English, not normative): ~Material Entity Type~ **Material Entity Type**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): MaterialEntity
* New definition of the term (normative): **A narrow category that best matches the nature of a dwc:MaterialEntity.**
* Previous definition of the term: ~A category that best matches the nature of a dwc:MaterialEntity.~
* New usage comments (recommendations regarding content, etc., not normative): **A more generic classification of a dwc:MaterialEntity than dwc:preparations. Recommended best practice is to use a controlled vocabulary. This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.** 
* Previous usage comments: ~A more generic classification of a dwc:MaterialEntity than dwc:preparations. Recommended best practice is to use a controlled vocabulary. This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.~
* New examples (not normative): **`Macro-object`; `Micro-object`; `Oversized object`; `Cut/polished gemstone`; `Compound Specimen`; `Core`; `Mixed Materials`; `Environmental sample`; `Microscope slide`; `Spore print`; `Macrofossil`; `Mesofossil`; `Microfossil`; `Pinned object/specimen`; `Taxidermy mount`; `Blood sampling cards`; `Oversized fossil`; `Anthropogenic Artifact`**
* Previous examples (not normative): ~`Macro-object`; `Micro-object`; `Oversized object`; `Cut/polished gemstone`; `Compound Specimen`; `Core`; `Mixed Materials`; `Environmental sample`; `Microscope slide`; `Spore print`; `Macrofossil`; `Mesofossil`; `Microfossil`; `Pinned object/specimen`; `Taxidermy mount`; `Blood sampling cards`; `Oversized fossil`; `Anthropogenic Artifact`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/materialEntityType-2025-06-12
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): skos:closeMatch to /DataSets/DataSet/Units/Unit/KindOfUnit. ABCD structural considerations prevent an exactMatch.
