# Privacy Policy — Snip

_Last updated: 7 July 2026_

Snip is an offline-first notes app. Your privacy is the default, not a setting.

## The short version

- Your notes live **on your device**. Snip has no servers, no analytics, no ads, no tracking SDKs.
- **No account is required** to use Snip. Signing in with Google is needed **only** if you choose the optional Google Drive backup.
- Nothing leaves your device unless you explicitly turn a sharing or backup feature on.

## What Snip stores on your device

All of the following is kept **only in local app storage** and never sent to us (we have nowhere to send it):

- Your notes, tasks and debts — including names, amounts, reminder times, `#tags` and payment history you enter.
- Phone numbers you save for people on the Debts tab (typed, or picked from your contacts).
- Photos or images you attach to a note (copied into the app's private files).
- Your own UPI ID, if you save one to compose "pay me back" links.
- Small preferences: settings, saved capture templates, learned type corrections (words you re-categorised), and the optional backup passphrase (stored on-device so silent backups can encrypt without prompting).

Deleting a note deletes it from the local database (Trash keeps it for 30 days first; "Delete forever" is immediate). Uninstalling the app removes all local app data.

## Google Sign-In and Drive backup (optional)

If you connect a Google account for backup:

- Snip requests the narrow **`drive.appdata`** permission. Your backup file is stored in Drive's hidden, app-private area (`appDataFolder`) that only Snip can access — Snip **cannot see any of your other Drive files**, and nothing else in your Google account.
- The backup contains your notes, debts, tasks, subtasks and payment history. It goes only to **your** Google account, never to us.
- Backups run when you tap "Back up now" and — if you leave **automatic backup** on — quietly after your notes change and when the app opens.
- **Encryption (optional):** you can set a backup passphrase in Settings → Privacy. With a passphrase set, the backup is encrypted on your device (AES-256-GCM) **before** it is uploaded, so it is unreadable in Drive — even to someone with access to your Google account. Without a passphrase, the backup is plain JSON stored in your private Drive area and governed by Google's privacy policy. If you lose the passphrase, the backup cannot be read by anyone.
- Google Sign-In itself is provided by Google; signing in shares your account email with the app (shown in Settings so you know where backups go) and is governed by Google's privacy policy.
- **Disconnecting** (Settings → Google Drive backup → Disconnect) stops all Drive access and automatic backups. You can delete the stored backup anytime from Google Drive → Settings → Manage apps.

## Voice input (microphone)

Snip has an optional **voice capture** button. When you tap the mic, Snip records audio only for that moment and passes it to **your device's own speech-recognition service** (for example, Google's on Android) to turn speech into text.

- Snip does not store recordings and does not send audio to us.
- Depending on your device and its settings, that system speech service **may process audio in the cloud**. That handling is governed by your device/OS provider's privacy policy, not Snip's.
- Voice input is entirely optional — if you never tap the mic, no audio is ever captured.

## Other features that touch device data

- **Contacts**: the "From contacts" button opens your phone's own contact picker. Snip receives **only the single entry you pick** (name and number) and stores it locally. Snip never reads or uploads your contact list and requests no contacts permission.
- **Photos / camera**: attaching a photo opens your system gallery or camera app. Snip receives only the image you choose and stores a copy locally.
- **Clipboard**: to offer the one-tap "Paste" chip, Snip may read the clipboard **only while the app is in the foreground** (Android already restricts clipboard access to the focused app). Clipboard contents are never stored or logged unless you tap the chip to capture them as a note.
- **Text shared into Snip**: if you share text from another app (or use the selected-text menu), that text is handled entirely on-device by the capture flow — it is only saved if you save it.
- **App lock (biometric)**: unlocking uses your device's own fingerprint/face/PIN system. Snip only receives "unlocked: yes/no" — it never sees or stores biometric data.
- **Call / WhatsApp / UPI shortcuts**: tapping a contact or payment action opens your dialer, WhatsApp or UPI app. No data is sent by Snip itself.

## Permissions we use and why

| Permission | Why |
| --- | --- |
| Notifications | To show the reminders you set. |
| Microphone | For optional voice capture (speech-to-text), only while you are dictating. |
| Run at startup | To re-schedule your reminders after the phone reboots. |
| Exact alarms | So reminders fire at the exact time, even in battery-saving modes. |
| Full-screen notifications | For reminders you mark "Ring as alarm", so they can show over the lock screen. |
| Biometric | For the optional App lock. |

Snip deliberately requests **no** contacts, camera, storage, or location permissions — those flows go through system pickers that hand Snip only what you choose.

## Data deletion

- Deleting a note removes it from the local database (via Trash, or immediately with "Delete forever").
- Uninstalling the app removes all app data from your device.
- Your Drive backup can be removed from Google Drive → Settings → Manage apps, or simply stops being updated once you disconnect.

## Children

Snip does not collect data from anyone, including children.

## Changes

If this policy changes, the change will be listed here and in the app's release notes before it takes effect.

## Contact

Questions? Open an issue at https://github.com/xmi1an/DynamicNotesApp/issues
