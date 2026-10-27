# Privacy Policy — Vazhe (واژه)

_Last updated: 26 October 2026_ · [فارسی](PRIVACY_POLICY.fa.md)

This Privacy Policy applies to **Vazhe (واژه)**, an English⇄Persian dictionary and study app for Android (package `app.vazhe.dictionary`) and its offline web version, published by **GiTi Tech** ("we", "us", "our"). You can reach us at **vazhe.app@gmail.com**.

## 1. Summary

- **We, the developer, do not collect, receive, store, sell or analyze personal data about you.** We run no servers for the app, and it has no accounts, no sign-in, no analytics of its own and no crash reporting.
- Searching, lessons, practice and cards work **fully offline**. Your history, favorites, progress and settings stay **on your device only**. We cannot see them.
- **The Android app shows ads served by Google AdMob** (the Google Mobile Ads SDK). To serve, limit and measure ads, Google processes some data from your device, for example your IP address, the Android advertising ID and ad interactions (section 5). We do not receive that data. Where the law requires it (for example in the EEA, the UK and Switzerland), Google's consent form is shown first and no ad is requested before you have made your choice.
- Ads are limited: never during lessons, quizzes, pronunciation practice, flashcard review, the camera or the translator, and never on the welcome, set-up and tour screens (section 5).
- The app uses the internet only for ads and the consent form, and — when you ask for it — to download the offline translation models once (section 4). Optional features use the **camera**, **microphone** and **notifications** permissions, requested only when you first use them. Photos are processed on your device and not kept; the app never stores or sends audio.
- You can delete everything yourself at any time (section 8).

## 2. Information we do not collect ourselves

