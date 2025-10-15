# SNOMED CT New Zealand Extension PRODUCTION Release Notes - October 2025

***

| **Date**             | **20251001** |
| -------------------- | ------------ |
| **Document Version** | **1.0**      |
| **Release Status**   | production   |

***

## Introduction

<figure><img src=".gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

Health New Zealand | Te Whatu Ora works with health agencies and their industry partners to develop SNOMED CT® reference sets, maps, language reference sets and other content for digital health solutions in Aotearoa New Zealand.

The SNOMED CT New Zealand Extension packages these components for release every April and October, to be used with the latest designated SNOMED CT International Edition release.

The content can be downloaded from our [member licensing and distribution service](https://mlds.ihtsdotools.org/#/landing/NZ?lang=en), viewed online using the [SNOMED CT browser](https://browser.ihtsdotools.org/) or accessed via a standard FHIR® API using the [NZ Health Terminology Service](https://www.tewhatuora.govt.nz/health-services-and-programmes/digital-health/terminology-service).&#x20;

We welcome your feedback and participation. For more information about SNOMED CT implementation in New Zealand, email [standards@hnz.govt.nz](mailto:standards@hnz.govt.nz), visit our [website](https://www.tewhatuora.govt.nz/health-services-and-programmes/digital-health/snomed-ct-national-release-centre) or join the standards channel at [ehealthforum.nz](https://ehealthforum.nz).

## Background

This document summarises the content changes included in the October 2025 production release of the SNOMED NZ Extension package.

It also includes technical notes detailing any known issues.

This SNOMED NZ Extension package is dependent upon and should therefore be consumed in conjunction with the SNOMED CT International Edition August 2025 release.

## New and updated content

The October 2025 release includes updates to the previously released content in the SNOMED NZ Extension and introduces some new content.

This release includes new content in the following areas.

#### ACC translation table map

The ACC translation table has been extended to further support automated processing of SNOMED coded injury claims for patients in public hospitals:

* 36 concepts modified
* 1382 mappings removed
* 1299 new mappings created

#### **Emergency care reference sets**

The chief presenting complaint and diagnosis reference sets have been updated as a result of the latest six-monthly clinical reference group review in August 2025.

Use of these reference sets to code the chief presenting complaint and diagnosis data elements for all ED presentations and submit this data to NNPAC has been mandatory since NCAMP 2021.

NCAMP 2026 includes the latest versions of the reference sets to ensure that emergency departments across the country are updating their systems for optimal clinical experience.

#### Health service type reference set

This reference set has been updated to support work underway by HealthPoint in the mapping of SNOMED CT concepts into their website and FHIR-based APIs for services used by consumers, healthcare professionals and helplines.

Patient friendly terms in NZ English are included for all health service types alongside te reo Māori translations provided by Te Taura Whiri i te Reo Māori | Māori Language Commission.

#### NZ Breast Device Registry (NZBDR)

The set of SNOMED concepts developed for the New Zealand Breast Device Registry (NZBDR) | Te Rehita Taputapu Uma o Aotearoa has been extended to add the following body structure concepts relating to the placement of an implant within a breast structure.

| **SCTID**       | **Fully Specified Name**                                         | **Preferred Term**                |
| --------------- | ---------------------------------------------------------------- | --------------------------------- |
| 245526002       | Structure of retromammary space (body structure)                 | Prepectoral space                 |
| 599301000210109 | Structure of retromammary space of left breast (body structure)  | Prepectoral space of left breast  |
| 599291000210105 | Structure of retromammary space of right breast (body structure) | Prepectoral space of right breast |
| 599271000210106 | Structure of sub-pectoral space of left breast (body structure)  | Subpectoral space of left breast  |
| 599281000210108 | Structure of sub-pectoral space of right breast (body structure) | Subpectoral space of right breast |
| 599261000210100 | Structure of sub-pectoral space (body structure)                 | Subpectoral space                 |

#### NZ Radiology procedures reference set

The radiology procedures reference set has been updated to include the RANZCR (Royal Australian and New Zealand College of Radiologists) reference set and the NICIP (National Interim Clinical Imaging Procedure) code set from the UK National Health Service.

#### Ophthalmology concepts

A set of SNOMED concepts has been developed and promoted to the SNOMED International Edition to support data collection in ophthalmology services.

#### Systemic Anti-Cancer Therapy Regimen Library

Further concepts representing systemic anti-cancer therapy (SACT) regimens have been added to support the CanShare programme. Responsibility for management of this content has moved from the NZULM team to the the CanShare team at Te Aho o Te Kahu | Cancer Control Agency .

#### **Other changes**

18 reference sets have been updated to replace inactive concepts with active concepts.

#### CanShare reference sets

Te Aho o Te Kahu | Cancer Control Agency has developed a collection of 474 CanShare reference sets for Aotearoa. These reference sets provide standard sets of SNOMED CT concepts to use for recording, sharing and querying cancer data in Aotearoa. Each concept in these reference sets has a preferred term in the CanShare language reference set (SCTID 231621000210105), selected by New Zealand clinicians to standardise the way that cancer data is displayed. These reference sets are designed to support a range of cancer data, including key diagnostic components, treatment plans, national registers and screening programmes.

This release includes 16 new CanShare reference sets, 48 updated reference sets, 410 static reference sets and 334 new concepts to support the following areas:

* **Cancer streams, substreams and primary cancer types** to support clinical workflows for medical oncology and haematology.
* **Topographies** for recording the primary site of a cancer. This includes a maximal set of body sites, a high-level set of commonly used body sites, and body sites specific to breast, thoracic, gastrointestinal, female genital, genitourinary, soft tissue & bone, skin, head & neck, central nervous system, endocrine & neuroendocrine, and eye cancers.
* **Lymph nodes** for recording a lymph node site (for pathology or surgery) for breast, thoracic, gastrointestinal, female genital, genitourinary, head & neck, and eye cancers.
* **Cancer histologies** for haematologic, breast, thoracic, gastrointestinal, female genital, genitourinary, soft tissue & bone, skin, head & neck, central nervous system, endocrine & neuroendocrine, eye, and paediatric cancers, based on the WHO Classification of Tumours 5th edition.
* **Grading systems** for haematology and solid cancers.&#x20;
* **Staging systems (AJCC and non AJCC)** for haematology and solid cancers, including clinical, pathological, recurrence or retreatment, and post therapy or post neoadjuvant therapy staging.
* **Prognostic factors** relevant to staging of solid cancers.
* **Prognostic scoring systems** for haematology, female genital, and genitourinary cancers.
* **Neoadjuvant therapy response scoring systems** for breast, colorectal, and female genital cancers.
* **Specimen collection procedures and specimens** to support all cancer types.
* **Ancillary study tests and results** for a wide range of cancers, to support testing eligibility for new cancer medicines, as well as breast and colorectal cancers.
* **Systemic anti-cancer therapy treatment plans** to support regimen design.
* **Radiation oncology** treatment plans and waitlist data.
* **Additional data** to support national screening programmes (eg, National Cervical Screening Programme) and registers (eg, Breast Cancer Foundation National Register).

## Release statistics

#### Concept and description statistics

Requests from the SNOMED NZ National Release Centre to SNOMED International have resulted in the promotion of 24 new concepts and 1 new description into the SNOMED International Edition since our April 2025 release.

Requests from the Sweden and Canada National Release Centres have resulted in 6 concepts being promoted from our extension into the SNOMED International Edition.

There are 443 new concepts and 2180 new descriptions in this release.

For a statistical breakdown of the content of the SNOMED NZ Edition and this release please visit [release statistics site](https://browser.ihtsdotools.org/qa/#/SNOMEDCT-NZ/descriptive-statistics).

#### Reference sets

There are 716 reference sets in this release, including 16 new reference sets.&#x20;

Visit [our website](https://www.tewhatuora.govt.nz/health-services-and-programmes/digital-health/snomed-ct-national-release-centre) for more information about our reference sets.

You can access New Zealand reference sets without login by visiting [SNOMED CT Reference Set Tool 2.0](https://rt2.ihtsdotools.org/library). Once there click on library in the top right-hand corner and then filter on New Zealand NRC in the organisation column to select a reference set.&#x20;

#### Deprecated and inactivated reference sets

31 reference sets have been removed from this release, and 169 reference sets have been inactivated pending full deprecation in the forthcoming April 2026 release.

_Table 1.1 Deprecated reference sets (These reference sets have been removed from this release)_

| **Reference set name**                                                                                                                                                             | **SCTID**       |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------- |
| New Zealand cancer soft tissue and bone topography reference set                                                                                                                   | 398421000210104 |
| New Zealand WHO classification of tumours (5th edition) haematolymphoid peripheral T-cell lymphoma histology reference set                                                         | 297181000210101 |
| New Zealand WHO classification of tumours (5th edition) haematolymphoid Epstein-Barr virus positive T-cell and natural killer cell lymphoiod proliferation histology reference set | 394281000210109 |
| New Zealand cancer follicular lymphoma grade reference set                                                                                                                         | 294721000210105 |
| New Zealand WHO classification of tumours (5th edition) malignant differentiation grade reference set                                                                              | 340991000210103 |
| New Zealand WHO classification of tumours (5th edition) malignant low high grade reference set                                                                                     | 341001000210104 |
| New Zealand WHO classification of tumours (5th edition) neuroendocrine tumour grade reference set                                                                                  | 332691000210107 |
| New Zealand cancer Nottingham Combined breast grade reference set                                                                                                                  | 253261000210100 |
| New Zealand cancer urinary and male genital renal pelvis and ureter lymph node reference set                                                                                       | 396191000210105 |
| New Zealand cancer nuclear grade of DCIS grade reference set                                                                                                                       | 253271000210106 |
| New Zealand cancer FIGO 2009 endometrial carcinoma grade reference set                                                                                                             | 331811000210105 |
| New Zealand WHO classification of tumours (5th edition) CNS tumour grade reference set                                                                                             | 351521000210103 |
| New Zealand cancer FIGO 2014 ovary and fallopian tube and primary peritoneal carcinoma stage reference set                                                                         | 331731000210108 |
| New Zealand cancer FIGO 2023 corpus uteri carcinoma and carcinosarcoma stage reference set                                                                                         | 331741000210100 |
| New Zealand cancer FIGO 2009 endometrial carcinoma stage reference set                                                                                                             | 476781000210105 |
| New Zealand cancer FIGO 2015 corpus uteri leiomyosarcoma and endometrial stromal sarcoma stage reference set                                                                       | 331751000210102 |
| New Zealand cancer FIGO 2015 corpus uteri adenosarcoma stage reference set                                                                                                         | 331761000210104 |
| New Zealand cancer FIGO 2001 gestational trophoblastic disease stage reference set                                                                                                 | 331771000210105 |
| New Zealand cancer FIGO 2018 cervix uteri stage reference set                                                                                                                      | 331781000210107 |
| New Zealand cancer FIGO 2018 vagina stage reference set                                                                                                                            | 331791000210109 |
| New Zealand cancer FIGO 2021 vulva stage reference set                                                                                                                             | 331801000210108 |
| New Zealand cancer Ann Arbor lymphoma stage reference set                                                                                                                          | 294731000210107 |
| New Zealand cancer GHSG Hodgkin treatment stratification stage reference set                                                                                                       | 294741000210104 |
| New Zealand cancer NK-cell and T-cell non-Hodgkin lymphoma treatment stratification stage reference set                                                                            | 294751000210101 |
| New Zealand cancer R-ISS for multiple myeloma stage reference set                                                                                                                  | 294761000210103 |
| New Zealand cancer Mayo staging for AL (amyloidosis) stage reference set                                                                                                           | 294771000210109 |
| New Zealand cancer revised Mayo staging 2012 for AL (amyloidosis) stage reference set                                                                                              | 294781000210106 |
| New Zealand cancer Rai staging for CLL stage reference set                                                                                                                         | 294791000210108 |
| New Zealand cancer Binet staging for CLL stage reference set                                                                                                                       | 294801000210107 |
| New Zealand cancer revised TNM-B staging for cutaneous T-cell lymphoma stage reference set                                                                                         | 294811000210109 |
| New Zealand cancer Lugano staging classification for lymphoma reference set                                                                                                        | 380781000210106 |

_Table 1.2 Inactivated reference sets (These reference sets have been inactivated and will be removed in the April 2026 release)_

| **Reference set name**                                                                                                                                                    | **SCTID**       |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------- |
| New Zealand cancer genetic test reference set                                                                                                                             | 447991000210106 |
| New Zealand cancer gene cell reference set                                                                                                                                | 466571000210109 |
| New Zealand cancer HER2 expression reference set                                                                                                                          | 253351000210105 |
| New Zealand cancer HER2 expression by molecular test reference set                                                                                                        | 394241000210102 |
| New Zealand cancer HER2 expression by immunohistochemistry reference set                                                                                                  | 395511000210104 |
| New Zealand AJCC 8th edition gastrointestinal colon and rectum clinical T category reference set                                                                          | 332901000210109 |
| New Zealand AJCC 8th edition haematology primary cutaneous B-cell or T-cell (non-MF/SS) lymphoma clinical T category reference set                                        | 253581000210105 |
| New Zealand AJCC 8th edition haematology primary cutaneous B-cell or T-cell (non-MF/SS) lymphoma pathological T category reference set                                    | 253601000210102 |
| New Zealand AJCC 8th edition haematology primary cutaneous B-cell or T-cell (non-MF/SS) lymphoma clinical N category reference set                                        | 253621000210105 |
| New Zealand AJCC 8th edition haematology primary cutaneous B-cell or T-cell (non-MF/SS) lymphoma pathological N category reference set                                    | 253641000210104 |
| New Zealand AJCC 9th edition female genital cervix uteri stage group reference set                                                                                        | 331721000210106 |
| New Zealand AJCC 9th edition female genital cervix uteri pathological N category reference set                                                                            | 331691000210103 |
| New Zealand AJCC 9th edition female genital cervix uteri clinical N category reference set                                                                                | 331641000210107 |
| New Zealand AJCC 9th edition female genital cervix uteri pathological T category reference set                                                                            | 331631000210104 |
| New Zealand AJCC 9th edition female genital cervix uteri clinical T category reference set                                                                                | 331621000210101 |
| New Zealand AJCC 9th edition female genital vulva stage group reference set                                                                                               | 398951000210101 |
| New Zealand AJCC 9th edition female genital vulva pathological N category reference set                                                                                   | 398921000210105 |
| New Zealand AJCC 9th edition female genital vulva clinical N category reference set                                                                                       | 398911000210100 |
| New Zealand AJCC 9th edition female genital vulva pathological T category reference set                                                                                   | 398901000210102 |
| New Zealand AJCC 9th edition female genital vulva clinical T category reference set                                                                                       | 398891000210103 |
| New Zealand AJCC 8th edition thoracic thymus clinical T category reference set                                                                                            | 297341000210105 |
| New Zealand AJCC 8th edition thoracic thymus pathological T category reference set                                                                                        | 297371000210100 |
| New Zealand AJCC 8th edition thoracic thymus stage group reference set                                                                                                    | 297311000210109 |
| New Zealand AJCC 8th edition thoracic lung stage group reference set                                                                                                      | 297321000210104 |
| New Zealand AJCC 8th edition thoracic malignant pleural mesothelioma clinical T category reference set                                                                    | 297361000210106 |
| New Zealand AJCC 8th edition thoracic malignant pleural mesothelioma pathological T category reference set                                                                | 297391000210101 |
| New Zealand AJCC 8th edition thoracic malignant pleural mesothelioma stage group reference set                                                                            | 297331000210102 |
| New Zealand AJCC 8th edition gastrointestinal stromal tumour clinical T category reference set                                                                            | 351141000210102 |
| New Zealand AJCC 8th edition gastrointestinal stromal tumour pathological T category reference set                                                                        | 351151000210104 |
| New Zealand AJCC 8th edition gastrointestinal stromal tumour gastric and omental stage group reference set                                                                | 351241000210106 |
| New Zealand AJCC 8th edition gastrointestinal stromal tumour small intestine and oesophageal and colon and rectum and mesenteric and peritoneal stage group reference set | 351251000210109 |
| New Zealand AJCC 8th edition breast clinical T category reference set                                                                                                     | 253491000210106 |
| New Zealand AJCC 8th edition breast pathological T category reference set                                                                                                 | 253511000210104 |
| New Zealand AJCC 8th edition breast clinical N category reference set                                                                                                     | 253531000210106 |
| New Zealand AJCC 8th edition breast pathological N category reference set                                                                                                 | 253551000210100 |
| New Zealand AJCC 8th edition breast stage group reference set                                                                                                             | 341021000210107 |
| New Zealand AJCC 8th edition female genital vulva clinical T category reference set                                                                                       | 331021000210108 |
| New Zealand AJCC 8th edition female genital vulva pathological T category reference set                                                                                   | 331151000210103 |
| New Zealand AJCC 8th edition female genital vulva clinical N category reference set                                                                                       | 331211000210109 |
| New Zealand AJCC 8th edition female genital vulva pathological N category reference set                                                                                   | 331331000210107 |
| New Zealand AJCC 8th edition female genital vulva stage group reference set                                                                                               | 330921000210102 |
| New Zealand AJCC 8th edition female genital vagina clinical T category reference set                                                                                      | 331011000210103 |
| New Zealand AJCC 8th edition female genital vagina pathological T category reference set                                                                                  | 331141000210101 |
| New Zealand AJCC 8th edition female genital vagina clinical N category reference set                                                                                      | 331201000210107 |
| New Zealand AJCC 8th edition female genital vagina pathological N category reference set                                                                                  | 331321000210105 |
| New Zealand AJCC 8th edition female genital vagina stage group reference set                                                                                              | 330911000210107 |
| New Zealand AJCC 8th edition female genital cervix uteri clinical T category reference set                                                                                | 331001000210100 |
| New Zealand AJCC 8th edition female genital cervix uteri pathological T category reference set                                                                            | 331131000210109 |
| New Zealand AJCC 8th edition female genital cervix uteri clinical N category reference set                                                                                | 331191000210105 |
| New Zealand AJCC 8th edition female genital cervix uteri pathological N category reference set                                                                            | 331311000210100 |
| New Zealand AJCC 8th edition female genital cervix uteri stage group reference set                                                                                        | 330901000210105 |
| New Zealand AJCC 8th edition female genital corpus uteri carcinoma and carcinosarcoma clinical T category reference set                                                   | 330961000210109 |
| New Zealand AJCC 8th edition female genital corpus uteri carcinoma and carcinosarcoma pathological T category reference set                                               | 331091000210106 |
| New Zealand AJCC 8th edition female genital corpus uteri carcinoma and carcinosarcoma clinical N category reference set                                                   | 331161000210100 |
| New Zealand AJCC 8th edition female genital corpus uteri carcinoma and carcinosarcoma pathological N category reference set                                               | 331281000210103 |
| New Zealand cancer modified Ryan tumour regression score reference set                                                                                                    | 351481000210103 |
| New Zealand cancer MD Anderson residual cancer burden class reference set                                                                                                 | 340921000210101 |
| New Zealand cancer Response Evaluation Criteria in Solid Tumours 1.1 reference set                                                                                        | 399061000210107 |
| New Zealand cancer Positron Emission Tomography Response Criteria in Solid Tumours 1.0 reference set                                                                      | 399051000210109 |
| New Zealand AJCC 8th edition gastrointestinal colon and rectum pathological T category reference set                                                                      | 332911000210106 |
| New Zealand AJCC 8th edition gastrointestinal colon and rectum clinical N category reference set                                                                          | 332921000210101 |
| New Zealand AJCC 8th edition gastrointestinal colon and rectum pathological N category reference set                                                                      | 332931000210104 |
| New Zealand AJCC 8th edition gastrointestinal colon and rectum clinical M category reference set                                                                          | 332941000210107 |
| New Zealand AJCC 8th edition gastrointestinal colon and rectum pathological M category reference set                                                                      | 332951000210105 |
| New Zealand AJCC 8th edition gastrointestinal colon and rectum stage group reference set                                                                                  | 351231000210103 |
| New Zealand AJCC 8th edition female genital gestational trophoblastic disease stage group reference set                                                                   | 330891000210109 |
| New Zealand AJCC 8th edition residual tumour category reference set                                                                                                       | 330721000210100 |
| New Zealand cancer ELN standardized reporting for genetic alteration in AML prognostic score reference set                                                                | 294821000210104 |
| New Zealand cancer CNS status in acute lymphoblastic leukaemia lymphoma prognostic score reference set                                                                    | 294831000210102 |
| New Zealand cancer IPSS-R for MDS prognostic score reference set                                                                                                          | 294841000210105 |
| New Zealand cancer IPSS-M for MDS prognostic score reference set                                                                                                          | 294851000210108 |
| New Zealand cancer International Prognostic Score for thrombosis in ET prognostic score reference set                                                                     | 294861000210106 |
| New Zealand cancer DIPSS+ for myelofibrosis prognostic score reference set                                                                                                | 294871000210100 |
| New Zealand cancer EUTOS prognostic score for CML prognostic score reference set                                                                                          | 294891000210101 |
| New Zealand cancer MIPI prognostic score reference set                                                                                                                    | 294901000210100 |
| New Zealand cancer FLIPI prognostic score reference set                                                                                                                   | 294911000210103 |
| New Zealand cancer IPI prognostic score reference set                                                                                                                     | 294921000210108 |
| New Zealand cancer BL-IPI prognostic score reference set                                                                                                                  | 294931000210105 |
| New Zealand cancer Sokal index for CML prognostic score reference set                                                                                                     | 294941000210102 |
| New Zealand cancer CNS-IPI for large B-cell lymphoma prognostic score reference set                                                                                       | 294951000210104 |
| New Zealand cancer IPSS for Waldenstrom Macroglobulinemia prognostic score reference set                                                                                  | 294961000210101 |
| New Zealand cancer IELSG (International Extranodal Lymphoma Study Group) prognostic score reference set                                                                   | 294971000210107 |
| New Zealand cancer PIT prognostic score reference set                                                                                                                     | 294981000210109 |
| New Zealand cancer Hodgkin lymphoma International Prognostic Score reference set                                                                                          | 294881000210103 |
| New Zealand cancer MIPSS 70+ v2.0 myelofibrosis prognostic score reference set                                                                                            | 380791000210108 |
| New Zealand cancer MIPSS 70 myelofibrosis prognostic score reference set                                                                                                  | 380801000210107 |
| New Zealand cancer MALT-IPI prognostic score reference set                                                                                                                | 380811000210109 |
| New Zealand cancer PINK-E prognostic score reference set                                                                                                                  | 380821000210104 |
| New Zealand cancer FIGO-modified WHO 2002 prognostic score reference set                                                                                                  | 341011000210102 |
| New Zealand AJCC 8th edition female genital corpus uteri carcinoma and carcinosarcoma stage group reference set                                                           | 330861000210104 |
| New Zealand AJCC 8th edition female genital corpus uteri leiomyosarcoma and endometrial stromal sarcoma clinical T category reference set                                 | 330971000210103 |
| New Zealand AJCC 8th edition female genital corpus uteri adenosarcoma clinical T category reference set                                                                   | 330981000210101 |
| New Zealand AJCC 8th edition female genital corpus uteri leiomyosarcoma and endometrial stromal sarcoma pathological T category reference set                             | 331101000210104 |
| New Zealand AJCC 8th edition female genital corpus uteri adenosarcoma pathological T category reference set                                                               | 331111000210102 |
| New Zealand AJCC 8th edition female genital corpus uteri leiomyosarcoma and endometrial stromal sarcoma clinical N category reference set                                 | 331171000210106 |
| New Zealand AJCC 8th edition female genital corpus uteri adenosarcoma clinical N category reference set                                                                   | 331181000210108 |
| New Zealand AJCC 8th edition female genital corpus uteri leiomyosarcoma and endometrial stromal sarcoma pathological N category reference set                             | 331291000210101 |
| New Zealand AJCC 8th edition female genital corpus uteri adenosarcoma pathological N category reference set                                                               | 331301000210102 |
| New Zealand AJCC 8th edition female genital corpus uteri leiomyosarcoma and endometrial stromal sarcoma stage group reference set                                         | 330871000210105 |
| New Zealand AJCC 8th edition female genital corpus uteri adenosarcoma stage group reference set                                                                           | 330881000210107 |
| New Zealand AJCC 8th edition female genital ovary and fallopian tube and primary peritoneal carcinoma clinical T category reference set                                   | 330941000210108 |
| New Zealand AJCC 8th edition female genital ovary and fallopian tube and primary peritoneal carcinoma pathological T category reference set                               | 331051000210104 |
| New Zealand AJCC 8th edition female genital ovary and fallopian tube and primary peritoneal carcinoma clinical N category reference set                                   | 331071000210107 |
| New Zealand AJCC 8th edition female genital ovary and fallopian tube and primary peritoneal carcinoma pathological N category reference set                               | 331241000210105 |
| New Zealand AJCC 8th edition female genital ovary and fallopian tube and primary peritoneal carcinoma stage group reference set                                           | 330841000210100 |
| New Zealand AJCC 8th edition female genital gestational trophoblastic disease clinical T category reference set                                                           | 330991000210104 |
| New Zealand AJCC 8th edition female genital gestational trophoblastic disease pathological T category reference set                                                       | 331121000210107 |
| New Zealand AJCC 8th edition neuroendocrine gastrointestinal colon and rectum clinical T category reference set                                                           | 332971000210102 |
| New Zealand AJCC 8th edition neuroendocrine gastrointestinal colon and rectum pathological T category reference set                                                       | 350741000210107 |
| New Zealand AJCC 8th edition neuroendocrine gastrointestinal colon and rectum clinical N category reference set                                                           | 332991000210103 |
| New Zealand AJCC 8th edition neuroendocrine gastrointestinal colon and rectum pathological N category reference set                                                       | 333041000210101 |
| New Zealand AJCC 8th edition neuroendocrine gastrointestinal colon and rectum clinical M category reference set                                                           | 333051000210103 |
| New Zealand AJCC 8th edition neuroendocrine gastrointestinal colon and rectum pathological M category reference set                                                       | 333061000210100 |
| New Zealand AJCC 8th edition neuroendocrine gastrointestinal colon and rectum stage group reference set                                                                   | 333071000210106 |
| New Zealand AJCC 8th edition haematology mycosis fungoides or sezary syndrome clinical T category reference set                                                           | 253571000210108 |
| New Zealand AJCC 8th edition haematology mycosis fungoides or sezary syndrome pathological T category reference set                                                       | 253591000210107 |
| New Zealand AJCC 8th edition haematology mycosis fungoides or sezary syndrome clinical N category reference set                                                           | 253611000210100 |
| New Zealand AJCC 8th edition haematology mycosis fungoides or sezary syndrome pathological N category reference set                                                       | 253631000210107 |
| New Zealand AJCC 8th edition haematology mycosis fungoides or sezary syndrome stage group reference set                                                                   | 253801000210103 |
| New Zealand AJCC 8th edition haematology paediatric non-Hodgkin lymphoma stage group reference set                                                                        | 253791000210102 |
| New Zealand AJCC 8th edition haematology Hodgkin or non-Hodgkin lymphoma stage group reference set                                                                        | 253761000210107 |
| New Zealand AJCC 8th edition haematology chronic lymphocytic leukaemia or small lymphocytic lymphoma stage group reference set                                            | 253771000210101 |
| New Zealand AJCC 8th edition haematology paediatric Hodgkin lymphoma stage group reference set                                                                            | 253781000210104 |
| New Zealand AJCC 8th edition haematology plasma cell myeloma stage group reference set                                                                                    | 253811000210101 |
| New Zealand AJCC 8th edition thoracic clinical T category reference set                                                                                                   | 297281000210106 |
| New Zealand AJCC 8th edition thoracic pathological T category reference set                                                                                               | 297291000210108 |
| New Zealand AJCC 8th edition thoracic clinical N category reference set                                                                                                   | 297301000210107 |
| New Zealand AJCC 8th edition thoracic pathological N category reference set                                                                                               | 297431000210108 |
| New Zealand AJCC 8th edition thoracic clinical M category reference set                                                                                                   | 297441000210100 |
| New Zealand AJCC 8th edition thoracic pathological M category reference set                                                                                               | 297451000210102 |
| New Zealand AJCC 8th edition thoracic stage group reference set                                                                                                           | 297271000210109 |
| New Zealand AJCC 8th edition gastrointestinal clinical T category reference set                                                                                           | 332801000210102 |
| New Zealand AJCC 8th edition gastrointestinal pathological T category reference set                                                                                       | 332811000210100 |
| New Zealand AJCC 8th edition gastrointestinal clinical N category reference set                                                                                           | 332821000210105 |
| New Zealand AJCC 8th edition gastrointestinal pathological N category reference set                                                                                       | 332831000210107 |
| New Zealand AJCC 8th edition gastrointestinal clinical M category reference set                                                                                           | 332841000210104 |
| New Zealand AJCC 8th edition gastrointestinal pathological M category reference set                                                                                       | 332851000210101 |
| New Zealand AJCC 8th edition gastrointestinal clinical stage group reference set                                                                                          | 351201000210108 |
| New Zealand AJCC 8th edition gastrointestinal pathological stage group reference set                                                                                      | 351211000210105 |
| New Zealand AJCC 8th edition gastrointestinal post therapy or post neoadjuvant therapy pathological stage group reference set                                             | 351221000210100 |
| New Zealand AJCC 8th edition neuroendocrine gastrointestinal clinical T category reference set                                                                            | 332871000210109 |
| New Zealand AJCC 8th edition neuroendocrine gastrointestinal pathological T category reference set                                                                        | 332881000210106 |
| New Zealand AJCC 8th edition neuroendocrine gastrointestinal clinical N category reference set                                                                            | 332891000210108 |
| New Zealand AJCC 8th edition neuroendocrine gastrointestinal pathological N category reference set                                                                        | 333001000210104 |
| New Zealand AJCC 8th edition neuroendocrine gastrointestinal clinical M category reference set                                                                            | 333011000210102 |
| New Zealand AJCC 8th edition neuroendocrine gastrointestinal pathological M category reference set                                                                        | 333021000210107 |
| New Zealand AJCC 8th edition neuroendocrine gastrointestinal stage group reference set                                                                                    | 333031000210109 |
| New Zealand AJCC 8th edition haematology clinical T category reference set                                                                                                | 253501000210101 |
| New Zealand AJCC 8th edition haematology pathological T category reference set                                                                                            | 253521000210109 |
| New Zealand AJCC 8th edition haematology clinical N category reference set                                                                                                | 253541000210103 |
| New Zealand AJCC 8th edition haematology pathological N category reference set                                                                                            | 253561000210102 |
| New Zealand AJCC 8th edition haematology stage group reference set                                                                                                        | 263581000210104 |
| New Zealand AJCC 8th edition female genital clinical T category reference set                                                                                             | 330931000210100 |
| New Zealand AJCC 8th edition female genital corpus uteri clinical T category reference set                                                                                | 330951000210106 |
| New Zealand AJCC 8th edition female genital pathological T category reference set                                                                                         | 331031000210105 |
| New Zealand AJCC 8th edition female genital corpus uteri pathological T category reference set                                                                            | 331061000210101 |
| New Zealand AJCC 8th edition female genital clinical N category reference set                                                                                             | 331041000210102 |
| New Zealand AJCC 8th edition female genital corpus uteri clinical N category reference set                                                                                | 331081000210109 |
| New Zealand AJCC 8th edition female genital pathological N category reference set                                                                                         | 331221000210104 |
| New Zealand AJCC 8th edition female genital corpus uteri pathological N category reference set                                                                            | 331251000210108 |
| New Zealand AJCC 8th edition female genital stage group reference set                                                                                                     | 330831000210108 |
| New Zealand AJCC 8th edition female genital corpus uteri stage group reference set                                                                                        | 330851000210102 |
| New Zealand AJCC 9th edition female genital clinical T category reference set                                                                                             | 331571000210103 |
| New Zealand AJCC 9th edition female genital pathological T category reference set                                                                                         | 331581000210101 |
| New Zealand AJCC 9th edition female genital clinical N category reference set                                                                                             | 331591000210104 |
| New Zealand AJCC 9th edition female genital pathological N category reference set                                                                                         | 331651000210105 |
| New Zealand AJCC 9th edition female genital stage group reference set                                                                                                     | 331681000210100 |
| New Zealand cancer medical oncology treatment intent reference set                                                                                                        | 253861000210104 |
| New Zealand cancer haematology treatment intent reference set                                                                                                             | 253871000210105 |

#### &#x20;Language reference sets

Language reference sets are created to define preferred terms and synonyms associated with each concept. There are 4 language reference sets in the October 2025 release.

#### Maps

5 maps between SNOMED CT and other code systems are contained in the October 2025 release.

## Technical notes

### Known issues&#x20;

Known issues are content or technical issues where the root cause is understood and the resolution has been discussed and agreed but has yet to be implemented. This can be due to a number of reasons, from lack of capacity within the current editing cycle, to the risk of impact to the stability of SNOMED CT if the fix were to be deployed at that stage in the product lifecycle.

The following known issues were identified, and agreed to be resolved in the next editing cycle:

### Notice of changes to the International Edition release schedule

The SNOMED CT International Edition has moved to a monthly release cycle. These more frequent releases of SNOMED CT will realize several benefits, including:

* The potential to be able to get content changes into the terminology in a shorter time frame.
* The fostering of better interoperability, as a result of entities being able to consume release content that is more aligned with other organizations.
* The prevention of circular dependencies that occur in longer projects, due to the move towards smaller, more manageable authoring projects.
* More automated validation services, as a result of the inherent removal of the Alpha/Beta stages in the Release cycle.

Whilst most users will continue unaffected (as they can simply continue to download the releases every 6 months as always), this transition will necessarily involve a few changes to process/packages:

* **Delta files have been removed from releases of the SNOMED CT International Edition and SNOMED NZ Extension.** A Delta Generation service will be provided for those who need it. The Delta Generation Tool allows users to create their own Delta between two fixed release dates - you can find it here:
  * [https://github.com/IHTSDO/delta-generator-tool/releases](https://github.com/IHTSDO/delta-generator-tool/releases)
* The ICD-O/ICD-10 Maps will continue to be published in each Monthly International Edition release package (in line with that month's content) for the foreseeable future, unless we experience issues with the new process in Production, and they need to be removed at a later date.

The first monthly Release of the SNOMED CT International Edition was published on the 28th February 2022 with the Delta files having been removed, and therefore they will be removed from the New Zealand Extension from the April 2022 Release onwards.

**Please note** - While the SNOMED CT International Edition is moving to monthly releases, the New Zealand Extension of SNOMED CT will remain on the current bi-annual release schedule of April and October for 2023.

### Notice of changes to the NZ Extension Release package

The New Zealand NRC has decided to extend the standard International DescriptionType specification, which currently restricts Description term lengths to 255 characters. The New Zealand Extension from April 2024 onwards, now specifies term lengths can be created up to 4096 characters.

This means that users wanting to utilise New Zealand Extension Descriptions, should use the specialised New Zealand DescriptionType.

***

**Approvals**

| **Final Version** | **Date** | **Approver**       | **Comments** |
| ----------------- | -------- | ------------------ | ------------ |
| 1.0               |          | Lea Miharsa        | Reviewed     |
| 1.0               |          | Alastair Kenworthy | Approved     |

***

**Draft Amendment History**

| **Version** | **Date** | **Editor**         | **Comments**          |
| ----------- | -------- | ------------------ | --------------------- |
| 0.1         |          | Andrew Atkinson    | Initial draft created |
| 0.2         |          | Lea Miharsa        | Reviewed              |
| 1.0         |          | Alastair Kenworthy | Final updates         |
