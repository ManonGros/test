

| definitions | context 1 |
|-|-|
| **Context - tables concerned** | <ul><li>molecular-protocol</li></ul> |
| **key** | fk |
| **title** | source_mat_id |
| **description** | A unique identifier assigned to a material sample (as defined by http://rs.tdwg.org/dwc/terms/materialSampleID, and as opposed to a particular digital record of a material sample) used for extracting nucleic acids, and subsequent sequencing. The identifier can refer either to the original material collected or to any derived sub-samples. The INSDC qualifiers /specimen_voucher, /bio_material, or /culture_collection may or may not share the same value as the source_mat_id field. For instance, the /specimen_voucher qualifier and source_mat_id may both contain ´UAM:Herps:14´ , referring to both the specimen voucher and sampled tissue with the same identifier. However, the /culture_collection qualifier may refer to a value from an initial culture (e.g. ATCC:11775) while source_mat_id would refer to an identifier from some derived culture from which the nucleic acids were extracted (e.g. xatc123 or ark:/2154/R2). |
| **comments** |  |
| **example** |  |
| **type** | string |
| **format** | default |
| **unique** | False |
| **required** | True |
| **minimum** |  |
| **maximum** |  |
| **namespace** | mixs |
| **dcterms:isVersionOf** | https://w3id.org/mixs/0000026 |
| **dcterms:references** |  |
| **rdfs:comment** | A unique identifier assigned to a material sample (as defined by http://rs.tdwg.org/dwc/terms/materialSampleID, and as opposed to a particular digital record of a material sample) used for extracting nucleic acids, and subsequent sequencing. The identifier can refer either to the original material collected or to any derived sub-samples. The INSDC qualifiers /specimen_voucher, /bio_material, or /culture_collection may or may not share the same value as the source_mat_id field. For instance, the /specimen_voucher qualifier and source_mat_id may both contain ´UAM:Herps:14´ , referring to both the specimen voucher and sampled tissue with the same identifier. However, the /culture_collection qualifier may refer to a value from an initial culture (e.g. ATCC:11775) while source_mat_id would refer to an identifier from some derived culture from which the nucleic acids were extracted (e.g. xatc123 or ark:/2154/R2). |
| **status** | recommended |
