## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/coordinateUncertaintyInMeters

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~coordinateUncertaintyInMeters~ **coordinateUncertaintyInMeters**
* Term label (English, not normative): ~Coordinate Uncertainty In Meters~ **Coordinate Uncertainty In Meters**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Event
* New definition of the term (normative): **A horizontal distance (in meters) from a given dwc:decimalLatitude and dwc:decimalLongitude describing the smallest circle containing the whole of the dcterms:Location.**
* Previous definition of the term: ~The horizontal distance (in meters) from the given dwc:decimalLatitude and dwc:decimalLongitude describing the smallest circle containing the whole of the dcterms:Location. Leave the value empty if the uncertainty is unknown, cannot be estimated, or is not applicable (because there are no coordinates). Zero is not a valid value for this term.~
* New usage comments (recommendations regarding content, etc., not normative): **Leave the value empty if the uncertainty is unknown, cannot be estimated, or is not applicable (because there are no coordinates). Zero is not a valid value for this term.** 
* Previous usage comments: ~~
* New examples (not normative): **`30` (reasonable lower limit on or after 2000-05-01 of a GPS reading under good conditions if the actual precision was not recorded at the time); `100` (reasonable lower limit before 2000-05-01 of a GPS reading under good conditions if the actual precision was not recorded at the time); `71` (uncertainty for a UTM coordinate having 100 meter precision and a known spatial reference system)**
* Previous examples (not normative): ~`30` (reasonable lower limit on or after 2000-05-01 of a GPS reading under good conditions if the actual precision was not recorded at the time); `100` (reasonable lower limit before 2000-05-01 of a GPS reading under good conditions if the actual precision was not recorded at the time); `71` (uncertainty for a UTM coordinate having 100 meter precision and a known spatial reference system)~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/coordinateUncertaintyInMeters-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Gathering/SiteCoordinateSets/SiteCoordinates/CoordinatesLatLon/CoordinateErrorDistanceInMeters
