# SNOMED CT Managed Service - Belgium Extension Release Notes - March 2025

| **Date**             | **20250315**                                                          |
| -------------------- | --------------------------------------------------------------------- |
| **Document Version** | **1.0**                                                               |
| **Release Status**   | <mark style="color:blue;background-color:blue;">**PRODUCTION**</mark> |

© 2025 International Health Terminology Standards Development Organisation. All rights reserved. SNOMED CT® was originally created by the College of American Pathologists.

This document forms part of the SNOMED CT® Belgium Extension release distributed by International Health Terminology Standards Development Organisation, trading as SNOMED International, and is subject to the SNOMED CT® Affiliate License, details of which may be found at [https://www.snomed.org/snomed-ct/get-snomed](http://www.snomed.org/snomed-ct/get-snomed)

No part of this document may be reproduced or transmitted in any form or by any means, or stored in any kind of retrieval system, except by an Affiliate of SNOMED International in accordance with the SNOMED CT® Affiliate License. Any modification of this document (including without limitation the removal or modification of this notice) is prohibited without the express written permission of SNOMED International.

Any copy of this document that is not obtained directly from SNOMED International \[or a Member of SNOMED International] is not controlled by SNOMED International, and may have been modified and may be out of date. Any recipient of this document who has received it by other means is encouraged to obtain a copy directly from SNOMED International \[or a Member of SNOMED International. Details of the Members of SNOMED International may be found at [http://www.snomed.org/members/](http://www.snomed.org/members/)].

***

## 1. Introduction <a href="#snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-introduction" id="snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-introduction"></a>

SNOMED CT terminology provides a common language that enables a consistent way of indexing, storing, retrieving, and aggregating clinical data across specialties and sites of care.

The International Health Terminology Standards Development organization (IHTSDO<sup>®</sup>), trading as SNOMED International, maintains the SNOMED CT technical design, the content architecture, the SNOMED CT content (includes the concepts table, the descriptions table, the relationships table, a history table, and ICD mappings), and related technical documentation.

## 2. Background <a href="#snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-background" id="snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-background"></a>

This document provides a summarized description of the content changes included in the March 2025 Production release of the SNOMED Clinical Terms<sup>®</sup> Managed Service Belgium Edition package.

It also includes technical notes detailing the known issues which have been identified (should any of these exist). These are content or technical issues where the root cause is understood, and the fix has been discussed and agreed, but has yet to be implemented.

2.1 Scope

This document is written for the purpose described above and is not intended to provide details of the technical specifications for SNOMED CT or encompass every change made during the release.

## 3. Content Development Activity <a href="#snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-contentdevelopmentactivity" id="snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-contentdevelopmentactivity"></a>

### 3.1. Summary <a href="#snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-summary" id="snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-summary"></a>

This extension contains concepts, relationships and reference sets with their Dutch, French and German translations for healthcare professionals/for use in healthcare profession.

ALERT

### 3.2. Warning about a critical clinical safety risk <a href="#snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-warningaboutacriticalclinicalsafetyrisk" id="snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-warningaboutacriticalclinicalsafetyrisk"></a>

{% hint style="warning" %}
The concept 431839003 |Magnetic resonance imaging of liver with contrast (procedure)| was translated to "imagerie par résonance magnétique du rein avec produit de contraste" and "IRM rénale avec contraste", both of which refer to the kidney instead of the liver. Please ensure that the other translations related to the liver are used (“imagerie par résonance magnétique du foie avec produit de contraste”, “IRM hépatique avec contraste” or “imagerie par IRM du foie avec contraste”).

This is also reported in the chapter related to the known issues.
{% endhint %}

3.2 New and Updated Content

**New Belgian content in this release:**

Inactivated concepts

No new concepts have been inactivated in this release.

New concepts

No new concepts have been created in this release.

New translated content

Regarding the GP language reference set:

* GP language reference set: the following table contains the total number of translations included in the GP language reference set:

| <p><br></p> | **Preferred** | **Acceptable** | **Total**  |
| ----------- | ------------- | -------------- | ---------- |
| DUTCH       | 11.685        | 6.173          | 17.858     |
| FRENCH      | 10.764        | 5.215          | 15.979     |
| TOTAL       | **22.449**    | **11.388**     | **33.837** |

\
Regarding the national language refset:\\

* New translations have been introduced, both for concepts that didn't have a translation yet as for concepts with existing translations.
* The following table contains the total number of translations included in the actual version of the Belgian language reference set:

| <p><br></p> | **Preferred** | **Acceptable** | **Total** |
| ----------- | ------------- | -------------- | --------- |
| DUTCH       | 306.652       | 324.029        | 630.681   |
| FRENCH      | 209.175       | 125.057        | 334.232   |
| GERMAN      | 41.795        | 13.459         | 55.254    |
| TOTAL       | 557.622       | 462.545        | 1.020.167 |

**The other changes are updates of existing content.**

| **Differences found in package Comparison**                                   | **No RF2 records impacted** | **Rationale**                                      |
| ----------------------------------------------------------------------------- | --------------------------- | -------------------------------------------------- |
| Concept files                                                                 | 0                           | 0 records added/updated                            |
| Association files                                                             | 10                          | 10 records added/updated, plus 0 inactivated       |
| AttributeValue files                                                          | 1727                        | 1716 records added/updated, plus 11 inactivated    |
| Description files (EN)                                                        | 0                           | 0 records added/updated, plus 0 inactivated        |
| Description files (FR)                                                        | 27.480                      | 26.730 records added/updated, plus 750 inactivated |
| Description files (NL)                                                        | 6.119                       | 6.092 records added/updated, plus 27 inactivated   |
| Description files (DE)                                                        | 6                           | 4 records added/updated, plus 2 inactivated        |
| Language files (EN)                                                           | 0                           | 0 records added/updated, plus 0 inactivated        |
| Language files (FR)                                                           | 28.137                      | 27.388 records added/updated, plus 749 inactivated |
| Language (FR) context specific GP Refset                                      | 97                          | 7 records added/updated, plus 90 inactivated       |
| Language files (NL)                                                           | 6.119                       | 6.092 records added/updated, plus 27 inactivated   |
| Language (NL) context specific GP Refset                                      | 3                           | 1 record added/updated, plus 2 inactivated         |
| Language files (DE)                                                           | 4                           | 2 records added/updated, plus 2 inactivated        |
| Inferred Relationship files                                                   | 0                           | 0 records added/updated, plus 0 inactivated        |
| OWLExpression files                                                           | 0                           | 0 records added/updated, plus 0 inactivated        |
| RefsetDescriptor files                                                        | 0                           | 0 records added, plus 0 updated                    |
| Translated Plant Materials Simple Refset                                      | 0                           | 0 records added/updated, plus 0 inactivated        |
| Translated Edible Substances Simple Refset                                    | 2                           | 1 records added/updated, plus 1 inactivated        |
| Translated Animal Materials Simple Refset                                     | 0                           | 0 records added/updated, plus 0 inactivated        |
| Belgian GP refset files                                                       | 0                           | 0 records added/updated, plus 0 inactivated        |
| Extended Map files (containing the new BE ICD-10 map content)                 | 0                           | 0 records added/updated, plus 0 inactivated        |
| Belgian subset for medical problems in patient health records refset          | 0                           | 0 records added/updated, plus 0 inactivated        |
| Belgian subset for Vaccination Simple Refset                                  | 0                           | 0 records added/updated, plus 0 inactivated        |
| Belgian subset for Allergy Intolerance Causative Agent Drug Simple Refset     | 6                           | 0 records added/updated, plus 6 inactivated        |
| Belgian subset for Allergy Intolerance Causative Agent Non-Drug Simple Refset | 2                           | 1 records added/updated, plus 1 inactivated        |
| Belgian subset for Allergy Intolerance Manifestation Simple Refset files      | 0                           | 0 records added/updated, plus 0 inactivated        |
| Identifier files                                                              | 0                           | 0 records added/updated, plus 0 inactivated        |
| Relationship Concrete files                                                   | 0                           | 0 records added/updated, plus 0 inactivated        |
| Subset For Nursing In Patient Health Records Simple Refset                    | 0                           | 0 records added/updated, plus 0 inactivated        |
| Subset For Neonatology In Patient Health Records Simple Refset                | 0                           | 0 records added/updated, plus 0 inactivated        |
| Subset For Pulmonology In Patient Health Records Simple Refset                | 0                           | 0 records added/updated, plus 0 inactivated        |
| Subset For Rheumatology In Patient Health Records Simple Refset               | 0                           | 0 records added/updated, plus 0 inactivated        |
| Subset For Nephrology In Patient Health Records Simple Refset                 | 0                           | 0 records added/updated, plus 0 inactivated        |
| Subset For Cardiology In Patient Health Records Simple Refset                 | 0                           | 0 records added/updated, plus 0 inactivated        |
| Subset For Hematology In Patient Health Records Simple Refset                 | 0                           | 0 records added/updated, plus 0 inactivated        |
| Subset For Infectious Diseases In Patient Health Records Simple Refset        | 0                           | 0 records added/updated, plus 0 inactivated        |
| Subset For Intensive Care In Patient Health Records Simple Refset             | 0                           | 0 records added/updated, plus 0 inactivated        |

## 4. SNOMED CT derived products <a href="#snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-snomedctderivedproducts" id="snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-snomedctderivedproducts"></a>

### 4.1. Reference sets <a href="#snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-referencesets" id="snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-referencesets"></a>

The release currently contains reference sets that serve one of the following 2 purposes :

\- Reference sets to support the implementation of SNOMED CT in eHR software for clinical data entry/capture. These reference sets have a six-monthly release cycle;\
\- Reference sets to support data interoperability (mainly subsets representing value lists of BE FHIR profiles required by the Care Sets). These reference sets have a monthly release cycle.

**A new version of a reference set is only published when there is a change compared to the previous version.** Reference sets that do not require an update (meaning having no delta) are not republished despite their release cycle.

Here is a summary of the different existing refsets and their purpose:

| Purpose                               | Subset                                                                        | SCTID           | Members | Content                                                                                                                                                                                                                             |
| ------------------------------------- | ----------------------------------------------------------------------------- | --------------- | ------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Clinical data entry                   | Belgian subset for medical problems in patient health records refset          | 40811000172108  | 7937    | Common disorders, findings and procedures found in general patient records.                                                                                                                                                         |
| Clinical data entry                   | Subset For Nursing In Patient Health Records Simple Refset                    | 100941000172101 | 4402    | Common disorders, findings and procedures registered by nurses.                                                                                                                                                                     |
| Clinical data entry                   | Subset For Neonatology In Patient Health Records Simple Refset                | 100971000172106 | 802     | Common disorders and findings found in newborns.                                                                                                                                                                                    |
| Clinical data entry                   | Subset For Pulmonology In Patient Health Records Simple Refset                | 100961000172102 | 229     | Common respiratory disorders and findings.                                                                                                                                                                                          |
| Clinical data entry                   | Subset For Rheumatology In Patient Health Records Simple Refset               | 100981000172109 | 200     | Common rheumatic disorders and findings.                                                                                                                                                                                            |
| Clinical data entry                   | Subset For Nephrology In Patient Health Records Simple Refset                 | 100951000172104 | 292     | Common kidney-related disorders and findings.                                                                                                                                                                                       |
| Clinical data entry                   | Subset For Cardiology In Patient Health Records Simple Refset                 | 131001000172104 | 445     | Common cardiovascular disorders and findings.                                                                                                                                                                                       |
| Clinical data entry                   | Subset For Hematology In Patient Health Records Simple Refset                 | 130991000172100 | 339     | Common blood disorders and symptoms.                                                                                                                                                                                                |
| Clinical data entry                   | Subset For Infectious Diseases In Patient Health Records Simple Refset        | 130981000172103 | 351     | Common infectious diseases caused by different pathogens.                                                                                                                                                                           |
| Clinical data entry                   | Subset For Intensive Care In Patient Health Records Simple Refset             | 130971000172101 | 1480    | Common disorders and findings diagnosed in patients in intensive care.                                                                                                                                                              |
| Clinical data entry                   | Belgian GP Subset                                                             | 721000172106    | 11967   | Common disorders, findings and procedures encountered by general practitioners in Belgium. This refset originated from a map between 3BT (Bilingual Biclassified Belgian Thesaurus) and SNOMED CT and has been enhanced thereafter. |
| Data interoperability (FHIR ValueSet) | Belgian subset for Allergy Intolerance Causative Agent Non-Drug Simple Refset | 50851000172106  | 1190    | Common non-drug substances that cause allergies or intolerances.                                                                                                                                                                    |
| Data interoperability (FHIR ValueSet) | Belgian subset for Allergy Intolerance Manifestation Simple Refset files      | 50861000172108  | 67      | Common manifestations of allergies or intolerances. Monthly release cycle.                                                                                                                                                          |
| Data interoperability (FHIR ValueSet) | Belgian subset for Vaccination Simple Refset                                  | 50831000172102  | 53      | Common vaccine products used in Belgium. Monthly release cycle.                                                                                                                                                                     |
| Data interoperability (FHIR ValueSet) | Belgian subset for Allergy Intolerance Causative Agent Drug Simple Refset     | 50841000172109  | 6396    | Common drugs that cause allergies or intolerances. Monthly release cycle.                                                                                                                                                           |

#### 4.1.1. New Reference sets <a href="#snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-newreferencesets" id="snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-newreferencesets"></a>

No new reference sets have been added to this release package.

#### 4.1.2. Changed Reference sets <a href="#snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-changedreferencesets" id="snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-changedreferencesets"></a>

No changes have been made to the reference sets in this release package.

## 5. Technical notes <a href="#snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-technicalnotes" id="snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-technicalnotes"></a>

### 5.1. Known Issues <a href="#snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-knownissues" id="snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-knownissues"></a>

Known Issues are content or technical issues where the root cause is understood, and the resolution has been discussed and agreed but has yet to be implemented. This can be due to a number of reasons, from lack of capacity within the current editing cycle, to the risk of impact to the stability of SNOMED CT if the fix were to be deployed at that stage in the Product lifecycle.

For the SNOMED CT Managed Service - Belgium Extension Release, the following Known Issues were identified, and agreed to be resolved in the next editing cycle:

\\

|                                                                          |                                                                                                                                                                                 |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |                                                                                     |
| ------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| Key                                                                      | Summary                                                                                                                                                                         | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | P                                                                                   |
| [ISRS-7181](https://jira.ihtsdotools.org/browse/ISRS-7181?src=confmacro) | [SNOMED CT Belgium Extension releases, 2025-03-15, SQL, 1a4e40a9-cf14-4703-b206-9f2fbeb56c7f, 2025-03-10T09:27:30](https://jira.ihtsdotools.org/browse/ISRS-7181?src=confmacro) | <p>All active Refset records are valid.<br>Total number of failures: 26<br>Report URL: <a href="https://prod-rvf.ihtsdotools.org/api/result/1741599479486?storageLocation=be/snomed_ct_be_releases/2025-03-10T09:27:30">https://prod-rvf.ihtsdotools.org/api/result/1741599479486?storageLocation=be/snomed_ct_be_releases/2025-03-10T09:27:30</a><br>First 10 failures:</p><ul><li>{ "conceptId": "426977000", "conceptFsn": null, "detail": "Reference component id:426977000 for refset id: 100941000172101 in simple refset must be valid.", "componentId": "b499f379-d8e9-4eb0-b02c-0324ad382ea0", "fullComponent": "1,11000172109,100941000172101,426977000..." }</li><li>{ "conceptId": "50712000", "conceptFsn": null, "detail": "Reference component id:50712000 for refset id: 100941000172101 in simple refset must be valid.", "componentId": "eb161679-dd39-4021-87e1-926776fff142", "fullComponent": "1,11000172109,100941000172101,50712000..." }</li><li>{ "conceptId": "161832001", "conceptFsn": null, "detail": "Reference component id:161832001 for refset id: 100941000172101 in simple refset must be valid.", "componentId": "f9c1dde6-c236-40eb-9722-8003e264f8d6", "fullComponent": "1,11000172109,100941000172101,161832001..." }</li><li>{ "conceptId": "61420007", "conceptFsn": null, "detail": "Reference component id:61420007 for refset id: 100941000172101 in simple refset must be valid.", "componentId": "5a1390fb-a9b0-490f-a453-9bbd97df1540", "fullComponent": "1,11000172109,100941000172101,61420007..." }</li><li>{ "conceptId": "190828008", "conceptFsn": null, "detail": "Reference component id:190828008 for refset id: 40811000172108 in simple refset must be valid.", "componentId": "94d43796-34f4-452a-8732-9164b745448d", "fullComponent": "1,11000172109,40811000172108,190828008..." }</li><li>{ "conceptId": "11101003", "conceptFsn": null, "detail": "Reference component id:11101003 for refset id: 40811000172108 in simple refset must be valid.", "componentId": "acec3c44-f936-4c0f-b544-0f2b77468df9", "fullComponent": "1,11000172109,40811000172108,11101003..." }</li><li>{ "conceptId": "447743004", "conceptFsn": null, "detail": "Reference component id:447743004 for refset id: 40811000172108 in simple refset must be valid.", "componentId": "c0a38b72-45d9-4f6c-8a8f-940a5a2c3731", "fullComponent": "1,11000172109,40811000172108,447743004..." }</li><li>{ "conceptId": "387644004", "conceptFsn": null, "detail": "Reference component id:387644004 for refset id: 40811000172108 in simple refset must be valid.", "componentId": "3c0a1022-2fb4-4954-ad81-c0e1cb2aa736", "fullComponent": "1,11000172109,40811000172108,387644004..." }</li><li>{ "conceptId": "31387002", "conceptFsn": null, "detail": "Reference component id:31387002 for refset id: 40811000172108 in simple refset must be valid.", "componentId": "61eef57c-99a8-42fd-8dcb-5b66361fc07b", "fullComponent": "1,11000172109,40811000172108,31387002..." }</li><li>{ "conceptId": "361197009", "conceptFsn": null, "detail": "Reference component id:361197009 for refset id: 100981000172109 in simple refset must be valid.", "componentId": "2d4618a5-4c1f-40b6-890f-692db5b3046b", "fullComponent": "1,11000172109,100981000172109,361197009..." }</li></ul><p>KNOWN ISSUE: These refset members are being exception-listed by the BE NRC, because the refsets have not yet been updated to the latest content version. This will be resolved in future BE Edition release packages. Please contact the BE NRC for further details if required.</p> | ![Major / Medium](https://jira.ihtsdotools.org/secure/attachment/18970/Linea_3.png) |
| [ISRS-7195](https://jira.ihtsdotools.org/browse/ISRS-7195?src=confmacro) | [SNOMED CT Belgium Extension releases, 2025-03-15, SQL, 03cf9850-7857-11e1-b0c4-0800200c9a66, 2025-03-10](https://jira.ihtsdotools.org/browse/ISRS-7195?src=confmacro)          | <p>Report URL: <a href="https://prod-rvf.ihtsdotools.org/api/result/1741620174?storageLocation=tmp/1741620174">https://prod-rvf.ihtsdotools.org/api/result/1741620174?storageLocation=tmp/1741620174</a></p><p>"testCategory": "file-centric-validation",<br>"testType": "SQL",<br>"assertionUuid": "03cf9850-7857-11e1-b0c4-0800200c9a66",<br>"assertionText": "Preferred Term exists exactly once in each language refset for each concept.",<br>"queryInMilliSeconds": 8847,<br>"failureCount": 1,<br>"firstNInstances": [</p><p>{ "conceptId": "431839003", "detail": "Concept: id=431839003 has multiple active preferred terms in language refset=21000172104", "componentId": "431839003", "moduleId": "900000000000207008", "fullComponent": "1,900000000000207008,900000000000073002" }</p><p>]</p><p>KNOWN ISSUE: The NRC has confirmed that multiple Preferred Terms, some of which contain clinically incorrect translations, were added to the concept. These issues will be fixed in a future BE Edition release. Please refer to the Clinical Risk Warning section in the Release Notes for further guidance.</p>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | ![Major / Medium](https://jira.ihtsdotools.org/secure/attachment/18970/Linea_3.png) |

[2 issues](https://jira.ihtsdotools.org/secure/IssueNavigator.jspa?reset=true\&jqlQuery=filter+%3D+%22MS+%28BE%29+20250315+-+Known+Issues%22+ORDER+BY+key+ASC++++++++++++++\&src=confmacro)

Other known issues to be aware of:

* Regarding the Refset cycle isn’t the same for all of them you can occasionnally find inactive components in them. There are actually 26 entries that can be found as inactive.
* The concept 431839003 |Magnetic resonance imaging of liver with contrast (procedure)| was translated to "imagerie par résonance magnétique du rein avec produit de contraste" and "IRM rénale avec contraste", both of which refer to the kidney instead of the liver. Please ensure that the other translations related to the liver are used (“imagerie par résonance magnétique du foie avec produit de contraste”, “IRM hépatique avec contraste” or “imagerie par IRM du foie avec contraste”).

### 5.2. Technical notes <a href="#snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-technicalnotes.1" id="snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-technicalnotes.1"></a>

#### 5.2.1. Notice of changes to the Belgium Extension Release Schedule <a href="#snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-noticeofchangestothebelgiumextensionrele" id="snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-noticeofchangestothebelgiumextensionrele"></a>

As you may already know SNOMED International have transitioned to a monthly delivery schedule for the International Edition of SNOMED CT. The move towards more frequent releases of SNOMED CT realizes several benefits, including:

* The potential to be able to get content changes into the terminology in a shorter time frame.
* The fostering of better interoperability, as a result of entities being able to consume release content that is more aligned with other organizations.
* The prevention of circular dependencies that occur in longer projects, due to the move towards smaller, more manageable authoring projects.
* More automated validation services, as a result of the inherent removal of the Alpha/Beta stages in the Release cycle.

Whilst most users will continue unaffected (as they can simply continue to download the releases every 6 months as always), this transition will necessarily involve a few changes to process/packages:

* **Delta files have been removed from both International and Managed Service release packages, including the Belgium Extension.** A Delta Generation service will be provided for those who need it. The Delta Generation Tool allows users to create their own Delta between two fixed release dates - you can find it here:
  * [https://github.com/IHTSDO/delta-generator-tool/releases](https://github.com/IHTSDO/delta-generator-tool/releases)
* The ICD-O/ICD-10 Maps will continue to be published in each Monthly International Edition release package (in line with that month's content) for the foreseeable future, unless we experience issues with the new process in Production, and they need to be removed at a later date.

The Belgium Extension is now following the precedents set down by the International Edition, and transitioning to monthly Releases of the Extension package. The first monthly BE Extension release is planned for publication in November 2024.

#### 5.2.2. Notice of changes to the BE Extension Release package <a href="#snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-noticeofchangestothebeextensionreleasepa" id="snomedctmanagedservicebelgiumextensionreleasenotesmarch2025-noticeofchangestothebeextensionreleasepa"></a>

In line with the refined implementation of Annotations, we are updating all Extensions in order to align them with the updated version of the refsets in the International Edition Release package (which were first published in June 2024).

* The languageCode field was specified as the two characters of ISO|-639-1 code for the language of the annotation text. The change includes support for specifying dialect when it is applicable by adhering to RFC 5646, which allows the combination of two characters of ISO 639-1 code and two uppercase letters of country code (ISO 3166) separated by a hyphen. The changes apply to both the [Member Annotations String Value Reference Set](https://confluence.ihtsdotools.org/display/DOCRELFMT/5.2.4.9+Member+Annotations+String+Value+Reference+Set)[ ](https://confluence.ihtsdotools.org/display/DOCRELFMT/5.2.4.9+Member+Annotations+String+Value+Reference+Set)+ [Component Annotation String Value reference set](https://confluence.ihtsdotools.org/display/DOCRELFMT/5.2.4.8+Component+Annotations+String+Value+Reference+Set):
  * The column "languageCode" has therefore been changed to "languageDialectCode".
    * Component Annotations (1292992004)
      * **OLD:** id effectiveTime active moduleId refsetId referencedComponentId languageCode typeId value
      * **NEW:** id effectiveTime active moduleId refsetId referencedComponentId languageDialectCode typeId value
    * Member Annotations (1292995002)
      * **OLD:** id effectiveTime active moduleId refsetId referencedComponentId referencedMemberId languageCode typeId value
      * **NEW:** id effectiveTime active moduleId refsetId referencedComponentId referencedMemberId languageDialectCode typeId value\\

***

**Approvals**

| Final Version | Date        | Approver           | Comments |
| ------------- | ----------- | ------------------ | -------- |
| 1.0           | 14 Mar 2025 | Nicolas De Vriendt | Approved |
| 1.0           | 14 Mar 2025 | David Op de Beeck  | Approved |

**Download .pdf here:**

***

**Draft Amendment History**

| Version | Date        | Editor             | Comments              |
| ------- | ----------- | ------------------ | --------------------- |
| 0.1     | 11 Feb 2025 | Andrew Atkinson    | Initial draft created |
| 1.0     | 14 Mar 2025 | Nicolas De Vriendt | Final updates         |
