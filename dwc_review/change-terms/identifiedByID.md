**Old term**

**Definition:** A person, group, or organization who assigned the dwc:Taxon to the subject.
**Label:** Identified By (IRI)
**Term Name:** dwciri:identifiedBy
**Term version IRI:** http://rs.tdwg.org/dwc/iri/version/identifiedBy-2025-06-12
**Version of:** http://rs.tdwg.org/dwc/iri/identifiedBy
**Issued:** 2025-06-12
**Type:** Property
**Status:** superseded
**Replaces:** http://rs.tdwg.org/dwc/iri/version/identifiedBy-2023-06-28


| definitions | context 1 |context 2 |context 3 |
|-|-|-|-|
| **Context - tables concerned** | <ul><li>material</li><li>occurrence</li></ul> | <ul><li>survey</li></ul> | <ul><li>identification</li></ul> |
| **key** | fk | fk | fk |
| **title** | Identified By ID | Identified By ID | Identified By ID |
| **description** | An identifier for a dcterms:Agent responsible for making a taxonomic determination of a dwc:Organism. | An identifier for a dcterms:Agent responsible for making a taxonomic determination of a dwc:Organism. | An identifier for a dcterms:Agent responsible for making a taxonomic determination of a dwc:Organism. |
| **comments** |  | When used in the context of a Survey, the subject consists of all of the dwc:Identifications related to the Survey. Recommended best practice is to provide a single identifier that disambiguates the details of the identifying dcterms:Agent. If a list is used, the order of the identifiers on the list should not be assumed to convey any semantics. Recommended best practice is to separate the values in a list with space vertical bar space (` | `). | When used in the context of a dwc:Survey, the subject consists of all of the dwc:Identifications related to the dwc:Survey. Recommended best practice is to provide a single identifier that disambiguates the details of the identifying dcterma:Agent. If a list is used, the order of the identifiers on the list should not be assumed to convey any semantics. Recommended best practice is to separate the values in a list with space vertical bar space (` | `). |
| **example** | `https://orcid.org/0000-0002-1825-0097` (for an individual); `https://orcid.org/0000-0002-1825-0097 | https://orcid.org/0000-0002-1825-0098` (for a list of people) | `https://orcid.org/0000-0002-1825-0097` | `https://orcid.org/0000-0002-1825-0097` (for an individual); `https://orcid.org/0000-0002-1825-0097 | https://orcid.org/0000-0002-1825-0098` (for a list of people) |
| **type** | string | string | string |
| **format** | default | default | default |
| **unique** | False | False | False |
| **required** | False | False | False |
| **minimum** |  |  |  |
| **maximum** |  |  |  |
| **namespace** | dwciri | dwciri | dwciri |
| **dcterms:isVersionOf** | http://rs.tdwg.org/dwc/iri/identifiedBy | http://rs.tdwg.org/dwc/iri/identifiedBy | http://rs.tdwg.org/dwc/iri/identifiedBy |
| **dcterms:references** | http://rs.tdwg.org/dwc/iri/version/identifiedBy-2025-06-12 | http://rs.tdwg.org/dwc/iri/version/identifiedBy-2025-06-12 | http://rs.tdwg.org/dwc/iri/version/identifiedBy-2025-06-12 |
| **rdfs:comment** | A person, group, or organization who assigned the dwc:Taxon to the subject. | A list (concatenated and separated) of the globally unique identifier for the person, people, groups, or organizations responsible for assigning the dwc:Taxon to the subject. | A person, group, or organization who assigned the dwc:Taxon to the subject. |
| **status** | recommended | recommended | recommended |
