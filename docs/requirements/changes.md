# Pollaris — Use-Case Specifications Change Log

**Document:** `Pollaris_Use_Case_Specifications_v2.0.docx`  
**Current version:** 2.0  
**Date:** 15 November 2026  
**Project team:** Group 05  
**Comparison baseline:** `Use-case Specs(1).docx` (PA2, version 1.0). The content additions were first assembled in the intermediate PA3 version 1.1; version 2.0 retains them and highlights all changes relative to the PA2 baseline.

## 1. Added

Seven detailed use-case specifications were appended as **Section 2.7–2.13**. Each follows the original seven-row template (*Use case Name, Brief description, Actors, Basic Flow, Alternative Flows, Pre-conditions, Post-conditions*).

| ID | Added use case | Vision Document v1.3 coverage |
|---|---|---|
| UC07 | Register and Manage User Account | M01; F01–F04 |
| UC08 | Change an Existing Vote | M03; F10; voting integrity NFR-06 |
| UC09 | Comment, Reply, and Manage Comments | M04; F13–F16 |
| UC10 | Set Personal Criteria and Request AI Comparison | M05; F17–F21 |
| UC11 | Record a Final Poll Decision | M03; F12 |
| UC12 | Report a Poll or Comment | M07; F26 |
| UC13 | Review Reports and Moderate Content | M07; F27–F28 |

Other additions:

- Added a **supplementary PA3 use-case model** illustrating UC07–UC13 after the existing PA2 use-case diagram. The original diagram remains intact.
- Added Section 2.7–2.13 entries to the **Table of Contents**.
- Added a **Revision History** entry describing the PA3 extension, dated 15 November 2026.

## 2. Modified

- Updated the **cover-page document version** from `1.0` (PA2 baseline) / `1.1` (intermediate extension) to **`2.0`**.
- Updated the **header version** to **`2.0`** and the header date from `31/Oct/26` to `15/Nov/26`.
- Updated the new **Revision History entry's version** from `1.1` to **`2.0`**. The original version `1.0` entry remains unchanged.
- Updated **Table of Contents page numbers** to match the expanded, 23-page document; existing section titles were not rewritten.
- Applied **blue font (`#0070C0`)** to text added or changed relative to the PA2 baseline: new use-case headings, requirement notes, use-case data cells, added TOC items, changed TOC page numbers, revision entry, version/date metadata, the supplementary diagram's labels, and its caption.

## 3. Removed

**None.** No original use cases, table fields, actors, flows, diagrams, or text sections were deleted.

## 4. Preserved unchanged

- Original **Word template**: cover design, sections, heading styles, table structure, page setup, header/footer layout, and existing use-case specification formatting.
- Original **PA2 use-case model**.
- Original **UC01–UC06** content, including their Basic Flows, Alternative Flows, Pre-conditions, and Post-conditions.
- Original **Revision History 1.0** entry.
- The existing placeholder fields (`<Use-Case Name>` and `<document identifier>`) were intentionally left as they were to avoid unrelated template/content changes.

## 5. Known content inconsistency (not changed)

**UC06** in the PA2 baseline describes guest voting and preventing subsequent submissions, while **Vision Document v1.3** requires authenticated single-choice voting and permits replacing a vote until poll closure. The new **UC08** specifies the replacement flow. UC06 was deliberately left unchanged to honor the instruction to preserve the previously approved content. This inconsistency should be resolved in a separately authorized content revision.

## 6. Validation

- 13 use cases total: **6 preserved + 7 added**.
- **23 rendered pages**; original and supplementary diagrams are present.
- New use-case data text is explicitly blue while the original UC01–UC06 text remains as before.
- No use-case content was removed.
