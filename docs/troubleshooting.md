---
title: Troubleshooting Instagram Export Imports
description: Fix common Instagram export import problems, missing follower or following lists, ZIP issues, and not-following-back report mismatches.
permalink: /troubleshooting/
---

# Troubleshooting

Use this page when an Instagram export does not load, a follower list looks empty, or a not-following-back report does not match what you expected.

## The Export Does Not Import

Try these steps:

1. Confirm the download finished completely.
2. Extract the archive before importing.
3. Choose the extracted folder instead of a single unrelated file.
4. Prefer JSON exports when available.
5. Keep original file names until after import.
6. Download a fresh export if the archive looks incomplete.

## Followers Or Following Are Missing

Possible causes:

- Instagram did not include those lists in the export scope you requested.
- The export format changed.
- The files are in a different folder than expected.
- The archive was partially extracted.
- The account relationship files are HTML-only and the app version expects JSON.

See [file formats](file-formats.md) and [Instagram data export guide](instagram-data-export-guide.md).

## Not-Following-Back Results Look Wrong

The report depends on the export date and the loaded files. Results can look wrong when:

- The export is old.
- A relationship changed after download.
- A username changed.
- One list imported but the other did not.
- An account was deleted, disabled, blocked, or restricted.

Download a fresh export and check that both followers and following loaded.

## AI Insights Look Incomplete

AI summaries can miss context. Check:

- Which list was selected
- Whether filters were active
- Whether both followers and following were loaded
- Whether the app had access to the fields needed for the summary

Always verify AI output against the visible list.

## The App Cannot Open A ZIP File

If direct ZIP import is not supported by your app version, extract the ZIP first and open the extracted folder.

## I Need Support

Open an issue using the bug report template or see [SUPPORT.md](../SUPPORT.md).
