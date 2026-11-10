# Privacy Policy — Vazha (واژه)

_Last updated: 10 November 2026_ · [فارسی](PRIVACY_POLICY.fa.md)

This Privacy Policy applies to **Vazha (واژه)**, an English⇄Persian dictionary and study app for Android (package `app.vazhe.dictionary`) and its offline web version, published by **GiTi Tech** ("we", "us", "our"). You can reach us at **support@ourgiti.com**.

## 1. Summary

- **We, the developer, do not collect, receive, store, sell or analyze personal data about you.** Apart from a static web host for the offline pack (no accounts, no database), we run no servers for the app. The only files the app downloads are static, public files: the offline pack from our own host and the offline translation models from Google (section 4). The app has no accounts, no sign-in, no analytics of its own and no crash reporting.
- The dictionary, the lessons, practice, cards and the file assistant work **fully offline**. After the first start the Android app downloads one offline pack (pictures, offline speech recognition and Persian text recognition) and the translation models in the background; after that everything works without internet. Your history, saved words, progress and settings stay **on your device** (and in your own Android backup if it is on; section 3). We cannot see them.
- **The Android app shows ads served by Google AdMob** (the Google Mobile Ads SDK). To serve, limit and measure ads, Google processes some data from your device, for example your IP address, the Android advertising ID and ad interactions (section 5). We do not receive that data. Where the law requires it (for example in the EEA, the UK and Switzerland), Google's consent form is shown first and no ad is requested before you have made your choice.
- Ads are limited: never during lessons, quizzes, pronunciation practice, flashcard review, the camera, the translator or the file assistant, and never on the welcome, set-up and tour screens (section 5).
- The app uses the internet only for ads and the consent form, the one-time background download of the offline pack and the translation models, and things you start yourself (an e-mail, a link, Google Play's rating dialog). Optional features use the **camera**, **microphone** and **notifications** permissions, requested only when you first use them. Photos and files are processed on your device and not kept; the app never stores or sends audio.
- You can delete everything yourself at any time (section 8).

## 2. Information we do not collect ourselves

We do not collect or ask for: your name, email address, phone number, address, account or login details, payment information, location, contacts, calendar, photo library, files, camera or microphone recordings, device identifiers, cookies, usage analytics, search queries or any other personal information. The Android permissions of the app are: `INTERNET` and `ACCESS_NETWORK_STATE` (ads, consent form, the offline pack and model downloads), `com.google.android.gms.permission.AD_ID` (the advertising ID used by Google's ad SDK), and the optional `CAMERA`, `RECORD_AUDIO` and `POST_NOTIFICATIONS`, described in sections 4 and 5; libraries add the usual system permissions for background work and Google Play. The app does not read your photo library, contacts, location or files, apart from the photos and files you choose to open (the camera, the file assistant, a backup file to import).

## 3. Information stored on your device

To work, the app keeps the following **only inside the app's private storage on your device**:

- your settings (interface language, theme, text size, accent, speech rate, level, daily goal, optional reminder time, translation preferences),
- your recent searches (history), and a list of the words you searched for and did not find (at most 100, with a count; Settings → My data → Words not found, where you can remove them or clear the list),
- **My words**: the words you saved with the heart, with their flashcard progress (Leitner box, due dates) and optional tags,
- your progress in lessons, practice, word packs, picture cards and the short stories (the page you stopped on and your answers to the reading questions), and a short log of your practice results (right/wrong, pronunciation scores as numbers — never audio),
- a short record of each finished practice **session** (which section, when, how long, how many questions, the score) for the Progress screen, and a **Certificate ID** (a one-way hash of the Android device identifier, so that one device gets one certificate; in a browser a random value; the identifier itself is never stored, shown or sent) with, for each level, the date you marked a certificate request as sent (never your name or email),
- small counters for the ads rules (number of app sessions, completed lessons, when the last ad was shown, until when you chose an ad-free day) and for the daily file translations of the file assistant (the date, the counts and a short code per file made from it, not its name or text),
- the offline pack and the translation models (data files, not personal data).

This data is created and used locally to provide the features you use. We do not upload, sync or receive it, and we cannot access, recover or restore it.

**Android backup.** So that your progress can move to a new phone, the app allows Android backup for one part of its data: your progress, My words, cards, settings (among them your ad choice and how many files you translated today) and the search history (kept in one database on the phone) and a small file with the app theme. Android copies this to your own Google account backup (end-to-end encrypted on phones with a screen lock) and puts it back when you set up a new phone; you can turn Android backup off in the phone's settings. We do not receive this backup. The offline pack, models, caches and the files you open in the file assistant are not included. You can also save and open a backup file yourself in Settings → My data.

## 4. Features that involve other software on your device

- **The offline pack.** After the first start, the Android app downloads one content pack in the background from our own web host, **vazhalearn.ourgiti.com**: the pictures of lessons and cards, the offline speech models and the Persian text model, so that the app then works without internet. Later starts only check a small list file there and fetch what changed. The app sends no account, no identifier and none of your data with these requests. As with any website, the host's web server sees your phone's IP address and normal request details and may keep them in its usual server logs for a short time; we use them only to keep the service working and do not link them to you. In Settings you can pause the download or allow it only on Wi-Fi.
- **Lesson downloads (Learn).** The lessons are inside the app. The Learn tab can also ask the same host for its list of lessons and offer extra lesson packs, which are downloaded **only when you tap Download** (or, if you switch it on, automatically on Wi-Fi) with the same kind of plain request. Downloaded lessons are stored in the app's private storage, work offline and can be deleted in Learn at any time; deleting a lesson does not delete your progress.
- **Pronunciation (text-to-speech).** When you tap a speaker, US or UK button, the app hands the English text to the text-to-speech engine you have selected in your Android settings (for example Google, Samsung or another vendor). That engine is a separate system component and is governed by its vendor's privacy policy. Depending on the engine and voice, the vendor's software may process the text in its own way; Vazha sends nothing over the network for this.
- **Microphone and speech recognition (pronunciation practice, voice translator).** When you speak, the app asks the speech-recognition service set on your device (often Google's) to turn your speech into text, and uses that text. **Your device's speech-recognition service may process the audio, including on its provider's servers, depending on your device and its settings**, and is covered by its provider's privacy policy. When there is no internet and your phone has no offline pack for the language, the app uses its own small speech model (Vosk, from the offline pack) on the phone instead; the sound is then processed only on the phone. The "Download for offline use" button of the voice translator asks Android for its offline speech pack (Android 13 and newer) or opens the phone's voice settings. The microphone permission is asked before your first recording and you can refuse it.
- **Compare your voice.** You can record yourself and see your voice next to the model voice. The recording is kept in the phone's memory only, is deleted when you leave the page or record again, and is never saved to a file or sent anywhere. The words in it can be checked by a small on-device speech model that comes with the offline pack.
- **Camera and photos.** When you tap the camera button, the app asks Android for one photo (camera app or photo picker) and reads the text in it on your device: English with Google's ML Kit text recognition (bundled in the app) and Persian with the open-source Tesseract recogniser, whose Persian model comes with the offline pack. The translation drawn over the photo is made on your phone too. The photo is held in memory only while it is used, the temporary file is deleted right after recognition, nothing is saved to your gallery, and the photo and the recognised text are not sent anywhere by the app. You can refuse the camera permission and still use the rest of the app.
- **File assistant.** You can open a PDF, a Word or text file, photos of pages or pasted text, also through Share or Open with from other apps. Vazha reads it on your phone (English and Persian, also in photos and scans): it opens as a chat in which it finds the parts that answer your questions, lists amounts and dates, helps with words and grammar and can translate the text with the on-device translator. The file, your questions and the answers are kept only in the phone's memory while the screen is open and are deleted when you leave it or remove the file. A picture made for text recognition is deleted at once. Nothing is sent anywhere; no file names, text or questions are recorded. If you choose Remind me on a date, a local notification is set on your phone. It gives no legal, financial or immigration advice and can make mistakes.
- **Voice translator and offline translation models.** Translation uses Google's ML Kit on-device translation. Once the first start is finished, the app downloads the two translation models (about 30 MB each) from Google in the background (Settings can limit this to Wi-Fi); afterwards translation runs on your device and the text you translate is not sent anywhere by the app. Google describes the data ML Kit itself may collect (device and app information, performance metrics, the configured source and destination languages and error codes, used for diagnostics and usage analytics) in its public ML Kit data disclosure: <https://developers.google.com/ml-kit/android-data-disclosure>. You can delete the downloaded models in Settings.
- **Backup export and import.** The export creates a JSON file **only when you tap the button**. It contains the words you saved and your progress — not your identity. It is passed to the Android share sheet, where **you** choose where it goes. Once you send it to another app or service, that app's or service's privacy policy applies. The file is not encrypted; treat it like any personal file. Import only reads a file you choose.
- **Notifications (daily reminder, come-back reminders, file reminders).** Optional. If you switch a reminder on, the app asks for the notification permission and schedules local notifications on your device: the daily reminder (one a day, at the time you chose, the day after your last visit) and the come-back reminders (only if you stay away: after 2 days, then weekly, then monthly, at most 6 monthly ones, between 9:00 and 20:00), and the dates you ask the file assistant to remind you of. To plan them the app keeps the time of your last visit on your device. Their wording uses your next lesson and your streak, which never leave the device. No push service, server or network is involved. You can switch them off any time, or refuse the permission.
- **Report a problem.** If you tap Report a problem, your email app opens with a draft to our support address. The draft contains the id and type of the word, lesson or question, the kind of problem you chose, the app version and the language of the screen (and, if you choose to send it, your list of words not found). Nothing is sent until you press send in your email app.
- **Rating the app.** Rarely, after a success such as a passed lesson, the app asks whether you would like to rate it and then opens Google Play's own rating dialog. Google Play decides whether the dialog appears; the app never learns your rating.
- **Links that open outside the app.** Some screens contain links (for example to this policy, license texts, Wiktionary, Tatoeba). Tapping one opens your browser, and the website you visit may receive technical information such as your IP address under its own privacy policy. Vazha does not contact these sites by itself.
- **Android System WebView.** The app draws its screens with the Android System WebView component supplied with your device. It is part of the operating system.
- **Google Play.** If you install the app from Google Play, Google processes information about your download and device under Google's own privacy policy. We do not receive personal data from Google. Google may give us aggregated, non-identifying statistics (for example installs by country or Android version, or crash and performance reports from users who chose to share diagnostics with Google); these do not come from code inside Vazha and do not identify you. Google AdMob also gives us aggregated reports about ad impressions and earnings, without identifying individual users.
- **Web version.** If you use the offline web version in a browser, it stores the same local data in your browser's storage and caches the dictionary files in your browser. It shows no ads. The server that hosts the web page may keep standard technical logs (such as IP address and browser type) under its own policy; we do not receive or analyze those logs and do not use analytics or cookies.
- **This policy page.** This page is hosted on GitHub Pages. GitHub may process technical data about visitors to this page under GitHub's privacy statement; we do not receive that data.

- **Certificate request (optional).** When you meet the conditions of a level you may ask for a "Certificate of completion". The app transmits nothing: it prepares an email (your name, email address, the Certificate ID and a summary of your results) in your email app, and **you** decide whether to send it to support@ourgiti.com. Vazha does not store your name or email address. If you send it, we receive it by email and use it only to issue and check the certificate and to detect duplicate requests, and keep it no longer than needed.

## 5. Advertising (Google AdMob)

**What we show.** The Android app shows ads from **Google AdMob**, which helps keep the app free. We use only Google's Mobile Ads SDK; there are no other ad networks, no mediation and no analytics SDKs in the app. There are three kinds:

- a small **banner** at the bottom of list and browse screens only (word page, the Learn and study lists, Practice topic lists, the Cards grid, the Stories library, a grammar rule card), from your second app session on;
- an occasional **full-screen ad** after you tap Done/Continue on the completion screen of a lesson, quiz, grammar session, story or unit — at most one per three completed sessions, at least 8 minutes apart, at most three a day, never in your first two days or first five completed sessions, never in the first 3 minutes after the app opens and never within 2 minutes after an error of the app;
- an **optional rewarded ad** that you choose to watch: for 24 hours without ads (Settings → Ads, or a card after a finished lesson), or for one more whole-file translation in the file assistant on a day you have used the free ones (one a day, three a day in your first week; up to five more a day with a video each). Questions about a file and everything else stay free.

There are no ads on the Home/Search screen, during the welcome, set-up and tour screens, active lessons, quizzes, pronunciation practice, grammar questions and results, flashcard review, the story reader, the camera, the translator, the file assistant, Settings or privacy screens. We limit ad content to the "PG" content rating and block sensitive ad categories in AdMob.

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

Vazha is a general-audience study app and is **not directed at children under 13** (or under 16 where local law sets a higher age); the target age group in Google Play is 13 and over. We do not knowingly collect personal information from children, and the app does not collect any itself. Because the app is not child-directed, the ad SDK is not set to child-directed treatment, but ad content is capped at "PG". The app is not part of Google Play's "Designed for Families" program. If you believe a child has sent us personal information, contact us and we will delete it. A dictionary can contain words that some people find offensive.

## 8. Your choices, access and deletion

- **Delete in the app:** Settings → **Delete all my data** removes recent searches, My words, lesson, practice, pack and picture-card progress, the practice log and settings. You can also clear only the recent searches or the words not found, remove single words, or reset only your progress.
- **Delete from your device:** Android Settings → Apps → Vazha → Storage → **Clear data** (this also removes the offline pack and the models), or **uninstall** the app.
- **Android backup:** turn it off in the phone's settings (Settings → Google → Backup, wording varies by device).
- **Certificate ID:** on Android it follows the device and is recomputed, so it cannot be deleted from inside the app; in a browser it goes with the site data. Keep the email of a certificate request.
- **Ads:** see section 5 (privacy options, advertising ID reset, ad personalization opt-out, ad-free day).
- **Offline translation models:** Settings → Voice & translation → delete. **Offline pack:** Settings → Voice & translation → Offline pack (pause, Wi-Fi only).
- **Web version:** clear the site's data in your browser settings.
- **Backup files** you exported are ordinary files you control; delete them wherever you saved or sent them.

## 9. Your rights

Depending on where you live (for example in the European Economic Area, the United Kingdom, California and other US states, Canada, Brazil, Australia and other countries), you may have rights over your personal data, such as to access, correct, delete, restrict, object to processing, move your data, withdraw consent, opt out of targeted advertising, and to complain to your data-protection authority. We hold no personal data about you, so there is nothing for us to access, correct, delete or transfer, and you control all locally stored data directly in the app (section 8). For data processed by Google for advertising, you can use the controls in section 5 and the tools Google provides (for example <https://myaccount.google.com/data-and-privacy>). We never discriminate against anyone for exercising privacy rights.

If you email us, we receive your email address and message. We use them only to answer you, keep them no longer than needed, and do not share them.

## 10. Security

We reduce risk by design: we have no accounts and no database of user data to breach; our web host serves only public, static files. Local data is protected by the Android app sandbox and your device's own security (screen lock and storage encryption); we recommend keeping them enabled. The offline pack is downloaded over HTTPS and every file is checked before use. Data sent by Google's ad SDK is encrypted in transit (TLS). No method is perfectly secure, and exported backup files are your responsibility.

## 11. International users

We do not transfer personal data across borders ourselves. Google may process advertising data in the United States and other countries where it operates, under its own privacy policy and transfer safeguards.

## 12. Do Not Track and Global Privacy Control

Android apps do not receive Do Not Track or Global Privacy Control browser signals. Use the choices in section 5 (consent form, privacy options, advertising ID and ad personalization settings of your device) to control advertising.

## 13. Open-source components and data

The app code is MIT-licensed. The dictionary data, lesson sentences and picture-card photographs come from open sources (Wiktionary via kaikki.org, Tatoeba, Princeton WordNet, Wikimedia Commons, the New General Service List and wordfreq for word-pack selection) or were written for the app (CC BY-SA 4.0), and the Vazirmatn font, Lucide icons and flag-icons are bundled too. Attributions and licenses are in the app (Settings → About & licenses), in `NOTICE.md` and in `docs/LICENSE_AUDIT.md`. The bundled libraries (Capacitor and its filesystem, share, haptics, local-notifications, text-to-speech, camera, speech-recognition, ML Kit text-recognition and ML Kit translation plugins, Vosk for offline speech, Tesseract for Persian text in pictures, AndroidX WorkManager for the background download) run on your device. The only components that contact a server are the Google Mobile Ads SDK and consent service (section 5), the ML Kit model download, the offline pack from our own host (section 4) and Google Play (the rating dialog).

## 14. Changes to this policy

We may update this policy, for example if the app changes. The "last updated" date at the top shows the current version, and earlier versions remain available in the project's public history. If a change affects what is collected or shared, we will update the policy, the Google Play Data safety form and the in-app text before shipping it.

## 15. Contact

**GiTi Tech** — **support@ourgiti.com**

If you are in the EEA or UK and are not satisfied with our answer, you may contact your local data-protection authority.
