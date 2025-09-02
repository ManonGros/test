**Old term**

**Definition:** Date the first digital version was created, if different from Original Date and Time found in the Temporal Coverage Vocabulary.
**Label:** Date and Time Digitized
**Term Name:** ac:digitizationDate
**Term version IRI:** http://rs.tdwg.org/ac/terms/version/digitizationDate-2020-01-27
**Version of:** http://rs.tdwg.org/ac/terms/digitizationDate
**Issued:** 2020-01-27
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/ac/terms/version/digitizationDate-2013-10-28


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>media</li></ul> |
| **key** |  |
| **title** | Digitization Date |
| **description** | A date on which the first digital version of a resource was created, if different from xmp:CreateDate. |
| **comments** | The date and time MUST comply with the World Wide Web Consortium (W3C) datetime practice, https://www.w3.org/TR/NOTE-datetime, which requires that date and time representation correspond to ISO 8601:1998, but with year fields always comprising 4 digits. This makes datetime records compliant with 8601:2004, https://www.iso.org/standard/40874.html. AC datetime values MAY also follow 8601:2004 for ranges by separating two IS0 8601 datetime fields by a solidus ("forward slash", '/'). Use the international (ISO/xml) format yyyy-mm-ddThh:mm (e. g. "2007-12-31" or "2007-12-31T14:59"). Where available, timezone information SHOULD be added. This is often not the media creation or modification date. For example, if photographic prints have been scanned, the date of that scanning is what this term carries, but Original Date and Time is that depicted in the print. In the case of digital images containing EXIF, whereas the EXIF capture date does not contain time zone information, but EXIF GPSDateStamp and GPSTimeStamp may be relevant as these include time-zone information. See also Metadata Working Group Guidelines for Handling Image Metadata, Version 2.0 (November 2010), https://web.archive.org/web/20180919181934/http://www.metadataworkinggroup.org/pdf/mwg_guidance.pdf, which has best practice advice on handling time-zone-less EXIF date/time data. See also the Wikipedia IS0 8601 entry, https://en.wikipedia.org/wiki/ISO_8601, for further explanation and examples. |
| **example** |  |
| **type** | string |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** |  |
| **maximum** |  |
| **namespace** | ac |
| **dcterms:isVersionOf** | http://rs.tdwg.org/ac/terms/digitizationDate |
| **dcterms:references** | http://rs.tdwg.org/ac/terms/version/digitizationDate-2020-01-27 |
| **rdfs:comment** | Date the first digital version was created, if different from Original Date and Time found in the Temporal Coverage Vocabulary. |
| **status** | recommended |
