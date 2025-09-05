## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/georeferenceProtocol

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~georeferenceProtocol~ **georeferenceProtocol**
* Term label (English, not normative): ~Georeference Protocol~ **Georeference Protocol**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Event
* New definition of the term (normative): **A description or reference to a dwc:Protocol used to determine a spatial footprint, coordinates, and uncertainties.**
* Previous definition of the term: ~A description or reference to the methods used to determine the spatial footprint, coordinates, and uncertainties.~
* New usage comments (recommendations regarding content, etc., not normative): **** 
* Previous usage comments: ~This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.~
* New examples (not normative): **`Georeferencing Quick Reference Guide (Zermoglio et al. 2020, https://doi.org/10.35035/e09p-h128)`**
* Previous examples (not normative): ~`Georeferencing Quick Reference Guide (Zermoglio et al. 2020, https://doi.org/10.35035/e09p-h128)`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/georeferenceProtocol-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Gathering/SiteCoordinateSets/SiteCoordinates/CoordinateMethod
