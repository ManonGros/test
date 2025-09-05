## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/startDayOfYear

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~startDayOfYear~ **startDayOfYear**
* Term label (English, not normative): ~Start Day Of Year~ **Start Day Of Year**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Event
* New definition of the term (normative): **The earliest integer day of the year on which a dwc:Event occurred.**
* Previous definition of the term: ~The earliest integer day of the year on which the dwc:Event occurred (1 for January 1, 365 for December 31, except in a leap year, in which case it is 366).~
* New usage comments (recommendations regarding content, etc., not normative): ** The value is 1 for January 1 and 365 for December 31, except in a leap year, in which case it is 366.** 
* Previous usage comments: ~~
* New examples (not normative): **`1` (1 January); `32` (1 February); `366` (31 December); `365` (30 December in a leap year, 31 December in a non-leap year)**
* Previous examples (not normative): ~`1` (1 January); `366` (31 December); `365` (30 December in a leap year, 31 December in a non-leap year)~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/startDayOfYear-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Gathering/DateTime/DayNumberBegin
