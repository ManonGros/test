**Old term**

**Definition:** The ratio of the area of the dwc:footprintWKT to the area of the true (original, or most specific) spatial representation of the dcterms:Location. Legal values are 0, greater than or equal to 1, or undefined. A value of 1 is an exact match or 100% overlap. A value of 0 should be used if the given dwc:footprintWKT does not completely contain the original representation. The dwc:footprintSpatialFit is undefined (and should be left empty) if the original representation is any geometry without area (e.g., a point or polyline) and without uncertainty and the given georeference is not that same geometry (without uncertainty). If both the original and the given georeference are the same point, the dwc:footprintSpatialFit is 1.
**Label:** Footprint Spatial Fit
**Term Name:** dwc:footprintSpatialFit
**Term version IRI:** http://rs.tdwg.org/dwc/terms/version/footprintSpatialFit-2023-06-28
**Version of:** http://rs.tdwg.org/dwc/terms/footprintSpatialFit
**Issued:** 2023-06-28
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/dwc/terms/version/footprintSpatialFit-2020-08-20


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>event</li></ul> |
| **key** |  |
| **title** | Footprint Spatial Fit |
| **description** | A ratio of the area of a footprint (dwc:footprintWKT) to the area of a true (original, or most specific) spatial representation of a dcterms:Location. |
| **comments** | Legal values are 0, greater than or equal to 1, or undefined. A value of 1 is an exact match or 100% overlap. A value of 0 should be used if the given footprint does not completely contain the original representation. A dwc:footprintSpatialFit is undefined (and should be left empty) if the original representation is any geometry without area (e.g., a point or polyline) and without uncertainty and the given georeference is not that same geometry (without uncertainty). If both the original and the given georeference are the same point, a dwc:footprintSpatialFit is 1. |
| **example** | `0`; `1`; `1.5708` |
| **type** | number |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** |  |
| **maximum** |  |
| **namespace** | dwc |
| **dcterms:isVersionOf** | http://rs.tdwg.org/dwc/terms/footprintSpatialFit |
| **dcterms:references** | http://rs.tdwg.org/dwc/terms/version/footprintSpatialFit-2023-06-28 |
| **rdfs:comment** | The ratio of the area of the dwc:footprintWKT to the area of the true (original, or most specific) spatial representation of the dcterms:Location. Legal values are 0, greater than or equal to 1, or undefined. A value of 1 is an exact match or 100% overlap. A value of 0 should be used if the given dwc:footprintWKT does not completely contain the original representation. The dwc:footprintSpatialFit is undefined (and should be left empty) if the original representation is any geometry without area (e.g., a point or polyline) and without uncertainty and the given georeference is not that same geometry (without uncertainty). If both the original and the given georeference are the same point, the dwc:footprintSpatialFit is 1. |
| **status** | recommended |
