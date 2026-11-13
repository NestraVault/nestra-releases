# Tijori privacy policy

*Last updated: 14 November 2026*

Tijori ("the app") is made by Tijori Vault. This policy explains what the app does with your information. The short version: your documents never leave your phone unless you send them somewhere yourself, and we never receive any of your data.

## What the app stores

The documents, card details, photos of documents, reminders and notes you add, and your settings. All of it is stored **only on your phone**:

- The database is encrypted with a key that is itself protected by your Vault Password and, if you turn it on, your fingerprint (through Android's secure key storage).
- Every scanned page and photo is encrypted before it is written to storage.
- Card CVVs are sealed with a separate key that never leaves this phone.
- Android's automatic cloud backup is turned off for the app, so none of this is copied to Google's backups.

We have no server and no copy of any of it. If you forget your Vault Password, we cannot recover your data.

## What the app does not do

- No account or sign-up.
- No advertising, analytics, crash reporting or tracking of any kind.
- It does not read other files, contacts, messages or location.

## When the app uses the internet

Only for updates:

- **Automatic update check (on by default).** Once a day, when you open the app, it downloads a small public file from GitHub (`github.com/tijorivault/tijori-releases`) that says what the latest version is. Nothing about you or your data is sent; like any website, GitHub can see the IP address the request comes from. You can turn this off in **Settings → About → Check for updates automatically**.
- **Downloading an update**, only when you tap Update. The download is checked against the published fingerprint before Android installs it.

Reading the text on documents happens on your phone; nothing is uploaded to do it.

## When information leaves your phone because you chose to

- **Share.** When you share a document or card details, the app hands a copy to the app you pick (for example WhatsApp or Gmail). That copy is **not encrypted** and is handled by that app's own policy. The app warns you before sharing, and never includes a card's CVV.
- **Copy.** Copied numbers go to Android's clipboard and are cleared after the time set in Settings (one minute by default).
- **Backup export.** An export is one file encrypted with a password you choose. You decide where it goes (Google Drive, a USB drive, email). Without the password it can't be read.

## Permissions

- **Camera:** to scan documents and cards.
- **Notifications and alarms:** for expiry reminders.
- **Run after restart:** to set the reminders again after the phone restarts.
- **Internet:** for the update check and downloads described above.
- **Install apps:** asked only when you install an update the app downloaded.

## Children

The app can store documents belonging to children in your family, kept on your phone under your control. We collect no information from or about anyone.

## Changes

If this policy changes, the new version will be published here with a new date, and described in the release notes.

## Contact

Open an issue at [github.com/tijorivault/tijori-releases/issues](https://github.com/tijorivault/tijori-releases/issues). Please never attach a photo of a real document.
