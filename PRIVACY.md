# AI History Bookmark - Privacy Policy

**Version:** 1.0.0  
**Last Updated:** 05 December 2025

## Overview

AI History Bookmark is committed to protecting your privacy. We use a hybrid approach that prioritizes local processing while leveraging a dedicated API for enhanced categorization. We are transparent about what data is processed locally and what is sent to our service.

## Data Collection

### What We Access Locally

The extension requires the following browser permissions to function:

1. **history**: Read your browsing history to display and categorize pages.
2. **bookmarks**: Create bookmark folders with selected pages.
3. **storage**: Save your preferences (last selected time range, folder location, visit count settings).
4. **tabs & scripting**: Access the active tab's title to calculate and display visit counts.

## Data Storage

### Local Storage

- **User preferences**: Stored in `chrome.storage.local`.
- **No history persistence**: History data is fetched fresh from the browser API.

### Remote Processing

- **Categorization API**: Our service receives domain names, returns their categories, and discards the data. We do not store your browsing history on our servers.

## Data Sharing

**We do not share any data with third parties.**

- Data sent to our API is strictly for categorization purposes.
- We do not sell or monetize your data.
- We do not share data with advertisers.

## Permissions Justification

| Permission           | Why We Need It                                       | What We Access                              |
| -------------------- | ---------------------------------------------------- | ------------------------------------------- |
| **history**          | To display and categorize your browsing history      | URLs, page titles, visit times (read-only)  |
| **bookmarks**        | To create bookmark folders with selected pages       | Bookmark tree structure, create new folders |
| **storage**          | To save your preferences between sessions            | Settings and configuration                  |
| **tabs**             | To update the visit count badge when you switch tabs | Active tab status                           |
| **scripting**        | To read the "clean" page title for visit counting    | Page title of the active tab                |
| **host_permissions** | To communicate with our API and access page titles   | all pages                                   |

## Your Rights

### Access Your Data

- **Preferences**: Check `chrome.storage.local` in browser DevTools.
- **History & Bookmarks**: Managed by your browser.

### Control Your Data

- **Uninstall extension**: Removes all stored preferences.
- **Disable permissions**: You can revoke permissions in browser settings (though this may break functionality).

## Third-Party Services

- **Categorization API**: Hosted by us.

## Changes to This Policy

We may update this privacy policy for future versions. Changes will be:

- Posted in this document with updated version number.
- Announced in extension release notes.

## Summary

**Your privacy is our priority:**

✅ Minimal data transmission
✅ No full URL tracking  
✅ No personal data collection  
✅ Transparent processing  
✅ Full user control  

---

*This privacy policy is part of the AI History Bookmark extension and is governed by the MIT License.*
