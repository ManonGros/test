**Old term**

**Definition:** The ratio of the area of the point-radius (dwc:decimalLatitude, dwc:decimalLongitude, dwc:coordinateUncertaintyInMeters) to the area of the true (original, or most specific) spatial representation of the dcterms:Location. Legal values are 0, greater than or equal to 1, or undefined. A value of 1 is an exact match or 100% overlap. A value of 0 should be used if the given point-radius does not completely contain the original representation. The dwc:pointRadiusSpatialFit is undefined (and should be left empty) if the original representation is any geometry without area (e.g., a point or polyline) and without uncertainty and the given georeference is not that same geometry (without uncertainty). If both the original and the given georeference are the same point, the dwc:pointRadiusSpatialFit is 1.
**Label:** Point Radius Spatial Fit
**Term Name:** dwc:pointRadiusSpatialFit
**Term version IRI:** http://rs.tdwg.org/dwc/terms/version/pointRadiusSpatialFit-2023-06-28
**Version of:** http://rs.tdwg.org/dwc/terms/pointRadiusSpatialFit
**Issued:** 2023-06-28
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/dwc/terms/version/pointRadiusSpatialFit-2020-08-20


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>event</li></ul> |
| **key** |  |
| **title** | Point Radius Spatial Fit |
| **description** | A ratio of the area of a point-radius (dwc:decimalLatitude, dwc:decimalLongitude, dwc:coordinateUncertaintyInMeters) to the area of a true (original, or most specific) spatial representation of a dcterms:Location. |
| **comments** | Legal values are 0, greater than or equal to 1, or undefined. A value of 1 is an exact match or 100% overlap. A value of 0 should be used if the given point-radius does not completely contain the original representation. The pointRadiusSpatialFit is undefined (and should be left empty) if the original representation is any geometry without area (e.g., a point or polyline) and without uncertainty and the given georeference is not that same geometry (without uncertainty). If both the original and the given georeference are the same point, the pointRadiusSpatialFit is 1. Detailed explanations with graphical examples can be found in the Georeferencing Best Practices, Chapman and Wieczorek, 2020 (https://doi.org/10.15468/doc-gg7h-s853). |
| **example** | `0`; `1`; `1.5708` |
| **type** | number |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** | 0.0 |
| **maximum** |  |
| **namespace** | dwc |
| **dcterms:isVersionOf** | http://rs.tdwg.org/dwc/terms/pointRadiusSpatialFit |
| **dcterms:references** | http://rs.tdwg.org/dwc/terms/version/pointRadiusSpatialFit-2023-06-28 |
| **rdfs:comment** | The ratio of the area of the point-radius (dwc:decimalLatitude, dwc:decimalLongitude, dwc:coordinateUncertaintyInMeters) to the area of the true (original, or most specific) spatial representation of the dcterms:Location. Legal values are 0, greater than or equal to 1, or undefined. A value of 1 is an exact match or 100% overlap. A value of 0 should be used if the given point-radius does not completely contain the original representation. The dwc:pointRadiusSpatialFit is undefined (and should be left empty) if the original representation is any geometry without area (e.g., a point or polyline) and without uncertainty and the given georeference is not that same geometry (without uncertainty). If both the original and the given georeference are the same point, the dwc:pointRadiusSpatialFit is 1. |
| **status** | recommended |
