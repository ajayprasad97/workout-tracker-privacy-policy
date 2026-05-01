# Privacy Policy — Workout Tracker

**Effective Date:** April 19, 2026
**Last Updated:** April 19, 2026

---

## Overview

Workout Tracker ("we", "us", or "our") is a fitness tracking application available on iOS and Android. This Privacy Policy explains what information we collect, how we use it, where it is stored, and the choices you have regarding your data.

We built this app to help you track your fitness progress — not to monetise your data. We do not sell your personal information, and we do not show advertisements.

Please read this policy carefully. By creating an account and using Workout Tracker, you agree to the practices described below.

---

## 1. Information We Collect

### 1.1 Account Information

When you create an account, we collect:

- **Email address** — used to authenticate your account via Firebase Authentication.
- **Display name** — the name shown on your profile and in the social feed.

We do not collect your full legal name, phone number, or payment information.

### 1.2 Workout Data

When you log workouts, we collect:

- Exercise names, sets, repetitions, and weights.
- Workout dates and session duration.
- Training notes such as rate of perceived exertion (RPE) and warmup flags.
- Your training goal (strength, hypertrophy, or endurance), training experience level (beginner, intermediate, advanced), available equipment, preferred session length, and days per week.
- Any problem areas or injuries you report during onboarding, so the app can filter exercises appropriately.

### 1.3 Body Statistics (Optional)

You may optionally enter:

- **Body weight** (in lbs)
- **Height** (in inches)

These fields are entirely optional. If you do not provide them, no body-stat data is collected. This data is stored locally on your device and, if you are signed in, synced to the cloud (see Section 3).

### 1.4 Social Interactions

If you use the social feed features, we collect:

- Workout posts you choose to share publicly.
- Likes and comments you make on other users' posts.
- Users you choose to follow and users who follow you.
- Trainer–athlete relationships (if you use the trainer role).

### 1.5 Technical and Usage Data

We do not operate third-party analytics pipelines. Firebase (our infrastructure provider) may collect limited technical information as described in their own privacy policy (see Section 3.2). This can include device type, operating system version, and crash reports.

We also collect anonymised, aggregated workout activity data (exercise names, muscle groups, sets, and repetitions) to improve workout recommendations. This analysis is performed on data that has been stripped of all identifying information — it cannot be traced back to you individually. You can opt out of this at any time from the app's Settings screen.

### 1.6 Location Data

**We do not collect location data.** A location-tracking feature has been considered for a future release but has not launched. If this changes, this policy will be updated and you will be asked for explicit permission before any location data is ever collected.

---

## 2. How We Use Your Information

We use the information we collect solely to provide and improve the Workout Tracker app:

| Purpose | Data Used |
|---|---|
| Authenticating your account | Email address |
| Displaying your profile | Display name, body stats (if provided) |
| Generating personalised workouts | Goal, equipment, training age, injuries, days per week |
| Logging and tracking your progress | Workout data (exercises, sets, reps, weights, dates) |
| Deload week detection and split cycling | Workout dates, cycle week counter |
| Showing your workout history | Workout data |
| Enabling the social feed | Posts, likes, comments, follow relationships |
| Product improvement and personalised recommendations | Anonymised, aggregated workout activity (exercise names, muscle groups, sets, reps — **no body stats, no personal identifiers**) |
| Trainer–athlete collaboration | Trainer role, client list, shared workout history |
| Syncing data across your devices | All data listed above |

**We do not:**
- Sell your personal information to any third party.
- Share your data with advertisers or advertising networks.
- Use your data to show you advertisements.
- Use your workout data to build profiles for third-party marketing.
- Use your body statistics (height, weight) in any aggregate or analytics pipeline.

---

## 3. Where Your Data Is Stored

### 3.1 On Your Device

Workout Tracker stores a local copy of your data in an SQLite database on your device using `expo-sqlite`. This allows the app to function fully offline. The local database is protected by your device's operating system-level security (iOS Keychain policies / Android sandboxing).

### 3.2 Firebase Cloud (Google)

When you are signed in, your data is also synced to **Google Firebase** (Firestore and Firebase Authentication). Firebase is operated by Google LLC and is subject to Google's own privacy policy:

- Firebase Privacy Policy: https://firebase.google.com/support/privacy
- Google Privacy Policy: https://policies.google.com/privacy

Firebase servers are located primarily in the United States. If you are located outside the United States, your data will be transferred to and processed in the United States (or other countries where Google operates infrastructure) in accordance with Google's data transfer safeguards (including Standard Contractual Clauses where applicable).

We have configured Firebase with reasonable security rules so that each user can only read and write their own workout data. Social data (likes, comments, shared posts) is accessible to other signed-in users within the app, consistent with the social features you use.

### 3.3 No Other Third-Party Services

