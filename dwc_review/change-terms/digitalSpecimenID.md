## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/digitalSpecimenID

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~digitalSpecimenID~ **digitalSpecimenID**
* Term label (English, not normative): ~Digital Specimen Identifier~ **Digital Specimen ID**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): MaterialEntity
* New definition of the term (normative): **An identifier for a Digital Specimen resource.**
* Previous definition of the term: ~An identifier for a particular instance of a Digital Specimen.~
* New usage comments (recommendations regarding content, etc., not normative): **A Digital Specimen as defined in https://doi.org/10.3897/rio.7.e67379. A dwc:digitalSpecimenID is intended to uniquely and persistently identify a Digital Specimen. Recommended best practice is to use a DOI with machine readable metadata in the DOI record that uses a community agreed metadata profile (also known as FDO profile) for a Digital Specimen. For an example see: https://doi.org/10.3535/N75-CR4-0SM?noredirect. The identifier is for a digital information artifact (the Digital Specimen) as opposed to an identifier for a specific instance of a dwc:MaterialEntity.** 
* Previous usage comments: ~A Digital Specimen is defined in https://doi.org/10.3897/rio.7.e67379. A dwc:digitalSpecimenID is intended to uniquely and persistently identify a Digital Specimen. Recommended best practice is to use a DOI with machine readable metadata in the DOI record that uses a community agreed metadata profile (also known as FDO profile) for a Digital Specimen. For an example see: https://doi.org/10.3535/N75-CR4-0SM?noredirect. The identifier is for a digital information artifact (the Digital Specimen) as opposed to an identifier for a specific instance of a dwc:MaterialEntity.~
* New examples (not normative): **`https://doi.org/10.3535/M42-Z4P-DRD`; `https://doi.org/10.3535/M42-Z4P-DRD?urlappend=/1`; `https://doi.org/10.3535/M42-Z4P-DRD?locatt=/1`; `doi:10.3535/M42-Z4P-DRD**
* Previous examples (not normative): ~`https://doi.org/10.3535/M42-Z4P-DRD`; `https://doi.org/10.3535/M42-Z4P-DRD?urlappend=/1`; `https://doi.org/10.3535/M42-Z4P-DRD?locatt=/1`; `doi:10.3535/M42-Z4P-DRD`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/digitalSpecimenID-2025-06-12
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): Note: /DataSets/DataSet/Units/Unit/UnitGUID could be used. A new term /DataSets/DataSet/Units/Unit/SpecimenUnit/digitalSpecimenID would make it distinguishable from URIs that identify the physical object or catalogue record.
