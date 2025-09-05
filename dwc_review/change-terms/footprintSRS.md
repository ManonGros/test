## Term change

* Submitter: Darwin Core Data Package Coordination Team
* Efficacy Justification (why is this term necessary?): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Demand Justification (name at least two organizations that independently need this term): see [Darwin Core Data Package (DwC-DP) Implementation Experience and Feature Report](https://gbif.github.io/dwc-dp/docs/dwc_dp_implementation_feature_reports.pdf)
* Stability Justification (what concerns are there that this might affect existing implementations?): None
* Implications for dwciri: namespace (does this change affect a dwciri term version)?: To be determined by DwC-MG

Current Term definition: http://rs.tdwg.org/dwc/terms/footprintSRS

Proposed attributes of the new term version (Please put actual changes to be implemented in **bold** and ~strikethrough~):

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): ~footprintSRS~ **footprintSRS**
* Term label (English, not normative): ~Footprint SRS~ **Footprint SRS**
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): Event
* New definition of the term (normative): **An ellipsoid, geodetic datum, or spatial reference system (SRS) upon which a geometry given in dwc:footprintWKT is based.**
* Previous definition of the term: ~The ellipsoid, geodetic datum, or spatial reference system (SRS) upon which the geometry given in dwc:footprintWKT is based.~
* New usage comments (recommendations regarding content, etc., not normative): **Recommended best practice is to use the EPSG code of the SRS, if known. Otherwise use a controlled vocabulary for the name or code of the geodetic datum, if known. Otherwise use a controlled vocabulary for the name or code of the ellipsoid, if known. If none of these is known, use the value `not recorded`. It is also permitted to provide the SRS in Well-Known-Text, especially if no EPSG code provides the necessary values for the attributes of the SRS. Do not use this term to describe the SRS of a dwc:decimalLatitude and dwc:decimalLongitude, nor of any verbatim coordinates - use dwc:geodeticDatum and dwc:verbatimSRS instead.** 
* Previous usage comments: ~Recommended best practice is to use the EPSG code of the SRS, if known. Otherwise use a controlled vocabulary for the name or code of the geodetic datum, if known. Otherwise use a controlled vocabulary for the name or code of the ellipsoid, if known. If none of these is known, use the value `not recorded`. It is also permitted to provide the SRS in Well-Known-Text, especially if no EPSG code provides the necessary values for the attributes of the SRS. Do not use this term to describe the SRS of the dwc:decimalLatitude and dwc:decimalLongitude, nor of any verbatim coordinates - use the dwc:geodeticDatum and dwc:verbatimSRS instead. This term has an equivalent in the dwciri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.~
* New examples (not normative): **`EPSG:4326`; `GEOGCS['GCS_WGS_1984', DATUM['D_WGS_1984', SPHEROID['WGS_1984',6378137,298.257223563]], PRIMEM['Greenwich',0], UNIT['Degree',0.0174532925199433]]` (WKT for the standard WGS84 Spatial Reference System EPSG:4326)**
* Previous examples (not normative): ~`EPSG:4326`; `GEOGCS["GCS_WGS_1984", DATUM["D_WGS_1984", SPHEROID["WGS_1984",6378137,298.257223563]], PRIMEM["Greenwich",0], UNIT["Degree",0.0174532925199433]]` (WKT for the standard WGS84 Spatial Reference System EPSG:4326); `not recorded`~
* Refines (identifier of the broader term this term refines; normative): http://rs.tdwg.org/dwc/terms/version/footprintSRS-2025-06-12
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative): not in ABCD
