**Old term**

**Definition:** A list (concatenated and separated) of identifiers of other dwc:Organisms and the associations of this dwc:Organism to each of them.
**Label:** Associated Organisms
**Term Name:** dwc:associatedOrganisms
**Term version IRI:** http://rs.tdwg.org/dwc/terms/version/associatedOrganisms-2023-06-28
**Version of:** http://rs.tdwg.org/dwc/terms/associatedOrganisms
**Issued:** 2023-06-28
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/dwc/terms/version/associatedOrganisms-2021-07-15


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>organism</li></ul> |
| **key** |  |
| **title** | Associated Organisms |
| **description** | A list (concatenated and separated) of identifiers of other dwc:Organisms and the associations of this dwc:Organism to each of them. |
| **comments** | This term can be used to provide a list of associations to other dwc:Organisms. Note that the dwc:ResourceRelationship class is an alternative means of representing associations, and with more detail. Recommended best practice is to separate the values in a list with space vertical bar space ( | ). |
| **example** | `"sibling of":"http://arctos.database.museum/guid/DMNS:Mamm:14171"`; ; `"parent of":"http://arctos.database.museum/guid/MSB:Mamm:196208" | "parent of":"http://arctos.database.museum/guid/MSB:Mamm:196523" | "sibling of":"http://arctos.database.museum/guid/MSB:Mamm:142638"` |
| **type** | string |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** |  |
| **maximum** |  |
| **namespace** | dwc |
| **dcterms:isVersionOf** | http://rs.tdwg.org/dwc/terms/associatedOrganisms |
| **dcterms:references** | http://rs.tdwg.org/dwc/terms/version/associatedOrganisms-2023-06-28 |
| **rdfs:comment** | A list (concatenated and separated) of identifiers of other dwc:Organisms and the associations of this dwc:Organism to each of them. |
| **status** | recommended |
