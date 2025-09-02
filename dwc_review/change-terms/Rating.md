

| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>media</li></ul> |
| **key** |  |
| **title** | Rating |
| **description** | A user-assigned rating for this file. The value shall be -1 or in the range [0..5], where -1 indicates "rejected" and 0 indicates "unrated". If xmp:Rating is not present, a value of 0 should be assumed. |
| **comments** | A rating for a dwc:Media resource, provided by record originators or editors, with '1' (worst) to '5' (best). Anticipated usage is for a typical 'star rating' UI, with the addition of a notion of rejection. Values MAY be decimal numbers in the permitted range. The origin of the rating is not communicated. It may, e. g., be based on user feedback or on editorial ratings. By "user-assigned" is meant assigned by the originator or editor of the record using the term. |
| **example** | `1`; `5` |
| **type** | string |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** |  |
| **maximum** |  |
| **namespace** | xmp |
| **dcterms:isVersionOf** | http://ns.adobe.com/xap/1.0/Rating |
| **dcterms:references** |  |
| **rdfs:comment** | A user-assigned rating for this file. The value shall be -1 or in the range [0..5], where -1 indicates "rejected" and 0 indicates "unrated". If xmp:Rating is not present, a value of 0 should be assumed. |
| **status** | recommended |
