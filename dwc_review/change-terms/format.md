**Old term**



| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>media</li></ul> |
| **key** |  |
| **title** | Format |
| **description** | The file format, physical medium, or dimensions of the resource, denoted by a controlled value string. |
| **comments** | A controlled value string describing the technical format of the resource (file format or physical medium). The string SHOULD be a controlled value from the Audiovisual Core Controlled Vocabulary for Dublin Core dcterms:format, although it MAY be any Media Type (MIME type) value from the IANA list of Media Types (https://www.iana.org/assignments/media-types/media-types.xhtml) or any commonly used file extension string. Human-readable information about the Controlled Vocabulary for format is at http://rs.tdwg.org/ac/doc/format/. This term can be used to describe offline digital content. In cases where the provided Service Access Point URL includes a standard file extension from which the format can be inferred, it is permissible to not provide a value for this property. See also the entry for dcterms:format in the Audiovisual Core term list document and see the DCMI FAQ on DC and DCTERMS Namespaces, https://web.archive.org/web/20171126043657/https://github.com/dcmi/repository/blob/master/mediawiki_wiki/FAQ/DC_and_DCTERMS_Namespaces.md, for discussion of the rationale for terms in two namespaces. It is best practice to use dcterms:format instead of dc:format whenever practical. Normal practice is to use the same Label if both are provided. Labels have no effect on information discovery and are only suggestions. |
| **example** |  |
| **type** | string |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** |  |
| **maximum** |  |
| **namespace** | dc |
| **dcterms:isVersionOf** | http://purl.org/dc/elements/1.1/format |
| **dcterms:references** | http://dublincore.org/usage/terms/history/#format-007 |
| **rdfs:comment** | The file format, physical medium, or dimensions of the resource. |
| **status** | recommended |
