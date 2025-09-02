**Old term**

**Definition:** The lesser distance in a range of distance from a reference surface in the vertical direction, in meters. Use positive values for locations above the surface, negative values for locations below. If depth measures are given, the reference surface is the location given by the depth, otherwise the reference surface is the location given by the elevation.
**Label:** Minimum Distance Above Surface In Meters
**Term Name:** dwc:minimumDistanceAboveSurfaceInMeters
**Term version IRI:** http://rs.tdwg.org/dwc/terms/version/minimumDistanceAboveSurfaceInMeters-2023-06-28
**Version of:** http://rs.tdwg.org/dwc/terms/minimumDistanceAboveSurfaceInMeters
**Issued:** 2023-06-28
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/dwc/terms/version/minimumDistanceAboveSurfaceInMeters-2017-10-06


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>event</li></ul> |
| **key** |  |
| **title** | Minimum Distance Above Surface In Meters |
| **description** | A lesser distance in a range of distance from a reference surface in the vertical direction, in meters. Use positive values for locations above the surface, negative values for locations below. If depth measures are given, the reference surface is the location given by the depth, otherwise the reference surface is the location given by the elevation. |
| **comments** |  |
| **example** | `-1.5` (below the surface); `4.2` (above the surface); For a 1.5 meter sediment core from the bottom of a lake (at depth 20m) at 300m elevation: verbatimElevation: `300m` minimumElevationInMeters: `300`, maximumElevationInMeters: `300`, verbatimDepth: `20m`, minimumDepthInMeters: `20`, maximumDepthInMeters: `20`, minimumDistanceAboveSurfaceInMeters: `0`, maximumDistanceAboveSurfaceInMeters: `-1.5`. |
| **type** | number |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** |  |
| **maximum** |  |
| **namespace** | dwc |
| **dcterms:isVersionOf** | http://rs.tdwg.org/dwc/terms/minimumDistanceAboveSurfaceInMeters |
| **dcterms:references** | http://rs.tdwg.org/dwc/terms/version/minimumDistanceAboveSurfaceInMeters-2023-06-28 |
| **rdfs:comment** | The lesser distance in a range of distance from a reference surface in the vertical direction, in meters. Use positive values for locations above the surface, negative values for locations below. If depth measures are given, the reference surface is the location given by the depth, otherwise the reference surface is the location given by the elevation. |
| **status** | recommended |
