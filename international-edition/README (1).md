# SNOMED CT April 2025 International Edition

[Content Tracker](https://jira.ihtsdotools.org/browse/CTCP-57)

| **Release Date**     | **20250401**                                                          |
| -------------------- | --------------------------------------------------------------------- |
| **Release Status**   | <mark style="color:blue;background-color:blue;">**PRODUCTION**</mark> |
| **Document Version** | **1.0**                                                               |

© 2025 International Health Terminology Standards Development Organisation. All rights reserved. SNOMED CT® was originally created by the College of American Pathologists.

This document forms part of the International Edition release of SNOMED CT® distributed by International Health Terminology Standards Development Organisation, trading as SNOMED International, and is subject to the SNOMED CT® Affiliate License, details of which may be found at [https://www.snomed.org/snomed-ct/get-snomed](http://www.snomed.org/snomed-ct/get-snomed).

No part of this document may be reproduced or transmitted in any form or by any means, or stored in any kind of retrieval system, except by an Affiliate of SNOMED International in accordance with the SNOMED CT® Affiliate License. Any modification of this document (including without limitation the removal or modification of this notice) is prohibited without the express written permission of SNOMED International.

Any copy of this document that is not obtained directly from SNOMED International \[or a Member of SNOMED International] is not controlled by SNOMED International, and may have been modified and may be out of date. Any recipient of this document who has received it by other means is encouraged to obtain a copy directly from SNOMED International \[or a Member of SNOMED International. Details of the Members of SNOMED International may be found at [http://www.snomed.org/members/](http://www.snomed.org/members/)].

***

## ![](.gitbook/assets/273515526.png) <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-introduction" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-introduction"></a>

## 1. Introduction <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-introduction" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-introduction"></a>

### 1.1. Background <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-background" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-background"></a>

SNOMED CT terminology provides a common language that enables a consistent way of indexing, storing, retrieving, and aggregating clinical data across specialties and sites of care.

SNOMED International maintains the SNOMED CT technical design, the content architecture, the SNOMED CT content (includes the concepts table, the descriptions table, the relationships table, a history table, and ICD mappings), and related technical documentation.

### 1.2. Purpose <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-purpose" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-purpose"></a>

This document provides a summarized description of the content changes included in the April 2025 release of SNOMED Clinical Terms<sup>®</sup> (SCT) International Edition.

It also includes notes detailing the known content or technical issues where the root cause is understood, the fix has been discussed and agreed to, but has yet to be implemented.

The SNOMED International release notes are available alongside the April 2025 International Edition.

### 1.3. Scope <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-scope" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-scope"></a>

This document is written for the purpose described above and is not intended to provide details of the technical specifications for SNOMED CT or encompass every change made.

### 1.4. Audience <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-audience" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-audience"></a>

The audience includes National Release Centers, WHO-FIC release centers, vendors of electronic health records, terminology developers and managers who wish to have an understanding of changes that have been incorporated into the April 2025 International Edition.

_**Please note, you may have to register for a Confluence user account in order to access the links included in these release notes.**_

## 2. Content Development Activity <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-contentdevelopmentactivity" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-contentdevelopmentactivity"></a>

### 2.1. Summary <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-summary" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-summary"></a>

Continuous quality improvement and enhancement of existing content is an ongoing process undertaken by SNOMED International in preparation for every release. The April 2025 International Edition has seen a continuation of the work driven by contributions from: Kaiser Permanente i.e. Convergent Medical Terminology (CMT), Global Medical Device Nomenclature Agency (GMDNA), Orphanet and other domain specific collaborations as well as requests received via the Content Request System (CRS).

Additionally quality improvement activities are advanced via project driven initiatives summarized below. Additional work items impacting every release are updates to the SNOMED CT derived maps such as ICD-10 and ICD-O; details are included in these release notes.

Information about editorial decisions may be found in the [SNOMED CT Editorial Guide](https://confluence.ihtsdotools.org/display/DOCEG/SNOMED+CT+Editorial+Guide); mapping guidance for ICD-10 can be found [here](https://confluence.ihtsdotools.org/display/DOCICD10).

### 2.2. Quality Initiative <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-qualityinitiative" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-qualityinitiative"></a>

The Quality Initiative (QI) project is the implementation of the Quality Strategy. After a successful pilot project for the July 2018 Edition release, the next stage has been implemented for subsequent releases including April 2025.

Quality improvement tasks are being deployed to improve internal structural consistency and ensure compliance with editorial policy related to the stated modeling of content. Additionally, correction or addition of defining relationships is being carried out to accurately reflect current clinical knowledge and ensure the semantic reliability of descriptions associated with a concept.

#### 2.2.1. Update Surgical Approach <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-updatesurgicalapproach" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-updatesurgicalapproach"></a>

A batch change has been implemented to update surgical procedure concepts currently modeled with 424876005 |Surgical approach (attribute)| to 116688005 |Procedure approach (attribute)|.

These changes have been implemented for [this Content Tracker](https://jira.ihtsdotools.org/browse/IHTSDO-1110) and are documented in this [Briefing Note.](https://docs.google.com/document/d/1axK8um25OlIIh8Vt94RqL_cFSgrPM1NnjLhweHd4aSY/edit?tab=t.0#heading=h.v6z56t1f04d1)

### 2.3. Body Structure <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-bodystructure" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-bodystructure"></a>

#### 2.3.1. Revision of Ovarian Follicle Concepts <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-revisionofovarianfollicleconcep" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-revisionofovarianfollicleconcep"></a>

The terminology relating to the developing ovarian follicle has been expanded to include the primordial, primary, secondary and Graafian follicle. The applicable parts have also been added and rationalized so it is possible to code the individual components of the different follicle stages.

Number of concepts edited (approx): 50

#### 2.3.2. Revision of Visceral Pleura and Parietal Pleura <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-revisionofvisceralpleuraandpari" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-revisionofvisceralpleuraandpari"></a>

Content relating to the visceral pleura has been enhanced to include five layers and the parietal pleura with two layers to aid with recording pathology studies.

Number of concepts edited (approx): 14

#### 2.3.3. New Concepts for Intraarticular/Extraarticular Ligaments <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-newconceptsforintraarticular-ex" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-newconceptsforintraarticular-ex"></a>

Two new Body structure concepts have been added 1362139003 |Structure of extraarticular ligament (body structure)| and 1362140001 |Structure of intraarticular ligament (body structure)| to improve the definition of related procedure concepts.

Number of concepts edited (approx): 9

#### 2.3.4. SEP and Laterality Anatomy Reference Sets <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-sepandlateralityanatomyreferenc" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-sepandlateralityanatomyreferenc"></a>

The release file for the lateralizable body structure reference set has been updated and validated.

The release file for the SEP reference set has been updated and validated.

### 2.4. Clinical Finding <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-clinicalfinding" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-clinicalfinding"></a>

#### 2.4.1. Revision of Hemorrhagic Cerebral Infarction <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-revisionofhemorrhagiccerebralin" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-revisionofhemorrhagiccerebralin"></a>

230706003 |Hemorrhagic cerebral infarction (disorder)| and subtypes have been remodeled. An additional supertype of 50960005 |Hemorrhage (morphologic abnormality)| has been added to 88880001 |Hemorrhagic necrosis (morphologic abnormality)| to improve subsumption.

230706003 |Hemorrhagic cerebral infarction (disorder)| is now a subtype of 5571000124103|Cerebrovascular accident with intracranial hemorrhage (disorder)|. A new synonym of 'ischemic stroke with hemorrhagic transformation' has also been added to the concept.

Number of concepts edited (approx): 12

#### 2.4.2. Revision of Inflammatory Bowel Disease <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-revisionofinflammatoryboweldise" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-revisionofinflammatoryboweldise"></a>

24526004 |Inflammatory bowel disease (disorder)| (IBD), including 34000006 |Crohn's disease (disorder)|, has been remodeled to classify as a disorder of the digestive tract. This change was made in response to submissions that, while recognizing the systemic nature of IBD, it should be classified as a digestive system disorder. The same adjustment has been applied to its subtype, Crohn’s disease. IBD remains classified as a subtype of 56019007 |Systemic disease (disorder)|.

Extraintestinal Crohn’s disease, which includes manifestations such as arthritis, iritis, and skin conditions, occurs outside the digestive tract based on its clinical definition. It has been remodeled as being due to Crohn’s disease. In a small number of cases, two role groups have been utilized to reflect that these manifestations frequently co-occur with IBD or Crohn’s disease, as indicated by their Fully Specified Name.

No changes were necessary for ulcerative colitis, as it was already modeled as a disorder of the colon.

Number of concepts edited (approx): 20

#### 2.4.3. Revision of Intestinal Obstruction <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-revisionofintestinalobstruction" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-revisionofintestinalobstruction"></a>

710572000 |Intestinal obstruction co-occurrent and due to decreased peristalsis (disorder)| and 10 other functional ileus concepts (e.g., 55525008 |Paralytic ileus (disorder)|) have been remodeled to reflect that these are functional rather than mechanical intestinal obstructions. 1162567000 |Postoperative paralytic ileus (disorder)| is now a subtype of 235833007 |Postoperative ileus (disorder)|.

Number of concepts edited (approx): 11

Future changes are planned [for this Content Tracker.](https://jira.ihtsdotools.org/browse/IHTSDO-1275)

#### 2.4.4. New Concepts for Genetic Disease <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-newconceptsforgeneticdisease" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-newconceptsforgeneticdisease"></a>

New concepts have been added for genetic disease:

* 1362108000 |Genetic intellectual disability (disorder)|
* 1359741006 |Genetic obesity disorder (disorder)|
* 1359760004 |Genetic childhood obesity disorder (disorder)|
* 1359761000 |Common polygenetic childhood obesity (disorder)|
* 1359763002 |Genetic syndromic childhood obesity (disorder)|

#### 2.4.5. New Concepts for Fetal Movement <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-newconceptsforfetalmovement" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-newconceptsforfetalmovement"></a>

Six new concepts have been added as subtypes of 289431008 |Fetal movements present (finding)|. Three new concepts have been added under 268470003 |Fetal movements felt (finding)| and a further three under 169731002 |Fetal movements seen (finding)| to capture whether the reporter is the mother, her partner, or a healthcare professional.

Number of concepts edited (approx): 6

#### 2.4.6. Update Fully Specified Name from 'Tumor' to 'Neoplasm' <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-updatefullyspecifiednamefromtum" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-updatefullyspecifiednamefromtum"></a>

Approximately 60 concepts with 'Tumor of' as the start of the FSN for descendants of 64572001 |Disease (disorder)| have had the description updated to 'Neoplasm of'.

#### 2.4.7. Inactivation of 'Splinter of X' Concepts <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-inactivationofsplinterofxconcep" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-inactivationofsplinterofxconcep"></a>

Concepts that represent 'splinter of \<x>, without major open wound' and 'splinter of \<x>, without major open wound, infected' are classification constructs. These concepts have been inactivated with historical associations to the base concept. Where required, new 'base' concepts have been created.

### 2.5. Procedure <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-procedure" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-procedure"></a>

#### 2.5.1. Revision of Endoscopic Ultrasound <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-revisionofendoscopicultrasound" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-revisionofendoscopicultrasound"></a>

447793000 |Endoscopic ultrasonography of mediastinum (procedure)| has been inactivated.

Content in this area has been revised for alignment of method and device.

Number of concepts edited (approx): 8

#### 2.5.2. Revision of B-Mode Ultrasound <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-revisionofb-modeultrasound" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-revisionofb-modeultrasound"></a>

B-mode ultrasound, also known as brightness mode ultrasound, is a technique for generating two-dimensional grayscale images. B-scan ultrasound is the application of B-mode ultrasound, often used in areas such as ophthalmology, where it provides cross-sectional imaging of ocular and orbital structures. Since B-scan directly uses B-mode ultrasound it has now been defined using 399009009 |B mode ultrasound (qualifier value)|, ensuring consistency and interoperability.

Number of concepts edited (approx): 23

#### 2.5.3. Radiographic Imaging <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-radiographicimaging" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-radiographicimaging"></a>

Work is progressing for [t](https://jira.ihtsdotools.org/browse/IHTSDO-161)[his content tracker](https://jira.ihtsdotools.org/browse/IHTSDO-161) for information please see [the informational briefing note here.](https://confluence.ihtsdotools.org/display/cmag/Proposed+update+to+content+in+the+Radiographic+imaging+procedure+\(procedure\)+hierarchy)

### 2.6. Observable Entity <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-observableentity" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-observableentity"></a>

#### 2.6.1. Revision of Assessment Scale Score <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-revisionofassessmentscalescore" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-revisionofassessmentscalescore"></a>

Concepts that are subtypes of 363788007 |Clinical history/examination observable (observable entity)| and contain the word ‘score’ that are not also subtypes of 782487009 |Assessment score (observable entity)|, have had 782487009 |Assessment score (observable entity)| added as another supertype.

Number of concepts edited (approx): 525

#### 2.6.2. Inactivation and Replacement of 284937000 |Ability to sit on toilet (observable entity)| and Related Finding Concepts <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-inactivationandreplacementof284" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-inactivationandreplacementof284"></a>

The concept 284937000 |Ability to sit on toilet (observable entity)| and related finding concepts e.g. 284938005 |Able to sit on toilet (finding)| are ambiguous as they could be interpreted to mean the ability to maintain a sitting position on a toilet seat or the ability to sit down on a toilet seat. These concepts have been inactivated and replaced with new concepts:

* Ability to maintain sitting position on toilet seat (observable entity)
* Ability to sit down on toilet seat (observable entity)

Relevant finding concepts e.g. Able to maintain sitting position on toilet seat (finding) have also been added.

### 2.7. Pharmaceutical/Biologic Product <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-pharmaceutical-biologicproduct" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-pharmaceutical-biologicproduct"></a>

#### 2.7.1. Inactivation of Paratyphoid Vaccine <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-inactivationofparatyphoidvaccin" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-inactivationofparatyphoidvaccin"></a>

Concepts referencing a stand-alone paratyphoid vaccination have been inactivated. There is currently no vaccine to prevent paratyphoid fever, and standalone paratyphoid vaccines are unlikely to be widely adopted.

4 concepts inactivated:

* 83798008 |Paratyphoid fever vaccination (procedure)|
* 428601009 |Paratyphoid vaccine (medicinal product)|
* 192707002 |Post paratyphoid vaccination encephalitis (disorder)|
* 219079000 |Adverse reaction to component of paratyphoid vaccine (disorder)|

Number of concepts edited (approx): 4

### 2.8. Situation With Explicit Context <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-situationwithexplicitcontext" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-situationwithexplicitcontext"></a>

#### 2.8.1. Revision of Personal History of Primary Malignant Neoplasm <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-revisionofpersonalhistoryofprim" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-revisionofpersonalhistoryofprim"></a>

Since their creation (primarily in 2005), Personal history of primary malignant neoplasm of X (situation) concepts have consistently represented a history of a primary malignant neoplasm. As a result, the non-synonymous 'malignant neoplasm' preferred term (PT) and synonym have been inactivated for ten situation concepts. The concepts have been changed from 'personal history of' to 'history of' in the new descriptions.

These descriptions may have originated from historical ICD clinical coding rules, which assumes that a malignancy unspecified as primary or metastatic is classified as primary.

Number of concepts edited (approx): 10

### 2.9. Qualifier Value <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-qualifiervalue" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-qualifiervalue"></a>

#### 2.9.1. New Semantic Tag <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-newsemantictag" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-newsemantictag"></a>

A new semantic tag has been added:

* 540091010000105| Calculation (calculation)|

The new concept is a descendant of (qualifier value). This concept will enable representation of concepts that are derived from calculations on other observations (e.g., “Anion gap in blood,” “Anion gap in urine”) with a relationship of Component (attribute) and value from the (calculation) sub-hierarchy.

### 2.10. Collaboration/Harmonization Agreements <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-collaboration-harmonizationagre" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-collaboration-harmonizationagre"></a>

#### 2.10.1. Convergent Medical Terminology (CMT) <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-convergentmedicalterminology-cm" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-convergentmedicalterminology-cm"></a>

80 new CMT concepts have been added with a focus on ophthalmology.

#### 2.10.2. Orphanet <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-orphanet" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-orphanet"></a>

Working in collaboration with [Orphanet](https://www.orpha.net/) efforts are ongoing to update rare disease concepts in SNOMED CT to maintain alignment with Orphanet for the annual update of the SNOMED CT to Orphanet Maps.

Work is ongoing to annotate content added for the Orphanet project with attribution to Inserm Orphanet. It is expected this work will be completed for the May 2025 International Edition release.

All of the concepts added for the Orphanet project have been mapped to ICD-10.

#### 2.10.3. Gravity <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-gravity" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-gravity"></a>

Work for this project is ongoing.

#### 2.10.4. Nursing <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-nursing" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-nursing"></a>

Work for this project is ongoing.

#### 2.10.5. Cancer Synoptic Reporting <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-cancersynopticreporting" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-cancersynopticreporting"></a>

Cancer synoptic reports are used by many member countries to record pathology examination of cancer specimens including the College of American Pathologists (US and Canada), Royal College of Pathology (UK), Royal College of Pathology Australasia (Australia, New Zealand), PALGA (The Netherlands), Swedish Society of Pathology, and others.

For more information about this project, please see [Cancer Synoptic Reporting Clinical Project Group](https://confluence.ihtsdotools.org/display/CSRPG/Cancer+Synoptic+Reporting+Clinical+Project+Group)

#### 2.10.6. International League Against Epilepsy (ILAE) <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-internationalleagueagainstepile" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-internationalleagueagainstepile"></a>

In line with approved harmonized terminology, this project is working on alignment including restructuring to update the hierarchy << 313307000 |Epileptic seizure (finding)|.

Further information about the project is available [here](https://confluence.ihtsdotools.org/display/IAP/Epilepsy+Status+Report)

### 2.11. Internal Quality Improvement <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-internalqualityimprovement" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-internalqualityimprovement"></a>

#### 2.11.1. Machine Readable Concept Model (MRCM) Changes <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-machinereadableconceptmodel-mrc" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-machinereadableconceptmodel-mrc"></a>

There have been two changes for the MRCM in the April 2025 International Edition.

* Extend range of component attribute to include <<540091010000105 |Calculation (calculation)|
* Update the range of 370132008 |Scale type (attribute)| to remove the redundancy. 117362005 |Nominal value (qualifier value)| is a subconcept of 26716007 |Qualitative (qualifier value)|. Hence, << 117362005 |Nominal value (qualifier value)| can be removed with no impact on the range.

Future changes that are currently in progress can be viewed via the [MRCM Daily Build Browser](https://dailybuild.ihtsdotools.org/mrcm/?branch=MAIN)

Please see [Early Visibility Release Notifications](https://confluence.ihtsdotools.org/display/RMT/2025+Early+Visibility+Release+Notifications) for future planned changes to MRCM.

#### 2.11.2. **Annotation Reference Set** <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-annotationreferenceset" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-annotationreferenceset"></a>

The addition of content for the Annotations refset was commenced in the July 2024 International Edition release and is ongoing for attribution of text definition to organizations with a collaboration agreement, starting with Inserm Orphanet.

### 2.12. SNOMED CT derived products <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-snomedctderivedproducts" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-snomedctderivedproducts"></a>

#### 2.12.1. ICD-10 map <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-icd-10map" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-icd-10map"></a>

The SNOMED CT to the International Statistical Classification of Diseases and Related Health Problems, Tenth Revision (© World Health Organization 1994) 2016 Version map (SNOMED CT to ICD-10 Map) is included in the SNOMED CT International Edition as a Baseline. The SNOMED CT to ICD-10 Map was created to support the epidemiological, statistical and administrative reporting needs of SNOMED International member countries and WHO Collaborating Centers.

The SNOMED CT to ICD-10 Map is released in Release Format 2 (RF2) only. It is located in the file der2\_iisssccRefset\_ExtendedMapFull\_INT\_20200731.txt, which is in the Map folder under Refset, in each of the three RF2 Release Type folders.

The SNOMED CT to ICD-10 Map is released as Refset 447562003 |SNOMED CT to ICD-10 extended map (foundation metadata concept).

The ICD-10 Mapping Technical Guide (including exemplars) is hosted here [https://confluence.ihtsdotools.org/display/DOCICD10](https://confluence.ihtsdotools.org/display/DOCICD10).

#### 2.12.2. **Content Development Activity Summary** <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-contentdevelopmentactivitysumma" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-contentdevelopmentactivitysumma"></a>

The map is a directed set of relationships from SNOMED CT source concepts to ICD-10 target classification codes. The SNOMED CT source domains for the map are constrained to subtypes of 404684003 |Clinical finding (finding)|, 272379006 |Event (event)|, and 243796009 |Situation with explicit context (situation)|. The target classification used is the ICD-10 WHO version 2016 ([https://icd.who.int/browse10/2016/en#/](https://icd.who.int/browse10/2016/en#/)).

**Mapped content for April 2025 release**

The map provided for this release has been updated and represents a complete map from the April 2025 release of the SNOMED CT International Edition to the ICD-10 WHO version 2016.

This includes:

* Addition of 407 new mapped concepts
* Updates to 334 existing mapped concepts
* Retirement of 110 mapped concepts

The SNOMED CT to ICD-O morphology map has zero (0) additions for this release.

We welcome feedback on any issues that users may detect when deploying the map. Issues can be reported to [mapping@snomed.org](mailto:mapping@snomed.org).

#### 2.12.3. SNOMED CT to OWL conversion and classification <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-snomedcttoowlconversionandclass" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-snomedcttoowlconversionandclass"></a>

The repository containing the toolkit enabling simple SNOMED CT to OWL conversion and classification can be found here, including documentation on its use: [**https://github.com/IHTSDO/snomed-owl-toolkit**](https://github.com/IHTSDO/snomed-owl-toolkit)

**Please contact SNOMED International at** [**support@snomed.org**](mailto:support@ihtsdo.org) **if you would like to provide any feedback on ways to extend and improve the new toolkit.**

## 3. Technical notes <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-technicalnotes" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-technicalnotes"></a>

### 3.1. Known Issues <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-knownissues" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-knownissues"></a>

Known Issues are content or technical issues where the root cause is understood, and the resolution has been discussed and agreed but has yet to be implemented. This can be due to a number of reasons, from lack of time within the new monthly editing cycles, to the risk of impact to the stability of SNOMED CT if the fix were to be deployed at that stage in the Product lifecycle.

For the current SNOMED CT International Edition, the following Known Issues were identified, and agreed to be resolved in future editing cycles:

|                                                                          |                                                                                                                                                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Key                                                                      | Summary                                                                                                                                                                                                                                                           | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| [ISRS-7135](https://jira.ihtsdotools.org/browse/ISRS-7135?src=confmacro) | [SNOMED CT International edition, 2025-02-01, 25334385-83b3-4531-8e6e-cf9e32ebccd2, Two active descriptions in the same hierarchy should not share the same term, unless the language is different.](https://jira.ihtsdotools.org/browse/ISRS-7135?src=confmacro) | <p>Two active descriptions in the same hierarchy should not share the same term, unless the language is different.<br>Total number of failures: 178<br>Environment: PROD<br>First 10 failures:</p><ul><li>{ "conceptId": "428639001", "componentId": "2695405017", "branchPath": "MAIN/BLKUPDATE6", "reason": "Temporarily exception listed whilst being reviewed for QI-900", "fullComponent": "1,900000000000207008,428639001,en,900000000000013009,Insert,900000000000448009" }</li><li>{ "conceptId": "428639001", "componentId": "2695405017", "branchPath": "MAIN/BLKUPDATE6", "reason": "Temporarily exception listed whilst being reviewed for QI-900", "fullComponent": "1,900000000000207008,428639001,en,900000000000013009,Insert,900000000000448009" }</li><li>{ "conceptId": "428639001", "componentId": "2695405017", "branchPath": "MAIN/BLKUPDATE6", "reason": "Temporarily exception listed whilst being reviewed for QI-900", "fullComponent": "1,900000000000207008,428639001,en,900000000000013009,Insert,900000000000448009" }</li><li>{ "conceptId": "428639001", "componentId": "2695405017", "branchPath": "MAIN/BLKUPDATE6", "reason": "Temporarily exception listed whilst being reviewed for QI-900", "fullComponent": "1,900000000000207008,428639001,en,900000000000013009,Insert,900000000000448009" }</li><li>{ "conceptId": "733001005", "componentId": "3498547014", "branchPath": "MAIN/BLKUPDATE6", "reason": "Temporarily exception listed whilst being reviewed for QI-900", "fullComponent": "1,900000000000207008,733001005,en,900000000000013009,Lyophilisate,900000000000448009" }</li><li>{ "conceptId": "738993004", "componentId": "3534539012", "branchPath": "MAIN/BLKUPDATE6", "reason": "Temporarily exception listed whilst being reviewed for QI-900", "fullComponent": "1,900000000000207008,738993004,en,900000000000013009,Insert,900000000000448009" }</li><li>{ "conceptId": "738993004", "componentId": "3534539012", "branchPath": "MAIN/BLKUPDATE6", "reason": "Temporarily exception listed whilst being reviewed for QI-900", "fullComponent": "1,900000000000207008,738993004,en,900000000000013009,Insert,900000000000448009" }</li><li>{ "conceptId": "225780003", "componentId": "339260018", "branchPath": "MAIN/BLKUPDATE6", "reason": "Temporarily exception listed whilst being reviewed for QI-900", "fullComponent": "1,900000000000207008,225780003,en,900000000000013009,Sublingual,900000000000448009" }</li><li>{ "conceptId": "733013000", "componentId": "3498572014", "branchPath": "MAIN/BLKUPDATE6", "reason": "Temporarily exception listed whilst being reviewed for QI-900", "fullComponent": "1,900000000000207008,733013000,en,900000000000013009,Sachet,900000000000448009" }</li><li>{ "conceptId": "410670007", "componentId": "2472324010", "branchPath": "MAIN/BLKUPDATE6", "reason": "Temporarily exception listed whilst being reviewed for QI-900", "fullComponent": "1,900000000000012004,410670007,en,900000000000013009,Time,900000000000448009" }</li></ul><p>KNOWN ISSUE: SNOMED International content team have confirmed that these issues have been analysed and exception-listed in the short term due to their low priority. They will be discussed and resolved by the end of 2025.</p> |

[1 issue](https://jira.ihtsdotools.org/secure/IssueNavigator.jspa?reset=true\&jqlQuery=filter+%3D+%22INT+20250201+-+Known+Issues+%28On+Hold%29%22+ORDER+BY+key+ASC++++++++++++++++++++++++++++++\&src=confmacro)

### 3.2. Resolved Issues <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-resolvedissues" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-resolvedissues"></a>

Resolved issues are Known Issues which were not fixed as part of the previous release lifecycle, but which have now been resolved in the latest release. They can also be issues found during testing of the current release, which were resolved before the final deployment of the Production release. Finally they can be issues which were reported or found during the testing phase, but which have been closed without any action taken.

The Resolved Issues for the current SNOMED CT International Edition can be found here:

|     |         |             |          |
| --- | ------- | ----------- | -------- |
| Key | Summary | Description | Resolved |

[No issues found](https://jira.ihtsdotools.org/secure/IssueNavigator.jspa?reset=true\&jqlQuery=filter+%3D+%22INT+20250201+-+Resolved+Issues%22+++++++++++++++ORDER+BY+key+ASC++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++\&src=confmacro)

### 3.3. Technical updates <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-technicalupdates" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-technicalupdates"></a>

#### 3.3.1. RF2 package format <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-rf2packageformat" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-rf2packageformat"></a>

The RF2 package convention dictates that all relevant files are included, regardless of whether or not there is content to be included in each release. Therefore, the package contains a mixture of files which contain both header rows and content data, and files that (intentionally) include only header records. The reason that these "empty" files are included in the package is to draw a clear distinction between:

1. ...files that have been deprecated (and therefore removed from the package completely), due to the content no longer being relevant to RF2 in future releases
2. ...files that happen to contain no data in this particular release (and are therefore included in the package with just a header record), but are still relevant to RF2, and could therefore contain content in future releases.

This allows users to easily distinguish between the two scenarios, as otherwise if files in option 2 were left out of the package it could be interpreted as an error, rather than an intentional lack of content in that release.

#### 3.3.2. Proposal to increase the maximum length of Description Types <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-proposaltoincreasethemaximumlen" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-proposaltoincreasethemaximumlen"></a>

Please find below the link to the recent announcement on the proposal to increase the limit of characters allowed in Descriptions:

* [https://confluence.ihtsdotools.org/pages/viewpage.action?pageId=238158325](https://confluence.ihtsdotools.org/pages/viewpage.action?pageId=238158325)

A community consultation was launched to solicit feedback on a proposal to increase the size limits of SNOMED CT concept descriptions to 4096 from the current limit of 255 characters. While this change does not represent a modification of the existing specification, it could be disruptive to implementers who have coded fixed length limits into their systems.

Please read the full proposal, along with [the latest Q\&A blog post](https://www.snomed.org/news/blog%3A-snomed-international-seeks-community-feedback-on-proposed-description-character-limit-increase) which details the proposed change, its potential benefits, the feedback process and timelines, and the issues that may need to be considered in such an update:

* [https://confluence.ihtsdotools.org/mag/community-consultations/snomed-international-proposal-to-increase-description-length-limit](https://confluence.ihtsdotools.org/mag/community-consultations/snomed-international-proposal-to-increase-description-length-limit)
* [https://www.snomed.org/news/blog%3A-snomed-international-seeks-community-feedback-on-proposed-description-character-limit-increase](https://www.snomed.org/news/blog%3A-snomed-international-seeks-community-feedback-on-proposed-description-character-limit-increase)

As always, SNOMED International greatly appreciated all feedback provided before the deadline (which was Dec 31, 2024). A summary of the feedback will be collated and disseminated in 2025, alongside a plan for the transition.

#### 3.3.3. Early visibility of impending changes in the upcoming 2025 Monthly International Edition releases <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-earlyvisibilityofimpendingchang" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-earlyvisibilityofimpendingchang"></a>

Please see the [Early Visibility Release Notifications](https://confluence.ihtsdotools.org/display/RMT/2025+Early+Visibility+Release+Notifications) Confluence page for details of forthcoming changes.

#### 3.3.4. Document links <a href="#snomedctapril2025internationaleditionsnomedinternationalreleasenotes-documentlinks" id="snomedctapril2025internationaleditionsnomedinternationalreleasenotes-documentlinks"></a>

All links provide information that is correct and current at the time of this Release. Updated versions may be available at a later date, but if so these will need to be requested from the relevant SNOMED International teams.

**NOTE**: To access any of the links in the pdf document, please visit the Release Notes [https://confluence.ihtsdotools.org/display/RMT/SNOMED+CT+April+2025+International+Edition+-+SNOMED+International+Release+notes](https://confluence.ihtsdotools.org/display/RMT/SNOMED+CT+April+2025+International+Edition+-+SNOMED+International+Release+notes)

***

**Approvals**

| **Final Version** | **Date**    | **Approver**  | **Comments** |
| ----------------- | ----------- | ------------- | ------------ |
| 1.0               | 17 Mar 2025 | Rory Davidson | Approved     |
| 1.0               | 17 Mar 2025 | Monica Harry  | Approved     |
| 1.0               | 18 Mar 2025 | Kelly Kuru    | Approved     |

***

**Draft Amendment History**

| **Version** | **Date**    | **Editor**                                           | **Comments**                               |
| ----------- | ----------- | ---------------------------------------------------- | ------------------------------------------ |
| 0.1         | 06 Mar 2025 | Andrew Atkinson                                      | First draft for review and comment         |
| 0.1         | 10 Mar 2025 | <p>Maria Braithwaite</p><p>Michael Harwood-Jones</p> | <p>Content Update</p><p>Mapping Update</p> |
| 1.0         | 16 Mar 2025 | Andrew Atkinson                                      | Final Production changes                   |
