# SNOMED CT Managed Service - Belgium Extension Release Notes - October 2025

| **Date**             | **20251015**                                                          |
| -------------------- | --------------------------------------------------------------------- |
| **Document Version** | **1.0**                                                               |
| **Release Status**   | <mark style="color:blue;background-color:blue;">**PRODUCTION**</mark> |

***

## Introduction

SNOMED CT terminology provides a common language that enables a consistent way of indexing, storing, retrieving, and aggregating clinical data across specialties and sites of care.

The International Health Terminology Standards Development organization (IHTSDO<sup>®</sup>), trading as SNOMED International, maintains the SNOMED CT technical design, the content architecture, the SNOMED CT content (includes the concepts table, the descriptions table, the relationships table, a history table, and ICD mappings), and related technical documentation.

We kindly encourage all Belgian users to submit their feedback on the content of the Belgian Edition through the new [Request Management Portal](https://rmp.ihtsdotools.org/), online again since October 7 (see [Technical Notes ](https://conf.spaces.snomed.org/wiki/spaces/RMT/pages/157516050/SNOMED+CT+Managed+Service+-+Belgium+Extension+Release+Notes+-+October+2025#Technical-notes)below for more details). &#x20;

## Background

This document provides a summarized description of the content changes included in the October 2025 Production release of the SNOMED Clinical Terms<sup>®</sup> Managed Service Belgium Edition package.

It also includes technical notes detailing the potential known issues. These are content or technical issues where the root cause is understood, and the fix has been discussed and agreed, but has yet to be implemented.

### Scope

This document is written for the purpose described above and is not intended to provide details of the technical specifications for SNOMED CT or encompass every change made during the release.

## Content Development Activity

### Summary

This extension contains concepts, relationships and reference sets with Dutch, French and German translations.

### New and Updated Content

#### **International content in this release**

This release contains 945 new concepts and 123 inactivated concepts from the latest international edition.

#### **Belgian content in this release**

**Concepts**

No Belgian concepts were created or inactivated.

**New translated content**

* National Language Reference Sets:

New translations have been introduced to the three national language reference sets, both for concepts that had not been yet translated and for concepts that already contained translations. Some existing translations were inactivated or updated. The following table contains the total number of currently active translations available in the present version of the Belgian language reference sets:

|           | **Preferred** | **Acceptable** | **Total**   |
| --------- | ------------- | -------------- | ----------- |
| DUTCH     | 309969        | 329943         | **639912**  |
| FRENCH    | 250094        | 149566         | **399660**  |
| GERMAN    | 41827         | 13431          | **55258**   |
| **TOTAL** | **601890**    | **492940**     | **1094830** |

* General Practitioner language reference sets: the following table contains the total number of translations included in the GP language reference set:

|           | **Preferred** | **Acceptable** | **Total** |
| --------- | ------------- | -------------- | --------- |
| DUTCH     | 11676         | 6155           | **17831** |
| FRENCH    | 10723         | 5150           | **15873** |
| **TOTAL** | **22399**     | **11305**      | **33704** |

## SNOMED CT derived products &#x20;

### Reference sets

The release currently contains reference sets that serve one of the following 2 purposes :

\- Reference sets to support the implementation of SNOMED CT in eHR software for clinical data entry/capture. These reference sets have a six-monthly release cycle.\
\- Reference sets to support data interoperability (mainly subsets representing value lists of BE FHIR profiles required by the Care Sets). These reference sets have a monthly release cycle.

**A new version of a reference set is only published when there is a change compared to the previous version.** Reference sets that do not require an update (meaning having no delta) are not republished despite their release cycle.

Summary of the different existing refsets and their purpose:

| Purpose                               | Subset                                                                                      | SCTID            | Content                                                                                                                                                                                                                             |
| ------------------------------------- | ------------------------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Clinical data entry                   | Belgian subset for medical problems in patient health records refset                        | 40811000172108   | Common disorders, findings and procedures found in general patient records.                                                                                                                                                         |
| Clinical data entry                   | Subset For Nursing In Patient Health Records Simple Refset                                  | 100941000172101  | Common disorders, findings and procedures registered by nurses.                                                                                                                                                                     |
| Clinical data entry                   | Subset For Neonatology In Patient Health Records Simple Refset                              | 100971000172106  | Common disorders and findings found in newborns.                                                                                                                                                                                    |
| Clinical data entry                   | Subset For Pulmonology In Patient Health Records Simple Refset                              | 100961000172102  | Common respiratory disorders and findings.                                                                                                                                                                                          |
| Clinical data entry                   | Subset For Rheumatology In Patient Health Records Simple Refset                             | 100981000172109  | Common rheumatic disorders and findings.                                                                                                                                                                                            |
| Clinical data entry                   | Subset For Nephrology In Patient Health Records Simple Refset                               | 100951000172104  | Common kidney-related disorders and findings.                                                                                                                                                                                       |
| Clinical data entry                   | Subset For Cardiology In Patient Health Records Simple Refset                               | 131001000172104  | Common cardiovascular disorders and findings.                                                                                                                                                                                       |
| Clinical data entry                   | Subset For Hematology In Patient Health Records Simple Refset                               | 130991000172100  | Common blood disorders and symptoms.                                                                                                                                                                                                |
| Clinical data entry                   | Subset For Infectious Diseases In Patient Health Records Simple Refset                      | 130981000172103  | Common infectious diseases caused by different pathogens.                                                                                                                                                                           |
| Clinical data entry                   | Subset For Intensive Care In Patient Health Records Simple Refset                           | 130971000172101  | Common disorders and findings diagnosed in patients in intensive care.                                                                                                                                                              |
| Clinical data entry                   | Belgian GP Subset                                                                           | 721000172106     | Common disorders, findings and procedures encountered by general practitioners in Belgium. This refset originated from a map between 3BT (Bilingual Biclassified Belgian Thesaurus) and SNOMED CT and has been enhanced thereafter. |
| Data interoperability (FHIR ValueSet) | Belgian subset for Allergy Intolerance Causative Agent Non-Drug Simple Refset               | 50851000172106   | Common non-drug substances that cause allergies or intolerances.                                                                                                                                                                    |
| Data interoperability (FHIR ValueSet) | Belgian subset for Allergy Intolerance Manifestation Simple Refset files                    | 50861000172108   | Common manifestations of allergies or intolerances. Monthly release cycle.                                                                                                                                                          |
| Data interoperability (FHIR ValueSet) | Belgian subset for Vaccination Simple Refset                                                | 50831000172102   | Common vaccine products used in Belgium. Monthly release cycle.                                                                                                                                                                     |
| Data interoperability (FHIR ValueSet) | Belgian subset for Allergy Intolerance Causative Agent Drug Simple Refset                   | 50841000172109   | Common drugs that cause allergies or intolerances. Monthly release cycle.                                                                                                                                                           |
| Data interoperability (FHIR ValueSet) | Belgian subset for Allergy Intolerance Exposure Route Simple Refset                         | 181051000172108  | Exposure routes involved in allergy or intolerance                                                                                                                                                                                  |
| Data interoperability (FHIR ValueSet) | Belgian subset for Allergy Intolerance No Allergy Simple Refset                             | 181061000172105  | To indicate absence of allergy or intolerance                                                                                                                                                                                       |
| Data interoperability (FHIR ValueSet) | Belgian subset for Allergy Intolerance Type Simple Refset                                   | 181041000172106  | Type of allergy or intolerance                                                                                                                                                                                                      |
| Data interoperability (FHIR ValueSet) | Belgian simple reference set for translated plant materials (foundation metadata concept)   | 551000172106     | To group plant material concepts that have been translated.                                                                                                                                                                         |
| Data interoperability (FHIR ValueSet) | Belgian simple reference set for translated animal materials (foundation metadata concept)  | 561000172108     | To group animal material concepts that have been translated.                                                                                                                                                                        |
| Data interoperability (FHIR ValueSet) | Belgian simple reference set for translated edible substances (foundation metadata concept) | 541000172109     | To group edible substance concepts that have been translated.                                                                                                                                                                       |

#### &#x20;Updated Reference sets

The following reference sets were updated (inactive concepts were removed and replacements added if not already present):

541000172109 Belgian simple reference set for translated edible substances (foundation metadata concept)

50841000172109 Belgian subset for AllergyIntolerance, causative agent, drug (foundation metadata concept)

50851000172106 Belgian subset for AllergyIntolerance, causative agent, non-drug (foundation metadata concept)

## Technical notes

New Request Management Platform has been released:

After a series of delays the new version of the Request Management Portal is now live and can be accessed at [https://rmp.ihtsdotools.org](https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Frmp.ihtsdotools.org%2F\&data=05%7C02%7Cpedro.diazlammertyn%40health.fgov.be%7C0cb44b624a744873138c08de05b192c6%7C66c008a4b56549a993c9c1e64cad2e11%7C0%7C0%7C638954457391537079%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C0%7C%7C%7C\&sdata=mD%2FdpuSJlCukVGU9sJ8IgudzTv0UnoC3Aoy86L4Faus%3D\&reserved=0). Please note that this new URL is different from the old one (rmp.**snomedtools**.org). SNOMED CT International has set up a redirection page at the old address to guide users to log in via their SNOMED Account, which will then grant them access to the landing page with links to the RMP.

The new site utilizes Single Sign-On (SSO). This means that once a user is logged into their SNOMED Account, they will be automatically logged into the Request Management Portal and will no longer need to sign in for each request.

If you encounter any issues logging in or using the platform, please contact us immediately via [terminologie@health.fgov.be](mailto:terminologie@health.fgov.be).

### Known Issues

Known Issues are content or technical issues where the root cause is understood, and the resolution has been discussed and agreed but has yet to be implemented.  This can be due to a number of reasons, from lack of capacity within the current editing cycle, to the risk of impact to the stability of SNOMED CT if the fix were to be deployed at that stage in the Product lifecycle. &#x20;

No known issues.

### Technical notes

#### Notice of changes to the Belgium Edition Release Schedule

As you may already know SNOMED International has transitioned to a monthly delivery schedule for the International Edition of SNOMED CT. The move towards more frequent releases of SNOMED CT has several benefits, including:

* Inclusion of suggested changes in a shorter timeframe.
* Better interoperability, as a result of entities being able to consume release content that is more aligned with other organizations.
* The prevention of circular dependencies that occur in longer projects, due to the move towards smaller, more manageable authoring projects.
* More automated validation services, as a result of the inherent removal of the Alpha/Beta stages in the Release cycle.

Whilst most users will continue unaffected (as they can simply continue to download the releases every 6 months as always), this transition will necessarily involve a few changes to process/packages:

* **Delta files have been removed from both International and Managed Service release packages, including the Belgium Extension.**  A Delta Generation service will be provided for those who need it. The Delta Generation Tool allows users to create their own Delta between two fixed release dates - you can find it here:
  * [https://github.com/IHTSDO/delta-generator-tool/releases](https://github.com/IHTSDO/delta-generator-tool/releases)
* The ICD-O/ICD-10 Maps will continue to be published in each Monthly International Edition release package (in line with that month's content) for the foreseeable future, unless we experience issues with the new process in Production, and they need to be removed at a later date.

The Belgian edition of SNOMED CT is also released monthly on the 15<sup>th</sup> of each month, except for January and August. The first monthly Belgian edition was published in November 2024.

#### Notice of changes to the BE Edition Release package

In line with the refined implementation of Annotations, we are updating all Extensions in order to align them with the updated version of the refsets in the International Edition Release package (which were first published in June 2024).

* The languageCode field was specified as the two characters of ISO-639-1 code for the language of the annotation text. The change includes support for specifying dialect when it is applicable by adhering to RFC 5646, which allows the combination of two characters of ISO 639-1 code and two uppercase letters of country code (ISO 3166) separated by a hyphen.  The changes apply to both the [Member Annotations String Value Reference Set ](https://docs.snomed.org/snomed-ct-specifications/snomed-ct-release-file-specification/reference-set-release-file-specification/5.2-reference-set-types/5.2.4-metadata-reference-sets/5.2.4.9-member-annotation-string-value-reference-set)+ [Component Annotation String Value reference set](https://docs.snomed.org/snomed-ct-specifications/snomed-ct-release-file-specification/reference-set-release-file-specification/5.2-reference-set-types/5.2.4-metadata-reference-sets/5.2.4.8-component-annotation-string-value-reference-set):
  * The column "languageCode" has therefore been changed to "languageDialectCode".
    * Component Annotations (1292992004)
      * **OLD:**    id    effectiveTime    active    moduleId    refsetId    referencedComponentId    languageCode    typeId    value
      * **NEW:**   id    effectiveTime    active    moduleId    refsetId    referencedComponentId    languageDialectCode    typeId    value
    * Member Annotations (1292995002)
      * **OLD:**   id    effectiveTime    active    moduleId    refsetId    referencedComponentId    referencedMemberId    languageCode    typeId    value
      * **NEW:**  id    effectiveTime    active    moduleId    refsetId    referencedComponentId    referencedMemberId    languageDialectCode    typeId    value

***

**Approvals**

| **Final Version** | **Date** | **Approver**         | **Comments** |
| ----------------- | -------- | -------------------- | ------------ |
| 1.0               |          | Pedro Diaz Lammertyn | Approved     |
| 1.0               |          | David Op de Beeck    | Approved     |

***

**Draft Amendment History**

| **Version** | **Date** | **Editor**           | **Comments**          |
| ----------- | -------- | -------------------- | --------------------- |
| 0.1         |          | Andrew Atkinson      | Initial draft created |
| 0.2         |          | Leong Hui Wong       | Draft updates         |
| 1.0         |          | Pedro Diaz Lammertyn | Final updates         |
