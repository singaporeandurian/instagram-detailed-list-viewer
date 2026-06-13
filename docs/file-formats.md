---
title: Instagram Export File Formats
description: Supported Instagram export formats for follower lists, following lists, relationship files, JSON exports, extracted folders, and ZIP archives.
permalink: /instagram-export-file-formats/
---

# File Formats

Instagram Detailed List Viewer is designed for Instagram data exports, especially JSON files that contain follower, following, and account relationship lists.

## Recommended Format

Use JSON when Instagram offers a choice. JSON exports are structured, easier to validate, and usually better for software tools than copied text or screenshots.

## Common Export Inputs

The app may work with files or folders that contain relationship data such as:

- Followers
- Following
- Pending follow requests
- Recent follow requests
- Blocked accounts
- Restricted accounts
- Hidden story lists
- Close friends, when included in the export

The exact file names can vary by Instagram export version, language, account type, and download settings.

## Typical File Extensions

- `.json`
- `.html`
- `.zip`, if the app version supports opening compressed archives directly

If the compressed archive does not import, extract it first and open the folder or individual JSON files.

## Why A File Might Not Load

A file may fail to load when:

- The export is incomplete.
- The archive was not fully extracted.
- The file was renamed or moved away from related export files.
- The export is HTML-only and the app version expects JSON.
- Instagram changed the internal structure of the export.
- The file contains a list type the current app version does not support.

## Best Practices

- Keep the original export archive unchanged as a backup.
- Work from an extracted copy.
- Prefer JSON exports.
- Label exports by date, such as `instagram-export-2026-06-12`.
- Save multiple dated exports if you want to compare account list changes over time.

## Related Help

- [Getting started](getting-started.md)
- [Troubleshooting](troubleshooting.md)
- [Instagram data export guide](instagram-data-export-guide.md)
