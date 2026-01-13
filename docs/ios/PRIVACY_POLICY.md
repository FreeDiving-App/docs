# Privacy Policy

**Last Updated:** January 13, 2026

---

## 1. Introduction

This Privacy Policy describes how the **Freedive App** application ("app", "we", "us") collects, uses, and protects your personal information.

By using the app, you agree to the collection and use of information in accordance with this policy.

**Developer:** Yurii Besedin (individual developer)
**Contact:** uabeseda@gmail.com

---

## 2. Information We Collect

### 2.1. Account Data (Optional)

Signing in is **OPTIONAL**. The app is fully functional without authentication. If you choose to sign in using Google Sign-In or Apple Sign-In:

- **Email address** - to identify your account
- **User name** - to personalize the interface
- **Profile photo** (Google Sign-In only) - to display in the app
- **Unique user ID** - for data synchronization with cloud storage

**Important:** You can use the app without signing in. All training features work offline without an account.

### 2.2. Workout Data (Hybrid Storage)

The app uses a **hybrid storage model** for your workout data:

**Local Storage (Hive database on your device):**
- Training history (dates, duration, exercise types)
- Timer settings (O2/CO2 tables, breathing exercises)
- Personal records and statistics
- User preferences and settings

**Cloud Storage (Supabase - when signed in):**
- All workout data is synced to Supabase cloud database
- Data location: **European Union (Stockholm, Sweden)** - AWS infrastructure
- Automatic bidirectional sync when online
- Enables access to your data across multiple devices

**How it works:**
1. Data is stored locally first (works offline)
2. When you sign in and have internet, data syncs to Supabase cloud
3. Data is merged between local and cloud storage
4. You can access your workouts on any device when signed in

**Data stored in Supabase cloud:**
- User profile (email, name, authentication metadata)
- Saved workout templates
- Workout history
- Personal bests
- User settings

### 2.3. Advertising Data (Google AdMob)

The app uses Google AdMob to display ads. AdMob may collect:

- Advertising Identifier (IDFA on iOS)
- IP address
- Device information (model, operating system, screen size)
- Ad interaction data (views, clicks)
- Location data (coarse location for ad targeting, if permitted)

