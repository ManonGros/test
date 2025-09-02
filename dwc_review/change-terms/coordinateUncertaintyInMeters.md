**Old term**

**Definition:** The horizontal distance (in meters) from the given dwc:decimalLatitude and dwc:decimalLongitude describing the smallest circle containing the whole of the dcterms:Location. Leave the value empty if the uncertainty is unknown, cannot be estimated, or is not applicable (because there are no coordinates). Zero is not a valid value for this term.
**Label:** Coordinate Uncertainty In Meters
**Term Name:** dwc:coordinateUncertaintyInMeters
**Term version IRI:** http://rs.tdwg.org/dwc/terms/version/coordinateUncertaintyInMeters-2023-06-28
**Version of:** http://rs.tdwg.org/dwc/terms/coordinateUncertaintyInMeters
**Issued:** 2023-06-28
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/dwc/terms/version/coordinateUncertaintyInMeters-2021-07-15


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>event</li></ul> |
| **key** |  |
| **title** | Coordinate Uncertainty In Meters |
| **description** | A horizontal distance (in meters) from a given dwc:decimalLatitude and dwc:decimalLongitude describing the smallest circle containing the whole of the dcterms:Location. |
| **comments** | Leave the value empty if the uncertainty is unknown, cannot be estimated, or is not applicable (because there are no coordinates). Zero is not a valid value for this term. |
| **example** | `30` (reasonable lower limit on or after 2000-05-01 of a GPS reading under good conditions if the actual precision was not recorded at the time); `100` (reasonable lower limit before 2000-05-01 of a GPS reading under good conditions if the actual precision was not recorded at the time); `71` (uncertainty for a UTM coordinate having 100 meter precision and a known spatial reference system) |
| **type** | number |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** | 1.0 |
| **maximum** | 20037509.0 |
| **namespace** | dwc |
| **dcterms:isVersionOf** | http://rs.tdwg.org/dwc/terms/coordinateUncertaintyInMeters |
| **dcterms:references** | http://rs.tdwg.org/dwc/terms/version/coordinateUncertaintyInMeters-2023-06-28 |
| **rdfs:comment** | The horizontal distance (in meters) from the given dwc:decimalLatitude and dwc:decimalLongitude describing the smallest circle containing the whole of the dcterms:Location. Leave the value empty if the uncertainty is unknown, cannot be estimated, or is not applicable (because there are no coordinates). Zero is not a valid value for this term. |
| **status** | recommended |
