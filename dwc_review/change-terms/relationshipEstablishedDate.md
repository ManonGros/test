## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/relationshipEstablishedDate

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~relationshipEstablishedDate~ **relationshipEstablishedDate**
* Term label (English, not normative): ~Relationship Established Date~ **Relationship Established Date**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): ResourceRelationship
* New definition of the term (normative): **A date on which a dwc:ResourceRelationship was established.**
* Previous definition of the term: ~The date-time on which the relationship between the two resources was established.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use a date that conforms to ISO 8601-1:2019.** 
* Previous usage comments: ~Recommended best practice is to use a date that conforms to ISO 8601-1:2019.~
* New examples (not normative): **`1963-03-08T14:07-06:00` (8 Mar 1963 at or after 2:07pm and before 2:08pm in the time zone six hours earlier than UTC); `2009-02-20T08:40Z` (20 February 2009 at or after 8:40am and before 8:41 UTC); `2018-08-29T15:19` (29 August 2018 at or after 3:19pm and before 3:20pm local time); `1809-02-12` (within the day 12 February 1809); `1906-06` (in the month of June 1906); `1971` (in the year 1971); `2007-03-01T13:00:00Z/2008-05-11T15:30:00Z` (some time within the interval beginning 1 March 2007 at 1pm UTC and before 11 May 2008 at 3:30pm UTC); `1900/1909` (some time within the interval between the beginning of the year 1900 and before the year 1909); `2007-11-13/15` (some time in the interval between the beginning of 13 November 2007 and before 15 November 2007)**
* Previous examples (not normative): ~`1963-03-08T14:07-06:00` (8 Mar 1963 at or after 2:07pm and before 2:08pm in the time zone six hours earlier than UTC); `2009-02-20T08:40Z` (20 February 2009 at or after 8:40am and before 8:41 UTC); `2018-08-29T15:19` (29 August 2018 at or after 3:19pm and before 3:20pm local time); `1809-02-12` (within the day 12 February 1809); `1906-06` (in the month of June 1906); `1971` (in the year 1971); `2007-03-01T13:00:00Z/2008-05-11T15:30:00Z` (some time within the interval beginning 1 March 2007 at 1pm UTC and before 11 May 2008 at 3:30pm UTC); `1900/1909` (some time within the interval between the beginning of the year 1900 and before the year 1909); `2007-11-13/15` (some time in the interval between the beginning of 13 November 2007 and before 15 November 2007)~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/relationshipEstablishedDate-2025-06-12
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
