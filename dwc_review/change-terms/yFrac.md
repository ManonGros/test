**Old term**

**Definition:** The vertical position of a reference point, measured from the top of the media item and expressed as a decimal fraction of the height of the media item.
**Label:** Fractional Y
**Term Name:** ac:yFrac
**Term version IRI:** http://rs.tdwg.org/ac/terms/version/yFrac-2021-10-05
**Version of:** http://rs.tdwg.org/ac/terms/yFrac
**Issued:** 2021-10-05
**Type:** Property
**Status:** recommended


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>media</li></ul> |
| **key** |  |
| **title** | Fractional Y |
| **description** | The vertical position of a reference point, measured from the top of a dwc:Media resource and expressed as a decimal fraction of the height of a dwc:Media resource. |
| **comments** | A valid value MUST be greater than or equal to zero and less than or equal to one. The precision of this value SHOULD be great enough that when the ac:yFrac value is multiplied by the exif:PixelYDimension of the Best Quality variant of the Service Access point, rounding to the nearest integer results in the same vertical pixel originally used to define the point. This point can serve as the vertical position of the upper left corner of a bounding rectangle, or as the center of a circle. |
| **example** | `0.5`; `1` |
| **type** | numeric |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** | 0.0 |
| **maximum** | 1.0 |
| **namespace** | ac |
| **dcterms:isVersionOf** | http://rs.tdwg.org/ac/terms/yFrac |
| **dcterms:references** | http://rs.tdwg.org/ac/terms/version/yFrac-2021-10-05 |
| **rdfs:comment** | The vertical position of a reference point, measured from the top of the media item and expressed as a decimal fraction of the height of the media item. |
| **status** | recommended |
