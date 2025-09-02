**Old term**

**Definition:** Language of description and other metadata (but not necessarily of the image itself) represented as an ISO639-2 three letter language code.
**Label:** Metadata Language
**Term Name:** ac:metadataLanguageLiteral
**Term version IRI:** http://rs.tdwg.org/ac/terms/version/metadataLanguageLiteral-2023-09-05
**Version of:** http://rs.tdwg.org/ac/terms/metadataLanguageLiteral
**Issued:** 2023-09-05
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/ac/terms/version/metadataLanguageLiteral-2020-01-27


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>media</li></ul> |
| **key** |  |
| **title** | Metadata Language Literal |
| **description** | Language of description and other metadata (but not necessarily of the image itself) represented as an ISO639-2 three letter language code. |
| **comments** | ISO639-1 two-letter codes are permitted but deprecated. At least one of ac:metadataLanguage and ac:metadataLanguageLiteral MUST be supplied but, when feasible, supplying both might make the metadata more widely useful. They MUST specify the same language. In case of ambiguity, ac:metadataLanguage prevails. This is NOT dc:language, which is about the resource, not the metadata. Metadata Language is deliberately single-valued, imposing on unstructured serializations a requirement that multi-lingual metadata be represented as separate, complete, metadata records. Audiovisual Core requires that each record also contains the language-neutral terms. In the absence of this requirement, metadata consumers would need to know which terms are language-neutral and merge these terms from all provided metadataLanguages into a single record. Metadata consumers may re-combine the information based on the dcterms:identifier that identifies the multimedia resource. Nothing in this document would, however, prevent an implementer, e. g. of an XML-Schema representation, from providing a fully hierarchical schema in which language neutral terms occur only a single time, and only the language-specific terms are repeated in a way that unambigously relates them to a metadata language. In RDF it may be a simple repetition of plain literals associated with a language (e.g., xml:lang attribute in RDF/XML). The language attribute would then be required in Audiovisual Core and would replace ac:metadataLanguage. |
| **example** |  |
| **type** | string |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** |  |
| **maximum** |  |
| **namespace** | ac |
| **dcterms:isVersionOf** | http://rs.tdwg.org/ac/terms/metadataLanguageLiteral |
| **dcterms:references** | http://rs.tdwg.org/ac/terms/version/metadataLanguageLiteral-2023-09-05 |
| **rdfs:comment** | Language of description and other metadata (but not necessarily of the image itself) represented as an ISO639-2 three letter language code. |
| **status** | recommended |
