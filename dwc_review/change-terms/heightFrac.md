**Old term**

**Definition:** The height of the bounding rectangle, expressed as a decimal fraction of the height of the media item.
**Label:** Fractional Height
**Term Name:** ac:heightFrac
**Term version IRI:** http://rs.tdwg.org/ac/terms/version/heightFrac-2021-10-05
**Version of:** http://rs.tdwg.org/ac/terms/heightFrac
**Issued:** 2021-10-05
**Type:** Property
**Status:** recommended


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>media</li></ul> |
| **key** |  |
| **title** | Fractional Height |
| **description** | The height of the bounding rectangle, expressed as a decimal fraction of the height of a dwc:Media resource. |
| **comments** | The sum of a valid value plus ac:yFrac MUST be greater than zero and less than or equal to one. The precision of this value SHOULD be great enough that when ac:heightFrac and ac:yFrac are used with the exif:PixelYDimension of the Best Quality variant of the Service Access point to calculate the lower right corner of the rectangle, rounding to the nearest integer results in the same vertical pixel originally used to define the point. This term MUST NOT be used with ac:radius to define a region of interest. Zero-sized bounding rectangles are not allowed. To designate a point, use the radius option with a zero value. |
| **example** | `0.5`; `1` |
| **type** | numeric |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** | 0.0 |
| **maximum** | 1.0 |
| **namespace** | ac |
| **dcterms:isVersionOf** | http://rs.tdwg.org/ac/terms/heightFrac |
| **dcterms:references** | http://rs.tdwg.org/ac/terms/version/heightFrac-2021-10-05 |
| **rdfs:comment** | The height of the bounding rectangle, expressed as a decimal fraction of the height of the media item. |
| **status** | recommended |
