# Folder Cairn privacy policy

Effective November 18, 2026

Folder Cairn is a read-only storage inspector for macOS. It measures storage on your Mac. The app has no accounts, analytics, advertising or tracking. It does not send your scan results, snapshots or preferences to the developer or anyone else.

## When you scan

You choose a folder or mounted volume in the macOS picker. Folder Cairn uses read-only access for that scan and releases access when the scan ends. You choose the location again for a later scan. The app does not save a permission bookmark.

Folder Cairn reads names, paths, file types and filesystem metadata to calculate allocated space. It does not read the contents of those files. The detailed file and folder listing stays in memory during use.

## When you save a snapshot

Selecting **Save Snapshot** in Storage Trends writes a record inside the app’s local container. It saves the following details.

- The full path of the folder or volume you selected, its volume UUID, and the selected folder’s filesystem identifier and creation date. These let Folder Cairn recognize the same location in a later scan. The path can include your account or project name.
- A snapshot identifier, the measurement time, total allocated space, and available volume space when the system reports it.
- A scan completeness flag and size totals for documents, media, archives and other files. Individual filenames within the selected location are omitted.

Display and retention preferences also stay on your Mac. Folder Cairn keeps snapshots for **30 days by default**. In **Settings → General → Local history**, you can choose 7, 30 or 90 days. History is limited to the newest 512 snapshots across all locations. The app prunes old records when it accesses history, including at launch, when saving or when you change retention. If the app is closed, pruning waits until its next use. [How to remove saved data](support.md#remove-saved-data)

## When you ask for help

Privacy and support links open GitHub in your browser. GitHub handles those visits under its own policy. If you email support, your mail provider sends the address, message and any attachments you choose to include. We use them to respond to your request. You can ask us to delete your support correspondence by emailing the same address. [GitHub privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) · [Email hello@skepticflow.com](mailto:hello@skepticflow.com)
