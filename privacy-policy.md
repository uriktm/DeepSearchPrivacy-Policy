# Privacy Policy

_Last updated: November 27, 2025_

Bookmark Deep Search ("the Extension") is a Chrome extension that helps you index and search your bookmarks locally on your device. This Privacy Policy explains what data we handle and how we keep it private.

## Data Collection and Processing

- **No personal data collection:** We do not collect, transmit, sell, or share any personally identifiable information.
- **No remote servers:** All processing happens entirely within the browser. The Extension never sends your bookmarks, browsing history, or usage information to external services or remote code.
- **Local storage only:** Bookmark metadata, embeddings, summaries, and indexing status are stored locally using Chrome storage and IndexedDB. You can clear this data at any time by removing the Extension or clearing the extension storage area.

## Permissions and Their Purpose

| Permission | Purpose |
| --- | --- |
| `bookmarks` | Read your bookmark tree so you can choose which folders to index. |
| `storage` | Save local configuration, indexing progress, and cached embeddings. |
| `alarms` | Schedule background indexing batches without keeping the popup open. |
| `offscreen` | Process and index web pages in the background without opening visible tabs. |
| `host_permissions` (`<all_urls>`) | Needed only while indexing to allow local extraction of content from the bookmarked page you selected. No data from these pages leaves your device. |

We request only the permissions required for the core functionality, and they are used exclusively for the purposes described above.

## Data Retention and Control

- All indexed data remains on your device until you remove the Extension or clear its storage.
- Removing a bookmark or folder and re-indexing clears the associated local data.
- You may uninstall the Extension at any time to delete all associated information.

## Third-Party Services

The Extension does not integrate with advertising networks, analytics providers, or external APIs. It does not load remote scripts or execute remote code.

## Security Measures

- Processing runs locally inside Chrome's extension sandbox.
- Pages are processed in an isolated offscreen document.
- No network requests are made with your bookmark data.

## Children’s Privacy

The Extension does not target children under 13 and does not knowingly collect any personal information.

## Changes to This Policy

If we make material changes to this Privacy Policy, we will update the "Last updated" date above and include the revised policy in the extension package and repository.

## Contact

For privacy questions or requests, please contact: **learningfavoritproject@gmail.com**
