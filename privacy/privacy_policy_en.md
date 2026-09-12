# Privacy Policy — BabyCare+

**Last updated:** 12 September 2026

This Privacy Policy describes how the **BabyCare+** application ("we", "the app") collects, uses, and protects user information. By installing and using the app, you agree to the practices described in this document.

---

## 1. Who we are

- **Data controller:** Murilo Chechá
- **Contact email:** muchecha@gmail.com
- **App:** BabyCare+
- **Platform:** Android (Google Play Store)

---

## 2. Minimum age

BabyCare+ is intended exclusively for **adults aged 18 or older** (parents, guardians, or caregivers). The app **is not intended for use by children**. We do not knowingly collect data from children under 18.

In particular, our Service does not address anyone under the age of 13, and we do not knowingly collect personally identifiable information from anyone under the age of 13. If we become aware that we have collected personal data from anyone under the age of 13 without verification of parental consent, we take steps to remove that information from our servers.

---

## 3. Data we collect

### 3.1 Data you provide directly
- **Account:** email, name, and profile photo obtained via Google Sign-In.
- **Baby data:** name, sex, date of birth, photo, family relationship (mother, father, nanny, etc.), frame colour.
- **Activity logs:** sleep, breastfeeding, bottle, solids, diaper, bath, crying, hospital, notes, diary photos, etc.
- **Measurements:** weight, height, head circumference, temperature.
- **Health:** vaccines administered, medications (pills) taken.
- **Family members:** invitations sent/accepted between caregivers who share care for the same baby.
- **Reminders:** schedules and custom messages for notifications configured by the user.

### 3.2 Data collected automatically
- **Advertising identifiers (Google Ad ID)** and IP address, collected by the Google Mobile Ads SDK to serve advertising.
- **Anonymised error logs**, to diagnose bugs.

### 3.3 Data we do **not** collect
- GPS location.
- Device contacts.
- Call or SMS history.
- Microphone.

---

## 4. How we store data

- **Backend:** data is stored in [Supabase](https://supabase.com), a PostgreSQL platform with encryption at rest (AES-256) and in transit (TLS 1.2+).
- **Server location:** EU/US (depending on the Supabase project region).
- **Access:** only the authenticated user and members they explicitly invited to the baby's "family" can access that baby's data. We apply Row Level Security (RLS) in Supabase to enforce this isolation.
- **Local cache:** some data is stored locally on the device via SharedPreferences and SQLite for offline functionality.

---

## 5. How we use the data

- Display the baby's activity timeline.
- Sync data across the same caregiver's devices and between invited caregivers.
- Send local notifications based on user-configured reminders (these notifications **do not** leave the device).
- Serve advertising (banner and interstitial) through Google AdMob — necessary to sustain the free version.

We do not sell, rent, or share your personal data with third parties for marketing purposes.

---

## 6. Sharing data with third parties

| Service | Purpose | Data shared |
|---|---|---|
| **Supabase** | Data storage | All account and baby data |
| **Google Sign-In** | Authentication | Email, name, profile photo |
| **Google AdMob** | Advertising | Ad ID, IP, technical device data |

Links to third-party privacy policies:
- Supabase: https://supabase.com/privacy
- Google: https://policies.google.com/privacy

---

## 7. Your rights (LGPD / GDPR)

You have the right to:
- **Access** the data we hold about you.
- **Correct** inaccurate data.
- **Delete** your account and all associated data.
- **Export** your data in a readable format.
- **Object** to processing, withdrawing your consent at any time.

To exercise any of these rights, send an email to **muchecha@gmail.com** with the phrase "LGPD/GDPR Request" in the subject and the account email. We respond within 30 days.

---

## 8. Account deletion

You can request deletion of your account:
1. By emailing **muchecha@gmail.com** with the subject "Delete account", including the account email.
2. We will confirm deletion within **15 business days**, removing all personal data and activities from the servers.

---

## 9. Cookies and similar technologies

The app uses local storage (SharedPreferences, SQLite) only for offline functionality and cache. We do not use third-party tracking cookies beyond what is required by the Google AdMob SDK.

---

## 10. Security

We adopt appropriate technical and organisational measures to protect personal data:
- Encrypted communication (HTTPS/TLS).
- OAuth2 authentication via Google.
- Row Level Security in Supabase to ensure isolation between users.
- Backend access restricted by API keys.

Despite these measures, no system is 100% secure. In the event of a security incident affecting your data, we will notify you within 72 hours as required by law.

---

## 11. Changes to this policy

We reserve the right to update this Policy. Significant changes will be notified via the app and/or email. Continued use of the app after an update constitutes acceptance of the new version.

---

## 12. Contact

For any questions about this Privacy Policy or the processing of your data:

**Email:** muchecha@gmail.com
