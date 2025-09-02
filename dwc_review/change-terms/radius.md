**Old term**

**Definition:** The radius of a bounding circle or arc, expressed as a fraction of the width of the media item.
**Label:** Radius
**Term Name:** ac:radius
**Term version IRI:** http://rs.tdwg.org/ac/terms/version/radius-2021-10-05
**Version of:** http://rs.tdwg.org/ac/terms/radius
**Issued:** 2021-10-05
**Type:** Property
**Status:** recommended


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>media</li></ul> |
| **key** |  |
| **title** | Radius |
| **description** | The radius of a bounding circle or arc, expressed as a fraction of the width of a dwc:Media resource. |
| **comments** | A valid value MUST be greater than or equal to zero. A valid value MAY cause the designated circle to extend beyond the bounds of a dwc:Media resource. In that case, the arc within a dwc:Media resource plus the bounds of a dwc:Media resource specify the region of interest. This term MUST NOT be used with ac:widthFrac or ac:heightFrac to define a region of interest. This term may be used with ac:xFrac and ac:yFrac to define a point. In that case, the implication is that the point falls on some object of interest within a dwc:Media resource, but nothing more can be assumed about the bounds of that object. |
| **example** | `100` |
| **type** | integer |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** | 0.0 |
| **maximum** |  |
| **namespace** | ac |
| **dcterms:isVersionOf** | http://rs.tdwg.org/ac/terms/radius |
| **dcterms:references** | http://rs.tdwg.org/ac/terms/version/radius-2021-10-05 |
| **rdfs:comment** | The radius of a bounding circle or arc, expressed as a fraction of the width of the media item. |
| **status** | recommended |
