Cribbit Privacy Policy
=======================

**Effective date:** November 19, 2026

Cribbit is published by Thumbo LLC, doing business as Thumbo ("Thumbo," "we," "us," or "our"). This Privacy Policy explains what information Cribbit handles, how it's used, and who it's shared with. Cribbit is currently offered to users in the United States only.

## 1. Information We Collect

**Voice recordings.** When you record an idea, Cribbit captures audio through your device's microphone so it can be transcribed. This audio is processed briefly and is not retained by us after transcription completes (see Section 3).

**Idea content you create.** Titles, transcripts, and tags you create or edit within the app are stored locally on your device. Cribbit does not require an account or login, and this content is not uploaded to or stored on servers we control.

**Anonymous app identifier and usage counts.** To keep the transcription service from being abused, and to apply Cribbit's voice plan, each installed copy of the app is given a random identifier using Apple's App Attest service. This identifier is not tied to your name, email, Apple ID, or any account. Our backend (Supabase) stores it along with simple counters, such as how many voice recordings have been transcribed, how many minutes of audio have been processed this month, and short-lived request counts. It does not store your audio or the text of your ideas. Network addresses used for rate limiting are converted to a scrambled value so they cannot be read back as an address.

**Voice subscription.** Writing, tasks, and organizing ideas in Cribbit are free. Voice transcription includes a number of free recordings, after which it requires an optional monthly subscription that begins with a free trial. If you subscribe, the purchase is made through Apple, and Apple handles your payment. We never see or store your card or payment details. We use RevenueCat, a subscription service, to confirm whether a purchase is active. RevenueCat receives the anonymous app identifier described above, together with purchase information such as the product, dates, and whether the subscription is active, and it may also receive technical details such as your device type and IP address. We use this only to unlock voice for you and to count your voice usage.

**Routine technical information.** Like any app that connects to the internet, Cribbit's connections produce basic technical records:

- When audio is sent for transcription, our hosting provider, Supabase, automatically keeps routine service logs about the request, which may include the date and time, the size of the request, and the IP address it came from. We use these logs only to operate, secure, and troubleshoot the service, and we do not use them to identify you.
- Cribbit checks for app updates through Expo's update service. These requests include basic technical details such as the app version and your device's operating system, along with your IP address.
- If you install Cribbit through TestFlight or the App Store, Apple may share limited, aggregated information with us, such as installs and crash reports, if you have chosen to share this with app developers. Apple handles that information under its own privacy policy.

**We do not collect:** your name, email address, account credentials, payment card details, contact lists, or location data. Cribbit has no user accounts, no cloud sync, no analytics or tracking tools, and no advertising integrations. We do not sell your information.

## 2. How We Use Information

Audio you record is sent, via our backend service, to a third-party provider, Groq, solely to produce your transcript and title. Groq converts your recorded audio into text, cleans that text up (punctuation, paragraph breaks, filler-word removal), and generates a suggested title.

Our backend function (hosted on Supabase) relays your audio and transcript text to Groq and returns the result to the app. It does not save your audio, ideas, or transcripts. Our agreement with Groq prohibits Groq from using your audio or text to train or fine-tune AI models, and we do not sell your information or use it for advertising.

We also use the anonymous app identifier, usage counters, and RevenueCat's purchase check described in Section 1 to apply the free recordings and monthly voice allowance, to confirm a subscription, and to protect the service from abuse.

Groq and our other service providers may process data in the United States and in other countries where they operate.

Each of these services processes data under its own privacy policy and terms, which we encourage you to review:

- Groq: https://groq.com/privacy-policy
- Supabase: https://supabase.com/privacy
- Expo: https://expo.dev/privacy
- RevenueCat: https://www.revenuecat.com/privacy/
- Apple: https://www.apple.com/legal/privacy/

## 3. Data Retention

- **Audio recordings** are discarded after transcription completes and are not retained by Cribbit. We have turned on Groq's Zero Data Retention setting for our account, so Groq does not keep your audio after the request is processed.
- **Transcript text sent for cleanup and titles** is not stored by Groq either. With Zero Data Retention on, the text we send is not logged or kept after the request is processed.
- **Anonymous identifier and usage counts.** Our backend keeps the anonymous app identifier and its usage counters for as long as needed to run the voice plan and protect the service. They are not linked to your name or any account. Because they are not linked to you, we generally cannot look up the ones that belong to your device, and deleting the app does not remove them. Contact us using the details below with any questions.
- **Subscription records** are kept by Apple and RevenueCat under their own policies.
- **Service records.** Groq may still keep basic usage records that do not include your content, such as request counts and timing, for billing and operations. Supabase service logs and Expo update requests are described in Section 1.
- **Ideas (titles, transcripts, tags)** are stored only locally on your device. We do not keep a separate copy. Deleting an idea, a tag, or the app itself removes this data from your device; we have no server-side copy to delete on our end.

## 4. Security

Audio and text travel between the app, our backend, and Groq over encrypted (HTTPS) connections. Ideas stored on your device are protected by your device's own security features, such as your passcode and device encryption. No method of transmission or storage is completely secure, so we cannot guarantee absolute security.

## 5. Your Choices

Because your idea content lives only on your device, you control it directly within the app. Editing, retagging, or deleting any idea removes it. You can also turn off Cribbit's microphone access at any time in your device's Settings under Privacy & Security, then Microphone. There is no account to manage or delete, since none exists. You can cancel a voice subscription at any time in your Apple ID subscription settings, and Cribbit also links to that page in Settings. If you have questions about information we may hold about you, such as service logs, contact us using the details below.

## 6. Children's Privacy

Cribbit is not directed at, and is not intended for use by, children under the age of 13. We do not knowingly collect information from children under 13.

## 7. International Users

Cribbit and this Privacy Policy currently address use within the United States. If we expand to support additional languages or make the app available to users in other regions, we will update this Privacy Policy accordingly to reflect any additional obligations that may apply.

## 8. Changes to This Policy

We may update this Privacy Policy from time to time as the app evolves. We'll update the effective date above when changes are made. Continued use of Cribbit after changes take effect constitutes acceptance of the updated policy.

## 9. Contact Us

Questions about this policy or how Cribbit handles data can be directed to:

**privacy@thumbo.com**
