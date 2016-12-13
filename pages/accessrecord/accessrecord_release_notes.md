---
title: Access Record Release Notes
keywords: getcarerecord, release notes
tags: []
sidebar: accessrecord_sidebar
permalink: accessrecord_release_notes.html
summary: "Release notes for the various versions of the Access Record capability."
---
- 1.0.0-rc.2 ((Released 4th December 2016))

   - The elaboration of page(s) content to reflect the validation of data-sharing agreements by the Spine Security Proxy only, and the requirement that Provider Data-Sharing configuration should not be applied or changed for GP Connect interactions 
  - The application of a configurable Legal Exclusion set - currently the RGCP set on TRUD -  which is being reviewed with amendments/changes expected Feb 2017
   - The indication of withheld information, either arising from Patient preferences, or the application of the exclusion set to be at line item level as well as in Section Banner , as this provides more valuable information as to when and volume of exclusions
  - Configurable Section Headings
  - Configurable Section Default Date Ranges
  - Section Content Messages for provider-specific description of how sections have been populated, or where content deviates from specification - eg Clinical/Administrative Items content; Problem 'Significance' values;  Patient withheld data indication;   see Section Pages
  - Default section date range where relevant to be 'All' items, where Consumer date-range not supplied
  - Section Heading Changes to: Current Repeat Medications, Problems and Issues, Allergies and Adverse Reactions
  - Current Repeat Medications section - Last Issued Column to be first column in table
  - Medication sections 'Drug' column heading to be 'Medication Item'
  - Past Medications section - to include references to Discontinued Repeats, Cancelled Acutes, either as 'Type', or within Details column
  - Investigations Section to be out of scope for Stage 1, pending further analysis
  - Observations Section to include Investigation items
  - Observations to be excluded from Clinical Items Section
  - Medications Sections to be reviewed as part of Stage 2
  - GP Name in Patient Banner (Details) to be the 'Usual' GP
  
- 1.0.0-rc.1
  - Beta version promoted to release candidate
- 1.0.0-beta.1
  - Initial release of the Access Record capability pack on GitHub in early August 2016.
- 1.0.0-alpha.1
  - Initial release for feedback/comments as part of the late May 2016 release. 
