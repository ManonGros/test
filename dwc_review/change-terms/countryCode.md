## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/countryCode

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~countryCode~ **countryCode**
* Term label (English, not normative): ~Country Code~ **Country Code**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Event
* New definition of the term (normative): **A standard code for a country in which a dcterms:Location occurs.**
* Previous definition of the term: ~The standard code for the country in which the dcterms:Location occurs.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use an ISO 3166-1-alpha-2 country code, or 'ZZ' (for an unknown location or a location unassignable to a single country code), or 'XZ' (for the high seas beyond national jurisdictions). Multiplicity and uncertainty of the geographic entity can be captured either in the term dwc:higherGeography or in the term dwc:locality, or both.** 
* Previous usage comments: ~Recommended best practice is to use an ISO 3166-1-alpha-2 country code, or `ZZ` (for an unknown location or a location unassignable to a single country code), or `XZ` (for the high seas beyond national jurisdictions).~
* New examples (not normative): **`AR`; `SV`; `XZ`; `ZZ`**
* Previous examples (not normative): ~`AR`; `SV`; `XZ`; `ZZ`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/countryCode-2025-06-12
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Gathering/Country/ISO3166Code
