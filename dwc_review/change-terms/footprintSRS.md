**Old term**

**Definition:** The ellipsoid, geodetic datum, or spatial reference system (SRS) upon which the geometry given in dwc:footprintWKT is based.
**Label:** Footprint SRS
**Term Name:** dwc:footprintSRS
**Term version IRI:** http://rs.tdwg.org/dwc/terms/version/footprintSRS-2025-06-12
**Version of:** http://rs.tdwg.org/dwc/terms/footprintSRS
**Issued:** 2025-06-12
**Type:** Property
**Status:** recommended
**Replaces:** http://rs.tdwg.org/dwc/terms/version/footprintSRS-2023-06-28


| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>event</li></ul> |
| **key** |  |
| **title** | Footprint SRS |
| **description** | An ellipsoid, geodetic datum, or spatial reference system (SRS) upon which a geometry given in dwc:footprintWKT is based. |
| **comments** | Recommended best practice is to use the EPSG code of the SRS, if known. Otherwise use a controlled vocabulary for the name or code of the geodetic datum, if known. Otherwise use a controlled vocabulary for the name or code of the ellipsoid, if known. If none of these is known, use the value `not recorded`. It is also permitted to provide the SRS in Well-Known-Text, especially if no EPSG code provides the necessary values for the attributes of the SRS. Do not use this term to describe the SRS of a dwc:decimalLatitude and dwc:decimalLongitude, nor of any verbatim coordinates - use dwc:geodeticDatum and dwc:verbatimSRS instead. |
| **example** | `EPSG:4326`; `GEOGCS['GCS_WGS_1984', DATUM['D_WGS_1984', SPHEROID['WGS_1984',6378137,298.257223563]], PRIMEM['Greenwich',0], UNIT['Degree',0.0174532925199433]]` (WKT for the standard WGS84 Spatial Reference System EPSG:4326) |
| **type** | string |
| **format** | default |
| **unique** |  |
| **required** |  |
| **minimum** |  |
| **maximum** |  |
| **namespace** | dwc |
| **dcterms:isVersionOf** | http://rs.tdwg.org/dwc/terms/footprintSRS |
| **dcterms:references** | http://rs.tdwg.org/dwc/terms/version/footprintSRS-2025-06-12 |
| **rdfs:comment** | The ellipsoid, geodetic datum, or spatial reference system (SRS) upon which the geometry given in dwc:footprintWKT is based. |
| **status** | recommended |
