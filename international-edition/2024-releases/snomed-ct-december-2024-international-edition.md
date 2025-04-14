# SNOMED CT December 2024 International Edition

[Content Tracker](https://jira.ihtsdotools.org/browse/CTCP-57)

| **Release Date**     | **20241201**                                                          |
| -------------------- | --------------------------------------------------------------------- |
| **Release Status**   | <mark style="color:blue;background-color:blue;">**PRODUCTION**</mark> |
| **Document Version** | **1.0**                                                               |

© 2025 International Health Terminology Standards Development Organisation. All rights reserved. SNOMED CT® was originally created by the College of American Pathologists.

This document forms part of the International Edition release of SNOMED CT® distributed by International Health Terminology Standards Development Organisation, trading as SNOMED International, and is subject to the SNOMED CT® Affiliate License, details of which may be found at [https://www.snomed.org/snomed-ct/get-snomed](http://www.snomed.org/snomed-ct/get-snomed).

No part of this document may be reproduced or transmitted in any form or by any means, or stored in any kind of retrieval system, except by an Affiliate of SNOMED International in accordance with the SNOMED CT® Affiliate License. Any modification of this document (including without limitation the removal or modification of this notice) is prohibited without the express written permission of SNOMED International.

Any copy of this document that is not obtained directly from SNOMED International \[or a Member of SNOMED International] is not controlled by SNOMED International, and may have been modified and may be out of date. Any recipient of this document who has received it by other means is encouraged to obtain a copy directly from SNOMED International \[or a Member of SNOMED International. Details of the Members of SNOMED International may be found at [http://www.snomed.org/members/](http://www.snomed.org/members/)].

***

## ![](../.gitbook/assets/273515526.png) <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-introduction" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-introduction"></a>

## 1. Introduction <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-introduction" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-introduction"></a>

### 1.1. Background <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-background" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-background"></a>

SNOMED CT terminology provides a common language that enables a consistent way of indexing, storing, retrieving, and aggregating clinical data across specialties and sites of care.

SNOMED International maintains the SNOMED CT technical design, the content architecture, the SNOMED CT content (includes the concepts table, the descriptions table, the relationships table, a history table, and ICD mappings), and related technical documentation.

### 1.2. Purpose <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-purpose" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-purpose"></a>

This document provides a summarized description of the content changes included in the December 2024 release of SNOMED Clinical Terms<sup>®</sup> (SCT) International Edition.

It also includes notes detailing the known content or technical issues where the root cause is understood, the fix has been discussed and agreed to, but has yet to be implemented.

The SNOMED International release notes are available alongside the December 2024 International Edition.

### 1.3. Scope <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-scope" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-scope"></a>

This document is written for the purpose described above and is not intended to provide details of the technical specifications for SNOMED CT or encompass every change made.

### 1.4. Audience <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-audience" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-audience"></a>

The audience includes National Release Centers, WHO-FIC release centers, vendors of electronic health records, terminology developers and managers who wish to have an understanding of changes that have been incorporated into the December 2024 International Edition.

_**Please note, you may have to register for a Confluence user account in order to access the links included in these release notes.**_

## 2. Content Development Activity <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-contentdevelopmentactivity" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-contentdevelopmentactivity"></a>

### 2.1. Summary <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-summary" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-summary"></a>

Continuous quality improvement and enhancement of existing content is an ongoing process undertaken by SNOMED International in preparation for every release. The December 2024 International Edition has seen a continuation of the work driven by contributions from: Kaiser Permanente i.e. Convergent Medical Terminology (CMT), Global Medical Device Nomenclature Agency (GMDNA), Orphanet and other domain specific collaborations as well as requests received via the Content Request System (CRS).

Additionally quality improvement activities are advanced via project driven initiatives summarized below. Additional work items impacting every release are updates to the SNOMED CT derived maps such as ICD-10 and ICD-O; details are included in these release notes.

Information about editorial decisions may be found in the [SNOMED CT Editorial Guide](https://confluence.ihtsdotools.org/display/DOCEG/SNOMED+CT+Editorial+Guide); mapping guidance for ICD-10 can be found [here](https://confluence.ihtsdotools.org/display/DOCICD10).

### 2.2. Quality Initiative <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-qualityinitiative" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-qualityinitiative"></a>

The Quality Initiative (QI) project is the implementation of the Quality Strategy. After a successful pilot project for the July 2018 Edition release, the next stage has been implemented for subsequent releases including December 2024.

Quality improvement tasks are being deployed to improve internal structural consistency and ensure compliance with editorial policy related to the stated modeling of content. Additionally, correction or addition of defining relationships is being carried out to accurately reflect current clinical knowledge and ensure the semantic reliability of descriptions associated with a concept.

#### 2.2.1. Update 418285008|Angioplasty of blood vessel (procedure)| <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-update418285008-or-angioplas" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-update418285008-or-angioplas"></a>

Work has been completed for this [content tracker.](https://jira.ihtsdotools.org/browse/IHTSDO-1077)

Descriptions have been updated to align with Editorial guidance to include access, approach, imaging modality and use of contrast. The FSN has been aligned with the definition as modeled. Clinical input was sought for correct naming of angioplasty procedures. All modeled as 'Percutaneous transluminal angioplasty using fluoroscopic guidance with contrast.'

Number of concepts edited (approx): 150

Concept inactivations: 102

#### 2.2.2. Update Gout, Hyperuricemia and Crystal-associated Arthropathies <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-updategout-hyperuricemiaandc" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-updategout-hyperuricemiaandc"></a>

A recent consensus document on terminology for gout, hyperuricemia and crystal-associated arthropathies ([https://pubmed.ncbi.nlm.nih.gov/31501138/](https://pubmed.ncbi.nlm.nih.gov/31501138/)) has been used to inform the remodeling of gout in SNOMED CT.

The prime definitional characteristic of gout is the deposition of monosodium urate crystals in tissues, with or without the presence of elevated levels of blood urate. As elevated blood urates are no longer considered definitional, gout and its subtypes are no longer subtypes of 269859006 |Blood urate above reference range (finding)|. Gouty arthritis concepts have been re-termed in accordance with the consensus document and classified as subtypes of Crystal arthropathy.

### 2.3. Body Structure <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-bodystructure" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-bodystructure"></a>

#### 2.3.1. Update Descendants of 21514008|Structure of genitourinary system (body structure)| <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-updatedescendantsof21514008" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-updatedescendantsof21514008"></a>

High level descendants of 21514008|Structure of genitourinary system (body structure)| have been reorganized.

Vas deferens parts and regions have been updated.

Number of concepts edited (approx): 39

#### 2.3.2. Remodel Descendants of 31435000|Fallopian tube structure (body structure)| <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-remodeldescendantsof31435000" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-remodeldescendantsof31435000"></a>

The hierarchy of 31435000|Fallopian tube structure (body structure)| has been updated.

Number of concepts edited (approx): 5

#### 2.3.3. SEP and Laterality Anatomy Reference Sets <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-sepandlateralityanatomyrefer" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-sepandlateralityanatomyrefer"></a>

The release file for the lateralizable body structure reference set has been updated and validated.

The release file for the SEP reference set has been updated and validated.

### 2.4. Clinical Finding <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-clinicalfinding" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-clinicalfinding"></a>

#### 2.4.1. Update Descriptions 169826009|Single live birth (finding)| <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-updatedescriptions169826009" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-updatedescriptions169826009"></a>

After consultation with the Content Managers Advisory Group, the descriptions for

169826009|Single live birth (finding)|

have been updated to

169826009 |Single live birth from singleton pregnancy (finding)|

A new concept has also been added 1351929005 |Single live birth from multiple pregnancy (finding)|

#### 2.4.2. Update Descriptions "Sample" to "Specimen" <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-updatedescriptions-sample-to" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-updatedescriptions-sample-to"></a>

64 clinical finding concepts which included "sample" in their FSN and/or PT have been updated to include "specimen" in place of "sample" in the FSN and/or PT. Descriptions have been inactivated and replaced; no concepts have been inactivated.

This follows similar work previously performed in the specimen hierarchy and noted in the [Editorial Guide](https://confluence.ihtsdotools.org/display/DOCEG/Specimen).

#### 2.4.3. Update Concepts Referring to 'Missile' <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-updateconceptsreferringtomis" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-updateconceptsreferringtomis"></a>

Missile as a generalized projectile and missile with the narrower meaning of a specific type of weapon have been conflated in the disorders, events and physical object hierarchy.

* 262572000 |Missile injury (disorder)| has been inactivated with reason ambiguous and historical association to 242999003 |Injury due to projectile (disorder)| and new concept 1352005003 |Injury due to missile weapon (disorder)|.
* The existing 52 subtypes of Missile injury (disorder)| - (types of bullet wound, pellet wound and shotgun wound) have been remodeled with the result that they are now subtypes of 242999003 |Injury due to projectile (disorder)| and siblings of 1352005003 |Injury due to missile weapon (disorder)|.
* 44468009 |Missile, device (physical object)| has been inactivated with reason ambiguous and historical association to 1351997000 |Projectile weapon device (physical object)| and new concept 1351998005 |Missile weapon device (physical object)|.
* 29 previous subtypes of 44468009 |Missile, device (physical object)| are now subtypes of 1351997000 |Projectile weapon device (physical object)| and siblings of 1351998005 |Missile weapon device (physical object)|.
* 45224000 |Struck by missile (event)| has been inactivated with reason ambiguous and historical association to 1352002000 |Struck by missile weapon (event)| and 63409001 |Struck by firearm discharge (event)|. Both the latter concepts are now siblings and subtypes of 84829006 |Struck by projectile (event)|.
* Previous subtypes of 45224000 |Struck by missile (event)| all with descriptions "Struck by object falling from x location" have been moved to become subtypes of 71893005 |Struck by falling object (event)|.

Changes in additional hierarchies: Event, physical object

Number of concepts edited (approx): 90

Concept inactivations: 3

### 2.5. Procedure <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-procedure" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-procedure"></a>

#### 2.5.1. Radiographic Imaging <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-radiographicimaging" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-radiographicimaging"></a>

Work is progressing for [t](https://jira.ihtsdotools.org/browse/IHTSDO-161)[his content tracker](https://jira.ihtsdotools.org/browse/IHTSDO-161) for information please see [the informational briefing note here.](https://confluence.ihtsdotools.org/display/cmag/Proposed+update+to+content+in+the+Radiographic+imaging+procedure+\(procedure\)+hierarchy)

28367004|Cholangiography (procedure)| and descendants have been reviewed for the December 2024 release. Where a procedure concept was modeled with method 278110001|Radiographic imaging - action (qualifier value)| but performed using a subtype of that modality such as 312275004|Fluoroscopic imaging - action (qualifier value)|, the concept has been inactivated and replaced with a new concept that specifies the imaging modality and the use of contrast. 28367004|Cholangiography (procedure)| has also been inactivated with historical association to imaging specific procedures.

#### 2.5.2. Update Laparoscopic Repair of Direct Inguinal Hernia <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-updatelaparoscopicrepairofdi" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-updatelaparoscopicrepairofdi"></a>

343560004 |Laparoscopic repair of bilateral, one direct and one indirect, inguinal hernia with graft (procedure)| and 1343561000 |Laparoscopic repair of bilateral, one direct and one indirect, inguinal hernia with prosthesis (procedure)| have both been inactivated with reason ambiguous and historical association to new replacement concepts:

* 1351936006 |Laparoscopic repair of right direct inguinal hernia and left indirect inguinal hernia with graft (procedure)|
* 1351937002 |Laparoscopic repair of left direct inguinal hernia and right indirect inguinal hernia with prosthesis (procedure)|
* 1351935005 |Laparoscopic repair of left direct inguinal hernia and right indirect inguinal hernia with graft (procedure)|
* 1351938007 |Laparoscopic repair of right direct inguinal hernia and left indirect inguinal hernia with prosthesis (procedure)|

Number of concepts edited (approx): 6

#### 2.5.3. Update Excision Small Intestine <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-updateexcisionsmallintestine" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-updateexcisionsmallintestine"></a>

The model has been updated to apply SEP (Structure, Entire, and Partial) for excision, total excision, and partial excisions of the small intestine.

280700008 |Vitellointestinal structure (body structure)| has been inactivated because of ambiguity and replaced by a new concept 1348261003 |Persistent embryonic vitelline duct (morphologic abnormality)| and 41629008 |Structure of yolk stalk (body structure)|. The disorders and procedures have been updated. Disorders of _persistent_ embryonic structures had been classified as disorders of embryonic structures and this has been resolved.

Ileectomy and anastomosis procedures have been fully defined by following the established modeling pattern.

Number of concepts edited (approx): 41

#### 2.5.4. Inactivation of 387644004 |Supracervical hysterectomy (procedure)| <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-inactivationof387644004-or-s" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-inactivationof387644004-or-s"></a>

387644004 |Supracervical hysterectomy (procedure)| has been inactivated with reason duplicate and historical association to its parent 387643005 |Partial hysterectomy (procedure)|.

387643005 |Partial hysterectomy (procedure)| remains active with 2 synonyms: Supracervical hysterectomy and Subtotal hysterectomy.

Number of concepts edited (approx): 13

### 2.6. Organism <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-organism" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-organism"></a>

#### 2.6.1. **Update Descriptions Salmonella** <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-updatedescriptionssalmonella" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-updatedescriptionssalmonella"></a>

One of the synonyms for many descendants of 398428002 |Salmonella enterica subsp. diarizonae (organism) was incorrectly included, e.g. "398387008 | Salmonella IIIb 61:c:z35 (organism) |" belongs to Salmonella IIIb i.e. "Salmonella enteric subs. diarizonae" but had "Salmonella III arizonae 61:c:z35" as a synonym. “Salmonella III arizonae” is an outdated name. “Salmonella enteric subs. arizonae” is now also known as Salmonella IIIa.

A batch update was performed to:

* Remove any synonyms containing "Salmonella III arizonae" (if one exists), e.g “Salmonella III arizonae 61:c:z35”
* Replace the inactivated synonym with a similar one containing “Salmonella enterica subs. diarizonae”, e.g. “Salmonella enterica subsp. diarizonae 61:c:z35”

Number of concepts edited (approx): 360

### 2.7. Pharmaceutical/Biologic Product <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-pharmaceutical-biologicprodu" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-pharmaceutical-biologicprodu"></a>

#### 2.7.1. Update Axiom Therapeutic Role <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-updateaxiomtherapeuticrole" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-updateaxiomtherapeuticrole"></a>

21 concepts in the medicinal products hierarchy were erroneously modeled with multiple stated sufficient axioms instead of a single additional axiom for the therapeutic role. These axioms have now been inactivated. A substance concept was also similarly identified with multiple sufficient axioms and has been remodeled. Further informations is available in this [briefing note.](https://confluence.ihtsdotools.org/display/MEMBERFORUM/For+Information+Only%3A+Follow-up+Briefing+Note+regarding+the+Inactivation+of+Therapeutic+Role+Groupers+in+the+Medicinal+Product+Hierarchy)

### 2.8. Substance <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-substance" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-substance"></a>

#### 2.8.1. Soft Hyphen in Descriptions <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-softhyphenindescriptions" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-softhyphenindescriptions"></a>

A report was received about the presence of ‘soft hyphens’ in the FSN and preferred term for this concept 138911000146100 |Trimethylbenzenepropanol (substance)| which was published in the 1 March 2024 International Edition.

The FSN and PT have been inactivated and replaced for this concept. No further instances were found in other published descriptions. New validation will be introduced to identify further issues of this type at the time of editing.

### 2.9. Collaboration/Harmonization Agreements <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-collaboration-harmonizationa" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-collaboration-harmonizationa"></a>

#### 2.9.1. Convergent Medical Terminology (CMT) <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-convergentmedicalterminology" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-convergentmedicalterminology"></a>

44 CMT concepts have been added, predominately in the injury domain.

#### 2.9.2. Orphanet <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-orphanet" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-orphanet"></a>

Working in collaboration with [Orphanet](https://www.orpha.net/) efforts are ongoing to update rare disease concepts in SNOMED CT to maintain alignment with Orphanet for the annual update of the SNOMED CT to Orphanet Maps. Work has commenced to annotate content added for the Orphanet project with attribution to Inserm Orphanet. As part of this effort, textual definitions for concepts previously added for the Orphanet project will be updated to align with the current published version of the Orphanet definition. This will result in published text definitions being inactivated and replaced in bulk. Timelines for publication of these changes can be found in the [Early Visibility Release Notifications](https://confluence.ihtsdotools.org/display/RMT/2025+Early+Visibility+Release+Notifications)

NOTE: approximately 130 new annotation are missing the languageDialectCode, this will be added as a batch update for a future international edition release.

All of the concepts added for the Orphanet project have been mapped to ICD-10.

#### 2.9.3. Cancer Synoptic Reporting <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-cancersynopticreporting" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-cancersynopticreporting"></a>

Cancer synoptic reports are used by many member countries to record pathology examination of cancer specimens including the College of American Pathologists (US and Canada), Royal College of Pathology (UK), Royal College of Pathology Australasia (Australia, New Zealand), PALGA (The Netherlands), Swedish Society of Pathology, and others.

For more information about this project, please see [Cancer Synoptic Reporting Clinical Project Group](https://confluence.ihtsdotools.org/display/CSRPG/Cancer+Synoptic+Reporting+Clinical+Project+Group)

#### 2.9.4. International League Against Epilepsy (ILAE) <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-internationalleagueagainstep" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-internationalleagueagainstep"></a>

In line with approved harmonized terminology, this project is working on alignment including restructuring to update the hierarchy << 313307000 |Epileptic seizure (finding)|.

Further information about the project is available [here](https://confluence.ihtsdotools.org/display/IAP/Epilepsy+Status+Report)

### 2.10. Internal Quality Improvement <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-internalqualityimprovement" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-internalqualityimprovement"></a>

#### 2.10.1. Machine Readable Concept Model (MRCM) Changes <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-machinereadableconceptmodel" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-machinereadableconceptmodel"></a>

There are no changes for the MRCM in the December 2024 International Edition.

Future changes that are currently in progress can be viewed via the [MRCM Daily Build Browser](https://dailybuild.ihtsdotools.org/mrcm/?branch=MAIN)

Please see [Early Visibility Release Notifications](https://confluence.ihtsdotools.org/display/RMT/2025+Early+Visibility+Release+Notifications) for future planned changes to MRCM.

#### 2.10.2. **Annotation Reference Set** <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-annotationreferenceset" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-annotationreferenceset"></a>

The addition of content for the Annotations refset was commenced in the July 2024 International Edition release and is ongoing for attribution of text definition to organizations with a collaboration agreement, starting with Inserm Orphanet.

NOTE: approximately 130 new annotation are missing the languageDialectCode, this will be added as a batch update for a future international edition release.

### 2.11. SNOMED CT derived products <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-snomedctderivedproducts" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-snomedctderivedproducts"></a>

#### 2.11.1. ICD-10 map <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-icd-10map" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-icd-10map"></a>

The SNOMED CT to the International Statistical Classification of Diseases and Related Health Problems, Tenth Revision (© World Health Organization 1994) 2016 Version map (SNOMED CT to ICD-10 Map) is included in the SNOMED CT International Edition as a Baseline. The SNOMED CT to ICD-10 Map was created to support the epidemiological, statistical and administrative reporting needs of SNOMED International member countries and WHO Collaborating Centers.

The SNOMED CT to ICD-10 Map is released in Release Format 2 (RF2) only. It is located in the file der2\_iisssccRefset\_ExtendedMapFull\_INT\_20200731.txt, which is in the Map folder under Refset, in each of the three RF2 Release Type folders.

The SNOMED CT to ICD-10 Map is released as Refset 447562003 |SNOMED CT to ICD-10 extended map (foundation metadata concept).

The ICD-10 Mapping Technical Guide (including exemplars) is hosted here [https://confluence.ihtsdotools.org/display/DOCICD10](https://confluence.ihtsdotools.org/display/DOCICD10)

#### 2.11.2. **Content Development Activity Summary** <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-contentdevelopmentactivitysu" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-contentdevelopmentactivitysu"></a>

The map is a directed set of relationships from SNOMED CT source concepts to ICD-10 target classification codes. The SNOMED CT source domains for the MAP are limited to subtypes of 404684003 |clinical finding|, 272379006 |event| and 243796009 |situation with explicit context|. The target classification codes are ICD-10 2016 release.

Mapped content for December 2024

The map provided for the December 2024 International Edition has been updated, and now represents a complete map from SNOMED CT International Edition to ICD-10 2016 version.

* 434 newly authored concepts have been added and mapped.
* The SNOMED to ICD-O (morphology) map has no additional concepts added as a result of the ICD-O 3.2 review or added due to CRS requests.

We would welcome feedback on any issues that users of the map may detect when using the map. Issues should be submitted via [mapping@snomed.org](mailto:mapping@snomed.org)

#### 2.11.3. SNOMED CT to OWL conversion and classification <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-snomedcttoowlconversionandcl" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-snomedcttoowlconversionandcl"></a>

The repository containing the toolkit enabling simple SNOMED CT to OWL conversion and classification can be found here, including documentation on its use: [**https://github.com/IHTSDO/snomed-owl-toolkit**](https://github.com/IHTSDO/snomed-owl-toolkit)

**Please contact SNOMED International at** [**support@snomed.org**](mailto:support@ihtsdo.org) **if you would like to provide any feedback on ways to extend and improve the new toolkit.**

## 3. Technical notes <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-technicalnotes" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-technicalnotes"></a>

### 3.1. Known Issues <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-knownissues" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-knownissues"></a>

Known Issues are content or technical issues where the root cause is understood, and the resolution has been discussed and agreed but has yet to be implemented. This can be due to a number of reasons, from lack of time within the new monthly editing cycles, to the risk of impact to the stability of SNOMED CT if the fix were to be deployed at that stage in the Product lifecycle.

For the current SNOMED CT International Edition, the following Known Issues were identified, and agreed to be resolved in future editing cycles:

|     |         |             |
| --- | ------- | ----------- |
| Key | Summary | Description |

[No issues found](https://jira.ihtsdotools.org/secure/IssueNavigator.jspa?reset=true\&jqlQuery=filter+%3D+%22INT+20241201+-+Known+Issues+%28On+Hold%29%22+ORDER+BY+key+ASC+++++++++++++++++++++++++\&src=confmacro)

### 3.2. Resolved Issues <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-resolvedissues" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-resolvedissues"></a>

Resolved issues are Known Issues which were not fixed as part of the previous release lifecycle, but which have now been resolved in the latest release. They can also be issues found during testing of the current release, which were resolved before the final deployment of the Production release. Finally they can be issues which were reported or found during the testing phase, but which have been closed without any action taken.

The Resolved Issues for the current SNOMED CT International Edition can be found here:

|     |         |             |          |
| --- | ------- | ----------- | -------- |
| Key | Summary | Description | Resolved |

[No issues found](https://jira.ihtsdotools.org/secure/IssueNavigator.jspa?reset=true\&jqlQuery=filter+%3D+%22INT+20241201+-+Resolved+Issues%22+++++++++++++++ORDER+BY+key+ASC++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++\&src=confmacro)

### 3.3. Technical updates <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-technicalupdates" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-technicalupdates"></a>

#### 3.3.1. RF2 package format <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-rf2packageformat" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-rf2packageformat"></a>

The RF2 package convention dictates that all relevant files are included, regardless of whether or not there is content to be included in each release. Therefore, the package contains a mixture of files which contain both header rows and content data, and files that (intentionally) include only header records. The reason that these "empty" files are included in the package is to draw a clear distinction between:

1. ...files that have been deprecated (and therefore removed from the package completely), due to the content no longer being relevant to RF2 in future releases
2. ...files that happen to contain no data in this particular release (and are therefore included in the package with just a header record), but are still relevant to RF2, and could therefore contain content in future releases.

This allows users to easily distinguish between the two scenarios, as otherwise if files in option 2 were left out of the package it could be interpreted as an error, rather than an intentional lack of content in that release.

#### 3.3.2. Changes to the Annotations Refset format <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-changestotheannotationsrefse" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-changestotheannotationsrefse"></a>

NOTICE

**PUBLISHED JUNE 2024 RELEASE - CHANGES TO THE ANNOTATIONS REFSET FORMAT**

After discussions with the community, SNOMED International has made changes to the coverage of language in the Annotations refsets in the following way:\\

* The languageCode field was specified as the two characters of ISO-639-1 code for the language of the annotation text. The change is to include support for specifying dialect when it is applicable by adhering to RFC 5646, which allows the combination of two characters of ISO 639-1 code and two uppercase letters of country code (ISO 3166) separated by a hyphen. \\
  * The column "languageCode" has therefore been changed to "languageDialectCode".
  * Component Annotations (1292992004)
    * **OLD:** id effectiveTime active moduleId refsetId referencedComponentId languageCode typeId value
    * **NEW:** id effectiveTime active moduleId refsetId referencedComponentId languageDialectCode typeId value
  * Member Annotations (1292995002)
    * **OLD:** id effectiveTime active moduleId refsetId referencedComponentId referencedMemberId languageCode typeId value
    * **NEW:** id effectiveTime active moduleId refsetId referencedComponentId referencedMemberId languageDialectCode typeId value
* The concept _1296895003|Language code (foundation metadata concept)|_ has been inactivated and replaced by _1304275002 |Language or dialect code (foundation metadata concept)|_
* The changes apply to both the [Member Annotations String Value Reference Set](https://confluence.ihtsdotools.org/display/DOCRELFMT/5.2.4.9+Member+Annotations+String+Value+Reference+Set)[ ](https://confluence.ihtsdotools.org/display/DOCRELFMT/5.2.4.9+Member+Annotations+String+Value+Reference+Set)+ [Component Annotation String Value reference set](https://confluence.ihtsdotools.org/display/DOCRELFMT/5.2.4.8+Component+Annotations+String+Value+Reference+Set)

The addition of content for the Annotations refset was commenced in the July 2024 International Edition release.

#### 3.3.3. Changes to the RefsetDescriptor records <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-changestotherefsetdescriptor" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-changestotherefsetdescriptor"></a>

NOTICE

**PUBLISHED JUNE 2024 RELEASE - Changes to the RefsetDescriptor records**

In line with the changes to the Annotations refsets (see above for details), the following refinements have also been made to the RefsetDescriptor records:\\

* 1\. The AttributeType for the (attributeOrder=0) refsetDescriptor record for both Member + Component Annotations has been changed from:
  * 900000000000461009 |Concept type component| to
  * 900000000000460005 |Component type (foundation metadata concept)|
  * (eg)
    * _**OLD:** 6cc1d4ca-32fd-44cb-8ad3-e49f23ec7760 20231201 1 900000000000012004 900000000000456007 1292992004 900000000000518009 900000000000461009 0_\\
    * _**NEW:** 6cc1d4ca-32fd-44cb-8ad3-e49f23ec7760 20240601 1 900000000000012004 900000000000456007 1292992004 900000000000518009 900000000000460005 0_\\
    * _**OLD:** f6d9647b-6ee6-400d-9c7f-77818fa1f986 20231201 1 900000000000012004 900000000000456007 1292995002 900000000000518009 900000000000461009 0_\\
    * _**NEW:** f6d9647b-6ee6-400d-9c7f-77818fa1f986 20240601 1 900000000000012004 900000000000456007 1292995002 900000000000518009 900000000000460005 0_
* 2\. The languageDialect column for a) the (attributeOrder=2) refsetDescriptor record for Member Annotations + b) the (attributeOrder=1) refsetDescriptor record for Component Annotations has been changed from:
  * 1296895003 |Language code (foundation metadata concept)| to the new concept
  * 1304275002 |Language or dialect code (foundation metadata concept)|
  * (eg)
    * _**OLD:** 2c0d0378-c28c-4705-b8af-f5f0f8276dfd 20231201 1 900000000000012004 900000000000456007 1292992004 1296895003 900000000000465000 1_
    * _**NEW:** 2c0d0378-c28c-4705-b8af-f5f0f8276dfd 20240601 1 900000000000012004 900000000000456007 1292992004 1304275002 900000000000465000 1_
    * _**OLD:** afe9824b-1323-4407-a0b7-a028ae2b780a 20231201 1 900000000000012004 900000000000456007 1292995002 1296895003 900000000000465000 2_
    * _**NEW:** afe9824b-1323-4407-a0b7-a028ae2b780a 20240601 1 900000000000012004 900000000000456007 1292995002 1304275002 900000000000465000 2_
* 3\. The AttributeType for a) the (attributeOrder=4) refsetDescriptor record for Member Annotations (1292995002) + b) the (attributeOrder=3) refsetDescriptor record for Component Annotations (1292992004), needs to be changed from:
  * 900000000000459000 (AttributeType) to
  * 900000000000465000 (String)
  * (eg)
    * _**OLD:** 54af9962-2a35-4538-86f3-a8c38de9200b 20231201 1 900000000000012004 900000000000456007 1292995002 900000000000519001 900000000000459000 4_
    * _**NEW:** 54af9962-2a35-4538-86f3-a8c38de9200b 20240601 1 900000000000012004 900000000000456007 1292995002 900000000000519001 900000000000465000 4_
    * _**OLD:** b46405ec-5ff1-46a3-a9cc-b2ef2bba23cc 20231201 1 900000000000012004 900000000000456007 1292992004 900000000000519001 900000000000459000 3_\\
    * _**NEW:** b46405ec-5ff1-46a3-a9cc-b2ef2bba23cc 20240601 1 900000000000012004 900000000000456007 1292992004 900000000000519001 900000000000465000 3_

#### 3.3.4. Proposal to increase the maximum length of Description Types <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-proposaltoincreasethemaximum" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-proposaltoincreasethemaximum"></a>

Please find below the link to the recent announcement on the proposal to increase the limit of characters allowed in Descriptions:

* [https://confluence.ihtsdotools.org/pages/viewpage.action?pageId=238158325](https://confluence.ihtsdotools.org/pages/viewpage.action?pageId=238158325)

A community consultation has been launched to solicit feedback on a proposal to increase the size limits of SNOMED CT concept descriptions to 4096 from the current limit of 255 characters. While this change does not represent a modification of the existing specification, it could be disruptive to implementers who have coded fixed length limits into their systems.

Please read the full proposal, along with [the latest Q\&A blog post](https://www.snomed.org/news/blog%3A-snomed-international-seeks-community-feedback-on-proposed-description-character-limit-increase) which details the proposed change, its potential benefits, the feedback process and timelines, and the issues that may need to be considered in such an update:

* [https://confluence.ihtsdotools.org/mag/community-consultations/snomed-international-proposal-to-increase-description-length-limit](https://confluence.ihtsdotools.org/mag/community-consultations/snomed-international-proposal-to-increase-description-length-limit)
* [https://www.snomed.org/news/blog%3A-snomed-international-seeks-community-feedback-on-proposed-description-character-limit-increase](https://www.snomed.org/news/blog%3A-snomed-international-seeks-community-feedback-on-proposed-description-character-limit-increase)

As always, SNOMED International greatly appreciates any thoughts or opinions that you would like to raise. If you would like to provide any feedback, please do so as soon as possible, at the very latest before the deadline on **Dec 31, 2024.**

#### 3.3.5. Early visibility of impending changes in the upcoming 2025 Monthly International Edition releases <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-earlyvisibilityofimpendingch" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-earlyvisibilityofimpendingch"></a>

Please see the [Early Visibility Release Notifications](https://confluence.ihtsdotools.org/display/RMT/2025+Early+Visibility+Release+Notifications) Confluence page for details of forthcoming changes.

#### 3.3.6. Document links <a href="#snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-documentlinks" id="snomedctdecember2024internationaleditionsnomedinternationalreleasenotes-documentlinks"></a>

All links provide information that is correct and current at the time of this Release. Updated versions may be available at a later date, but if so these will need to be requested from the relevant SNOMED International teams.

**NOTE**: To access any of the links in the pdf document, please visit the Release Notes [https://confluence.ihtsdotools.org/display/RMT/SNOMED+CT+December+2024+International+Edition+-+SNOMED+International+Release+notes](https://confluence.ihtsdotools.org/display/RMT/SNOMED+CT+December+2024+International+Edition+-+SNOMED+International+Release+notes)

***

**Approvals**

| **Final Version** | **Date**    | **Approver**  | **Comments** |
| ----------------- | ----------- | ------------- | ------------ |
| 1.0               | 29 Nov 2024 | Rory Davidson | Approved     |
| 1.0               | 20 Nov 2024 | Monica Harry  | Approved     |
| 1.0               | 29 Nov 2024 | Kelly Kuru    | Approved     |

***

**Draft Amendment History**

| **Version** | **Date**    | **Editor**                                  | **Comments**                               |
| ----------- | ----------- | ------------------------------------------- | ------------------------------------------ |
| 0.1         | 01 Nov 2024 | Andrew Atkinson                             | First draft for review and comment         |
| 0.1         | 11 Nov 2024 | <p>Maria Braithwaite</p><p>Donna Morgan</p> | <p>Content Update</p><p>Mapping Update</p> |
| 1.0         | 20 Nov 2024 | Andrew Atkinson                             | Final Production changes                   |