Learn more: [Google AdMob Privacy Policy](https://support.google.com/admob/answer/6128543)

### 2.4. Analytics Data

We may collect anonymous information about app usage:

- App launch frequency
- Usage of different timer types (O2, CO2, breathing exercises, STA)
- Session duration
- Technical crash reports (for bug fixes)
- Feature usage statistics

This data is anonymized and cannot be used to identify you personally.

---

## 3. How We Use Data

- **Provide app functionality** - save workouts, settings, enable timers
- **Cloud synchronization** - sync your data across devices (when signed in)
- **Personalization** - display your name and profile photo (if signed in)
- **App improvement** - analyze usage to add new features and fix bugs
- **Monetization** - display ads through Google AdMob
- **Technical support** - diagnose and fix crashes and errors

---

## 4. Data Sharing with Third Parties

We do **NOT** sell or share your personal data with third parties for marketing purposes.

We share data with the following service providers:

### 4.1. Supabase (Cloud Database & Authentication)
- **Purpose:** Cloud storage, authentication, data synchronization
- **Data shared:** Email, name, profile photo, workout data (when signed in)
- **Data location:** European Union (Stockholm, Sweden) - GDPR compliant
- **Privacy Policy:** [https://supabase.com/privacy](https://supabase.com/privacy)

### 4.2. Google LLC (Sign-In & Advertising)
- **Google Sign-In:** Email, name, profile photo for authentication
- **Google AdMob:** Advertising identifier, device info, ad interactions
- **Privacy Policy:** [https://policies.google.com/privacy](https://policies.google.com/privacy)

### 4.3. Apple Inc. (Sign-In)
- **Purpose:** Authentication via Apple ID
- **Data shared:** Email (optional), name, user identifier
- **Privacy Policy:** [https://www.apple.com/legal/privacy/](https://www.apple.com/legal/privacy/)

---

## 5. Data Security

We take reasonable measures to protect your data:

- **Local encryption:** Workout data stored securely on your device (Hive database)
- **Cloud encryption:** All data transmitted to Supabase uses HTTPS/TLS encryption
- **EU data residency:** Cloud data stored in European Union (Stockholm, Sweden)
- **No password storage:** Authentication handled by Google/Apple (OAuth 2.0)
- **Access controls:** Only you can access your cloud data when authenticated

**However:** No system is 100% secure. You are responsible for the security of your device and account.

---

## 6. Your Rights

You have the right to:

### 6.1. Access Your Data
- View all data we store about you
- Request a copy of your data (data export)
- Contact us at uabeseda@gmail.com for data access requests

### 6.2. Delete Your Data
- **Delete local data:** Uninstall the app or clear app data in iOS Settings
- **Delete cloud data:** Sign in to the app and delete your account, or contact us at uabeseda@gmail.com
- **Delete authentication:** Revoke access in your Google/Apple account settings

### 6.3. Control Advertising
- **Disable personalized ads:** iOS Settings → Privacy & Security → Tracking → Disable for Freedive App
- **Limit Ad Tracking:** iOS Settings → Privacy & Security → Apple Advertising → Disable Personalized Ads

### 6.4. Withdraw Consent
- You can delete the app at any time
- Uninstalling the app removes all local data
- Contact us to delete cloud data: uabeseda@gmail.com

---

## 7. Data Retention

- **Local workout data:** Stored until you delete the app or clear app data
- **Cloud workout data:** Stored until you delete your account
- **Authentication data:** Managed by Google/Apple, deleted when you revoke app access
- **Analytics data:** Stored up to 26 months (per Google Analytics policy)
- **Deleted data:** Permanently removed from Supabase within 30 days

---

## 8. Children's Privacy

The app is **NOT** intended for children under 13. We do NOT knowingly collect data from children under 13.

**Important warning:** Breath-hold training can be dangerous. Children should use the app only under adult supervision. Consult a medical professional before starting any breath-hold training, especially for children.

If we discover that a child under 13 has provided us with personal information, we will delete it immediately. If you believe a child has provided us with information, contact us at uabeseda@gmail.com.

---

## 9. International Data Transfers

**If you are located outside the European Union:**

Your data may be transferred to and stored in the European Union (Stockholm, Sweden) where Supabase servers are located. By using the app and signing in, you consent to this transfer.

The EU provides adequate data protection under GDPR. Your data is protected by:
- GDPR compliance (EU regulation)
- HTTPS/TLS encryption in transit
- Secure cloud infrastructure (AWS EU region)
- Access controls and authentication

---

## 10. Changes to This Privacy Policy

We may update this policy from time to time. We will notify you of significant changes via:

- In-app notifications
- Email notifications (if you provided email and signed in)
- App Store update notes

The "Last Updated" date at the top of this document indicates when changes were made.

**Continued use of the app after changes constitutes acceptance of the updated policy.**

---

## 11. Legal Compliance

This Privacy Policy complies with:

- **GDPR** (General Data Protection Regulation, European Union)
- **CCPA** (California Consumer Privacy Act, United States)
- **Apple App Store Guidelines** (Privacy requirements)
- **Google Play Store Policies** (Data disclosure requirements)

---

## 12. Contact Information

If you have questions about this Privacy Policy or want to exercise your data rights:

**Email:** uabeseda@gmail.com
**Developer:** Yurii Besedin

**Data Protection Requests:**
- Data access requests: uabeseda@gmail.com
- Data deletion requests: uabeseda@gmail.com
- Privacy concerns: uabeseda@gmail.com

We will respond to your request within 30 days.

---

## 13. California Privacy Rights (CCPA)

If you are a California resident, you have additional rights under CCPA:

- **Right to Know:** What personal information we collect, use, and share
- **Right to Delete:** Request deletion of your personal information
- **Right to Opt-Out:** Opt out of sale of personal information (we do NOT sell your data)
- **Non-Discrimination:** We will not discriminate against you for exercising your rights

To exercise these rights, contact us at uabeseda@gmail.com.

---

## 14. European Privacy Rights (GDPR)

If you are in the European Union, you have rights under GDPR:

- **Right of Access:** Access your personal data
- **Right to Rectification:** Correct inaccurate data
- **Right to Erasure:** Request deletion of your data ("right to be forgotten")
- **Right to Restriction:** Restrict processing of your data
- **Right to Data Portability:** Receive your data in a portable format
- **Right to Object:** Object to processing of your data
- **Right to Withdraw Consent:** Withdraw consent at any time

To exercise these rights, contact us at uabeseda@gmail.com.

**Data Controller:** Yurii Besedin
**Legal Basis for Processing:** Consent (you agreed to this policy when using the app)

---

## Summary

**What we collect:**
- Email, name, profile photo (optional, only if you sign in)
- Workout data (timers, history, personal bests)
- Advertising data (AdMob identifiers)
- Anonymous usage analytics

**Where we store it:**
- Locally on your device (Hive database - always)
- Cloud storage in EU Stockholm (Supabase - when signed in)

**Who we share with:**
- Supabase (cloud storage, EU region)
- Google (authentication, advertising)
- Apple (authentication)

**Your rights:**
- Access, delete, or export your data anytime
- Opt out of personalized ads
- Delete your account

**Questions?** Email us at uabeseda@gmail.com

---

**This Privacy Policy is effective as of January 13, 2026.**
