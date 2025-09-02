**Old term**

**Definition:** The horizontal position of a reference point, measured from the left side of the media item and expressed as a decimal fraction of the width of the media item.
**Label:** Fractional X
**Term Name:** ac:xFrac
**Term version IRI:** http://rs.tdwg.org/ac/terms/version/xFrac-2021-10-05
**Version of:** http://rs.tdwg.org/ac/terms/xFrac
**Issued:** 2021-10-05
**Type:** Property
**Status:** recommended


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>media</li></ul> |
| **key** |  |
| **title** | Fractional X |
| **description** | The horizontal position of a reference point, measured from the left side of a dwc:Media resource and expressed as a decimal fraction of the width of a dwc:Media resource. |
| **comments** | A valid value MUST be greater than or equal to zero and less than or equal to one. The precision of this value SHOULD be great enough that when the ac:xFrac value is multiplied by the exif:PixelXDimension of the Best Quality variant of the Service Access point, rounding to the nearest integer results in the same horizontal pixel location originally used to define the point. This point can serve as the horizontal position of the upper left corner of a bounding rectangle, or as the center of a circle. |
| **example** | `0.5`; `1` |
| **type** | numeric |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** | 0.0 |
| **maximum** | 1.0 |
| **namespace** | ac |
| **dcterms:isVersionOf** | http://rs.tdwg.org/ac/terms/xFrac |
| **dcterms:references** | http://rs.tdwg.org/ac/terms/version/xFrac-2021-10-05 |
| **rdfs:comment** | The horizontal position of a reference point, measured from the left side of the media item and expressed as a decimal fraction of the width of the media item. |
| **status** | recommended |