Workout Tracker does not use any third-party analytics SDKs, advertising SDKs, or crash-reporting services beyond what is included in Firebase. Exercise data is sourced from the open-source **free-exercise-db** project (https://github.com/yuhonas/free-exercise-db) — no personal data is sent to this service.

---

## 4. Data Sharing

We do not sell, rent, or share your personal data with third parties, except in the following limited circumstances:

- **With Firebase/Google** — as the infrastructure provider described in Section 3.2.
- **With other users you interact with** — your display name and any workout posts you explicitly share are visible to other Workout Tracker users in the social feed. Comments and likes are attributed to your display name.
- **Trainer–athlete relationships** — if you add a trainer (or are added as a client), that trainer can view your recent workout history within the app. You can remove a trainer at any time from your profile settings.
- **Legal requirements** — we may disclose information if required to do so by law, court order, or in good faith belief that such disclosure is necessary to protect the rights, property, or safety of Workout Tracker, its users, or the public.

---

## 5. Your Rights and Choices

### 5.1 Access and Correction

You can view and edit your account information (display name, body stats, training goal, equipment, injuries, and split preferences) directly within the app from the Profile and Settings screens.

### 5.2 Analytics Opt-Out

You can opt out of anonymised analytics at any time from the app's **Settings** screen under "Privacy". Opting out prevents your workout activity from being included in aggregate product improvement analysis. Your core workout tracking and social features are not affected by this choice.

### 5.3 Data Portability

Your workout history is accessible in full within the app's History screen. We plan to add a data export feature in a future release.

### 5.4 Account and Data Deletion

You can delete your account at any time from the app's Profile screen. When you delete your account:

- Your Firebase Authentication account is permanently deleted.
- All your Firestore data (workout posts, likes, comments, follow relationships, trainer connections) is permanently deleted.
- The local SQLite database on your device is cleared.

Deletion is permanent and cannot be undone. Residual data in Firebase backups may persist for up to 30 days before it is purged from backup systems.

If you are unable to delete your account through the app, you may contact us at **rep.app.dev@gmail.com** and we will complete the deletion within 30 days.

### 5.5 Withdrawing Consent

You may stop using the app and delete your account at any time. Uninstalling the app removes the local database from your device; your cloud data is removed when you delete your account as described above.

### 5.6 California Residents (CCPA)

California residents have additional rights under the California Consumer Privacy Act (CCPA), including the right to know what personal information is collected, the right to deletion, and the right to opt out of the sale of personal information. **We do not sell personal information.** To exercise your rights, contact us at **rep.app.dev@gmail.com**.

### 5.7 European Residents (GDPR)

If you are located in the European Economic Area (EEA), United Kingdom, or Switzerland, you have rights under the GDPR (or equivalent local law), including:

- **Right of access** — request a copy of the data we hold about you.
- **Right to rectification** — request correction of inaccurate data.
- **Right to erasure** — request deletion of your data (see Section 5.3).
- **Right to restriction** — request that we restrict processing of your data.
- **Right to object** — object to processing based on legitimate interests.
- **Right to data portability** — receive your data in a portable format.

Our lawful basis for processing your data is **contract performance** (providing the app service you signed up for) and **legitimate interests** (maintaining security and improving the service). To exercise your GDPR rights, contact us at **rep.app.dev@gmail.com**.

---

## 6. Data Retention

We retain your data for as long as your account is active. If you delete your account, all associated data is deleted as described in Section 5.3.

We do not retain workout data, social data, or account data after account deletion, except as may remain in Firebase's automated backups (cleared within 30 days) or as required by law.

---

## 7. Data Security

We take reasonable steps to protect your information:

- **Authentication** is handled by Firebase Authentication, which includes protections against credential stuffing and brute-force attacks.
- **Data in transit** is encrypted using HTTPS/TLS between the app and Firebase.
- **Data at rest** in Firestore is encrypted by Google (AES-256).
- **Local data** on your device is protected by your device's operating system sandboxing and, on iOS, the device encryption backed by the Secure Enclave.

No method of transmission over the internet or electronic storage is 100% secure. While we strive to use commercially acceptable means to protect your data, we cannot guarantee absolute security.

---

## 8. Children's Privacy

Workout Tracker is not directed to children under the age of 13. We do not knowingly collect personal information from children under 13. If you are a parent or guardian and you believe your child has provided us with personal information, please contact us immediately at **rep.app.dev@gmail.com** and we will take steps to delete that information.

If we learn that we have collected personal information from a child under 13 without verification of parental consent, we will delete that information promptly and in compliance with the Children's Online Privacy Protection Act (COPPA).

Users between the ages of 13 and 18 should review this policy with a parent or guardian before creating an account.

---

## 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. When we make material changes, we will:

- Update the "Last Updated" date at the top of this document.
- Display an in-app notice the next time you open the app, or notify you via the email address associated with your account.

Your continued use of Workout Tracker after a policy update constitutes your acceptance of the revised policy. If you disagree with any changes, you may delete your account (Section 5.3) before the changes take effect.

---

## 10. Contact Us

If you have questions, concerns, or requests relating to this Privacy Policy or your personal data, please contact us:

**Email:** rep.app.dev@gmail.com

We will respond to all legitimate inquiries within 30 days.

---

*Workout Tracker is an independent app. It is not affiliated with, endorsed by, or sponsored by any exercise equipment manufacturer, gym chain, or fitness brand.*
