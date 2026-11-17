# Folder Cairn support

For help with Folder Cairn or a question about privacy, email **[hello@skepticflow.com](mailto:hello@skepticflow.com)**. No GitHub account is needed. The app version and build from **Settings → About**, your macOS version, and a short description of what happened are usually enough. You can leave out filenames, folder paths, screenshots and attachments.

## Scan a folder or compare scans

1. Open Folder Cairn from the menu bar and choose **Storage Explorer**.
2. Choose the folder or volume you want to inspect. The scan measures storage without changing the selected files.
3. To keep a measurement, open **Storage Trends** and choose **Save Snapshot**. For a comparison, select the same location again and complete another scan.

To change how long snapshots are kept, open **Settings → General → Local history**. The default is 30 days, with 7 and 90 days also available.

## Remove saved data

### Remove snapshots and keep your settings

1. Quit Folder Cairn from its menu bar menu.
2. In Finder, choose **Go → Go to Folder** and paste the snapshot folder path below.

   `~/Library/Containers/com.vdsnuff.mac-space-cleaner/Data/Library/Application Support/com.vdsnuff.mac-space-cleaner.storage/`

3. Move **only** `snapshots-v1.json` to the Trash. If the folder or file is absent, there is no snapshot file there to remove.

### Reset all local Folder Cairn data, including settings

Quit the app. In Finder, use **Go → Go to Folder** to open `~/Library/Containers/`. Find the container at `~/Library/Containers/com.vdsnuff.mac-space-cleaner` (Finder may display its app name). Move only that container to the Trash.

These steps apply to the Store edition. Files in the folders you scanned stay in place. Items you move to the Trash can be recovered until you remove them from the Trash. Previous backups follow your backup settings. [Folder Cairn privacy policy](privacy.md)
