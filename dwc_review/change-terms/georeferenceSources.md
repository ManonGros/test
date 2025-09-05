## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/georeferenceSources

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~georeferenceSources~ **georeferenceSources**
* Term label (English, not normative): ~Georeference Sources~ **Georeference Sources**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Event
* New definition of the term (normative): **A list (concatenated and separated) of maps, gazetteers, or other resources used to georeference a dcterms:Location, described specifically enough to allow anyone in the future to use the same resources.**
* Previous definition of the term: ~A list (concatenated and separated) of maps, gazetteers, or other resources used to georeference the dcterms:Location, described specifically enough to allow anyone in the future to use the same resources.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to separate the values in a list with space vertical bar space (` | `).** 
* Previous usage comments: ~Recommended best practice is to separate the values in a list with space vertical bar space (` | `). This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.~
* New examples (not normative): **`GeoLocate`, 'GeoPick`; `https://www.geonames.org/`; `USGS 1:24000 Florence Montana Quad 1967 | Terrametrics 2008 on Google Earth`**
* Previous examples (not normative): ~`https://www.geonames.org/`; `USGS 1:24000 Florence Montana Quad 1967 | Terrametrics 2008 on Google Earth`; `GeoLocate`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/georeferenceSources-2023-06-28
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): DataSets/DataSet/Units/Unit/Gathering/SiteCoordinateSets/SiteCoordinates/GeoreferenceSources
