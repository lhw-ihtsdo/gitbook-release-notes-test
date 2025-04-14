# SNOMED CT New Zealand Extension PRODUCTION Release Notes - April 2025

| **Date**             | **20250401**                                                          |
| -------------------- | --------------------------------------------------------------------- |
| **Document Version** | **1.0**                                                               |
| **Release Status**   | <mark style="color:blue;background-color:blue;">**PRODUCTION**</mark> |

© 2025 International Health Terminology Standards Development Organisation. All rights reserved. SNOMED CT® was originally created by the College of American Pathologists.

This document forms part of the SNOMED CT® New Zealand Extension release distributed by International Health Terminology Standards Development Organisation, trading as SNOMED International, and is subject to the SNOMED CT® Affiliate License, details of which may be found at [https://www.snomed.org/snomed-ct/get-snomed](http://www.snomed.org/snomed-ct/get-snomed)

No part of this document may be reproduced or transmitted in any form or by any means, or stored in any kind of retrieval system, except by an Affiliate of SNOMED International in accordance with the SNOMED CT® Affiliate License. Any modification of this document (including without limitation the removal or modification of this notice) is prohibited without the express written permission of SNOMED International.

Any copy of this document that is not obtained directly from SNOMED International \[or a Member of SNOMED International] is not controlled by SNOMED International, and may have been modified and may be out of date. Any recipient of this document who has received it by other means is encouraged to obtain a copy directly from SNOMED International \[or a Member of SNOMED International. Details of the Members of SNOMED International may be found at [http://www.snomed.org/members/](http://www.snomed.org/members/)].

***

![](.gitbook/assets/278299358.png)

## Introduction <a href="#snomedctnewzealandextensionproductionreleasenotesapril2025-introduction" id="snomedctnewzealandextensionproductionreleasenotesapril2025-introduction"></a>

![](.gitbook/assets/278299346.jpg)

Health New Zealand | Te Whatu Ora works with health agencies and their industry partners to develop SNOMED CT® reference sets, maps, language reference sets and other content for digital health solutions in Aotearoa New Zealand.

The SNOMED CT New Zealand Extension packages these components for release every April and October, to be used with the latest designated SNOMED CT International Edition release.

The content can be downloaded from our [member licensing and distribution service](https://mlds.ihtsdotools.org/#/landing/NZ?lang=en), viewed online using the [SNOMED CT browser](https://browser.ihtsdotools.org/) or accessed via a standard FHIR® API using the [NZ Health Terminology Service](https://www.tewhatuora.govt.nz/health-services-and-programmes/digital-health/terminology-service).

We welcome your feedback and participation. For more information about SNOMED CT implementation in New Zealand, email [standards@tewhatuora.govt.nz](mailto:standards@tewhatuora.govt.nz), visit our [website](https://www.tewhatuora.govt.nz/health-services-and-programmes/digital-health/snomed-ct-national-release-centre) or join the standards channel at [ehealthforum.nz](https://ehealthforum.nz).

## Background <a href="#snomedctnewzealandextensionproductionreleasenotesapril2025-background" id="snomedctnewzealandextensionproductionreleasenotesapril2025-background"></a>

This document summarises the content changes included in the April 2025 production release of the SNOMED NZ Extension package.

It also includes technical notes detailing any known issues.

This SNOMED NZ Extension package is dependent upon and should therefore be consumed in conjunction with the SNOMED CT International Edition February 2025 release.

## New and updated content <a href="#snomedctnewzealandextensionproductionreleasenotesapril2025-newandupdatedcontent" id="snomedctnewzealandextensionproductionreleasenotesapril2025-newandupdatedcontent"></a>

### The April 2025 release includes updates to the previously released content in the SNOMED NZ Extension and introduces some new content. <a href="#snomedctnewzealandextensionproductionreleasenotesapril2025-theapril2025releaseincludesupdatestothepr" id="snomedctnewzealandextensionproductionreleasenotesapril2025-theapril2025releaseincludesupdatestothepr"></a>

This release includes new content in the following areas.

#### Gambling harm intervention reference set <a href="#snomedctnewzealandextensionproductionreleasenotesapril2025-gamblingharminterventionreferenceset" id="snomedctnewzealandextensionproductionreleasenotesapril2025-gamblingharminterventionreferenceset"></a>

This reference set has been developed to support the collection and reporting of gambling harm intervention data as specified by draft standard [HISO 10112:2025 Gambling Harm Intervention Data Standard](https://www.tewhatuora.govt.nz/corporate-information/consultations/current-consultations/hiso-101122025-gambling-harm-intervention-data-standard).

#### **Health service type reference set** <a href="#snomedctnewzealandextensionproductionreleasenotesapril2025-healthservicetypereferenceset" id="snomedctnewzealandextensionproductionreleasenotesapril2025-healthservicetypereferenceset"></a>

This reference set has been updated in partnership with Healthpoint to extend the SNOMED CT content available for the health directory services used by consumers, health professionals and helplines.

#### Patient friendly terms <a href="#snomedctnewzealandextensionproductionreleasenotesapril2025-patientfriendlyterms" id="snomedctnewzealandextensionproductionreleasenotesapril2025-patientfriendlyterms"></a>

The set of patient friendly terms in NZ English and Te Reo Māori for health service types has been further extended in partnership with Healthpoint and Te Taura Whiri i te Reo Māori | Māori Language Commission.

#### **Emergency care reference sets** <a href="#snomedctnewzealandextensionproductionreleasenotesapril2025-emergencycarereferencesets" id="snomedctnewzealandextensionproductionreleasenotesapril2025-emergencycarereferencesets"></a>

The chief presenting complaint and diagnosis reference sets have been updated as a result of the latest six-monthly review in February 2025.

#### CanShare reference sets <a href="#snomedctnewzealandextensionproductionreleasenotesapril2025-cansharereferencesets" id="snomedctnewzealandextensionproductionreleasenotesapril2025-cansharereferencesets"></a>

Te Aho o Te Kahu | Cancer Control Agency has developed a collection of CanShare reference sets for New Zealand and this content has been further extended in this release. These reference sets provide standard sets of SNOMED CT concepts to use for recording, sharing and querying cancer data in Aotearoa. Each concept in these reference sets has a preferred term in the CanShare language reference set (SCTID 231621000210105), selected by New Zealand clinicians to standardise the way that cancer data is displayed . These reference sets support a range of cancer data, including key diagnostic components, treatment plans, national registers and screening programmes.

The April 2025 release includes 53 new CanShare reference sets, 115 updated reference sets, 459 static reference sets and 443 new concepts in the following areas:

* **Cancer streams, sub-streams and primary cancer types** to support clinical workflows for medical oncology and haematology.
* **Topographies** for recording the primary site of a cancer. This includes a maximal set of body sites, a high-level set of commonly used body sites, and body sites specific to breast, thoracic, gastrointestinal, female genital, genitourinary, soft tissue & bone, skin, head & neck, central nervous system, endocrine & neuroendocrine, and eye cancers.
* **Lymph nodes** for recording a lymph node site (for pathology or surgery) for breast, thoracic, gastrointestinal, female genital, genitourinary, head & neck, and eye cancers.
* **Cancer histologies** for haematologic, breast, thoracic, gastrointestinal, female genital, genitourinary, soft tissue & bone, skin, head & neck, central nervous system, endocrine & neuroendocrine, eye, and paediatric (new) cancers, based on the WHO Classification of Tumours 5th edition.
* **Grading systems** for haematology and solid (new) cancers.
* **Staging systems (AJCC and non AJCC)** for haematology and solid (new) cancers, including clinical, pathological, and a subset of recurrence or retreatment, and post therapy or post neoadjuvant therapy staging.
* **Prognostic scoring systems** for haematology, female genital, and genitourinary (new) cancers.
* **Neoadjuvant therapy response scoring systems** for breast, colorectal, and female genital cancers.
* **Specimen collection procedures and specimens** to support all cancer types.
* **Ancillary study tests and results** for a wide range of cancers, to support testing eligibility for new cancer medicines (new), as well as breast and colorectal (new) cancers.
* **Additional data** to support radiation oncology and systemic anti-cancer therapy treatment plans, radiation oncology waitlist data (new) and national screening programmes eg, national cervical screening programme (new).

#### **Systemic anti-cancer therapy regimens** <a href="#snomedctnewzealandextensionproductionreleasenotesapril2025-systemicanti-cancertherapyregimens" id="snomedctnewzealandextensionproductionreleasenotesapril2025-systemicanti-cancertherapyregimens"></a>

Further concepts representing systemic anti-cancer therapy regimens have been added to support the CanShare programme.

#### **Other changes** <a href="#snomedctnewzealandextensionproductionreleasenotesapril2025-otherchanges" id="snomedctnewzealandextensionproductionreleasenotesapril2025-otherchanges"></a>

Fifteen reference sets have been updated to replace inactive concepts with the active concepts.

## Release statistics <a href="#snomedctnewzealandextensionproductionreleasenotesapril2025-releasestatistics" id="snomedctnewzealandextensionproductionreleasenotesapril2025-releasestatistics"></a>

#### Concept statistics <a href="#snomedctnewzealandextensionproductionreleasenotesapril2025-conceptstatistics" id="snomedctnewzealandextensionproductionreleasenotesapril2025-conceptstatistics"></a>

Requests from the SNOMED NZ National Release Centre to SNOMED International have resulted in the promotion of one new concept into the International Edition between October 2024 and February 2025.

_Table 1. New concepts in the SNOMED International Edition February 2025 release by hierarchy_

| **Total number of concepts**       | 1 |
| ---------------------------------- | - |
| Staging and scales (staging scale) | 1 |

There are 549 new concepts added to SNOMED NZ Extension April 2025 release.

_Table 2. New concepts in the SNOMED NZ Extension April 2025 release by hierarchy_

| **Total number of concepts**                                | 549 |
| ----------------------------------------------------------- | --- |
| Body structure (body structure)                             | 90  |
| Clinical finding (finding)                                  | 145 |
| Environment or geographical location (environment/location) | 5   |
| Observable entity (observable entity)                       | 104 |
| Physical object (physical object)                           | 1   |
| Procedure (procedure)                                       | 26  |
| Qualifier value (qualifier value)                           | 79  |
| Record artifact (record artifact)                           | 2   |
| SNOMED CT Model Component (metadata)                        | 55  |
| Social context (social concept)                             | 1   |
| Specimen (specimen)                                         | 6   |
| Staging and scales (staging scale)                          | 32  |
| Substance (substance)                                       | 3   |

#### Description statistics <a href="#snomedctnewzealandextensionproductionreleasenotesapril2025-descriptionstatistics" id="snomedctnewzealandextensionproductionreleasenotesapril2025-descriptionstatistics"></a>

There are 2121 new descriptions added to our April 2025 release.

For a statistical breakdown of the content of the SNOMED NZ Extension and the April 2025 release please visit [release statistics site](https://browser.ihtsdotools.org/qa/#/SNOMEDCT-NZ/descriptive-statistics).

Reference sets

There are 731 reference sets in the April 2025 release including 54 new reference sets.

For more information about New Zealand reference sets, please visit [our website](https://www.tewhatuora.govt.nz/health-services-and-programmes/digital-health/snomed-ct-national-release-centre).

You can access New Zealand reference sets without log-in by visiting [SNOMED CT Reference set Tool 2.0](https://rt2.ihtsdotools.org/library). Once there click on library in the top right-hand corner and then you can filter on New Zealand NRC in the organisation column and select the preferred reference set.

Please note due to licencing reasons only a simplified RF2 version or a list of ID's can be downloaded for unregistered users.

#### Deprecated and inactivated reference sets <a href="#snomedctnewzealandextensionproductionreleasenotesapril2025-deprecatedandinactivatedreferencesets" id="snomedctnewzealandextensionproductionreleasenotesapril2025-deprecatedandinactivatedreferencesets"></a>

88 reference sets have been removed from the April 2025 release, and 31 reference sets have been inactivated pending full deprecation in the October 2025 release.

_Table 3.1 Deprecated reference sets (These reference sets have been removed from the April 2025 release)_

| Reference set name                                                                                                                            | SCTID           |
| --------------------------------------------------------------------------------------------------------------------------------------------- | --------------- |
| New Zealand cancer female genital fallopian tube topography reference set                                                                     | 330801000210103 |
| New Zealand cancer laterality reference set                                                                                                   | 253241000210101 |
| New Zealand cancer soft tissue and bone substream reference set                                                                               | 302541000210109 |
| New Zealand cancer genitourinary substream reference set                                                                                      | 302961000210103 |
| New Zealand AJCC (8th edition) female genital pathological M category reference set                                                           | 331411000210108 |
| New Zealand AJCC (8th edition) female genital ovary and fallopian tube and primary peritoneal carcinoma pathological M category reference set | 331421000210103 |
| New Zealand AJCC (8th edition) female genital corpus uteri pathological M category reference set                                              | 331431000210101 |
| New Zealand AJCC (8th edition) female genital gestational trophoblastic disease pathological M category reference set                         | 331471000210104 |
| New Zealand AJCC (8th edition) female genital cervix uteri pathological M category reference set                                              | 331481000210102 |
| New Zealand AJCC (8th edition) female genital vagina pathological M category reference set                                                    | 331491000210100 |
| New Zealand AJCC (8th edition) female genital vulva pathological M category reference set                                                     | 331501000210105 |
| New Zealand AJCC (8th edition) female genital clinical M category reference set                                                               | 331231000210102 |
| New Zealand AJCC (8th edition) female genital ovary and fallopian tube and primary peritoneal carcinoma clinical M category reference set     | 331261000210106 |
| New Zealand AJCC (8th edition) female genital corpus uteri clinical M category reference set                                                  | 331271000210100 |
| New Zealand AJCC (8th edition) female genital gestational trophoblastic disease clinical M category reference set                             | 331371000210109 |
| New Zealand AJCC (8th edition) female genital cervix uteri clinical M category reference set                                                  | 331381000210106 |
| New Zealand AJCC (8th edition) female genital vagina clinical M category reference set                                                        | 331391000210108 |
| New Zealand AJCC (8th edition) female genital vulva clinical M category reference set                                                         | 331401000210106 |
| New Zealand AJCC (9th edition) female genital pathological M category reference set                                                           | 331671000210102 |
| New Zealand AJCC (9th edition) female genital cervix uteri pathological M category reference set                                              | 331711000210101 |
| New Zealand AJCC (9th edition) female genital cervix uteri clinical M category reference set                                                  | 331701000210103 |
| New Zealand AJCC (9th edition) female genital clinical M category reference set                                                               | 331661000210108 |
| New Zealand AJCC 8th edition breast pathological M category reference set                                                                     | 253721000210100 |
| New Zealand AJCC 8th edition breast clinical M category reference set                                                                         | 253701000210108 |
| New Zealand cancer neuroendocrine substream reference set                                                                                     | 302531000210101 |
| New Zealand cancer leukaemia substream reference set                                                                                          | 302591000210100 |
| New Zealand cancer lymphoma substream reference set                                                                                           | 302601000210105 |
| New Zealand cancer neuroendocrine cancer type reference set                                                                                   | 302661000210109 |
| New Zealand cancer indolent non-Hodgkin B cell lymphoma cancer type reference set                                                             | 351831000210104 |
| New Zealand cancer aggressive non-Hodgkin B cell lymphoma cancer type reference set                                                           | 351841000210107 |
| New Zealand WHO classification of tumours (5th edition) haematolymphoid indolent non-hodgkin B cell lymphoma histology reference set          | 350821000210107 |
| New Zealand WHO classification of tumours (5th edition) haematolymphoid aggressive non-hodgkin B cell lymphoma histology reference set        | 350831000210109 |
| New Zealand WHO classification of tumours (5th edition) haematolymphoid extranodal NK-cell and T-cell lymphoma histology reference set        | 297161000210109 |
| New Zealand AJCC 8th edition haematology pathological M category reference set                                                                | 253731000210103 |
| New Zealand AJCC 8th edition haematology mycosis fungoides or sezary syndrome pathological M category reference set                           | 253841000210100 |
| New Zealand AJCC 8th edition haematology primary cutaneous B-cell or T-cell (non-MF/SS) lymphoma pathological M category reference set        | 253851000210102 |
| New Zealand AJCC 8th edition haematology clinical M category reference set                                                                    | 253711000210105 |
| New Zealand AJCC 8th edition haematology mycosis fungoides or sezary syndrome clinical M category reference set                               | 253821000210106 |
| New Zealand AJCC 8th edition haematology primary cutaneous B-cell or T-cell (non-MF/SS) lymphoma clinical M category reference set            | 253831000210108 |
| New Zealand AJCC 8th edition gastrointestinal stromal tumour pathological M category reference set                                            | 351191000210106 |
| New Zealand AJCC 8th edition gastrointestinal stromal tumour clinical M category reference set                                                | 351181000210109 |
| New Zealand AJCC 8th edition gastrointestinal stromal tumour pathological N category reference set                                            | 351171000210107 |
| New Zealand AJCC 8th edition gastrointestinal stromal tumour clinical N category reference set                                                | 351161000210101 |
| New Zealand AJCC 8th edition thoracic malignant pleural mesothelioma pathological M category reference set                                    | 297541000210101 |
| New Zealand AJCC 8th edition thoracic malignant pleural mesothelioma clinical M category reference set                                        | 297511000210102 |
| New Zealand WHO classification of tumours (5th edition) haematolymphoid primary central nervous system lymphoma histology reference set       | 297211000210100 |
| New Zealand cancer unknown site topography reference set                                                                                      | 294711000210100 |
| New Zealand cancer gastrointestinal appendix topography reference set                                                                         | 332471000210106 |
| New Zealand cancer thorax thymus topography reference set                                                                                     | 296941000210108 |
| New Zealand cancer thorax pleura topography reference set                                                                                     | 296961000210109 |
| New Zealand SACT basis of diagnosis reference set                                                                                             | 253131000210102 |
| New Zealand cancer gastrointestinal substream reference set                                                                                   | 302511000210108 |
| New Zealand cancer skin and melanoma substream reference set                                                                                  | 302551000210107 |
| New Zealand cancer leukaemia cancer type reference set                                                                                        | 302741000210101 |
| New Zealand cancer acute leukaemia cancer type reference set                                                                                  | 302791000210105 |
| New Zealand cancer chronic leukaemia cancer type reference set                                                                                | 302801000210109 |
| New Zealand cancer lymphoma cancer type reference set                                                                                         | 302731000210109 |
| New Zealand cancer B cell lymphoma cancer type reference set                                                                                  | 302771000210106 |
| New Zealand cancer T/NK cell lymphoma cancer type reference set                                                                               | 302811000210106 |
| New Zealand cancer non Hodgkin lymphoma cancer type reference set                                                                             | 302821000210101 |
| New Zealand cancer endocrine and neuroendocrine substream reference set                                                                       | 302521000210103 |
| New Zealand cancer T/NK cell lymphoid substream reference set                                                                                 | 302581000210102 |
| New Zealand WHO classification of tumours (5th edition) haematolymphoid essential thrombocythaemia histology reference set                    | 297061000210108 |
| New Zealand WHO classification of tumours (5th edition) haematolymphoid polycythaemia vera histology reference set                            | 297051000210105 |
| New Zealand WHO classification of tumours (5th edition) haematolymphoid chronic myeloid leukaemia histology reference set                     | 297011000210106 |
| New Zealand cancer histiocytic and dendritic cell cancer type reference set                                                                   | 351821000210101 |
| New Zealand cancer upper gastrointestinal cancer type reference set                                                                           | 302701000210104 |
| New Zealand cancer hepatopancreaticobiliary cancer type reference set                                                                         | 302841000210107 |
| New Zealand WHO classification of tumours (5th edition) haematolymphoid lymphoplasmacytic lymphoma histology reference set                    | 297251000210101 |
| New Zealand AJCC 8th edition thoracic thymus clinical N category reference set                                                                | 297401000210103 |
| New Zealand AJCC 8th edition thoracic lung clinical T category reference set                                                                  | 297351000210108 |
| New Zealand AJCC 8th edition thoracic lung pathological T category reference set                                                              | 297381000210103 |
| New Zealand AJCC 8th edition thoracic lung clinical N category reference set                                                                  | 297411000210101 |
| New Zealand AJCC 8th edition thoracic malignant pleural mesothelioma clinical N category reference set                                        | 297421000210106 |
| New Zealand AJCC 8th edition thoracic thymus pathological N category reference set                                                            | 297461000210104 |
| New Zealand AJCC 8th edition thoracic lung pathological N category reference set                                                              | 297471000210105 |
| New Zealand AJCC 8th edition thoracic malignant pleural mesothelioma pathological N category reference set                                    | 297481000210107 |
| New Zealand AJCC 8th edition thoracic thymus clinical M category reference set                                                                | 297491000210109 |
| New Zealand AJCC 8th edition thoracic lung clinical M category reference set                                                                  | 297501000210104 |
| New Zealand cancer gastrointestinal ileum and jejunum topography reference set                                                                | 332461000210100 |
| New Zealand cancer plasma cell cancer type reference set                                                                                      | 302781000210108 |
| New Zealand WHO classification of tumours (5th edition) haematolymphoid myeloid precursor lesion histology reference set                      | 350781000210100 |
| New Zealand cancer thoracic cancer type reference set                                                                                         | 302951000210101 |
| New Zealand WHO classification of tumours (5th edition) haematolymphoid primary myelofibrosis histology reference set                         | 297131000210100 |
| New Zealand WHO classification of tumours (5th edition) haematolymphoid Burkitt lymphoma histology reference set                              | 297201000210102 |
| New Zealand WHO classification of tumours (5th edition) haematolymphoid amyloidosis histology reference set                                   | 297121000210102 |
| New Zealand AJCC 8th edition thoracic lung pathological M category reference set                                                              | 297531000210109 |
| New Zealand AJCC 8th edition thoracic thymus pathological M category reference set                                                            | 297521000210107 |

_Table 3.2 Inactivated reference sets (These reference sets have been inactivated and will be removed in the October 2025 release)_\\

| Reference set name                                                                                                                                                                 | SCTID           |
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

#### Language reference sets <a href="#snomedctnewzealandextensionproductionreleasenotesapril2025-languagereferencesets" id="snomedctnewzealandextensionproductionreleasenotesapril2025-languagereferencesets"></a>

Language reference sets are created to define preferred terms and synonyms associated with each concept. There are four language reference sets in the April 2025 release.

| **Language reference set name**                                                                                            | **SCTID**                      | **Members** |
| -------------------------------------------------------------------------------------------------------------------------- | ------------------------------ | ----------- |
| Māori \[International Organization for Standardization 639-1 code mi] language reference set (foundation metadata concept) | <p>291000210106</p><p><br></p> | 561         |
| New Zealand English language reference set (foundation metadata concept)                                                   | <p>271000210107</p><p><br></p> | 1336326     |
| New Zealand English patient friendly terms language reference set (foundation metadata concept)                            | <p>281000210109</p><p><br></p> | 711         |
| New Zealand CanShare context language reference set (foundation metadata concept)                                          | 231621000210105                | 8060        |

#### Maps <a href="#snomedctnewzealandextensionproductionreleasenotesapril2025-maps" id="snomedctnewzealandextensionproductionreleasenotesapril2025-maps"></a>

Five maps between SNOMED CT and other code systems are contained in the April 2025 release.

| Map name                                                              | SCTID        | Members |
| --------------------------------------------------------------------- | ------------ | ------- |
| ACC translation table map (foundation metadata concept)               | 401000210101 | 12794   |
| MSD translation table map (foundation metadata concept)               | 411000210104 | 58170   |
| NZMT medicinal product to SNOMED CT map (foundation metadata concept) | 311000210107 | 2125    |
| READ v2 to SNOMED CT map (foundation metadata concept)                | 31000210106  | 88280   |
| SNOMED CT to READ v2 map (foundation metadata concept)                | 41000210103  | 66968   |

## Technical notes <a href="#snomedctnewzealandextensionproductionreleasenotesapril2025-technicalnotes" id="snomedctnewzealandextensionproductionreleasenotesapril2025-technicalnotes"></a>

### Known issues <a href="#snomedctnewzealandextensionproductionreleasenotesapril2025-knownissues" id="snomedctnewzealandextensionproductionreleasenotesapril2025-knownissues"></a>

Known issues are content or technical issues where the root cause is understood and the resolution has been discussed and agreed but has yet to be implemented. This can be due to a number of reasons, from lack of capacity within the current editing cycle, to the risk of impact to the stability of SNOMED CT if the fix were to be deployed at that stage in the product lifecycle.

The following known issues were identified, and agreed to be resolved in the next editing cycle:

| Key                                                                      | Summary                                                                                                                                                                              | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | P                                                                                   |
| ------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| [ISRS-7239](https://jira.ihtsdotools.org/browse/ISRS-7239?src=confmacro) | [SNOMED CT New Zealand Extension releases, 2025-04-01, SQL, 3cb10511-33b7-4eca-ba0e-93bcccf70d86, 2025-03-13T17:44:28](https://jira.ihtsdotools.org/browse/ISRS-7239?src=confmacro)  | <p>There is a 1:1 relationship between the id and the key values in the simple map refset snapshot.<br>Total number of failures: 10<br>Report URL: <a href="https://prod-rvf.ihtsdotools.org/api/result/1741889101767?storageLocation=nz/snomed_ct_nz_releases/2025-03-13T17:44:28">https://prod-rvf.ihtsdotools.org/api/result/1741889101767?storageLocation=nz/snomed_ct_nz_releases/2025-03-13T17:44:28</a><br>First 10 failures:</p><ul><li>{ "conceptId": "87628006", "conceptFsn": null, "detail": "referencedcomponentId:87628006 refsetId:31000210106 mapTarget:A3BX.00 are duplicated in the simple map fefset snapshot file.", "componentId": "c774792c-5514-11ea-b44c-6f151e555197", "fullComponent": "1,21000210109,31000210106,87628006,A3BX.00..." }</li><li>{ "conceptId": "123536004", "conceptFsn": null, "detail": "referencedcomponentId:123536004 refsetId:31000210106 mapTarget:S50X.00 are duplicated in the simple map fefset snapshot file.", "componentId": "c77b6340-5514-11ea-b44c-6f151e555197", "fullComponent": "1,21000210109,31000210106,123536004,S50X.00..." }</li><li>{ "conceptId": "129135003", "conceptFsn": null, "detail": "referencedcomponentId:129135003 refsetId:31000210106 mapTarget:SJ5X.00 are duplicated in the simple map fefset snapshot file.", "componentId": "c77d1b7c-5514-11ea-b44c-6f151e555197", "fullComponent": "1,21000210109,31000210106,129135003,SJ5X.00..." }</li><li>{ "conceptId": "129136002", "conceptFsn": null, "detail": "referencedcomponentId:129136002 refsetId:31000210106 mapTarget:SJ6X.00 are duplicated in the simple map fefset snapshot file.", "componentId": "c77d2036-5514-11ea-b44c-6f151e555197", "fullComponent": "1,21000210109,31000210106,129136002,SJ6X.00..." }</li><li>{ "conceptId": "313222007", "conceptFsn": null, "detail": "referencedcomponentId:313222007 refsetId:31000210106 mapTarget:339R.00 are duplicated in the simple map fefset snapshot file.", "componentId": "c7d26370-5514-11ea-b44c-6f151e555197", "fullComponent": "1,21000210109,31000210106,313222007,339R.00..." }</li><li>{ "conceptId": "44054006", "conceptFsn": null, "detail": "referencedcomponentId:44054006 refsetId:411000210104 mapTarget:C10F.00 are duplicated in the simple map fefset snapshot file.", "componentId": "c8801948-5514-11ea-b44c-6f151e555197", "fullComponent": "1,21000210109,411000210104,44054006,C10F.00..." }</li><li>{ "conceptId": "231478008", "conceptFsn": null, "detail": "referencedcomponentId:231478008 refsetId:411000210104 mapTarget:E240.12 are duplicated in the simple map fefset snapshot file.", "componentId": "b4b991b4-2fa6-4107-bd9e-e69193867121", "fullComponent": "1,21000210109,411000210104,231478008,E240.12..." }</li><li>{ "conceptId": "310497006", "conceptFsn": null, "detail": "referencedcomponentId:310497006 refsetId:411000210104 mapTarget:Eu32600 are duplicated in the simple map fefset snapshot file.", "componentId": "b1a9b0c2-3df7-46ff-8e39-860535be5f75", "fullComponent": "1,21000210109,411000210104,310497006,Eu32600..." }</li><li>{ "conceptId": "371081002", "conceptFsn": null, "detail": "referencedcomponentId:371081002 refsetId:411000210104 mapTarget:N06z611 are duplicated in the simple map fefset snapshot file.", "componentId": "c8ceeabe-5514-11ea-b44c-6f151e555197", "fullComponent": "1,21000210109,411000210104,371081002,N06z611..." }</li><li>{ "conceptId": "387800004", "conceptFsn": null, "detail": "referencedcomponentId:387800004 refsetId:411000210104 mapTarget:N11E.00 are duplicated in the simple map fefset snapshot file.", "componentId": "c8cf9248-5514-11ea-b44c-6f151e555197", "fullComponent": "1,21000210109,411000210104,387800004,N11E.00..." }</li></ul><p>KNOWN ISSUE: These are historical issues with 5 duplicate maps added in the October 2024 release, that the NZ NRC will work on fixing in future editing cycles.</p> | ![Major / Medium](https://jira.ihtsdotools.org/secure/attachment/18970/Linea_3.png) |
| [ISRS-7238](https://jira.ihtsdotools.org/browse/ISRS-7238?src=confmacro) | [SNOMED CT New Zealand Extension releases, 2025-04-01, MRCM, 10463044-9762-48dd-b2f3-a9b66d18d5ec, 2025-03-13T17:44:28](https://jira.ihtsdotools.org/browse/ISRS-7238?src=confmacro) | INFERRED FORM: 370130000                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Property (attribute)                                                                |
| [ISRS-7234](https://jira.ihtsdotools.org/browse/ISRS-7234?src=confmacro) | [SNOMED CT New Zealand Extension releases, 2025-04-01, MRCM, d64f229c-4721-4fba-b71c-12bf49e13013, 2025-03-13T17:44:28](https://jira.ihtsdotools.org/browse/ISRS-7234?src=confmacro) | INFERRED FORM: 370132008                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Scale type (attribute)                                                              |
| [ISRS-7230](https://jira.ihtsdotools.org/browse/ISRS-7230?src=confmacro) | [SNOMED CT New Zealand Extension releases, 2025-04-01, MRCM, abeccf84-0af3-41be-87a2-335a3bf24c62, 2025-03-13T17:44:28](https://jira.ihtsdotools.org/browse/ISRS-7230?src=confmacro) | INFERRED FORM: 370134009                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Time aspect (attribute)                                                             |

[4 issues](https://jira.ihtsdotools.org/secure/IssueNavigator.jspa?reset=true\&jqlQuery=filter+%3D+%22MS+%28NZ%29+20250401+-+Known+Issues+%28On+Hold%29%22+++++++++++++++++\&src=confmacro)

### Notice of changes to the International Edition release schedule <a href="#snomedctnewzealandextensionproductionreleasenotesapril2025-noticeofchangestotheinternationaleditionr" id="snomedctnewzealandextensionproductionreleasenotesapril2025-noticeofchangestotheinternationaleditionr"></a>

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

### Notice of changes to the NZ Extension Release package <a href="#snomedctnewzealandextensionproductionreleasenotesapril2025-noticeofchangestothenzextensionreleasepac" id="snomedctnewzealandextensionproductionreleasenotesapril2025-noticeofchangestothenzextensionreleasepac"></a>

The New Zealand NRC has decided to extend the standard International DescriptionType specification, which currently restricts Description term lengths to 255 characters. The New Zealand Extension from April 2024 onwards, now specifies term lengths can be created up to 4096 characters.

This means that users wanting to utilise New Zealand Extension Descriptions, should use the specialised New Zealand DescriptionType.

***

**Draft Amendment History**

| Version | Date        | Editor             | Comments              |
| ------- | ----------- | ------------------ | --------------------- |
| 0.1     | 03 Mar 2025 | Andrew Atkinson    | Initial draft created |
| 0.2     | 19 Mar 2025 | Lea Miharsa        | Reviewed              |
| 1.0     | 19 Mar 2025 | Alastair Kenworthy | Final draft           |

***

**Approvals**

| Final Version | Date        | Approver           | Comments |
| ------------- | ----------- | ------------------ | -------- |
| 0.1           | 19 Mar 2025 | Lea Miharsa        | Approved |
| 1.0           | 19 Mar 2025 | Alastair Kenworthy | Approved |
