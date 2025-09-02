**Old term**

**Definition:** URI for a reviewer.
**Label:** Reviewer
**Term Name:** ac:reviewer
**Term version IRI:** http://rs.tdwg.org/ac/terms/version/reviewer-2023-09-05
**Version of:** http://rs.tdwg.org/ac/terms/reviewer
**Issued:** 2023-09-05
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/ac/terms/version/reviewer-2020-01-27


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>media</li></ul> |
| **key** | fk |
| **title** | Reviewer ID |
| **description** | An identifier for a dcterms:Agent primarily responsible for providing the ac:reviewerComments |
| **comments** | If present, then resource is peer-reviewed, even if ac:reviewerComments is absent or empty. Its presence tells whether an expert in the subject featured in the media has reviewed a dwc:Media resource or collection and approved its metadata description; MUST display a name or the literal "anonymous" (= anonymously reviewed). Provider is asserting they accept this review as competent. See also ac:reviewerLiteral and the section Namespaces, Prefixes and Term Names in the Audiovisual Core Term List document for discussion of the rationale for separate terms taking URI values from those taking Literal values where both are possible. Normal practice is to use the same Label if both are provided. Labels have no effect on information discovery and are only suggestions. |
| **example** |  |
| **type** | string |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** |  |
| **maximum** |  |
| **namespace** | ac |
| **dcterms:isVersionOf** | http://rs.tdwg.org/ac/terms/reviewer |
| **dcterms:references** | http://rs.tdwg.org/ac/terms/version/reviewer-2023-09-05 |
| **rdfs:comment** | URI for a reviewer. |
| **status** | recommended |
