

| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>media</li></ul> |
| **key** |  |
| **title** | Metadata Date |
| **description** | The date and time that any metadata for this resource was last changed. It should be the same as or more recent than dcterms:modified. |
| **comments** | Point in time recording when the last modification to metadata (not necessarily the media object itself) occurred. The date and time MUST comply with the World Wide Web Consortium (W3C) datetime practice, https://www.w3.org/TR/NOTE-datetime, which requires that date and time representation correspond to ISO 8601:1998, but with year fields always comprising 4 digits. This makes datetime records compliant with 8601:2004, https://www.iso.org/standard/40874.html. AC datetime values MAY also follow 8601:2004 for ranges by separating two IS0 8601 datetime fields by a solidus ("forward slash", '/'). This is not dcterms:modified, which refers to the resource itself rather than its metadata. See also the wikipedia IS0 8601 entry, https://en.wikipedia.org/wiki/ISO_8601, for further explanation and examples. |
| **example** |  |
| **type** | string |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** |  |
| **maximum** |  |
| **namespace** | xmp |
| **dcterms:isVersionOf** | http://ns.adobe.com/xap/1.0/MetadataDate |
| **dcterms:references** |  |
| **rdfs:comment** | The date and time that any metadata for this resource was last changed. It should be the same as or more recent than xmp:ModifyDate. |
| **status** | recommended |
