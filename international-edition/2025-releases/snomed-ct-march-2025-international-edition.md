# SNOMED CT March 2025 International Edition

[Content Tracker](https://jira.ihtsdotools.org/browse/CTCP-57)

| **Release Date**     | **20250301**   |
| -------------------- | -------------- |
| **Release Status**   | **PRODUCTION** |
| **Document Version** | **1.0**        |

© 2025 International Health Terminology Standards Development Organisation. All rights reserved. SNOMED CT® was originally created by the College of American Pathologists.

This document forms part of the International Edition release of SNOMED CT® distributed by International Health Terminology Standards Development Organisation, trading as SNOMED International, and is subject to the SNOMED CT® Affiliate License, details of which may be found at [https://www.snomed.org/snomed-ct/get-snomed](http://www.snomed.org/snomed-ct/get-snomed).

No part of this document may be reproduced or transmitted in any form or by any means, or stored in any kind of retrieval system, except by an Affiliate of SNOMED International in accordance with the SNOMED CT® Affiliate License. Any modification of this document (including without limitation the removal or modification of this notice) is prohibited without the express written permission of SNOMED International.

Any copy of this document that is not obtained directly from SNOMED International \[or a Member of SNOMED International] is not controlled by SNOMED International, and may have been modified and may be out of date. Any recipient of this document who has received it by other means is encouraged to obtain a copy directly from SNOMED International \[or a Member of SNOMED International. Details of the Members of SNOMED International may be found at [http://www.snomed.org/members/](http://www.snomed.org/members/)].

***

![](../.gitbook/assets/273515523.jpg)

## 1. Introduction <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-introduction" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-introduction"></a>

### 1.1. Background <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-background" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-background"></a>

SNOMED CT terminology provides a common language that enables a consistent way of indexing, storing, retrieving, and aggregating clinical data across specialties and sites of care.

SNOMED International maintains the SNOMED CT technical design, the content architecture, the SNOMED CT content (includes the concepts table, the descriptions table, the relationships table, a history table, and ICD mappings), and related technical documentation.

### 1.2. Purpose <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-purpose" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-purpose"></a>

This document provides a summarized description of the content changes included in the March 2025 release of SNOMED Clinical Terms<sup>®</sup> (SCT) International Edition.

It also includes notes detailing the known content or technical issues where the root cause is understood, the fix has been discussed and agreed to, but has yet to be implemented.

The SNOMED International release notes are available alongside the March 2025 International Edition.

### 1.3. Scope <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-scope" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-scope"></a>

This document is written for the purpose described above and is not intended to provide details of the technical specifications for SNOMED CT or encompass every change made.

### 1.4. Audience <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-audience" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-audience"></a>

The audience includes National Release Centers, WHO-FIC release centers, vendors of electronic health records, terminology developers and managers who wish to have an understanding of changes that have been incorporated into the March 2025 International Edition.

_**Please note, you may have to register for a Confluence user account in order to access the links included in these release notes.**_

## 2. Content Development Activity <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-contentdevelopmentactivity" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-contentdevelopmentactivity"></a>

### 2.1. Summary <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-summary" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-summary"></a>

Continuous quality improvement and enhancement of existing content is an ongoing process undertaken by SNOMED International in preparation for every release. The March 2025 International Edition has seen a continuation of the work driven by contributions from: Kaiser Permanente i.e. Convergent Medical Terminology (CMT), Global Medical Device Nomenclature Agency (GMDNA), Orphanet and other domain specific collaborations as well as requests received via the Content Request System (CRS).

Additionally quality improvement activities are advanced via project driven initiatives summarized below. Additional work items impacting every release are updates to the SNOMED CT derived maps such as ICD-10 and ICD-O; details are included in these release notes.

Information about editorial decisions may be found in the [SNOMED CT Editorial Guide](https://confluence.ihtsdotools.org/display/DOCEG/SNOMED+CT+Editorial+Guide); mapping guidance for ICD-10 can be found [here](https://confluence.ihtsdotools.org/display/DOCICD10).

### 2.2. Quality Initiative <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-qualityinitiative" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-qualityinitiative"></a>

The Quality Initiative (QI) project is the implementation of the Quality Strategy. After a successful pilot project for the July 2018 Edition release, the next stage has been implemented for subsequent releases including March 2025.

Quality improvement tasks are being deployed to improve internal structural consistency and ensure compliance with editorial policy related to the stated modeling of content. Additionally, correction or addition of defining relationships is being carried out to accurately reflect current clinical knowledge and ensure the semantic reliability of descriptions associated with a concept.

#### 2.2.1. Revision 240279008 |Fetoscopic procedure (procedure)| <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-revision240279008-or-fetoscopic" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-revision240279008-or-fetoscopic"></a>

Added inspection role group to 240279008 |Fetoscopic procedure (procedure)| and subtypes to facilitate appropriate classification.

* Method = inspection
* Using device = fetoscope
* Occurrence = fetal period

### 2.3. Body Structure <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-bodystructure" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-bodystructure"></a>

#### 2.3.1. Inactivation of 46141003|Structure of alveolus dentalis (body structure)| <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-inactivationof46141003-or-struc" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-inactivationof46141003-or-struc"></a>

Working in consultation with the Dentistry Clinical Reference Group, 46141003 |Structure of alveolus dentalis (body structure)| and 1240400004 |Structure of tooth socket (body structure)| have been identified as duplicate concepts.

46141003|Structure of alveolus dentalis (body structure)| has been inactivated with historical association to 1240400004|Structure of tooth socket (body structure)|.

Additional changes have been made to concepts which had been modeled with site 46141003|Structure of alveolus dentalis (body structure)|, the model for these concepts has been updated to include site 1240400004|Structure of tooth socket (body structure)|.

Number of concepts edited (approx): 16

#### 2.3.2. Revision 17176004|Structure of bridge of nose (body structure)| and 84047001|Structure of dorsum of nose (body structure)| <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-revision17176004-or-structureof" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-revision17176004-or-structureof"></a>

A text definition has been added to the concepts 17176004|Structure of bridge of nose (body structure)| and 84047001|Structure of dorsum of nose (body structure)|.

Regions of the external nose have been reorganized.

Number of concepts edited (approx): 33

#### 2.3.3. SEP and Laterality Anatomy Reference Sets <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-sepandlateralityanatomyreferenc" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-sepandlateralityanatomyreferenc"></a>

The release file for the lateralizable body structure reference set has been updated and validated.

The release file for the SEP reference set has been updated and validated.

### 2.4. Procedure <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-procedure" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-procedure"></a>

#### 2.4.1. Radiographic Imaging <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-radiographicimaging" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-radiographicimaging"></a>

Work is progressing for [t](https://jira.ihtsdotools.org/browse/IHTSDO-161)[his content tracker](https://jira.ihtsdotools.org/browse/IHTSDO-161) for information please see [the informational briefing note here.](https://confluence.ihtsdotools.org/display/cmag/Proposed+update+to+content+in+the+Radiographic+imaging+procedure+\(procedure\)+hierarchy)

### 2.5. Situation with Explicit Context <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-situationwithexplicitcontext" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-situationwithexplicitcontext"></a>

#### 2.5.1. Update Descriptions <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-updatedescriptions" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-updatedescriptions"></a>

The fully specified name and preferred term for descendants of 41769001 |Disease suspected (situation)| have been updated to the agreed pattern of 'X disorder/finding' before the word 'suspected' to improve consistency in this hierarchy.

Number of concepts edited (approx): 150

### 2.6. Collaboration/Harmonization Agreements <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-collaboration-harmonizationagre" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-collaboration-harmonizationagre"></a>

#### 2.6.1. Convergent Medical Terminology (CMT) <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-convergentmedicalterminology-cm" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-convergentmedicalterminology-cm"></a>

41 new concepts have been added for the ophthalmology domain.

#### 2.6.2. Orphanet <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-orphanet" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-orphanet"></a>

Working in collaboration with [Orphanet](https://www.orpha.net/) efforts are ongoing to update rare disease concepts in SNOMED CT to maintain alignment with Orphanet for the annual update of the SNOMED CT to Orphanet Maps.

Work has commenced to annotate content added for the Orphanet project with attribution to Inserm Orphanet. As part of this effort, textual definitions for concepts previously added for the Orphanet project have been updated to align with the current published version of the Orphanet definition. This has resulted in published text definitions being inactivated and replaced in bulk and this work has been completed for the March 2025 release. There remains approximately 200 concepts with text definition that will be updated to include attribution.

All of the concepts added for the Orphanet project have been mapped to ICD-10.

#### 2.6.3. Gravity <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-gravity" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-gravity"></a>

Work for this project is ongoing.

#### 2.6.4. Nursing <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-nursing" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-nursing"></a>

Five concepts have been added to support the domain of nursing.

#### 2.6.5. Cancer Synoptic Reporting <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-cancersynopticreporting" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-cancersynopticreporting"></a>

Cancer synoptic reports are used by many member countries to record pathology examination of cancer specimens including the College of American Pathologists (US and Canada), Royal College of Pathology (UK), Royal College of Pathology Australasia (Australia, New Zealand), PALGA (The Netherlands), Swedish Society of Pathology, and others.

For more information about this project, please see [Cancer Synoptic Reporting Clinical Project Group](https://confluence.ihtsdotools.org/display/CSRPG/Cancer+Synoptic+Reporting+Clinical+Project+Group)

#### 2.6.6. International League Against Epilepsy (ILAE) <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-internationalleagueagainstepile" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-internationalleagueagainstepile"></a>

In line with approved harmonized terminology, this project is working on alignment including restructuring to update the hierarchy << 313307000 |Epileptic seizure (finding)|.

Further information about the project is available [here](https://confluence.ihtsdotools.org/display/IAP/Epilepsy+Status+Report)

### 2.7. Internal Quality Improvement <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-internalqualityimprovement" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-internalqualityimprovement"></a>

#### 2.7.1. Machine Readable Concept Model (MRCM) Changes <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-machinereadableconceptmodel-mrc" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-machinereadableconceptmodel-mrc"></a>

There have been no changes for the MRCM in the March 2025 International Edition.

Future changes that are currently in progress can be viewed via the [MRCM Daily Build Browser](https://dailybuild.ihtsdotools.org/mrcm/?branch=MAIN)

Please see [Early Visibility Release Notifications](https://confluence.ihtsdotools.org/display/RMT/2025+Early+Visibility+Release+Notifications) for future planned changes to MRCM.

#### 2.7.2. **Annotation Reference Set** <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-annotationreferenceset" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-annotationreferenceset"></a>

The addition of content for the Annotations refset was commenced in the July 2024 International Edition release and is ongoing for attribution of text definition to organizations with a collaboration agreement, starting with Inserm Orphanet.

### 2.8. SNOMED CT derived products <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-snomedctderivedproducts" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-snomedctderivedproducts"></a>

#### 2.8.1. ICD-10 map <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-icd-10map" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-icd-10map"></a>

The SNOMED CT to the International Statistical Classification of Diseases and Related Health Problems, Tenth Revision (© World Health Organization 1994) 2016 Version map (SNOMED CT to ICD-10 Map) is included in the SNOMED CT International Edition as a Baseline. The SNOMED CT to ICD-10 Map was created to support the epidemiological, statistical and administrative reporting needs of SNOMED International member countries and WHO Collaborating Centers.

The SNOMED CT to ICD-10 Map is released in Release Format 2 (RF2) only. It is located in the file der2\_iisssccRefset\_ExtendedMapFull\_INT\_20200731.txt, which is in the Map folder under Refset, in each of the three RF2 Release Type folders.

The SNOMED CT to ICD-10 Map is released as Refset 447562003 |SNOMED CT to ICD-10 extended map (foundation metadata concept).

The ICD-10 Mapping Technical Guide (including exemplars) is hosted here [https://confluence.ihtsdotools.org/display/DOCICD10](https://confluence.ihtsdotools.org/display/DOCICD10)

#### 2.8.2. **Content Development Activity Summary** <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-contentdevelopmentactivitysumma" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-contentdevelopmentactivitysumma"></a>

The map is a directed set of relationships from SNOMED CT source concepts to ICD-10 target classification codes. The SNOMED CT source domains for the MAP are limited to subtypes of 404684003 |clinical finding|, 272379006 |event| and 243796009 |situation with explicit context|. The target classification codes are ICD-10 2016 release.

Mapped content for March 2025

The map provided for the March 2025 International Edition has been updated, and now represents a complete map from SNOMED CT International Edition to ICD-10 2016 version.

* 501 newly authored concepts have been added and mapped.
* The SNOMED to ICD-O (morphology) map has zero additional concepts added as a result of the ICD-O 3.2 review or added due to CRS requests.

We would welcome feedback on any issues that users of the map may detect when using the map. Issues should be submitted via [mapping@snomed.org](mailto:mapping@snomed.org)

#### 2.8.3. SNOMED CT to OWL conversion and classification <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-snomedcttoowlconversionandclass" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-snomedcttoowlconversionandclass"></a>

The repository containing the toolkit enabling simple SNOMED CT to OWL conversion and classification can be found here, including documentation on its use: [**https://github.com/IHTSDO/snomed-owl-toolkit**](https://github.com/IHTSDO/snomed-owl-toolkit)

**Please contact SNOMED International at** [**support@snomed.org**](mailto:support@ihtsdo.org) **if you would like to provide any feedback on ways to extend and improve the new toolkit.**

## 3. Technical notes <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-technicalnotes" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-technicalnotes"></a>

### 3.1. Known Issues <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-knownissues" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-knownissues"></a>

Known Issues are content or technical issues where the root cause is understood, and the resolution has been discussed and agreed but has yet to be implemented. This can be due to a number of reasons, from lack of time within the new monthly editing cycles, to the risk of impact to the stability of SNOMED CT if the fix were to be deployed at that stage in the Product lifecycle.

For the current SNOMED CT International Edition, the following Known Issues were identified, and agreed to be resolved in future editing cycles:

|                                                                          |                                                                                                                                                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Key                                                                      | Summary                                                                                                                                                                                                                                                           | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| [ISRS-7135](https://jira.ihtsdotools.org/browse/ISRS-7135?src=confmacro) | [SNOMED CT International edition, 2025-02-01, 25334385-83b3-4531-8e6e-cf9e32ebccd2, Two active descriptions in the same hierarchy should not share the same term, unless the language is different.](https://jira.ihtsdotools.org/browse/ISRS-7135?src=confmacro) | <p>Two active descriptions in the same hierarchy should not share the same term, unless the language is different.<br>Total number of failures: 178<br>Environment: PROD<br>First 10 failures:</p><ul><li>{ "conceptId": "428639001", "componentId": "2695405017", "branchPath": "MAIN/BLKUPDATE6", "reason": "Temporarily exception listed whilst being reviewed for QI-900", "fullComponent": "1,900000000000207008,428639001,en,900000000000013009,Insert,900000000000448009" }</li><li>{ "conceptId": "428639001", "componentId": "2695405017", "branchPath": "MAIN/BLKUPDATE6", "reason": "Temporarily exception listed whilst being reviewed for QI-900", "fullComponent": "1,900000000000207008,428639001,en,900000000000013009,Insert,900000000000448009" }</li><li>{ "conceptId": "428639001", "componentId": "2695405017", "branchPath": "MAIN/BLKUPDATE6", "reason": "Temporarily exception listed whilst being reviewed for QI-900", "fullComponent": "1,900000000000207008,428639001,en,900000000000013009,Insert,900000000000448009" }</li><li>{ "conceptId": "428639001", "componentId": "2695405017", "branchPath": "MAIN/BLKUPDATE6", "reason": "Temporarily exception listed whilst being reviewed for QI-900", "fullComponent": "1,900000000000207008,428639001,en,900000000000013009,Insert,900000000000448009" }</li><li>{ "conceptId": "733001005", "componentId": "3498547014", "branchPath": "MAIN/BLKUPDATE6", "reason": "Temporarily exception listed whilst being reviewed for QI-900", "fullComponent": "1,900000000000207008,733001005,en,900000000000013009,Lyophilisate,900000000000448009" }</li><li>{ "conceptId": "738993004", "componentId": "3534539012", "branchPath": "MAIN/BLKUPDATE6", "reason": "Temporarily exception listed whilst being reviewed for QI-900", "fullComponent": "1,900000000000207008,738993004,en,900000000000013009,Insert,900000000000448009" }</li><li>{ "conceptId": "738993004", "componentId": "3534539012", "branchPath": "MAIN/BLKUPDATE6", "reason": "Temporarily exception listed whilst being reviewed for QI-900", "fullComponent": "1,900000000000207008,738993004,en,900000000000013009,Insert,900000000000448009" }</li><li>{ "conceptId": "225780003", "componentId": "339260018", "branchPath": "MAIN/BLKUPDATE6", "reason": "Temporarily exception listed whilst being reviewed for QI-900", "fullComponent": "1,900000000000207008,225780003,en,900000000000013009,Sublingual,900000000000448009" }</li><li>{ "conceptId": "733013000", "componentId": "3498572014", "branchPath": "MAIN/BLKUPDATE6", "reason": "Temporarily exception listed whilst being reviewed for QI-900", "fullComponent": "1,900000000000207008,733013000,en,900000000000013009,Sachet,900000000000448009" }</li><li>{ "conceptId": "410670007", "componentId": "2472324010", "branchPath": "MAIN/BLKUPDATE6", "reason": "Temporarily exception listed whilst being reviewed for QI-900", "fullComponent": "1,900000000000012004,410670007,en,900000000000013009,Time,900000000000448009" }</li></ul><p>KNOWN ISSUE: SNOMED International content team have confirmed that these issues have been analysed and exception-listed in the short term due to their low priority. They will be discussed and resolved by the end of 2025.</p> |

[1 issue](https://jira.ihtsdotools.org/secure/IssueNavigator.jspa?reset=true\&jqlQuery=filter+%3D+%22INT+20250201+-+Known+Issues+%28On+Hold%29%22+ORDER+BY+key+ASC+++++++++++++++++++++++++++++\&src=confmacro)

### 3.2. Resolved Issues <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-resolvedissues" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-resolvedissues"></a>

Resolved issues are Known Issues which were not fixed as part of the previous release lifecycle, but which have now been resolved in the latest release. They can also be issues found during testing of the current release, which were resolved before the final deployment of the Production release. Finally they can be issues which were reported or found during the testing phase, but which have been closed without any action taken.

The Resolved Issues for the current SNOMED CT International Edition can be found here:

|     |         |             |          |
| --- | ------- | ----------- | -------- |
| Key | Summary | Description | Resolved |

[No issues found](https://jira.ihtsdotools.org/secure/IssueNavigator.jspa?reset=true\&jqlQuery=filter+%3D+%22INT+20250201+-+Resolved+Issues%22+++++++++++++++ORDER+BY+key+ASC+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++\&src=confmacro)

### 3.3. Technical updates <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-technicalupdates" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-technicalupdates"></a>

#### 3.3.1. RF2 package format <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-rf2packageformat" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-rf2packageformat"></a>

The RF2 package convention dictates that all relevant files are included, regardless of whether or not there is content to be included in each release. Therefore, the package contains a mixture of files which contain both header rows and content data, and files that (intentionally) include only header records. The reason that these "empty" files are included in the package is to draw a clear distinction between:

1. ...files that have been deprecated (and therefore removed from the package completely), due to the content no longer being relevant to RF2 in future releases
2. ...files that happen to contain no data in this particular release (and are therefore included in the package with just a header record), but are still relevant to RF2, and could therefore contain content in future releases.

This allows users to easily distinguish between the two scenarios, as otherwise if files in option 2 were left out of the package it could be interpreted as an error, rather than an intentional lack of content in that release.

#### 3.3.2. Proposal to increase the maximum length of Description Types <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-proposaltoincreasethemaximumlen" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-proposaltoincreasethemaximumlen"></a>

Please find below the link to the recent announcement on the proposal to increase the limit of characters allowed in Descriptions:

* [https://confluence.ihtsdotools.org/pages/viewpage.action?pageId=238158325](https://confluence.ihtsdotools.org/pages/viewpage.action?pageId=238158325)

A community consultation was launched to solicit feedback on a proposal to increase the size limits of SNOMED CT concept descriptions to 4096 from the current limit of 255 characters. While this change does not represent a modification of the existing specification, it could be disruptive to implementers who have coded fixed length limits into their systems.

Please read the full proposal, along with [the latest Q\&A blog post](https://www.snomed.org/news/blog%3A-snomed-international-seeks-community-feedback-on-proposed-description-character-limit-increase) which details the proposed change, its potential benefits, the feedback process and timelines, and the issues that may need to be considered in such an update:

* [https://confluence.ihtsdotools.org/mag/community-consultations/snomed-international-proposal-to-increase-description-length-limit](https://confluence.ihtsdotools.org/mag/community-consultations/snomed-international-proposal-to-increase-description-length-limit)
* [https://www.snomed.org/news/blog%3A-snomed-international-seeks-community-feedback-on-proposed-description-character-limit-increase](https://www.snomed.org/news/blog%3A-snomed-international-seeks-community-feedback-on-proposed-description-character-limit-increase)

As always, SNOMED International greatly appreciated all feedback provided before the deadline (which was Dec 31, 2024). A summary of the feedback will be collated and disseminated in 2025, alongside a plan for the transition.

#### 3.3.3. Early visibility of impending changes in the upcoming 2025 Monthly International Edition releases <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-earlyvisibilityofimpendingchang" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-earlyvisibilityofimpendingchang"></a>

Please see the [Early Visibility Release Notifications](https://confluence.ihtsdotools.org/display/RMT/2025+Early+Visibility+Release+Notifications) Confluence page for details of forthcoming changes.

#### 3.3.4. Document links <a href="#snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-documentlinks" id="snomedctmarch2025internationaleditionsnomedinternationalreleasenotes-documentlinks"></a>

All links provide information that is correct and current at the time of this Release. Updated versions may be available at a later date, but if so these will need to be requested from the relevant SNOMED International teams.

**NOTE**: To access any of the links in the pdf document, please visit the Release Notes [https://confluence.ihtsdotools.org/display/RMT/SNOMED+CT+March+2025+International+Edition+-+SNOMED+International+Release+notes](https://confluence.ihtsdotools.org/display/RMT/SNOMED+CT+March+2025+International+Edition+-+SNOMED+International+Release+notes)

***

**Approvals**

| **Final Version** | **Date**    | **Approver**  | **Comments** |
| ----------------- | ----------- | ------------- | ------------ |
| 1.0               | 13 Feb 2025 | Rory Davidson | Approved     |
| 1.0               | 10 Feb 2025 | Monica Harry  | Approved     |
| 1.0               | 13 Feb 2025 | Kelly Kuru    | Approved     |

***

**Draft Amendment History**

| **Version** | **Date**    | **Editor**                                           | **Comments**                               |
| ----------- | ----------- | ---------------------------------------------------- | ------------------------------------------ |
| 0.1         | 31 Jan 2025 | Andrew Atkinson                                      | First draft for review and comment         |
| 0.1         | 10 Feb 2025 | <p>Maria Braithwaite</p><p>Michael Harwood-Jones</p> | <p>Content Update</p><p>Mapping Update</p> |
| 1.0         | 12 Feb 2025 | Andrew Atkinson                                      | Final Production changes                   |
