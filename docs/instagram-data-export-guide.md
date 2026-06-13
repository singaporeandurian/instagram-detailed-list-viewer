---
title: Instagram Data Export Viewer Guide
description: Learn which Instagram data export files matter for followers, following, account relationships, and not-following-back reports.
permalink: /instagram-data-export-viewer/
---

# Instagram Data Export Guide

Instagram Detailed List Viewer is built around your official Instagram data export. This guide explains what to download, which files are useful, and how to prepare the export for analysis.

## What Is An Instagram Data Export?

An Instagram data export is a copy of information associated with your account. Depending on your settings and Instagram's current export format, it may include profile information, content history, messages, account relationship lists, comments, likes, saved items, and more.

For this app, the most important files are the account relationship lists. These are the files that help answer questions like:

- Who follows me?
- Who am I following?
- Which accounts do I follow that do not appear in my follower list?
- Which followers do I not follow back?
- Which follow requests, blocked accounts, or restricted accounts are included in my export?

## Recommended Export Settings

When Instagram gives you a choice, use:

- Format: JSON
- Scope: complete or account information export
- Date range: all time, unless you only need a narrow review
- Delivery: download link saved to a private folder

JSON is recommended because it is structured and easier to parse consistently.

## Useful Folders And Files

Instagram's export structure can vary, but relationship files often appear in folders related to followers, following, connections, or account interactions.

Look for files with names similar to:

- `followers`
- `following`
- `pending_follow_requests`
- `recent_follow_requests`
- `blocked_accounts`
- `restricted_accounts`
- `hide_story_from`
- `close_friends`

The exact names may differ. See [file formats](file-formats.md) for troubleshooting.

## What The Export Cannot Show

Your export is not the same as official live Instagram analytics. It may not include:

- Profile reach
- Saves
- Impressions
- Story viewers
- Private metrics for other accounts
- Ad performance
- Demographics
- A guaranteed complete history of who unfollowed you

To identify historical changes, save multiple exports over time and compare the snapshots. A single export can show current relationships, but it cannot always prove when a change happened.

## Safe Handling Tips

- Keep your export private.
- Do not upload someone else's account data without permission.
- Delete old exports when you no longer need them.
- Store exports on a device or drive you trust.
- Review AI settings before sending any data to an external provider.

## Related Guides

- [Instagram follower list analyzer](instagram-follower-list-analyzer.md)
- [Instagram following list viewer](instagram-following-list-viewer.md)
- [Not-following-back report](not-following-back-report.md)
- [Privacy and security](privacy-and-security.md)
