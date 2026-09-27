# Privacy Policy for VoiceParty

**Last Updated: September 27, 2026**  
**Effective Date: September 27, 2026**  
**Google Play Console Compliance Version: 2.4.0**

Welcome to **VoiceParty** ("we," "our," "us"). We respect your privacy and are committed to protecting your personal data in full compliance with the **Google Play Developer Program Policies**, including the **Google Play User Data Policy** and **Account Deletion Policy**.

This Privacy Policy applies to the VoiceParty Android application, web applications, APIs, embedded webview games, and related services (collectively, the "**Services**").

Please read this Privacy Policy carefully. By downloading, installing, registering, or using VoiceParty, you consent to the collection, use, and disclosure practices described herein. If you do not agree with this policy, please do not use the application.

---

## Google Play Data Safety Disclosure Summary

To assist you and comply with **Google Play Store Data Safety** requirements, below is a direct mapping of the data types collected by VoiceParty and how they are handled:

| Data Category | Data Type | Collected? | Shared? | Purpose | Ephemeral / Stored |
| :--- | :--- | :---: | :---: | :--- | :--- |
| **Voice / Audio** | Live Voice & Mic | Yes | No | Live voice room broadcasting | **Ephemeral only** (Processed in RAM, **Never Recorded/Stored**) |
| **Personal Info** | Email, Name, Username, User ID, DOB, Gender | Yes | No | Account creation, authentication, profile management | Stored securely in database |
| **Messages** | Room chat, Whispers (DMs), Announcements | Yes | No | Communication, social interaction, room history | Stored securely in database |
| **Photos & Media** | Avatars, Room Wallpapers, Moment posts | Optional | No | User profile customization & social sharing | Stored securely in Supabase Storage |
| **Financial Info** | Virtual Coin History, Gift Ledgers, VIP status | Yes | No | In-app virtual economy & reward tracking | Stored securely (**Payments handled by Google Play**) |
| **Device & IDs** | Android ID, UUID, Push Tokens, IP address | Yes | No | App functionality, security, fraud prevention | Stored securely in database |
| **App Performance** | Crash logs, latency, performance metrics | Yes | No | System stability & bug fixing | Stored securely |

- **Encryption in Transit**: All data transmitted between the app and our servers is encrypted using **HTTPS, TLS 1.3, Secure WebSockets (WSS), and WebRTC (DTLS-SRTP)**.
- **Account Deletion**: Users can request complete account and data deletion both **in-app** and **via web/email** without re-installing the app.

---

