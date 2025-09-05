## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/footprintWKT

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~footprintWKT~ **footprintWKT**
* Term label (English, not normative): ~Footprint WKT~ **Footprint WKT**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Event
* New definition of the term (normative): **A Well-Known Text (WKT) representation of the shape (footprint, geometry) that defines a dcterms:Location.**
* Previous definition of the term: ~A Well-Known Text (WKT) representation of the shape (footprint, geometry) that defines the dcterms:Location. A dcterms:Location may have both a point-radius representation (see dwc:decimalLatitude) and a footprint representation, and they may differ from each other.~
* New usage comments (recommendations regarding content, etc., not normative): **A dcterms:Location may have both a point-radius representation (see dwc:decimalLatitude) and a footprint representation, and they may differ from each other.** 
* Previous usage comments: ~This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.~
* New examples (not normative): **`POLYGON ((10 20, 11 20, 11 21, 10 21, 10 20))` (the one-degree bounding box with opposite corners at longitude=10, latitude=20 and longitude=11, latitude=21)**
* Previous examples (not normative): ~`POLYGON ((10 20, 11 20, 11 21, 10 21, 10 20))` (the one-degree bounding box with opposite corners at longitude=10, latitude=20 and longitude=11, latitude=21)~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/footprintWKT-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Gathering/FootprintWKT (ABCD v2.06b)
