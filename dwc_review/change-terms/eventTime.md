## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/eventTime

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~eventTime~ **eventTime**
* Term label (English, not normative): ~Event Time~ **Event Time**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Event
* New definition of the term (normative): **A time interval during which a dwc:Event occurred.**
* Previous definition of the term: ~The time or interval during which a dwc:Event occurred.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use a time of day that conforms to ISO 8601-1:2019.** 
* Previous usage comments: ~Recommended best practice is to use a time of day that conforms to ISO 8601-1:2019.~
* New examples (not normative): **`14:07-06:00` (2:07pm in the time zone six hours earlier than UTC); `08:40:21Z` (8:40:21am UTC); `13:00:00Z/15:30:00Z` (the interval between 1pm UTC and 3:30pm UTC)**
* Previous examples (not normative): ~`14:07-06:00` (at or after 2:07pm and before 2:08pm in the time zone six hours earlier than UTC); `08:40:21Z` (at or after 8:40:21am and before 8:41:22am UTC); `13:00:00Z/15:30:00Z` (at or after 1pm and before 3:30pm UTC)~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/eventTime-2025-06-12
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): accessible from DataSets/DataSet/Units/Unit/Gathering/ISODateTimeBegin and DataSets/DataSet/Units/Unit/Gathering/ISODateTimeEnd
