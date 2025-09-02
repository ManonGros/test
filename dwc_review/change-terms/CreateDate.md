

| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>media</li></ul> |
| **key** |  |
| **title** | Original Date and Time |
| **description** | The date and time a resource was created. For a digital file, this need not match a file-system creation time. For a freshly created resource, it should be close to that time, modulo the time taken to write the file. Later file transfer, copying, and so on, can make the file-system time arbitrarily different. |
| **comments** | The date of the creation of the original resource from which the digital media was derived or created. The date and time MUST comply with the World Wide Web Consortium (W3C) datetime practice, https://www.w3.org/TR/NOTE-datetime, which requires that date and time representation correspond to ISO 8601:1998, but with year fields always comprising 4 digits. This makes datetime records compliant with 8601:2004, https://www.iso.org/standard/40874.html. AC datetime values MAY also follow 8601:2004 for ranges by separating two IS0 8601 datetime fields by a solidus ("forward slash", '/'). When applied to a media resource with temporal extent such as audio or video, this property indicates the startTime of the recording. What constitutes "original" is determined by the metadata author. Example: Digitization of a photographic slide of a map would normally give the date at which the map was created; however a photographic work of art including the same map as its content may give the date of the original photographic exposure. Imprecise or unknown dates can be represented as ISO dates or ranges. Compare also Date and Time Digitized in the Resource Creation Vocabulary. See also the wikipedia IS0 8601 entry, https://en.wikipedia.org/wiki/ISO_8601, for further explanation and examples. |
| **example** |  |
| **type** | string |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** |  |
| **maximum** |  |
| **namespace** | xmp |
| **dcterms:isVersionOf** | http://ns.adobe.com/xap/1.0/CreateDate |
| **dcterms:references** |  |
| **rdfs:comment** | The date and time the resource was created. For a digital file, this need not match a file-system creation time. For a freshly created resource, it should be close to that time, modulo the time taken to write the file. Later file transfer, copying, and so on, can make the file-system time arbitrarily different. |
| **status** | recommended |
