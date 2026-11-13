<p align="center">
  <img src="assets/tijori-lockup.png" alt="Tijori" width="360">
</p>

<h3 align="center">Encrypted Document Vault</h3>

<p align="center">Your family's IDs and cards, kept on your phone, locked, and a tap away.</p>

---

**Tijori** is an encrypted document vault. It keeps your family's Aadhaar, PAN, passport, driving licence, voter ID, marksheets and bank cards in one place, encrypted on your phone. Find Mom's PAN and copy the number in one tap, while you're on a call or filling a form.

## Download

**[Download the latest Tijori APK](https://github.com/tijorivault/tijori-releases/releases/latest)** (Android 8 and newer).

Once installed, Tijori checks here once a day and offers new versions itself. You can turn that off in Settings.

## What it does

- **A drawer for each person.** Each family member has a tab; their documents and cards sit in their drawer.
- **Scan a document.** Point the camera; Tijori finds the page edges, straightens it and reads the ID number and expiry date on the phone. Nothing is uploaded to read it.
- **Copy in one tap.** Numbers stay masked on screen; the copy button puts the full number on the clipboard, which clears itself after a minute.
- **Expiry reminders.** Passports, licences and cards show how many days are left, and remind you before they expire.
- **Share when you choose.** Send a document as a PDF, as photos, or as text through WhatsApp, Gmail or anything else. Tijori warns you that the shared copy is no longer encrypted.
- **Cards.** Card numbers are masked; the CVV needs your fingerprint to show, hides again after 20 seconds, and is never shared.
- **Backup.** Export everything to one password-protected file and keep it wherever you like (Google Drive, a pen drive, email).

## Privacy, in short

- **Everything stays on your phone.** No account, no sign-up, no server. We never see your documents.
- **Encrypted at rest.** The database and every scanned page are encrypted. Your Vault Password and fingerprint unlock them.
- **No ads, no analytics, no tracking.**
- **Forget the Vault Password and the data can't be recovered.** That is the point of real encryption. Keep a backup.

Full policy: [PRIVACY.md](PRIVACY.md).

## Installing

1. Download the `.apk` from the [latest release](https://github.com/tijorivault/tijori-releases/releases/latest) on your phone.
2. Open it. Android asks you to allow installing from your browser or Files app the first time; allow it.
3. Open **Tijori**, set a Vault Password and add your first family member.

## Is this APK genuine?

Every Tijori release is signed with the same key. Android refuses an update signed with any other key, so once you've installed Tijori, only real updates can replace it.

To check a download yourself, compare its signing certificate with:

```
SHA-256: FC:BA:FA:17:5D:69:CA:3B:C6:1E:5D:42:26:6D:88:56:45:B1:C4:C4:1E:D7:50:FE:57:D4:58:7D:5B:28:F7:61
```

(`apksigner verify --print-certs Tijori-<version>.apk`). Each release also lists the APK's own SHA-256 in `latest.json`.

## Questions and problems

Open an [issue](https://github.com/tijorivault/tijori-releases/issues). Please never attach a photo of a real document.

---

<p align="center">Made with love in India by Tijori Vault</p>
