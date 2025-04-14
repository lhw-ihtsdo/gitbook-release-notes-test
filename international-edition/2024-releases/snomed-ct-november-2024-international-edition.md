# SNOMED CT November 2024 International Edition

[Content Tracker](https://jira.ihtsdotools.org/browse/CTCP-57)

| **Release Date**     | **20241101**                                                          |
| -------------------- | --------------------------------------------------------------------- |
| **Release Status**   | <mark style="color:blue;background-color:blue;">**PRODUCTION**</mark> |
| **Document Version** | **1.0**                                                               |

© 2025 International Health Terminology Standards Development Organisation. All rights reserved. SNOMED CT® was originally created by the College of American Pathologists.

This document forms part of the International Edition release of SNOMED CT® distributed by International Health Terminology Standards Development Organisation, trading as SNOMED International, and is subject to the SNOMED CT® Affiliate License, details of which may be found at [https://www.snomed.org/snomed-ct/get-snomed](http://www.snomed.org/snomed-ct/get-snomed).

No part of this document may be reproduced or transmitted in any form or by any means, or stored in any kind of retrieval system, except by an Affiliate of SNOMED International in accordance with the SNOMED CT® Affiliate License. Any modification of this document (including without limitation the removal or modification of this notice) is prohibited without the express written permission of SNOMED International.

Any copy of this document that is not obtained directly from SNOMED International \[or a Member of SNOMED International] is not controlled by SNOMED International, and may have been modified and may be out of date. Any recipient of this document who has received it by other means is encouraged to obtain a copy directly from SNOMED International \[or a Member of SNOMED International. Details of the Members of SNOMED International may be found at [http://www.snomed.org/members/](http://www.snomed.org/members/)].

***

![](../.gitbook/assets/256869561.jpg)

## 1. Introduction <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-introduction" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-introduction"></a>

### 1.1. Background <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-background" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-background"></a>

SNOMED CT terminology provides a common language that enables a consistent way of indexing, storing, retrieving, and aggregating clinical data across specialties and sites of care.

SNOMED International maintains the SNOMED CT technical design, the content architecture, the SNOMED CT content (includes the concepts table, the descriptions table, the relationships table, a history table, and ICD mappings), and related technical documentation.

### 1.2. Purpose <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-purpose" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-purpose"></a>

This document provides a summarized description of the content changes included in the November 2024 release of SNOMED Clinical Terms<sup>®</sup> (SCT) International Edition.

It also includes notes detailing the known content or technical issues where the root cause is understood, the fix has been discussed and agreed to, but has yet to be implemented.

The SNOMED International release notes are available alongside the November 2024 International Edition.

### 1.3. Scope <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-scope" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-scope"></a>

This document is written for the purpose described above and is not intended to provide details of the technical specifications for SNOMED CT or encompass every change made.

### 1.4. Audience <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-audience" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-audience"></a>

The audience includes National Release Centers, WHO-FIC release centers, vendors of electronic health records, terminology developers and managers who wish to have an understanding of changes that have been incorporated into the November 2024 International Edition.

_**Please note, you may have to register for a Confluence user account in order to access the links included in these release notes.**_

## 2. Content Development Activity <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-contentdevelopmentactivity" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-contentdevelopmentactivity"></a>

### 2.1. Summary <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-summary" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-summary"></a>

Continuous quality improvement and enhancement of existing content is an ongoing process undertaken by SNOMED International in preparation for every release. The November 2024 International Edition has seen a continuation of the work driven by contributions from: Kaiser Permanente i.e. Convergent Medical Terminology (CMT), Global Medical Device Nomenclature Agency (GMDNA), Orphanet and other domain specific collaborations as well as requests received via the Content Request System (CRS).

Additionally quality improvement activities are advanced via project driven initiatives summarized below. Additional work items impacting every release are updates to the SNOMED CT derived maps such as ICD-10 and ICD-O; details are included in these release notes.

Information about editorial decisions may be found in the [SNOMED CT Editorial Guide](https://confluence.ihtsdotools.org/display/DOCEG/SNOMED+CT+Editorial+Guide); mapping guidance for ICD-10 can be found [here](https://confluence.ihtsdotools.org/display/DOCICD10).

### 2.2. Quality Initiative <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-qualityinitiative" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-qualityinitiative"></a>

The Quality Initiative (QI) project is the implementation of the Quality Strategy. After a successful pilot project for the July 2018 Edition release, the next stage has been implemented for subsequent releases including November 2024.

Quality improvement tasks are being deployed to improve internal structural consistency and ensure compliance with editorial policy related to the stated modeling of content. Additionally, correction or addition of defining relationships is being carried out to accurately reflect current clinical knowledge and ensure the semantic reliability of descriptions associated with a concept.

#### 2.2.1. Update Spondylosis and Osteoarthritis <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-updatespondylosisandosteoart" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-updatespondylosisandosteoart"></a>

Concepts relating to 8847002|Spondylosis (disorder)| and 396275006|Osteoarthritis (disorder)| have been remodeled to represent the difference between these two closely related terms. Spondylosis represents a more general degenerative process in the spine whereas osteoarthritis is now recognized as having both a degenerative and inflammatory process. Additionally, spondylosis may affect any area of the spine whereas osteoarthritis of the spine is generally restricted to the joint structure.

An FSN which specifies 'Osteoarthritis' has been added to concepts where the current FSN represents 'Degenerative joint disease', for example:

* 22193007|Degenerative joint disease of hand (disorder)|

has been updated to

* 22193007 |Osteoarthritis of joint of hand (disorder)|

#### 2.2.2. Update Procedure Device <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-updateproceduredevice" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-updateproceduredevice"></a>

Procedure content modeled with 424226004 |Using device (attribute)| and 363699004 |Direct device (attribute)| has been updated to align with the Editorial Guide.

Number of concepts edited (approx): 163

#### 2.2.3. Update 17423001 |Epiphysiodesis (procedure)| and Descendants <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-update17423001-or-epiphysiod" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-update17423001-or-epiphysiod"></a>

17423001 |Epiphysiodesis (procedure)| and descendants has been reviewed and remodeled where required.

Number of concepts edited (approx): 36

#### 2.2.4. New Grouping Concepts for Cannula/Catheter Procedures <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-newgroupingconceptsforcannul" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-newgroupingconceptsforcannul"></a>

New concepts have been added

* 1344997009 |Cannula or catheter procedure (procedure)|
* 1344996000 |Cannulation or catheterization (procedure)|

Both new concepts have been added with GCI and group procedures of this type into one area of the hierarchy.

Number of concepts edited (approx): 24

#### 2.2.5. Update 65801008 |Excision (procedure)| Hierarchy <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-update65801008-or-excision-p" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-update65801008-or-excision-p"></a>

65801008 |Excision (procedure)| and descendants have been reviewed and remodeled where required. 129304002 |Excision - action (qualifier value)| has been added as the target value for the 260686004 |Method (attribute)| with update to proximal primitive parent.

360020006 |Extirpation - action (qualifier value) has been made a subtype of 129304002 |Excision - action (qualifier value)|.

### 2.3. Body Structure <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-bodystructure" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-bodystructure"></a>

#### 2.3.1. Inactivation of 127907005 |Structure of undescended testis (body structure)| and Descendants <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-inactivationof127907005-or-s" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-inactivationof127907005-or-s"></a>

127907005 |Structure of undescended testis (body structure)| and descendants have been inactivated as they are not true anatomical notions but relate to an abnormal location of a testis. These concepts have been given a historical association to an appropriate disorder in the 204878001 |Undescended testicle (disorder)| hierarchy.

Procedure concepts relating to undescended testis have been remodeled where appropriate using the ‘Has focus’ attribute: as a consequence all concepts in the hierarchy 85419002 |Orchidopexy (procedure)| have been modeled using this attribute-value pair where the procedure is exclusively performed for undescended testis (some orchidopexy procedures can also be deployed for torsion of the testes).

Number of concepts edited (approx): 40

#### 2.3.2. Remodel 88481005 |Sublingual gland structure (body structure)| <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-remodel88481005-or-sublingua" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-remodel88481005-or-sublingua"></a>

Concepts relating to 88481005 |Sublingual gland structure (body structure)| have been updated to harmonize the approach used with the other major salivary gland - specifically an 'apparatus' parent.

76922005 |Structure of polystomatic sublingual gland (body structure)| and 3198009 |Structure of monostomatic sublingual gland (body structure)| have been inactivated as they are not used to describe human anatomy. The major salivary glands have also been defined in relation to the region where they are located which has resulted in additional superordinates for the disorders and procedures which the anatomy defines.

Number of concepts edited (approx): 10

#### 2.3.3. New Concept 1351430008 |Structure of velopharynx (body structure)| <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-newconcept1351430008-or-stru" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-newconcept1351430008-or-stru"></a>

1351430008 |Structure of velopharynx (body structure)| has been added which is an important notion particularly in relation to disorders of speech and language - those disorders have been remodeled with this new concept resulting in improved classification.

Number of concepts edited (approx): 20

#### 2.3.4. Update Descendants of 372203005 |Parotid gland part (body structure)| <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-updatedescendantsof372203005" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-updatedescendantsof372203005"></a>

​New descendants of 372203005 |Parotid gland part (body structure)| have been added:

* 1351360004 |Structure of glenoid process of parotid gland (body structure)|
* 1351361000 |Structure of pterygoid process of parotid gland (body structure)|
* 1351369003 |Structure of corniculate tubercle (body structure)|.

Number of concepts edited (approx): 8

#### 2.3.5. SEP and Laterality Anatomy Reference Sets <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-sepandlateralityanatomyrefer" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-sepandlateralityanatomyrefer"></a>

The release file for the lateralizable body structure reference set has been updated and validated.

The release file for the SEP reference set has been updated and validated.

### 2.4. Clinical Finding <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-clinicalfinding" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-clinicalfinding"></a>

#### 2.4.1. Update Crystal-associated Arthropathies <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-updatecrystal-associatedarth" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-updatecrystal-associatedarth"></a>

Crystal-associated arthropathies such as 1348274009 |Hydroxyapatite deposition disease (disorder)| and descendants have been modeled as subtypes of Periarthritis as the deposition occurs in the periarticular soft tissues.

### 2.5. Procedure <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-procedure" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-procedure"></a>

#### 2.5.1. Radiographic Imaging <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-radiographicimaging" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-radiographicimaging"></a>

Work is progressing for [t](https://jira.ihtsdotools.org/browse/IHTSDO-161)[his content tracker](https://jira.ihtsdotools.org/browse/IHTSDO-161) for information please see [the informational briefing note here.](https://confluence.ihtsdotools.org/display/cmag/Proposed+update+to+content+in+the+Radiographic+imaging+procedure+\(procedure\)+hierarchy)

#### 2.5.2. Revision of 363243005|Nonsurgical manipulation procedure (procedure)| <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-revisionof363243005-or-nonsu" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-revisionof363243005-or-nonsu"></a>

363243005|Nonsurgical manipulation procedure (procedure)| has been updated to add missing subtypes.

#### 2.5.3. Reactivation of 307279007 |Replacement of heart valve with prosthesis (procedure)| <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-reactivationof307279007-or-r" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-reactivationof307279007-or-r"></a>

307279007 |Replacement of heart valve with prosthesis (procedure)| has been reactivated (with new FSN). The previous modeling with a single role group using the 713295009 |Surgical replacement - action (qualifier value)| has been substituted with 2 role groups.

* Role group one: 129306000 |Surgical removal - action (qualifier value)| and 405813007 |Procedure site - Direct (attribute)| with target values << 17401000 |Cardiac valve structure (body structure)|
* Role group two: 129338005 |Surgical implantation - action (qualifier value)| and 405814001 |Procedure site - Indirect (attribute)| with target values << 305437000 |Structure of cardiac valve annulus (body structure)| as the site of anchoring of prosthetic replacements.

Subtypes of 307279007 |Replacement of heart valve with prosthesis (procedure)| related to 'repair with anastomosis' have not been updated and will be reviewed as part of work being undertaken for bypass graft.

​Number of concepts edited (approx): 167

### 2.6. Substance <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-substance" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-substance"></a>

#### 2.6.1. **Update 385420005 |Contrast media (substance)|** <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-update385420005-or-contrastm" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-update385420005-or-contrastm"></a>

The 95 subtypes of 385420005 |Contrast media (substance) have been updated.

New substance concepts including groupers have been added, these changes include:

* New subtypes (and change to FSN) for 419098001 |Radiographic imaging contrast media (substance)|
* New grouper subtype 1348252003 |Iodinated radiographic imaging contrast media (substance)| for existing concept 426722004 |Iodinated contrast media (substance)|
* New concept 1340006004 |Ionic iodinated radiographic imaging contrast media (substance)|
* New concept 1340009006 |Non-ionic iodinated radiographic imaging contrast media (substance)|
* New concept 1340007008 |Ionic high-osmolality iodinated radiographic imaging contrast media (substance)|
* New concept 1340008003 |Ionic low-osmolality iodinated radiographic imaging contrast media (substance)|
* New concept 1348316000 |Barium-based radiographic imaging contrast media (substance)|
* Description update for 419909004 |Magnetic resonance imaging contrast media (substance)|
* New concept 1348311005 |Gadolinium-based contrast media (substance)| with subtypes added
* New concept 1348313008 |Iron-based contrast media (substance)| with subtypes added
* New concept 1348312003 |Manganese-based contrast media (substance)| with subtypes added
* New concept 1348310006 |Paramagnetic contrast media (substance)| with subtypes added
* New concept 1348314002 |Superparamagnetic contrast media (substance)| with subtypes added
* New concept 1348321002 |Ultrasound contrast media (substance)| with subtypes added

1295466006 |Plain X-ray with contrast (procedure)| and subtypes have been updated with the appropriate contrast media substance. Radiographic imaging procedures that use barium contrast have also been updated. Other contrast procedures for differing imaging modalities will be updated as part of the QI project.

### 2.7. Physical Object <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-physicalobject" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-physicalobject"></a>

#### 2.7.1. Inactivation of 105789008 |Cannula/tube/catheter, device (physical object)| <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-inactivationof105789008-or-c" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-inactivationof105789008-or-c"></a>

105789008 |Cannula/tube/catheter, device (physical object)| has been inactivated as AMBIGUOUS with target relationship POSSIBLY EQUIVALENT TO: 83059008 |Tube, device (physical object)|; 19923001 |Catheter, device (physical object)|;and 12150006 |Cannula, device (physical object)|.

### 2.8. Social Context <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-socialcontext" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-socialcontext"></a>

#### 2.8.1. Inactivation 255409004 |Pregnant woman (person)| <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-inactivation255409004-or-pre" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-inactivation255409004-or-pre"></a>

255409004 |Pregnant woman (person)| has been inactivated with reason Nonconformance to editorial policy and replaced by 77386006 |Pregnancy (finding)|.

### 2.9. Collaboration/Harmonization Agreements <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-collaboration-harmonizationa" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-collaboration-harmonizationa"></a>

#### 2.9.1. Convergent Medical Terminology (CMT) <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-convergentmedicalterminology" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-convergentmedicalterminology"></a>

Work is ongoing for this content area.

#### 2.9.2. Orphanet <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-orphanet" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-orphanet"></a>

Working in collaboration with [Orphanet](https://www.orpha.net/) efforts are ongoing to update rare disease concepts in SNOMED CT to maintain alignment with Orphanet for the annual update of the SNOMED CT to Orphanet Maps. Work has commenced to annotate content added for the Orphanet project with attribution to Inserm Orphanet. As part of this effort, textual definitions for concepts previously added for the Orphanet project will be updated to align with the current published version of the Orphanet definition. This will result in published text definitions being inactivated and replaced in bulk. Timelines for publication of these changes can be found in the [Early Visibility Release Notifications](https://confluence.ihtsdotools.org/display/RMT/2024+Early+Visibility+Release+Notifications).

All of the concepts added for the Orphanet project have been mapped to ICD-10.

#### 2.9.3. Cancer Synoptic Reporting <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-cancersynopticreporting" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-cancersynopticreporting"></a>

Cancer synoptic reports are used by many member countries to record pathology examination of cancer specimens including the College of American Pathologists (US and Canada), Royal College of Pathology (UK), Royal College of Pathology Australasia (Australia, New Zealand), PALGA (The Netherlands), Swedish Society of Pathology, and others.

For more information about this project, please see [Cancer Synoptic Reporting Clinical Project Group](https://confluence.ihtsdotools.org/display/CSRPG/Cancer+Synoptic+Reporting+Clinical+Project+Group)

#### 2.9.4. International League Against Epilepsy (ILAE) <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-internationalleagueagainstep" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-internationalleagueagainstep"></a>

In line with approved harmonized terminology, this project is working on alignment including restructuring to update the hierarchy << 313307000 |Epileptic seizure (finding)|.

Further information about the project is available [here](https://confluence.ihtsdotools.org/display/IAP/Epilepsy+Status+Report)

#### 2.9.5. Nursing <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-nursing" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-nursing"></a>

30 nursing procedure concepts have been added. These included informing, education, giving encouragement, assessments and management.

#### 2.9.6. Eye Care Clinical Reference Group <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-eyecareclinicalreferencegrou" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-eyecareclinicalreferencegrou"></a>

80 new procedures have been added to support the treatment of glaucoma including lateralized content. Additionally, new body structures have been created to define the new concepts.

This ongoing work aims to establish a preferred list of glaucoma procedures for international use, facilitating outcomes research.

### 2.10. Internal Quality Improvement <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-internalqualityimprovement" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-internalqualityimprovement"></a>

#### 2.10.1. Machine Readable Concept Model (MRCM) Changes <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-machinereadableconceptmodel" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-machinereadableconceptmodel"></a>

There are no changes for the MRCM in the November 2024 International Edition.

Future changes that are currently in progress can be viewed via the [MRCM Daily Build Browser](https://dailybuild.ihtsdotools.org/mrcm/?branch=MAIN)

Please see [early visibility](https://confluence.ihtsdotools.org/display/RMT/2024+Early+Visibility+Release+Notifications) for future planned changes to MRCM.

#### 2.10.2. **Annotation Reference Set** <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-annotationreferenceset" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-annotationreferenceset"></a>

The addition of content for the Annotations refset was commenced in the July 2024 International Edition release and is ongoing for attribution of text definition to organizations with a collaboration agreement, starting with Inserm Orphanet.

### 2.11. SNOMED CT derived products <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-snomedctderivedproducts" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-snomedctderivedproducts"></a>

#### 2.11.1. ICD-10 map <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-icd-10map" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-icd-10map"></a>

The SNOMED CT to the International Statistical Classification of Diseases and Related Health Problems, Tenth Revision (© World Health Organization 1994) 2016 Version map (SNOMED CT to ICD-10 Map) is included in the SNOMED CT International Edition as a Baseline. The SNOMED CT to ICD-10 Map was created to support the epidemiological, statistical and administrative reporting needs of SNOMED International member countries and WHO Collaborating Centers.

The SNOMED CT to ICD-10 Map is released in Release Format 2 (RF2) only. It is located in the file der2\_iisssccRefset\_ExtendedMapFull\_INT\_20200731.txt, which is in the Map folder under Refset, in each of the three RF2 Release Type folders.

The SNOMED CT to ICD-10 Map is released as Refset 447562003 |SNOMED CT to ICD-10 extended map (foundation metadata concept).

The ICD-10 Mapping Technical Guide (including exemplars) is hosted here [https://confluence.ihtsdotools.org/display/DOCICD10](https://confluence.ihtsdotools.org/display/DOCICD10)

#### 2.11.2. **Content Development Activity Summary** <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-contentdevelopmentactivitysu" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-contentdevelopmentactivitysu"></a>

The map is a directed set of relationships from SNOMED CT source concepts to ICD-10 target classification codes. The SNOMED CT source domains for the MAP are limited to subtypes of 404684003 |clinical finding|, 272379006 |event| and 243796009 |situation with explicit context|. The target classification codes are ICD-10 2016 release.

Mapped content for November 2024

The map provided for the November 2024 International Edition has been updated, and now represents a complete map from SNOMED CT International Edition to ICD-10 2016 version.

* 129 newly authored concepts have been added and mapped.
* The SNOMED to ICD-O (morphology) map has no additional concept added as a result of the ICD-O 3.2 review or added due to CRS requests.

We would welcome feedback on any issues that users of the map may detect when using the map. Issues should be submitted via [mapping@snomed.org](mailto:mapping@snomed.org)

#### 2.11.3. SNOMED CT to OWL conversion and classification <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-snomedcttoowlconversionandcl" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-snomedcttoowlconversionandcl"></a>

The repository containing the toolkit enabling simple SNOMED CT to OWL conversion and classification can be found here, including documentation on its use: [**https://github.com/IHTSDO/snomed-owl-toolkit**](https://github.com/IHTSDO/snomed-owl-toolkit)

**Please contact SNOMED International at** [**support@snomed.org**](mailto:support@ihtsdo.org) **if you would like to provide any feedback on ways to extend and improve the new toolkit.**

## 3. Technical notes <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-technicalnotes" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-technicalnotes"></a>

### 3.1. Known Issues <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-knownissues" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-knownissues"></a>

Known Issues are content or technical issues where the root cause is understood, and the resolution has been discussed and agreed but has yet to be implemented. This can be due to a number of reasons, from lack of time within the new monthly editing cycles, to the risk of impact to the stability of SNOMED CT if the fix were to be deployed at that stage in the Product lifecycle.

For the current SNOMED CT International Edition, the following Known Issues were identified, and agreed to be resolved in future editing cycles:

|     |         |             |
| --- | ------- | ----------- |
| Key | Summary | Description |

[No issues found](https://jira.ihtsdotools.org/secure/IssueNavigator.jspa?reset=true\&jqlQuery=filter+%3D+%22INT+20241101+-+Known+Issues+%28On+Hold%29%22+ORDER+BY+key+ASC++++++++++++++++++++++++\&src=confmacro)

### 3.2. Resolved Issues <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-resolvedissues" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-resolvedissues"></a>

Resolved issues are Known Issues which were not fixed as part of the previous release lifecycle, but which have now been resolved in the latest release. They can also be issues found during testing of the current release, which were resolved before the final deployment of the Production release. Finally they can be issues which were reported or found during the testing phase, but which have been closed without any action taken.

The Resolved Issues for the current SNOMED CT International Edition can be found here:

|     |         |             |          |
| --- | ------- | ----------- | -------- |
| Key | Summary | Description | Resolved |

[No issues found](https://jira.ihtsdotools.org/secure/IssueNavigator.jspa?reset=true\&jqlQuery=filter+%3D+%22INT+20241101+-+Resolved+Issues%22+++++++++++++++ORDER+BY+key+ASC+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++\&src=confmacro)

### 3.3. Technical updates <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-technicalupdates" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-technicalupdates"></a>

#### 3.3.1. RF2 package format <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-rf2packageformat" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-rf2packageformat"></a>

The RF2 package convention dictates that all relevant files are included, regardless of whether or not there is content to be included in each release. Therefore, the package contains a mixture of files which contain both header rows and content data, and files that (intentionally) include only header records. The reason that these "empty" files are included in the package is to draw a clear distinction between:

1. ...files that have been deprecated (and therefore removed from the package completely), due to the content no longer being relevant to RF2 in future releases
2. ...files that happen to contain no data in this particular release (and are therefore included in the package with just a header record), but are still relevant to RF2, and could therefore contain content in future releases.

This allows users to easily distinguish between the two scenarios, as otherwise if files in option 2 were left out of the package it could be interpreted as an error, rather than an intentional lack of content in that release.

#### 3.3.2. Changes to the Annotations Refset format <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-changestotheannotationsrefse" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-changestotheannotationsrefse"></a>

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

#### 3.3.3. Changes to the RefsetDescriptor records <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-changestotherefsetdescriptor" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-changestotherefsetdescriptor"></a>

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

#### 3.3.4. Proposal to increase the maximum length of Description Types <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-proposaltoincreasethemaximum" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-proposaltoincreasethemaximum"></a>

Please find below the link to the recent announcement on the proposal to increase the limit of characters allowed in Descriptions:

* [https://confluence.ihtsdotools.org/pages/viewpage.action?pageId=238158325](https://confluence.ihtsdotools.org/pages/viewpage.action?pageId=238158325)

A community consultation has been launched to solicit feedback on a proposal to increase the size limits of SNOMED CT concept descriptions to 4096 from the current limit of 255 characters. While this change does not represent a modification of the existing specification, it could be disruptive to implementers who have coded fixed length limits into their systems.

Please read the full proposal, along with [the latest Q\&A blog post](https://www.snomed.org/news/blog%3A-snomed-international-seeks-community-feedback-on-proposed-description-character-limit-increase) which details the proposed change, its potential benefits, the feedback process and timelines, and the issues that may need to be considered in such an update:

* [https://confluence.ihtsdotools.org/mag/community-consultations/snomed-international-proposal-to-increase-description-length-limit](https://confluence.ihtsdotools.org/mag/community-consultations/snomed-international-proposal-to-increase-description-length-limit)
* [https://www.snomed.org/news/blog%3A-snomed-international-seeks-community-feedback-on-proposed-description-character-limit-increase](https://www.snomed.org/news/blog%3A-snomed-international-seeks-community-feedback-on-proposed-description-character-limit-increase)

As always, SNOMED International greatly appreciates any thoughts or opinions that you would like to raise. If you would like to provide any feedback, please do so as soon as possible, at the very latest before the deadline on **Dec 31, 2024.**

#### 3.3.5. Early visibility of impending changes in the upcoming 2024 Monthly International Edition releases <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-earlyvisibilityofimpendingch" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-earlyvisibilityofimpendingch"></a>

Please see the [early visibility](https://confluence.ihtsdotools.org/display/RMT/2024+Early+Visibility+Release+Notifications) Confluence page for details of forthcoming changes.

#### 3.3.6. Document links <a href="#snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-documentlinks" id="snomedctnovember2024internationaleditionsnomedinternationalreleasenotes-documentlinks"></a>

All links provide information that is correct and current at the time of this Release. Updated versions may be available at a later date, but if so these will need to be requested from the relevant SNOMED International teams.

**NOTE**: To access any of the links in the pdf document, please visit the Release Notes [https://confluence.ihtsdotools.org/display/RMT/SNOMED+CT+November+2024+International+Edition+-+SNOMED+International+Release+notes](https://confluence.ihtsdotools.org/display/RMT/SNOMED+CT+November+2024+International+Edition+-+SNOMED+International+Release+notes)

***

**Approvals**

| **Final Version** | **Date**    | **Approver**  | **Comments** |
| ----------------- | ----------- | ------------- | ------------ |
| 1.0               | 15 Oct 2024 | Rory Davidson | Approved     |
| 1.0               | 07 Oct 2024 | Monica Harry  | Approved     |
| 1.0               | 15 Oct 2024 | Kelly Kuru    | Approved     |

***

**Draft Amendment History**

| **Version** | **Date**    | **Editor**                                  | **Comments**                               |
| ----------- | ----------- | ------------------------------------------- | ------------------------------------------ |
| 0.1         | 01 Oct 2024 | Andrew Atkinson                             | First draft for review and comment         |
| 0.1         | 07 Oct 2024 | <p>Maria Braithwaite</p><p>Donna Morgan</p> | <p>Content Update</p><p>Mapping Update</p> |
| 1.0         | 09 Oct 2024 | Andrew Atkinson                             | Final Production changes                   |
