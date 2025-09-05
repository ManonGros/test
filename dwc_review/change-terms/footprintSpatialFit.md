## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/footprintSpatialFit

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~footprintSpatialFit~ **footprintSpatialFit**
* Term label (English, not normative): ~Footprint Spatial Fit~ **Footprint Spatial Fit**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Event
* New definition of the term (normative): **A ratio of the area of a footprint (dwc:footprintWKT) to the area of a true (original, or most specific) spatial representation of a dcterms:Location.**
* Previous definition of the term: ~The ratio of the area of the dwc:footprintWKT to the area of the true (original, or most specific) spatial representation of the dcterms:Location. Legal values are 0, greater than or equal to 1, or undefined. A value of 1 is an exact match or 100% overlap. A value of 0 should be used if the given dwc:footprintWKT does not completely contain the original representation. The dwc:footprintSpatialFit is undefined (and should be left empty) if the original representation is any geometry without area (e.g., a point or polyline) and without uncertainty and the given georeference is not that same geometry (without uncertainty). If both the original and the given georeference are the same point, the dwc:footprintSpatialFit is 1.~
* New usage comments (recommendations regarding content, etc., not normative): **Legal values are 0, greater than or equal to 1, or undefined. A value of 1 is an exact match or 100% overlap. A value of 0 should be used if the given footprint does not completely contain the original representation. A dwc:footprintSpatialFit is undefined (and should be left empty) if the original representation is any geometry without area (e.g., a point or polyline) and without uncertainty and the given georeference is not that same geometry (without uncertainty). If both the original and the given georeference are the same point, a dwc:footprintSpatialFit is 1.** 
* Previous usage comments: ~Detailed explanations with graphical examples can be found in the Georeferencing Best Practices, Chapman and Wieczorek, 2020 (https://doi.org/10.15468/doc-gg7h-s853).~
* New examples (not normative): **`0`; `1`; `1.5708`**
* Previous examples (not normative): ~`0`; `1`; `1.5708`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/footprintSpatialFit-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Gathering/FootprintSpatialFit
