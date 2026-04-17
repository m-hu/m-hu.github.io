# Privacy Policy

**App:** my.email.client
**Developer:** Hao Hu
**Contact:** hao.hu.fr@gmail.com
**Effective date:** 2026-04-17

This app is a personal email client derived from Thunderbird for Android. The
sections below describe, in plain terms, what data it handles and where that
data goes.

## What the app processes

To function as an email client, the app handles the following information that
*you* provide or that lives on your device:

- **Email account settings** — server addresses, usernames, passwords,
  OAuth tokens, and (for S3-backed accounts) the S3 access key, secret key, and
  the RSA private key you paste in to decrypt encrypted messages.
- **Email content** — messages, headers, attachments, folder structure, and
  flags (read/unread, starred, etc.) synchronized from the mail servers you
  configure.
- **Contacts** — when you grant the contacts permission, the app reads names
  and email addresses from your device's contacts list to offer address
  autocomplete when composing messages.
- **Photos and camera captures** — only when you explicitly attach a photo to
  an outgoing message or scan a QR code during the migration flow. The app
  never opens the camera on its own.

## Where the data goes

- All of the data above is stored **locally on your device** in the app's
  private storage.
- Email data is transmitted **only** between your device and the mail servers
  you configure yourself (IMAP/POP3/SMTP/S3). Those transmissions happen over
  the security protocol you choose in the account settings (TLS/STARTTLS).
- Nothing is sent to the developer, nothing is sent to third-party analytics,
  advertising, or tracking services. The app does not embed ads.

## Permissions and why they're requested

| Permission | Why |
| --- | --- |
| `INTERNET`, `ACCESS_NETWORK_STATE` | Talk to the mail servers you configure |
| `READ_CONTACTS` | Autocomplete addresses when composing |
| `POST_NOTIFICATIONS` | Notify you of new mail |
| `CAMERA` | Scan QR codes during setup migration; attach photos to outgoing mail |
| `USE_BIOMETRIC`, `USE_FINGERPRINT` | Optional app-lock with your device biometrics |
| `FOREGROUND_SERVICE`, `SCHEDULE_EXACT_ALARM`, `WAKE_LOCK`, `RECEIVE_BOOT_COMPLETED` | Background mail sync |

You can revoke any of these in Android Settings at any time. Features that
need the revoked permission will stop working; the rest of the app continues
to function.

## Data retention and deletion

- All local data is deleted when you uninstall the app or remove the account
  from the app's account settings.
- The developer does not hold any copy of your data and therefore has nothing
  to delete on your behalf.

## Children

The app is not directed to children under 13 and does not knowingly collect
data from them.

## Third-party services

The app does not integrate third-party analytics, crash reporting, advertising
SDKs, or social-login providers beyond the OAuth flows initiated by you when
adding an account with a provider such as Google or Microsoft. Those OAuth
interactions are governed by the respective provider's privacy policy.

## Changes to this policy

If the policy changes, the updated version will replace the text at this URL
and the effective date at the top will be bumped. Material changes will be
communicated in the app's release notes.

## Contact

Questions about this policy can be sent to hao.hu.fr@gmail.com.
