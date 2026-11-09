Cribbit Privacy Policy
=======================

**Effective date:** November 9, 2026

Cribbit is published by Thumbo LLC, doing business as Thumbo ("Thumbo," "we," "us," or "our"). This Privacy Policy explains what information Cribbit handles, how it's used, and who it's shared with. Cribbit is currently offered to users in the United States only.

## 1. Information We Collect

**Voice recordings.** When you record an idea, Cribbit captures audio through your device's microphone so it can be transcribed. This audio is processed briefly and is not retained by us after transcription completes (see Section 3).

**Idea content you create.** Titles, transcripts, and tags you create or edit within the app are stored locally on your device. Cribbit does not require an account or login, and this content is not uploaded to or stored on servers we control.

**Routine technical information.** Like any app that connects to the internet, Cribbit's connections produce basic technical records:

- When audio is sent for transcription, our hosting provider, Supabase, automatically keeps routine service logs about the request, which may include the date and time, the size of the request, and the IP address it came from. We use these logs only to operate, secure, and troubleshoot the service, and we do not use them to identify you.
- Cribbit checks for app updates through Expo's update service. These requests include basic technical details such as the app version and your device's operating system, along with your IP address.
- If you install Cribbit through TestFlight or the App Store, Apple may share limited, aggregated information with us, such as installs and crash reports, if you have chosen to share this with app developers. Apple handles that information under its own privacy policy.

**We do not collect:** account credentials, contact lists, or location data. Cribbit has no user accounts, no cloud sync, no analytics or tracking tools, and no advertising integrations. We do not sell your information.

## 2. How We Use Information

Audio you record is sent, via our backend service, to the following third-party providers solely to produce your transcript and title:

- **Deepgram** converts your recorded audio into a raw text transcript.
- **Groq** receives the transcript text (not the audio) and cleans it up (punctuation, paragraph breaks, filler-word removal) and generates a suggested title.

Our backend function (hosted on Supabase) relays your audio and transcript text to these providers and returns the result to the app. It does not save your audio, ideas, or transcripts.

Each of these providers processes data under their own privacy policies and terms, which we encourage you to review:

- Deepgram: https://deepgram.com/privacy-policy
- Groq: https://groq.com/privacy-policy
- Supabase: https://supabase.com/privacy
- Expo: https://expo.dev/privacy
- Apple: https://www.apple.com/legal/privacy/

## 3. Data Retention

- **Audio recordings** are discarded after transcription completes and are not retained by Cribbit. We have configured our requests to Deepgram to opt out of its Model Improvement Program. With that setting, Deepgram does not store your audio or transcript after returning the result, and does not use it to train its models.
- **Transcript text sent for cleanup and titles** is not stored by Groq. We have turned on Groq's Zero Data Retention setting for our account, so the text we send is not logged or kept after the request is processed.
- **Service records.** Deepgram and Groq may still keep basic records that do not include your content, such as request counts and timing, for billing and operations. Supabase service logs and Expo update requests are described in Section 1.
- **Ideas (titles, transcripts, tags)** are stored only locally on your device. We do not keep a separate copy. Deleting an idea, a tag, or the app itself removes this data from your device; we have no server-side copy to delete on our end.

## 4. Security

Audio and text travel between the app, our backend, and our providers over encrypted (HTTPS) connections. Ideas stored on your device are protected by your device's own security features, such as your passcode and device encryption. No method of transmission or storage is completely secure, so we cannot guarantee absolute security.

## 5. Your Choices

Because your idea content lives only on your device, you control it directly within the app. Editing, retagging, or deleting any idea removes it. You can also turn off Cribbit's microphone access at any time in your device's Settings under Privacy & Security, then Microphone. There is no account to manage or delete, since none exists. If you have questions about information we may hold about you, such as service logs, contact us using the details below.

## 6. Children's Privacy

Cribbit is not directed at, and is not intended for use by, children under the age of 13. We do not knowingly collect information from children under 13.

## 7. International Users

Cribbit and this Privacy Policy currently address use within the United States. If we expand to support additional languages or make the app available to users in other regions, we will update this Privacy Policy accordingly to reflect any additional obligations that may apply.

## 8. Changes to This Policy

We may update this Privacy Policy from time to time as the app evolves. We'll update the effective date above when changes are made. Continued use of Cribbit after changes take effect constitutes acceptance of the updated policy.

## 9. Contact Us

Questions about this policy or how Cribbit handles data can be directed to:

**privacy@thumbo.com**
