## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/georeferencedBy

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~georeferencedBy~ **georeferencedBy**
* Term label (English, not normative): ~Georeferenced By~ **Georeferenced By**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Event
* New definition of the term (normative): **A list (concatenated and separated) of names of dcterms:Agents responsible for determining a georeference (spatial representation) for a dcterms:Location.**
* Previous definition of the term: ~A list (concatenated and separated) of names of people, groups, or organizations who determined the georeference (spatial representation) for the dcterms:Location.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to separate the values in a list with space vertical bar space (` | `).** 
* Previous usage comments: ~Recommended best practice is to separate the values in a list with space vertical bar space (` | `). This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.~
* New examples (not normative): **`Brad Millen (ROM)`; `Kristina Yamamoto | Janet Fang`**
* Previous examples (not normative): ~`Brad Millen (ROM)`; `Kristina Yamamoto | Janet Fang`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/georeferencedBy-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