## Table of Contents
1. [Information We Collect](#1-information-we-collect)
2. [Google Play Permissions Requested](#2-google-play-permissions-requested)
3. [Real-Time Audio & Microphone Privacy (Google Play Audio Policy Compliance)](#3-real-time-audio--microphone-privacy-google-play-audio-policy-compliance)
4. [How We Use Your Information](#4-how-we-use-your-information)
5. [In-App Virtual Currency & Interactive Mini-Games](#5-in-app-virtual-currency--interactive-mini-games)
6. [Data Sharing & Disclosure](#6-data-sharing--disclosure)
7. [Third-Party SDKs & Service Providers](#7-third-party-sdks--service-providers)
8. [Data Security & Encryption Practices](#8-data-security--encryption-practices)
9. [Google Play Account & Data Deletion Policy](#9-google-play-account--data-deletion-policy)
10. [Children's Privacy (Age Limit 13+ / 18+)](#10-childrens-privacy-age-limit-13--18)
11. [Your Privacy Rights (GDPR / CCPA / Global)](#11-your-privacy-rights-gdpr--ccpa--global)
12. [Changes to This Privacy Policy](#12-changes-to-this-privacy-policy)
13. [Contact Information & Support](#13-contact-information--support)

---

## 1. Information We Collect

We collect information required to deliver, secure, and personalize the VoiceParty experience.

### A. Personal & Account Information
- **Account Credentials**: When signing up via **Email One-Time Password (OTP)** or **Google Sign-In**, we collect your email address, display name, username, gender, date of birth / age verification, and profile avatar.
- **Profile & Social Connections**: Biography, Couple Partner (CP) intimacy status, Sibling connections (Brother/Sister), Family clan memberships, badges, avatar frames, and follower/following lists.
- **User-Generated Content**: Messages sent in public voice rooms, direct messages (whispers/DMs), room titles, custom wallpapers, room announcements, and community moments/posts.

### B. Virtual Currency & Financial Data
- **Virtual Coins & Gifting**: History of virtual coin purchases, wallet ledgers, gift sending/receiving records, VIP subscriptions, and agency/reseller transfers.
- **Google Play Billing**: **We do not collect or store credit card, debit card, or banking details.** All monetary transactions are processed securely through **Google Play Billing**.

### C. Automatically Collected Technical Data
- Device model, operating system version, unique device identifier (Android ID / UUID), IP address, network connection state, push notification token, app version, crash logs, and latency metrics.

---

## 2. Google Play Permissions Requested

To deliver live voice streaming and social features, the VoiceParty Android app requests the following runtime system permissions:

| Permission Name | System Identifier | Purpose & Usage Scope |
| :--- | :--- | :--- |
| **Microphone** | `RECORD_AUDIO`, `MODIFY_AUDIO_SETTINGS` | Required to stream your voice in real time when you take an active mic seat in a voice room. **Audio is streamed live and is not saved or recorded.** |
| **Photos & Media** | `READ_MEDIA_IMAGES` / Storage | Used only when you choose to upload a custom avatar, room wallpaper background, or photo attached to community moments. |
| **Notifications** | `POST_NOTIFICATIONS` | Used to send push alerts for room invites, direct messages, CP relationship requests, and system updates. Can be toggled in app settings. |
| **Network & Internet** | `INTERNET`, `ACCESS_NETWORK_STATE` | Required to maintain WebSockets, WebRTC live audio feeds, API sync, and real-time database state (CDC mapping). |

---

## 3. Real-Time Audio & Microphone Privacy (Google Play Audio Policy Compliance)

VoiceParty provides high-fidelity, low-latency live audio rooms powered by secure WebRTC technology (LiveKit infrastructure).

> **STRICT GOOGLE PLAY AUDIO DISCLOSURE:**  
> - VoiceParty uses microphone permissions (`RECORD_AUDIO`) **exclusively for real-time live voice communication** between room participants.
> - We **DO NOT record, store, save, archive, or analyze live voice conversations** during standard room operations.
> - Live voice packets pass ephemerally through volatile memory (RAM) solely for real-time routing and are immediately discarded upon transmission.
> - Audio data is **NEVER** used for advertising, profiling, marketing, or sold to third parties.

---

## 4. How We Use Your Information

We process your data strictly for legitimate operational, security, and legal purposes:
1. **Core Service Operations**: Establishing live voice connections, managing room mic seats, synchronizing room wallpapers, and updating real-time participant lists.
2. **Social & Intimacy Features**: Rendering CP partner intimacy meters, Family rosters, VIP status frames, and gifting leaderboards.
3. **Virtual Economy Management**: Processing atomic coin debits/credits, executing gift animations, and updating wallet ledgers.
4. **Interactive Mini-Games**: Powering embedded webview games (*Greedy Animal Wheel, Lucky 77, Food Wheel Party*), processing bet placements, and broadcasting celebratory winning banners ("pattis").
5. **Platform Safety & Anti-Fraud**: Moderating abusive content, preventing unauthorized account takeovers, enforcing bans, and preventing financial fraud.

---

## 5. In-App Virtual Currency & Interactive Mini-Games

VoiceParty includes interactive mini-games and a virtual gifting economy:
- **Public Gameplay Announcements**: When you place bets, win multi-tier rewards, or send high-value virtual gifts, your public username, avatar, and winning tier may appear in live in-room feeds or floating platform-wide announcement banners ("pattis") as part of the social experience.
- **Fair Play & Audit Logs**: Game transactions and coin transfers are logged in server-side audit trails to ensure balance integrity, prevent exploit abuse, and resolve billing disputes.

---

## 6. Data Sharing & Disclosure

**We DO NOT sell, rent, or trade your personal data to third parties for advertising or marketing purposes.**

Your information is only shared under these limited conditions:
- **Public Profile Visibility**: Your display name, username, avatar, user ID, VIP level, received gift showcase, CP partner status, and public room activity are visible to other VoiceParty users.
- **Infrastructure Service Providers**: We share data with trusted infrastructure providers (cloud hosting, WebRTC routing, database management) who operate under strict confidentiality and data protection contracts.
- **Legal Compliance & Safety**: We may disclose information if required by law, subpoena, court order, or governmental authority, or to protect the safety, rights, or property of our users, the public, or VoiceParty.

---

## 7. Third-Party SDKs & Service Providers

VoiceParty integrates with industry-standard third-party providers to deliver app functionality:

- **LiveKit**: WebRTC real-time voice streaming infrastructure. [(LiveKit Privacy Policy)](https://livekit.io/privacy)
- **Supabase & PostgreSQL**: User authentication, database management, and GraphQL API endpoints. [(Supabase Privacy Policy)](https://supabase.com/privacy)
- **Google Sign-In**: OAuth 2.0 user authentication. [(Google Privacy Policy)](https://policies.google.com/privacy)
- **Expo & React Native**: Mobile app runtime environment and push notification gateway. [(Expo Privacy Policy)](https://expo.dev/privacy)
- **Railway**: Cloud server hosting infrastructure. [(Railway Privacy Policy)](https://railway.app/legal/privacy)

---

## 8. Data Security & Encryption Practices

We apply robust, industry-standard security measures to safeguard your personal data:
- **In-Transit Encryption**: All network traffic between our mobile app, web mini-games, and backend servers is encrypted using **HTTPS, TLS 1.3, and WSS (Secure WebSockets)**.
- **Audio Encryption**: WebRTC voice media streams are encrypted using **DTLS-SRTP** standards.
- **Access Control & Session Tokens**: Secure JSON Web Tokens (JWT) with automatic token rotation are used for user sessions. Passwords are never stored in plaintext.
- **Database Protections**: Production databases employ row-level security (RLS), atomic financial transaction locks, and strict role-based access control.

---

## 9. Google Play Account & Data Deletion Policy

In compliance with **Google Play’s Account Deletion Requirement**, VoiceParty provides users with clear paths to delete their account and associated personal data:

### A. In-App Deletion Path
1. Open the VoiceParty Mobile App.
2. Go to **Profile** &rarr; **Settings** &rarr; **Account & Security**.
3. Tap **Delete Account** and confirm your request.

### B. Web & Email Deletion Request (No App Re-installation Required)
If you cannot access the mobile application, you can submit an account deletion request online:
- **Web Deletion Request Form**: Send an email to `privacy@voiceparty.com` or `support@voiceparty.com` with the subject line *"Google Play Account Deletion Request"*.
- **Required Details**: Provide your registered email address and username.

### C. Data Retention & Purging Schedule
Upon confirmation of your deletion request:
- Profile details, social connections, photos, moments, and chat history will be **permanently deleted or anonymized within 30 days**.
- Financial transaction records (such as Google Play purchase ledgers) will be retained solely as required by tax, legal, and anti-fraud reporting laws.

---

## 10. Children's Privacy (Age Limit 13+ / 18+)

VoiceParty is designed for general social audiences and is **strictly intended for individuals who are at least 13 years of age** (or 18 years of age in jurisdictions where required for live voice streaming and virtual gifting applications).

We do not knowingly collect or solicit personal information from children under 13 years of age. If we discover that a child under 13 has provided us with personal data without verified parental consent, we will immediately delete such data and terminate the account. If you believe a child under 13 is using our platform, please contact us at `safety@voiceparty.com`.

---

## 11. Your Privacy Rights (GDPR / CCPA / Global)

Depending on your geographic location, you hold rights under regulations such as GDPR (EU/UK) and CCPA/CPRA (California):
- **Access & Export**: Request a copy of your personal data.
- **Correction**: Update inaccurate profile details directly in the app.
- **Erasure**: Request permanent account deletion.
- **Privacy Controls**: Manage DM permissions, block harassing users, disable room invitations, and toggle push notifications in app settings.

---

## 12. Changes to This Privacy Policy

We may update this Privacy Policy periodically to reflect new app features, technological advancements, or Google Play policy updates. When changes are made, we will update the **"Last Updated"** date at the top of this document and notify users via in-app notifications or email for material updates.

---

## 13. Contact Information & Support

If you have questions, concerns, or privacy requests regarding this Privacy Policy or our data practices, please reach out to us:

- **Privacy & Data Protection Email**: `privacy@voiceparty.com`
- **Customer Support Email**: `support@voiceparty.com`
- **Community Safety Email**: `safety@voiceparty.com`
- **Official Web Server**: [https://voiceparty-production-7818.up.railway.app](https://voiceparty-production-7818.up.railway.app)
- **Application**: VoiceParty Mobile App (Settings &rarr; Help & Support)

---
*© 2026 VoiceParty. All rights reserved. Google Play is a trademark of Google LLC.*
