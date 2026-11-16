# Privacy Policy for Al Quran: Hifz, Audio, Tafsir

**Effective Date:** November 4, 2026  
**Official Hosted Version:** [sites.google.com/view/privacypolicy-al-quran/home](https://sites.google.com/view/privacypolicy-al-quran/home)

Salmanul Khairy built the **Al Quran: Hifz, Audio, Tafsir** application (formerly known as *Al-Quran Read n Learn*, package ID: `com.salmanul.alquran`) as a free, ad-free, non-commercial Islamic educational application. This Service is provided by Salmanul Khairy at no cost and is intended for use as is.

If you choose to use this Service, you agree to the collection and use of information in accordance with this Privacy Policy. The information used by the application is strictly for providing and improving the Service. I do not sell, rent, trade, or share your personal information with any third parties except as described in this Privacy Policy.

---

## 1. Information Collection and Use — Local & Auto-Backup Storage

Al Quran: Hifz, Audio, Tafsir does not require user registration or user accounts. All personal study data—including bookmarks, personal reflections and reading notes, Hifz (memorization) progress, Spaced Repetition (SRS) review schedules, Khatm Planner goals, Digital Tasbih counts, unlocked achievement badges, and downloaded translations, Tafsir, or audio files—is stored locally on your device.

We never upload your personal study data to any developer-operated servers.

- **Manual Backup & Restore:** When you use the Export or Share Backup feature, your backup file (`.json`) is saved directly to the local folder or cloud app that you explicitly select.
- **Android Auto Backup:** If enabled on your Android device, Android's built-in system backup may store a lightweight snapshot (`auto_cloud_vault.json`) in your private Google Drive app-data folder solely to restore your progress when switching devices. You can permanently erase this snapshot at any time using the in-app **"Delete All Data & Reset ID"** button.

---

## 2. Location Information (Prayer Times & Qibla Compass)

To provide accurate daily prayer times, Hijri calendar dates, and Qibla compass direction, the app requests optional access to your device's geographic location.

- **Collection:** We access your geographic coordinates (latitude and longitude) only when you explicitly request a prayer time update, tap the location refresh button on the Home screen, or open the Qibla Compass.
- **Usage & Ephemeral Processing:** Coordinates are used locally on your device to calculate the Qibla bearing toward Makkah, and are transmitted via encrypted HTTPS to the [Aladhan API](https://aladhan.com) solely to calculate daily prayer timings for your area. We do not track your location in the background and do not store your location history on any external server.
- **User Control:** Location access is completely optional. You can deny or revoke location permission at any time in your Android device settings, or clear your saved coordinates inside the app via **Settings → Delete All Data & Reset ID**.

---

## 3. Microphone & Voice Recognition (Voice Verse Finder & Tasmee' Exam)

The app includes a **Voice Verse Finder** (to identify a Quranic verse recited aloud) and a **Tasmee' AI Hifz Exam** (to test your Quran memorization by recitation).

- **Collection & Usage:** Microphone access (`RECORD_AUDIO`) is activated only when you explicitly tap the Microphone button inside the Voice Verse Finder or Tasmee' AI Exam screens. Spoken Arabic input is processed ephemerally in real time using Android's `SpeechRecognizer` service to match recited words against the offline 6,236-verse Quranic index on your device.
- **No Audio Storage:** We never record, save, store, or upload your voice recordings to any developer server.
- **User Control:** Microphone access is completely optional and is active only while you are actively reciting in those features. You may revoke Microphone permission at any time in your Android Settings.

---

## 4. Third-Party Services & Public Content APIs

The app uses trusted platform services and public Islamic content APIs over encrypted HTTPS to deliver app stability diagnostics, translations, Tafsir, audio recitations, and prayer times:

- **Google Play Services:** [policies.google.com/privacy](https://policies.google.com/privacy)
- **Google Analytics for Firebase & Firebase Remote Config** *(used strictly for anonymous usage/stability diagnostics and app configuration; Google Advertising ID collection and ad personalization are permanently disabled)*: [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)
- **Aladhan API** *(used for calculating prayer times and Hijri dates)*: [aladhan.com](https://aladhan.com)
- **Quran.com / Quran.Foundation API & QuranWBW.com** *(used for translations, word-by-word glosses, and Tafsir)*: [quran.com](https://quran.com)
- **AlQuran.cloud / Islamic Network** *(used for Quranic text and translations)*: [alquran.cloud](https://alquran.cloud)
- **MP3Quran.net, EveryAyah.com & QuranicAudio.com** *(used for streaming and caching Quranic audio recitations)*

---

## 5. Device Permissions Explained

- **Internet & Network State (`INTERNET`, `ACCESS_NETWORK_STATE`):** Required to stream or download Quran audio recitations, translations, Tafsir commentaries, and prayer times.
- **Approximate & Precise Location (`ACCESS_COARSE_LOCATION`, `ACCESS_FINE_LOCATION`):** Optional; used only at your request to compute accurate prayer timings and Qibla compass direction.
- **Microphone (`RECORD_AUDIO`):** Optional; used only when you tap the microphone button in the Voice Verse Finder or Tasmee' AI Recitation Exam.
- **Foreground Service — Media Playback (`FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_MEDIA_PLAYBACK`):** Required to play Quran audio recitations smoothly in the background while you use other apps or lock your screen.
- **Notifications (`POST_NOTIFICATIONS`):** Optional; used to display the background media player controller and to send optional daily reading, Hifz streak, and Sunnah reminders (such as Friday Surah Al-Kahf and nightly Surah Al-Mulk reminders).
- **Vibration (`VIBRATE`):** Used for subtle haptic feedback in the Digital Tasbih counter and interactive controls.
- **No Advertising ID:** This app is 100% ad-free. The Google Advertising ID (`com.google.android.gms.permission.AD_ID`) permission is explicitly removed from the application manifest.

---

## 6. Log Data & Diagnostics

When you use this Service, anonymous diagnostic and performance data may be collected through Google Play Services and Firebase Analytics to help identify bugs and improve stability. This data may include your device model, Android OS version, app version, screen interactions, and timestamps. Diagnostic logs never include your personal reading notes, bookmarks, exact saved coordinates, or voice audio.

---

## 7. Data Retention, Self-Service Deletion & Analytics Reset

Because Al Quran: Hifz, Audio, Tafsir does not use user accounts or store personal profiles on developer servers, all personal progress and preferences remain on your device for only as long as you choose to keep them.

You can permanently delete all of your app data and reset your anonymous Firebase Analytics identifier at any time directly inside the app:

1. Open **Al Quran** and tap the **Settings (Gear)** icon on the Home screen.
2. In the **General** tab, scroll down to the **Cloud & Local Backup** card.
3. Tap **"Delete All Data & Reset ID"**.
4. *(Optional)* Check **"Also reset app theme, font & display settings"** if you want a full factory reset.
5. Check the confirmation box and tap **"Delete All Data"**.

**What this deletes immediately:**
- All Hifz memorization & SRS review records, bookmarks, personal notes, study sessions, and unlocked achievement badges.
- Saved prayer-time location coordinates, Khatm Planner schedules, Digital Tasbih counters, and Tajweed Guide mastery progress.
- Your local/cloud backup vault snapshot (`auto_cloud_vault.json`) and temporary backup cache.
- Your anonymous Firebase Analytics instance ID (via `FirebaseAnalytics.resetAnalyticsData()`), disassociating your device from any prior analytics events.

**Alternative Deletion Methods:**
- You may also erase all application data at any time by uninstalling the app or by opening **Android Settings → Apps → Al Quran → Storage & cache → Clear storage / Clear data**.

---

## 8. Your Privacy Rights (GDPR, CCPA & Global Data Protection)

Regardless of where you reside, we provide built-in tools to exercise your data protection rights directly within the app without waiting for a manual support request:

- **Right to Access & Data Portability:** You can export a complete, human-readable JSON copy of all your study records, bookmarks, notes, and settings at any time via **Settings → General → Cloud & Local Backup → Export File**.
- **Right to Erasure ("Right to be Forgotten"):** You can permanently wipe all local data, cloud backup snapshots, and reset your Firebase Analytics ID at any time via **Settings → General → Cloud & Local Backup → Delete All Data & Reset ID**.
- **Right to Withdraw Consent:** You can disable optional permissions (Location, Microphone, Notifications) at any time via your Android device settings.

---

## 9. Intellectual Property, Data Credits & Open-Source Licenses

We gratefully acknowledge the scholarly institutions, Waqf projects, and open-source authors whose resources are used in this non-commercial educational application:

- **Quranic Script & Mushaf Data:** King Fahd Glorious Quran Printing Complex (Uthmani script standard) and Tanzil.net Project (verified Quran text distributed under the Creative Commons Attribution-NoDerivs 3.0 Unported License, CC BY-ND 3.0, Copyright © Tanzil.net, [tanzil.net](https://tanzil.net)).
- **Bundled Arabic Typography:** Scheherazade New (Copyright © 1994–2025 SIL Global, [software.sil.org/scheherazade](https://software.sil.org/scheherazade/)) and Amiri Typeface (Copyright © 2010–2022 The Amiri Project Authors / Khaled Hosny, [amirifont.org](https://www.amirifont.org/)), both licensed under the SIL Open Font License, Version 1.1 ([scripts.sil.org/OFL](http://scripts.sil.org/OFL)).
- **Morphology & Grammar Corpus:** The Quranic Arabic Corpus v0.4 (Copyright © Kais Dukes, Language Research Group, University of Leeds, [corpus.quran.com](https://corpus.quran.com)), used with academic attribution under the GNU General Public License v3 (GPLv3).
- **Translations & Tafsir:** Saheeh International, Cheriyamundam Abdul Hameed & Kunhi Mohammed Parappoor, Amani Thafseer, Lalithasaram, Quran.com, AlQuran.cloud, QuranWBW.com, and classical/modern Tafsir collections (Ibn Kathir, Al-Jalalayn, Al-Sa'di, Al-Tabari, Al-Qurtubi, Maariful Quran, and spa5k/tafsir_api contributors).
- **Open-Source Software Libraries:** Built using AndroidX, Jetpack Compose, Room, Dagger Hilt, Kotlin Coroutines, Gson, Retrofit & OkHttp (Copyright © Square, Inc.), and MPAndroidChart (Copyright © Philipp Jahoda), licensed under the Apache License, Version 2.0 ([apache.org/licenses/LICENSE-2.0](https://www.apache.org/licenses/LICENSE-2.0)).

---

## 10. Security

I value your trust in using this application and use industry-standard HTTPS/TLS encryption in transit, AES-256-GCM asset protection, and Android application sandboxing to protect your data. However, please remember that no method of transmission over the internet or method of electronic storage is 100% secure and reliable, and absolute security cannot be guaranteed.

---

## 11. Children's Privacy

This Service is a general-audience Islamic educational application and does not knowingly collect personally identifiable information from children under 13 years of age (or the applicable age of digital consent in your jurisdiction). Because no user accounts or personal profiles are collected, children can use the app's Quran reading and memorization features safely offline.

---

## 12. Changes to This Privacy Policy

I may update this Privacy Policy from time to time. You are advised to review this page periodically for any changes. We will notify users of any changes by posting the new Privacy Policy on this page and updating the "Effective Date" at the top. Changes are effective immediately after they are posted on this page.

---

## 13. Contact Us

If you have any questions, data privacy inquiries, or suggestions regarding this Privacy Policy, please contact me:

- **Developer:** Salmanul Khairy
- **Application:** Al Quran: Hifz, Audio, Tafsir (`com.salmanul.alquran`)
- **Community & Support Channel:** [https://t.me/Tijaniconnect](https://t.me/Tijaniconnect)
- **GitHub Issues:** [Open an issue](../../issues)
