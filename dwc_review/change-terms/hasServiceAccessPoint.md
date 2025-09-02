**Old term**

**Definition:** In a chosen serialization (RDF, XML Schema, etc.) the potentially multiple service access points (e.g., for different resolutions of an image) might be provided in a referenced or in a nested object. This property identifies one such access point. That is, each of potentially multiple values of hasServiceAccessPoint identifies a set of representation-dependent metadata using the properties defined under the Service Access Point Vocabulary section of the Audiovisual Core Term List document.
**Label:** Service Access Point
**Term Name:** ac:hasServiceAccessPoint
**Term version IRI:** http://rs.tdwg.org/ac/terms/version/hasServiceAccessPoint-2023-09-05
**Version of:** http://rs.tdwg.org/ac/terms/hasServiceAccessPoint
**Issued:** 2023-09-05
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/ac/terms/version/hasServiceAccessPoint-2020-01-27


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>media</li></ul> |
| **key** |  |
| **title** | Service Access Point |
| **description** | In a chosen serialization (RDF, XML Schema, etc.) the potentially multiple service access points (e.g., for different resolutions of an image) might be provided in a referenced or in a nested object. |
| **comments** | This property identifies one such access point. That is, each of potentially multiple values of hasServiceAccessPoint identifies a set of representation-dependent metadata using the properties defined under the Service Access Point Vocabulary section of the Audiovisual Core Term List document. Some serializations may flatten the model of service-access points by (a) dropping ac:hasServiceAccessPoint, ac:variant and ac:variantLiteral, (b) repeating properties from the Service Access Point Vocabulary and prefixing them with values of ac:variantLiteral. If such a flat serialization is necessary for services, we recommend to select from among term names of the form "AB" where "A" is one of thumbnail, trailer, lowerQuality, mediumQuality, goodQuality, bestQuality, offline and "B" is one of AccessURI, Format, Extent, FurtherInformationURL, LicensingException, ServiceExpectation (example: thumbnailAccessURI). Implementers in specific constraint languages such as XML Schema or RDF may wish to make Access URI and perhaps dcterms:format mandatory on instances of the service access point. |
| **example** |  |
| **type** | string |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** |  |
| **maximum** |  |
| **namespace** | ac |
| **dcterms:isVersionOf** | http://rs.tdwg.org/ac/terms/hasServiceAccessPoint |
| **dcterms:references** | http://rs.tdwg.org/ac/terms/version/hasServiceAccessPoint-2023-09-05 |
| **rdfs:comment** | In a chosen serialization (RDF, XML Schema, etc.) the potentially multiple service access points (e.g., for different resolutions of an image) might be provided in a referenced or in a nested object. This property identifies one such access point. That is, each of potentially multiple values of hasServiceAccessPoint identifies a set of representation-dependent metadata using the properties defined under the Service Access Point Vocabulary section of the Audiovisual Core Term List document. |
| **status** | recommended |