We do not collect or ask for: your name, email address, phone number, address, account or login details, payment information, location, contacts, calendar, photo library, files, camera or microphone recordings, device identifiers, cookies, usage analytics, search queries or any other personal information. The Android permissions of the app are: `INTERNET` and `ACCESS_NETWORK_STATE` (ads, consent form, optional model download), `com.google.android.gms.permission.AD_ID` (the advertising ID used by Google's ad SDK), and the optional `CAMERA`, `RECORD_AUDIO` and `POST_NOTIFICATIONS`, described in sections 4 and 5. The app does not read your photo library, contacts, location or files (apart from the one photo you choose to scan or the one backup file you choose to import).

## 3. Information stored on your device

To work, the app keeps the following **only inside the app's private storage on your device**:

- your settings (interface language, theme, text size, accent, speech rate, level, daily goal, optional reminder time, translation preferences),
- your recent searches (history),
- **My words**: the words you saved with the heart, with their flashcard progress (Leitner box, due dates) and optional tags,
- your progress in lessons, practice, word packs, picture cards and the short stories (the page you stopped on and your answers to the reading questions), and a short log of your practice results (right/wrong, pronunciation scores as numbers — never audio),
- a short record of each finished practice **session** (which section, when, how long, how many questions, the score) for the Progress screen, and a **Certificate ID** (a one-way hash of the Android device identifier, so that one device gets one certificate; in a browser a random value; the identifier itself is never stored, shown or sent) with, for each level, the date you marked a certificate request as sent (never your name or email),
- small counters for the ads rules (number of app sessions, completed lessons, when the last ad was shown, and until when you chose an ad-free day), so that ads stay limited.

This data is created and used locally to provide the features you use. We do not upload, sync or receive it, and we cannot access, recover or restore it. The app opts out of Android's automatic cloud backup, so this data is not copied to cloud backups by the app.

## 4. Features that involve other software on your device

- **Pronunciation (text-to-speech).** When you tap a speaker, US or UK button, the app hands the English text to the text-to-speech engine you have selected in your Android settings (for example Google, Samsung or another vendor). That engine is a separate system component and is governed by its vendor's privacy policy. Depending on the engine and voice, the vendor's software may process the text in its own way; Vazhe sends nothing over the network for this.
- **Backup export and import.** The export creates a JSON file **only when you tap the button**. It contains the words you saved and your progress — not your identity. It is passed to the Android share sheet, where **you** choose where it goes. Once you send it to another app or service, that app's or service's privacy policy applies. The file is not encrypted; treat it like any personal file. Import only reads a file you choose.
- **Camera and photos (text lookup).** When you tap the camera button, the app asks Android for one photo (camera app or photo picker) and reads the text in it with Google's ML Kit text-recognition model, which is bundled inside the app and runs entirely on your device. The photo is held in memory only while it is analysed, the temporary file is deleted right after recognition, nothing is saved to your gallery, and the photo and the recognised text are not sent anywhere by the app. You can refuse the camera permission and still use the rest of the app.
- **Microphone and speech recognition (pronunciation practice, voice translator).** When you record, the app asks the speech-recognition service set on your device (often Google's) to turn your speech into text, and uses that text. The app itself does not record, store or send audio and receives only the resulting text. **Your device's speech-recognition service may process the audio, including on its provider's servers, depending on your device and its settings**, and is covered by its provider's privacy policy; Vazhe cannot force it to work offline (you can install an offline language pack in your system settings). The microphone permission is asked before your first recording and you can refuse it.
- **Voice translator and offline translation models.** Translation uses Google's ML Kit on-device translation. The first time you use a language, the model (about 30 MB) is downloaded from Google over the internet — only after you tap to download or translate; afterwards translation runs on your device and the text you translate is not sent anywhere by the app. Google describes the data ML Kit itself may collect (device and app information, performance metrics, the configured source and destination languages and error codes, used for diagnostics and usage analytics) in its public ML Kit data disclosure: <https://developers.google.com/ml-kit/android-data-disclosure>. You can delete the downloaded models in Settings.
- **Notifications (daily reminder and come-back reminders).** Two separate, optional switches. If you switch one on, the app asks for the notification permission and schedules local notifications on your device: the daily reminder (one a day, at the time you chose, the day after your last visit) and the come-back reminders (only if you stay away: after 2 days, then weekly, then monthly, at most 6 monthly ones, between 9:00 and 20:00). To plan them the app keeps the time of your last visit on your device. Their wording uses your next lesson and your streak, which never leave the device. No push service, server or network is involved. You can switch either off any time, or refuse the permission.
- **Links that open outside the app.** Some screens contain links (for example to this policy, license texts, Wiktionary, Tatoeba). Tapping one opens your browser, and the website you visit may receive technical information such as your IP address under its own privacy policy. Vazhe does not contact these sites by itself.
- **Android System WebView.** The app draws its screens with the Android System WebView component supplied with your device. It is part of the operating system.
- **Google Play.** If you install the app from Google Play, Google processes information about your download and device under Google's own privacy policy. We do not receive personal data from Google. Google may give us aggregated, non-identifying statistics (for example installs by country or Android version, or crash and performance reports from users who chose to share diagnostics with Google); these do not come from code inside Vazhe and do not identify you. Google AdMob also gives us aggregated reports about ad impressions and earnings, without identifying individual users.
- **Web version.** If you use the offline web version in a browser, it stores the same local data in your browser's storage and caches the dictionary files in your browser. It shows no ads. The server that hosts the web page may keep standard technical logs (such as IP address and browser type) under its own policy; we do not receive or analyze those logs and do not use analytics or cookies.
- **This policy page.** This page is hosted on GitHub Pages. GitHub may process technical data about visitors to this page under GitHub's privacy statement; we do not receive that data.

- **Certificate request (optional).** When you meet the conditions of a level you may ask for a "Certificate of completion". The app transmits nothing: it prepares an email (your name, email address, the Certificate ID and a summary of your results) in your email app, and **you** decide whether to send it to vazhe.app@gmail.com. Vazhe does not store your name or email address. If you send it, we receive it by email and use it only to issue and check the certificate and to detect duplicate requests, and keep it no longer than needed.

## 5. Advertising (Google AdMob)

**What we show.** The Android app shows ads from **Google AdMob**, which helps keep the app free. We use only Google's Mobile Ads SDK; there are no other ad networks, no mediation and no analytics SDKs in the app. There are three kinds:

- a small **banner** at the bottom of browsing screens only (Search/Home, word page, Learn level list, Practice, Cards), from your second app session on;
- an occasional **full-screen ad** after you tap Done/Continue on the completion screen of a lesson or quiz — at most one per three completed sessions, at least 8 minutes apart, at most three a day, and none in your first two days or first five completed sessions;
- an **optional rewarded ad** that you choose to watch (Settings → Ads, or a card after a finished lesson) to get 24 hours without ads.

There are no ads during the welcome, set-up and tour screens, active lessons, quizzes, pronunciation recording, flashcard review, the camera, the translator, Settings or privacy screens. We limit ad content to the "PG" content rating and block sensitive ad categories in AdMob.

**Data Google collects for ads.** According to Google's published Play data disclosure for the Google Mobile Ads SDK (<https://developers.google.com/admob/android/privacy/play-data-disclosure>, checked 25 October 2026), the SDK collects and shares, for advertising, analytics and fraud prevention: **IP address** (which can help estimate a device's general location), **user product interactions** (such as app launches, taps and video views), **diagnostic information** (such as launch time, hang rate and energy usage) and **device and account identifiers** (including the Android advertising ID and the app set ID). This data is encrypted in transit. We do not receive it and we cannot see it.

**Consent and your choices.**

- On every app start, after the welcome flow, the app first asks Google's consent service (User Messaging Platform) whether consent is required where you are. Only if it is required is a form shown; **no ad is requested and the ad SDK is not started until that is resolved.** If you are offline or the form is unavailable, no ads are shown.
- Where a privacy-options entry is required, **Settings → Ads → Ad privacy options** lets you change your choice at any time.
- You can reset or delete your **advertising ID**, or opt out of ad personalization, in your Android settings (Settings → Google → Ads, wording varies by device). Ad-ID collection can be stopped by the device.
- You can get **24 ad-free hours** by watching one rewarded ad.
- Google's own privacy policy and advertising information: <https://policies.google.com/privacy> and <https://policies.google.com/technologies/ads>. How Google uses data from apps that use its services: <https://policies.google.com/technologies/partner-sites>.

**Selling and sharing.** We do not sell your personal information and we do not receive any from the ad SDK. In some places (for example some US states) the processing of ad identifiers by an advertising partner can count as "sharing" for cross-context behavioural advertising or "targeted advertising"; Google acts as an independent party for that processing under its own terms and policies, and the choices above (consent form where required, privacy options, ad-ID reset, ad personalization opt-out) are how you control it.

## 6. Legal basis and our role

We do not collect or receive personal data ourselves, so for the parts of the app that run on your device we do not act as a controller or processor of personal data about you in the sense of the EU General Data Protection Regulation (GDPR), the UK GDPR or similar laws. For advertising, Google determines the purposes and means of the processing it carries out through its ad services. Where consent is the legal basis (for example in the EEA, the UK and Switzerland), it is requested through Google's certified consent form, and you can withdraw it at any time through the privacy options described above or in your device settings.

## 7. Children

Vazhe is a general-audience study app and is **not directed at children under 13** (or under 16 where local law sets a higher age); the target age group in Google Play is 13 and over. We do not knowingly collect personal information from children, and the app does not collect any itself. Because the app is not child-directed, the ad SDK is not set to child-directed treatment, but ad content is capped at "PG". The app is not part of Google Play's "Designed for Families" program. If you believe a child has sent us personal information, contact us and we will delete it. A dictionary can contain words that some people find offensive.

## 8. Your choices, access and deletion

- **Delete in the app:** Settings → **Delete all my data** removes recent searches, My words, lesson, practice, pack and picture-card progress, the practice log and settings. You can also clear only the recent searches or remove single words, or reset only your progress.
- **Delete from your device:** Android Settings → Apps → Vazhe → Storage → **Clear data**, or **uninstall** the app.
- **Certificate ID:** on Android it follows the device and is recomputed, so it cannot be deleted from inside the app; in a browser it goes with the site data. Keep the email of a certificate request.
- **Ads:** see section 5 (privacy options, advertising ID reset, ad personalization opt-out, ad-free day).
- **Offline translation models:** Settings → Voice & translation → delete.
- **Web version:** clear the site's data in your browser settings.
- **Backup files** you exported are ordinary files you control; delete them wherever you saved or sent them.

## 9. Your rights

Depending on where you live (for example in the European Economic Area, the United Kingdom, California and other US states, Canada, Brazil, Australia and other countries), you may have rights over your personal data, such as to access, correct, delete, restrict, object to processing, move your data, withdraw consent, opt out of targeted advertising, and to complain to your data-protection authority. We hold no personal data about you, so there is nothing for us to access, correct, delete or transfer, and you control all locally stored data directly in the app (section 8). For data processed by Google for advertising, you can use the controls in section 5 and the tools Google provides (for example <https://myaccount.google.com/data-and-privacy>). We never discriminate against anyone for exercising privacy rights.

If you email us, we receive your email address and message. We use them only to answer you, keep them no longer than needed, and do not share them.

## 10. Security

We reduce risk by design: we have no accounts, no servers and no database of user data to breach. Local data is protected by the Android app sandbox and your device's own security (screen lock and storage encryption); we recommend keeping them enabled. Data sent by Google's ad SDK is encrypted in transit (TLS). No method is perfectly secure, and exported backup files are your responsibility.

## 11. International users

We do not transfer personal data across borders ourselves. Google may process advertising data in the United States and other countries where it operates, under its own privacy policy and transfer safeguards.

## 12. Do Not Track and Global Privacy Control

Android apps do not receive Do Not Track or Global Privacy Control browser signals. Use the choices in section 5 (consent form, privacy options, advertising ID and ad personalization settings of your device) to control advertising.

## 13. Open-source components and data

The app code is MIT-licensed. The dictionary data, lesson sentences and picture-card photographs come from open sources (Wiktionary via kaikki.org, Tatoeba, Princeton WordNet, Wikimedia Commons, the New General Service List and wordfreq for word-pack selection) or were written for the app (CC BY-SA 4.0), and the Vazirmatn font, Lucide icons and flag-icons are bundled too; all of it is inside the app and never fetched at run time. Attributions and licenses are in the app (Settings → About & licenses), in `NOTICE.md` and in `docs/LICENSE_AUDIT.md`. The bundled libraries (Capacitor and its filesystem, share, haptics, local-notifications, text-to-speech, camera, speech-recognition, ML Kit text-recognition and ML Kit translation plugins) run on your device. The only components that contact a server are the Google Mobile Ads SDK / consent service (section 5) and the ML Kit model download (section 4).

## 14. Changes to this policy

We may update this policy, for example if the app changes. The "last updated" date at the top shows the current version, and earlier versions remain available in the project's public history. If a change affects what is collected or shared, we will update the policy, the Google Play Data safety form and the in-app text before shipping it.

## 15. Contact

**GiTi Tech** — **vazhe.app@gmail.com**

If you are in the EEA or UK and are not satisfied with our answer, you may contact your local data-protection authority.
