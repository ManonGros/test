**Old term**

**Definition:** The width of the bounding rectangle, expressed as a decimal fraction of the width of the media item.
**Label:** Fractional Width
**Term Name:** ac:widthFrac
**Term version IRI:** http://rs.tdwg.org/ac/terms/version/widthFrac-2021-10-05
**Version of:** http://rs.tdwg.org/ac/terms/widthFrac
**Issued:** 2021-10-05
**Type:** Property
**Status:** recommended


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>media</li></ul> |
| **key** |  |
| **title** | Fractional Width |
| **description** | The width of the bounding rectangle, expressed as a decimal fraction of the width of a dwc:Media resource. |
| **comments** | The sum of a valid value plus ac:xFrac MUST be greater than zero and less than or equal to one. The precision of this value SHOULD be great enough that when ac:widthFrac and ac:xFrac are used with the exif:PixelXDimension of the Best Quality variant of the Service Access point to calculate the lower right corner of the rectangle, rounding to the nearest integer results in the same horizontal pixel originally used to define the point. This term MUST NOT be used with ac:radius to define a region of interest. Zero-sized bounding rectangles are not allowed. To designate a point, use the radius option with a zero value. |
| **example** | `0.5`; `1` |
| **type** | numeric |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** | 0.0 |
| **maximum** | 1.0 |
| **namespace** | ac |
| **dcterms:isVersionOf** | http://rs.tdwg.org/ac/terms/widthFrac |
| **dcterms:references** | http://rs.tdwg.org/ac/terms/version/widthFrac-2021-10-05 |
| **rdfs:comment** | The width of the bounding rectangle, expressed as a decimal fraction of the width of the media item. |
| **status** | recommended |
