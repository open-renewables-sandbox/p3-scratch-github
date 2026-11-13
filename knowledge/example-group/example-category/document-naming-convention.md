---
type: Item
uid: ITM-0002
title: Document naming convention
description: How files in a project data room are named so they can be found again.
tags: [group:example-group, category:example-category]
status: draft
---

# Document naming convention

## Description

A document-naming convention gives every file in a project data room a name built from the same parts in the same order, so that a person can find a file by sorting or searching the folder listing. A typical pattern is the date as year-month-day, a short subject, a document kind and a version number, joined with hyphens, for example `2026-03-14-grid-study-report-v02.pdf`. Putting the date first makes names sort in time order, and lower-case words without spaces avoid problems when files move between systems.[^1] The convention is agreed once, written down in the data room's index, and applied to every upload.

## Checks

- **Name parts present**: each file name carries a date, a subject, a document kind and a version.
    - Pass: all four parts appear in the agreed order.
    - Flag: a part is missing or out of order; raise it with the owner.
- **Portable characters only**: file names use lower-case letters, digits and hyphens.
    - Pass: no spaces, accents or other special characters appear.
    - Flag: a name contains a character that may break when the file is moved or linked.

## Revision history

<!-- Maintained by CI. Do not edit. -->

[^1]: Rehearsal placeholder source, <https://example.org/rehearsal-source>.
