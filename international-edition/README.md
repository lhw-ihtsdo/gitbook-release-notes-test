# SNOMED CT October 2025 International Edition

| **Release Date**     | **20251001**                                                          |
| -------------------- | --------------------------------------------------------------------- |
| **Release Status**   | <mark style="color:blue;background-color:blue;">**PRODUCTION**</mark> |
| **Document Version** | **1.0**                                                               |

© 2025 International Health Terminology Standards Development Organisation.  All rights reserved.  SNOMED CT® was originally created by the College of American Pathologists.

This document forms part of the International Edition release of SNOMED CT® distributed by International Health Terminology Standards Development Organisation, trading as SNOMED International, and is subject to the SNOMED CT® Affiliate License, details of which may be found at

[Get SNOMED CT | SNOMED International](https://www.snomed.org/get-snomed)

No part of this document may be reproduced or transmitted in any form or by any means, or stored in any kind of retrieval system, except by an Affiliate of SNOMED International in accordance with the SNOMED CT® Affiliate License. Any modification of this document (including without limitation the removal or modification of this notice) is prohibited without the express written permission of SNOMED International.

Any copy of this document that is not obtained directly from SNOMED International \[or a Member of SNOMED International] is not controlled by SNOMED International, and may have been modified and may be out of date. Any recipient of this document who has received it by other means is encouraged to obtain a copy directly from SNOMED International \[or a Member of SNOMED International. Details of the Members of SNOMED International may be found at [http://www.snomed.org/members/](http://www.snomed.org/members/)].

***

## ![](.gitbook/assets/273515526.png) <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-introduction" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-introduction"></a>

## Introduction

### Background

SNOMED CT provides a common language that enables a consistent way of indexing, storing, retrieving, and aggregating clinical data across specialties and sites of care.

SNOMED International maintains the SNOMED CT technical design, the content architecture, the SNOMED CT content (includes the concepts table, the descriptions table, the relationships table, a history table, and ICD mappings), and related technical documentation.

### Purpose

This document provides a summarized description of the content changes included in the October 2025 release of SNOMED Clinical Terms<sup>®</sup> (SCT) International Edition.

It also includes notes detailing the known content or technical issues where the root cause is understood, the fix has been discussed and agreed to, but has yet to be implemented.

The SNOMED International release notes are available alongside the October 2025 International Edition.

### Scope

This document is written for the purpose described above and is not intended to provide details of the technical specifications for SNOMED CT or encompass every change made.

### Audience

The audience includes National Release Centers, WHO-FIC release centers, vendors of electronic health records, terminology developers and managers who wish to have an understanding of changes that have been incorporated into the October 2025 International Edition.

_**Please note, you may have to register for a Confluence user account in order to access the links included in these release notes.**_

## Content Development Activity

### Summary

Continuous quality improvement and enhancement of existing content is an ongoing process undertaken by SNOMED International in preparation for every release. The October 2025 International Edition has seen a continuation of the work driven by contributions from: Kaiser Permanente i.e. Convergent Medical Terminology (CMT), Global Medical Device Nomenclature Agency (GMDNA), Orphanet and other domain specific collaborations as well as requests received via the Content Request System (CRS).&#x20;

Additionally quality improvement activities are advanced via project driven initiatives summarized below.  Additional work items impacting every release are updates to the SNOMED CT derived maps such as ICD-10 and ICD-O; details are included in these release notes. &#x20;

Information about editorial decisions may be found in the [SNOMED CT Editorial Guide](https://conf.spaces.snomed.org/wiki/spaces/DOCEG); mapping guidance for ICD-10 can be found [here.](https://docs.snomed.org/snomed-ct-specifications/snomed-ct-to-icd-10-map-specification/)

### Quality Initiative

The Quality Initiative (QI) project is the implementation of the Quality Strategy. After a successful pilot project for the July 2018 Edition release, the next stage has been implemented for subsequent releases including October 2025.&#x20;

Quality improvement tasks are being deployed to improve internal structural consistency and ensure compliance with editorial policy related to the stated modeling of content. Additionally, correction or addition of defining relationships is being carried out to accurately reflect current clinical knowledge and ensure the semantic reliability of descriptions associated with a concept.

### Body Structure&#x20;

#### Update Mouth and Upper Respiratory Tract

The anatomical hierarchy in relation to parts of the mouth that constitute the upper digestive tract have been reviewed. The upper digestive tract is considered to include the pharynx (and component parts such as the velopharynx; the oral cavity; oral soft tissues; and the periodontal tissues) these class members are similar to those included by Foundation Model of Anatomy (FMA). As part of the reorganization 1351430008 |Structure of velopharynx (body structure) is part of the pharynx; and the location of both the masticator space and the canine space has also been improved. The 700016008 |Structure of region of internal part of mouth and 74336005 |Oral soft tissue structure have been rationalized to relate to the mouth from the 367601008 |Structure of fauces space to the mucocutaneous junction of the lip. The 28777000 |Structure of glossopalatine arch marks the boundary between the oropharynx and the oral cavity but the palatine tonsil and 5944009 |Structure of pharyngopalatine arch are only part of the oropharynx.

A new concept 1363232008 |Structure of fauces region (body structure)| with synonym ‘faucial part of oropharynx’ has been added to clarify the relationship of the structures that make up the fauces from the space which it surrounds. 367601008 |Fauces structure (body structure)| describes a space and has the additional synonyms of ‘isthmus of fauces’ and ‘oropharyngeal isthmus’ – its class has been populated with fauces (space); palatine arch; palatine tonsil; and tonsillar fossa.

A new concept 1371360000 |Structure of soft tissue of internal mouth (body structure)| has been added as a subordinate of 74336005 |Oral soft tissues structure (body structure)| - so the latter, which is more general, can include the entire lip, whereas the former more limited concept only includes soft tissue entirely within the oral cavity region.

The suboptimal arrangement of the hard palate has also been improved with only the lamina horizontalis of the palatine bone and palatine process of the maxilla being components. The major salivary glands are now components of the mouth region, which is a more general region compared to the ‘internal region of mouth’ to which they used to be assigned – only the minor salivary glands and the orifices of the ducts of the major salivary glands are now included under this more detailed region. Finally, the vestibule of mouth and sulci are considered spaces and concepts previously modelled with these notions will be reassigned the relevant mucosal sites e.g. 254448008 |Neoplasm of labial sulcus will be modelled with 59641005|Structure of mucous membrane of lip rather than 419500006 |Structure of labial sulcus (body structure)|.

The change in anatomy has improved relationships of concepts relating to findings, disorders and procedures modeled with this anatomical class.

Number of concepts edited (approx): 25

#### Update Anatomy Relating to Cornual Pregnancy

The anatomy relating to the cornual region of the uterine body has been updated with resulting changes to dependent disorder concepts e.g. cornual polyp, pregnancy and ectopic; and procedure hierarchies e.g. Fallopian tube cornual resection.

The ‘cornu of fallopian tube’ is a feature of the uterus, not the fallopian tube, and is the region containing the anatomical transition of the fallopian tube through the uterine wall to the uterine (body) cavity, called the _interstitial_ or _intramural_ segment. In normal human embryology, the uterus develops from the fusion of the paired Müllerian (paramesonephric) ducts, which form a single uterine cavity.

The term "horn of the uterus" refers to the lateral projections seen in certain congenital anomalies, such as a bicornuate or unicornuate uterus, where incomplete fusion or development of the Müllerian ducts results in one or more uterine "horns"—these are considered malformations, not normal developmental structures: 1357788002 |Horn of uterus (morphologic abnormality) has been added to allow the modelling of these malformations.

Number of concepts edited (approx): 30

#### Update Wall of Blood Vessels

The layers of wall of blood vessels, tunica adventitia, tunica media, tunica intima, have been updated with new concepts for the pulmonary artery.

Number of concepts edited (approx): 9

#### SEP and Laterality Anatomy Reference Sets

The release file for the lateralizable body structure reference set has been updated and validated.

The release file for the SEP reference set has been updated and validated.

### Clinical Finding

#### Update for Meningioma

A new morphologic abnormality concept has been created:

* 1373614004 |Meningioma (morphologic abnormality)|

Twenty-one subtypes have been aligned with the WHO Classification of Tumours of the Central Nervous System, 5th edition, and grouped under malignant, uncertain behavior, and benign morphologic abnormality parents as appropriate.

A new morphology concept has also been created:

* 1373721006 |Metastatic meningioma (morphologic abnormality)|

The disorder concept 393566004 |Meningioma (disorder)| has been reactivated.

Concepts such as 302820008 |Intracranial meningioma (disorder)|, previously defined with 127579001 |Meningeal neoplasm (morphologic abnormality)|, have been remodeled to use 1373614004 |Meningioma (morphologic abnormality)|.

New disorder concepts have been added:

* &#x20;1373719001 |Malignant meningioma (disorder)|
* 1373720007 |Metastatic malignant meningioma (disorder)|

Remodeling of the 393566004 |Meningioma (disorder)| subhierarchy has been completed, including:

* Inactivation of one duplicate concept 388871003 |Primary optic nerve sheath meningioma (disorder)|
* Inactivation of one ambiguous concept, with a replacement provided:126948004 |Cerebellopontine angle meningioma (disorder)| replaced by 1373635002 |Benign cerebellopontine angle meningioma (disorder)|

Number of concepts edited (approx): 30

#### Update 56717001|Tuberculosis (disorder)|

For the hierarchy 56717001|Tuberculosis (disorder)| and descendants, redundant role groups modeled with associated morphology Granulomatous inflammation (morphologic abnormality) have been inactivated since 416728004 |Granulomatous abscess (morphologic abnormality)| is a type of 409775006 |Granulomatous inflammatory morphology (morphologic abnormality)|.

The morphology Granulomatous inflammation (morphologic abnormality) has been added to concepts where required.

'Tuberculous' in descriptions for synonyms is now restricted to those Tuberculosis subtypes defined by 113858008 |Mycobacterium tuberculosis complex (organism)| as value for 246075003 |Causative agent (attribute)|.

#### Update Disorder of Mouth

Disorders of the mouth relating to the oral vestibule have been remodeled with the applicable mucosa anatomical structure (rather than the space). This has resulted in minimal change of the disorder hierarchy but has been augmented by some new associations such as affiliation to disorders of the soft tissues of the mouth.

Number of concepts edited (approx): 40

#### Update subtypes of 42012007 |Neuronal ceroid lipofuscinosis (disorder)|

Neuronal ceroid lipofuscinosis (NCL) was originally diagnosed based on clinical features and ultrastructural abnormalities found with electron microscopy and were formerly grouped into four classic forms:

* 58258004 |Infantile neuronal ceroid lipofuscinosis (disorder)|
* 14637005 |Late-infantile neuronal ceroid lipofuscinosis (disorder)|
* 61663001 |Juvenile neuronal ceroid lipofuscinosis (disorder)|
* 62009002 |Adult neuronal ceroid lipofuscinosis (disorder)|

NCL experts now recommend primary disease classification by gene or protein and secondary classification by age at onset and clinical features. Additional subtypes of 42012007 |Neuronal ceroid lipofuscinosis (disorder)| have been added to align with Orphanet. These additional forms of NCL with clinical features similar to those of the four classic forms have been added as siblings alongside the existing published concepts.

#### Update Heart Failure

364006 |Acute left-sided heart failure (disorder)| has been inactivated as a duplicate of 195114002 |Acute left ventricular failure (disorder)|. All descriptions were retained as synonyms on 195114002 |Acute left ventricular failure (disorder)|.  This change was made because both concepts were modeled identically with body structure site of the left ventricle, and represent the same clinical concept, consistent with ICD-11.

195114002 |Acute left ventricular failure (disorder)| has been remodeled. The FSN for 85232009 |Left heart failure (disorder)| has been changed to Left ventricular failure (disorder). The preferred term is now Left ventricular failure, with synonyms of Left heart failure and Left-sided heart failure retained.

Number of concepts edited (approx): 3

### Procedure

#### Radiographic Imaging

Work is progressing for [this Content Tracker](https://projects.jira.snomed.org/browse/IHTSDO-161) for the hierarchy 363680008|Radiographic imaging procedure (procedure)|.

For the October 2025 release a review of 315293005|Contrast meal (procedure)| and descendants has been undertaken. Subtypes that do not specify an imaging modality/align with the editorial guidance have been reviewed for inactivation and replaced by an imaging specific procedure concept.

#### Update Partial Excision

In order to support the model of partial excision procedures, new 'X part' body structures have been added. Updates have also been made to the existing published concepts. Over 280 partial excision procedure concepts (identified by the ECL below) have been reviewed and updated.&#x20;

<< 71388002 |Procedure (procedure)| \{{D Term = "partial"\}} : 260686004 |Method (attribute)| = << 129304002 |Excision - action (qualifier value)|

Most of these concepts have been defined by the direct procedure site of X part body structures.

Number of concepts edited (approx): 120

#### Update Descriptions - Measurement of Borrelia burgdorferi&#x20;

The descriptions for 14 concepts referring to "Measurement of Borrelia burgdorferi X kiloDalton antibody (procedure)|" have been updated. In addition, IS\_A relationships to stated sufficiently defined parents have been inactivated. No changes in classification occurred.

Number of concepts edited (approx): 14

### Pharmaceutical/Biologic Product

#### Correction of Case Significance

Following case sensitivity validation and user feedback, corrections have been made to ensure that the unit of measure ‘gram’ is represented in accordance with editorial guidance. The Preferred Terms (PT) for the following concepts have been inactivated due to a grammatical error (use of an uppercase ‘G’ instead of a lowercase ‘g’), and new PT descriptions have been added reflecting the correct lowercase representation of gram as g.

* 785222005 |Product containing precisely human immunoglobulin G 2.5 gram/1 vial powder for conventional release solution for injection (clinical drug)|
* 785223000 |Product containing precisely human immunoglobulin G 3 gram/1 vial powder for conventional release solution for injection (clinical drug)|
* 785224006 |Product containing precisely human immunoglobulin G 5 gram/1 vial powder for conventional release solution for injection (clinical drug)|
* 1163192004 |Product containing precisely human immunoglobulin G 6 gram/1 vial powder for conventional release solution for injection (clinical drug)|
* 785220002 |Product containing precisely human immunoglobulin G 10 gram/1 vial powder for conventional release solution for injection (clinical drug)|

This change ensures consistency with SI unit notation and SNOMED International editorial policy.

Number of concepts edited (approx): 5

#### Update Prolonged Release Vaginal Ring Products

Following the recent changes to prolonged-release patch products, a similar issue was identified regarding prolonged-release vaginal ring clinical drugs. After discussion at the DEUSG, these products have been updated to use **presentation strength** in line with the manufacturer’s SPC (/24 hours).

This update involved the creation of a new unit of presentation:

* 1373712005 |Vaginal delivery system (unit of presentation)|

The following clinical drug concepts have been inactivated and replaced:

Inactivated:

* 326190009 |Product containing precisely estradiol 312.5 nanogram/1 hour prolonged-release vaginal ring (clinical drug)|
* 407771008 |Product containing precisely estradiol 2.083 microgram/1 hour prolonged-release vaginal ring (clinical drug)|
* 409300002 |Product containing precisely estradiol 4.167 microgram/1 hour prolonged-release vaginal ring (clinical drug)|
* 1204465002 |Product containing precisely progesterone 416.667 microgram/1 hour prolonged-release vaginal ring (clinical drug)|

New Concepts:

* 1373467005 |Product containing precisely estradiol 7.5 microgram/24 hour prolonged-release vaginal ring (clinical drug)|
* 1375978007 |Product containing precisely estradiol 50 microgram/24 hour prolonged-release vaginal ring (clinical drug)|
* 1375977002 |Product containing precisely estradiol 100 microgram/24 hour prolonged-release vaginal ring (clinical drug)|
* 1373477007 |Product containing precisely progesterone 10 milligram/24 hour prolonged-release vaginal ring (clinical drug)|

Number of concepts edited (approx): 9

### Substance

#### Update Descriptions - Borrelia burgdorferi&#x20;

The descriptions for approximately 30 "Borrelia burgdorferi X-kD antibody" substance concepts have been updated, for example

* The FSN of 120945008|Antibody to Borrelia burgdorferi 25-kD (substance) has been updated to "Antibody to Borrelia burgdorferi 25 kilodalton (substance)" with preferred term "Borrelia burgdorferi 25 kDa antibody."

Number of concepts edited (approx): 30

### Qualifier Value&#x20;

#### New Concepts Supporting AJCC Autopsy TNM Categories and Prefixes and Suffixes

In agreement with American Joint Committee on Cancer (AJCC), new content to support AJCC autopsy TNM classification has been added to SNOMED CT.

A total of 78 new autopsy concepts have been added:  the top-level grouping concept 1373417003 |American Joint Committee on Cancer autopsy allowable value (qualifier value)| and subtypes:

* aT category values: 40 new concepts
* aN category values: 19 new concepts
* aM category values: 18 new concepts

Also new prefixes and suffixes have been added to extend the use of the TNM codes.

The top level grouper concept is 1370921001 |American Joint Committee on Cancer allowable prefix and/or suffix value (qualifier value)| with 7 new subtype concepts representing prefixes and suffixes: y, r, a, (f), (m), (s), and (sn).

Number of concepts edited (approx): 86

### Collaboration/Harmonization Agreements

#### Convergent Medical Terminology (CMT)

68 new concepts have been added for the October 2025 release. Key topic areas include osteomyelitis, infections associated with devices and history of disorders.

#### Orphanet

Working in collaboration with [Orphanet](https://www.orpha.net/) efforts are ongoing to update rare disease concepts in SNOMED CT to maintain alignment with Orphanet for the annual update of the SNOMED CT to Orphanet Maps. In scope content has been annotated with attribution to Inserm Orphanet.

All of the concepts added for the Orphanet project have been mapped to ICD-10.

#### Cancer Synoptic Reporting

Cancer synoptic reports are used by many member countries to record pathology examination of cancer specimens including the College of American Pathologists (US and Canada), Royal College of Pathology (UK), Royal College of Pathology Australasia (Australia, New Zealand), PALGA (The Netherlands), Swedish Society of Pathology, and others.

For more information about this project, please see [Cancer Synoptic Reporting Clinical Project Group](https://conf.spaces.snomed.org/wiki/spaces/CSRPG)&#x20;

#### International League Against Epilepsy (ILAE)

In line with approved harmonized terminology, this project is working on alignment including restructuring to update the hierarchy  << 313307000 |Epileptic seizure (finding)|.

Further information about this collaboration is available [here.](https://www.snomed.org/our-partnerships/international-league-against-epilepsy)

#### Gravity

Six new concepts have been added with the key content areas being procedures related for family reunification services and community meal services.

### Internal Quality Improvement

#### Machine Readable Concept Model (MRCM) Changes

No changes have been made for the MRCM in the October 2025 International Edition.

Future changes that are currently in progress can be viewed via the [MRCM Daily Build Browser](https://dailybuild.ihtsdotools.org/mrcm/?branch=MAIN)

Please see [Early Visibility Notifications](https://conf.spaces.snomed.org/wiki/spaces/RMT/pages/131958586) for future planned changes to MRCM.

#### Annotation Reference Set

The addition of content for the Annotations refset was commenced in the July 2024 International Edition release and is ongoing for attribution of in scope content that is part of a collaboration agreement. Where content with attribution no longer falls into scope for a collaboration agreement, the attribution has been inactivated.

### SNOMED CT derived products

#### SNOMED CT - ICD-10 map

The SNOMED CT to the International Statistical Classification of Diseases and Related Health Problems, Tenth Revision (© World Health Organization 1994) 2016 Version map (SNOMED CT to ICD-10 Map) is included in the SNOMED CT International Edition as a Baseline. The SNOMED CT to ICD-10 Map was created to support the epidemiological, statistical and administrative reporting needs of SNOMED International member countries and WHO Collaborating Centers.

The SNOMED CT to ICD-10 Map is released in Release Format 2 (RF2) only. It is located in the file der2\_iisssccRefset\_ExtendedMapFull\_INT\_20200731.txt, which is in the Map folder under Refset, in each of the three RF2 Release Type folders.&#x20;

The SNOMED CT to ICD-10 Map is released as Refset 447562003 |SNOMED CT to ICD-10 extended map (foundation metadata concept).

The ICD-10 Mapping Technical Guide (including exemplars) is [here.](https://docs.snomed.org/snomed-ct-specifications/snomed-ct-to-icd-10-map-specification/)

#### **Content Development Activity Summary**

The map is a directed set of relationships from SNOMED CT source concepts to ICD-10 target classification codes.  The SNOMED CT source domains for the map are constrained to subtypes of 404684003 |Clinical finding (finding)|, 272379006 |Event (event)|, and 243796009 |Situation with explicit context (situation)|. The target classification used is the ICD-10 WHO version 2016 ([https://icd.who.int/browse10/2016/en#/](https://icd.who.int/browse10/2016/en#/)).

The map provided for this release has been updated and represents a complete map from the October 2025 release of the SNOMED CT International Edition to the ICD-10 WHO version 2016.

This includes:

**Mapped content for October 2025 release**

* Addition of 398 new mapped concepts
* Updates to 247 existing mapped concepts
* Retirement of 57 mapped concepts

The SNOMED CT to ICD-O morphology map has 1 addition for this release.

We welcome feedback on any issues that users may detect when deploying the map. Issues can be reported to [mapping@snomed.org](mailto:mapping@snomed.org).

#### SNOMED CT to OWL conversion and classification

The repository containing the toolkit enabling simple SNOMED CT to OWL conversion and classification can be found here, including documentation on its use: [**https://github.com/IHTSDO/snomed-owl-toolkit**](https://github.com/IHTSDO/snomed-owl-toolkit)

**Please contact SNOMED International at** [**support@snomed.org**](mailto:support@ihtsdo.org) **if you would like to provide any feedback on ways to extend and improve the new toolkit.**

## Technical notes

### Known Issues

Known Issues are content or technical issues where the root cause is understood, and the resolution has been discussed and agreed but has yet to be implemented.  This can be due to a number of reasons, from lack of time within the new monthly editing cycles, to the risk of impact to the stability of SNOMED CT if the fix were to be deployed at that stage in the Product lifecycle. &#x20;

For the current SNOMED CT International Edition, the following Known Issues were identified, and agreed to be resolved in future editing cycles:

### Resolved Issues

Resolved issues are Known Issues which were not fixed as part of the previous release lifecycle, but which have now been resolved in the latest release.  They can also be issues found during testing of the current release, which were resolved before the final deployment of the Production release.  Finally they can be issues which were reported or found during the testing phase, but which have been closed without any action taken. &#x20;

The Resolved Issues for the current SNOMED CT International Edition can be found here:

### Technical updates

#### RF2 package format

The RF2 package convention dictates that all relevant files are included, regardless of whether or not there is content to be included in each release.  Therefore, the package contains a mixture of files which contain both header rows and content data, and files that (intentionally) include only header records.  The reason that these "empty" files are included in the package is to draw a clear distinction between:

1. ...files that have been deprecated (and therefore removed from the package completely), due to the content no longer being relevant to RF2 in future releases&#x20;
2. ...files that happen to contain no data in this particular release (and are therefore included in the package with just a header record), but are still relevant to RF2, and could therefore contain content in future releases.

This allows users to easily distinguish between the two scenarios, as otherwise if files in option 2 were left out of the package it could be interpreted as an error, rather than an intentional lack of content in that release.

#### ADVANCED NOTICE: Increase to the maximum length of Description Types

Please see [here](https://forums.snomed.org/t/conclusion-on-increasing-description-type-length-limits/323) for the latest announcement on the plan to increase the limit of characters allowed in Descriptions.

A community consultation was completed to solicit feedback on the proposal to increase the size limits of SNOMED CT concept descriptions to 4096 from the current limit of 255 characters. While this change does not represent a modification of the existing specification, there is a potential for it to be disruptive to implementers who have coded fixed length limits into their systems. &#x20;

Please read the full proposal, along with [the latest Q\&A blog post](https://www.snomed.org/news/blog%3A-snomed-international-concludes-community-feedback-period-on-proposed-description-character-limit-increase-and-finalizes-next-steps) for details of the planned changes, the potential benefits, and the issues that may need to be considered to prepare for the transition in 2026.

#### Early visibility of impending changes in the upcoming 2025 Monthly International Edition releases

Please see the [Early Visibility Notifications](https://conf.spaces.snomed.org/wiki/spaces/RMT/pages/131958586) for details of forthcoming changes.

***

**Approvals**

| **Final Version** | **Date** | **Approver**                 | **Comments**                                 |
| ----------------- | -------- | ---------------------------- | -------------------------------------------- |
| 1.0               |          | Maria Braithwaite            | Approved                                     |
| 1.0               |          | Monica Harry                 | Approved                                     |
| _1.0_             | n/a      | _Rory Davidson / Kelly Kuru_ | _(Only required for major Breaking changes)_ |

***

**Draft Amendment History**

| **Version** | **Date** | **Editor**                                  | **Comments**                               |
| ----------- | -------- | ------------------------------------------- | ------------------------------------------ |
| 0.1         |          | Andrew Atkinson                             | First draft for review and comment         |
| 0.1         |          | <p>Maria Braithwaite</p><p>Donna Morgan</p> | <p>Content Update</p><p>Mapping Update</p> |
| 1.0         |          | Andrew Atkinson                             | Final Production changes                   |
