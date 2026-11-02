# Privacy Policy for Level Meter

**Last Updated:** November 2, 2026  
**Effective Date:** November 2, 2026  
**Application Name:** Level Meter (Bubble Level & Angle Meter)  
**Package Name:** `com.dimension.levelmeter`  
**Developer / Publisher:** Dimension  
**Contact Email:** [darkdotdarkline@gmail.com](mailto:darkdotdarkline@gmail.com)  

---

## 1. Introduction

Welcome to **Level Meter** ("we", "our", or "us"). We are committed to protecting your privacy and ensuring you have a safe and transparent experience while using our application.

This Privacy Policy explains how our Android mobile application ("Level Meter", "App") handles information, the nature of device permissions utilized, the role of third-party advertising partners, and how you can contact us regarding your privacy rights.

By installing and using **Level Meter**, you agree to the collection and use of information in accordance with this policy.

---

## 2. Information We Do NOT Collect (Zero Personal Data Policy)

Level Meter is designed as a standalone digital tool. We believe in data minimization and user privacy:

- **No Personal Identifiable Information (PII):** We do not collect, store, sell, or rent your personal information such as your full name, email address, home address, phone number, financial details, contact list, or biometric identifiers.
- **No User Account / Registration:** You do not need to register an account or log in to use Level Meter.
- **No Access to Media or Sensitive Files:** The app does not access your photos, media gallery, camera, microphone, or storage files.
- **No Precise GPS Location:** We do not request or access GPS location data.

---

## 3. Information Processed by the Application

### A. Device Hardware Sensors (Orientation, Accelerometer, Gravity, Gyroscope)
- **What is accessed:** The App accesses your device's built-in motion and position hardware sensors (`TYPE_ROTATION_VECTOR`, `TYPE_GRAVITY`, `TYPE_ACCELEROMETER`, and `TYPE_GYROSCOPE`).
- **Purpose:** These sensors are used solely in real-time to compute physical surface angles, tilt, pitch, roll, and level alignment across Bullseye, Tubular (vial), and Clinometer measurement modes.
- **Data Retention & Transmission:** All sensor calculations occur entirely in volatile memory (RAM) on your physical device. Sensor measurements are **never transmitted** over the internet, never saved to remote servers, and never shared with third parties.

### B. Local Preferences & Calibration Data
- **What is saved locally:** The app saves user-configured calibration offsets (e.g. setting custom zero angles), sound feedback preferences, and unit selection (degrees, pitch, percent).
- **Storage:** Stored locally on your device using Android `SharedPreferences`. This information never leaves your device and is automatically removed if you clear app data or uninstall the application.

### C. Fleet Health & Remote Configuration
- **What is processed:** To ensure app stability, deliver mandatory security updates, verify maintenance status, and configure non-intrusive remote feature flags, the app may connect to our cloud configuration service (Supabase REST API).
- **Data processed:** Anonymized technical device properties (device model, manufacturer, Android OS version, app version code, and a randomly generated installation UUID or non-personal device ID).
- **Purpose:** Strictly limited to diagnosing fleet compatibility, preventing app crashes, and informing users when a critical update is required. This data is not linked to any personal identity.

---

## 4. Third-Party Services and Advertising

To provide Level Meter as a free application, we display advertisements provided by third-party ad networks.

### Google AdMob
We integrate the **Google Mobile Ads SDK (Google AdMob)**. Google AdMob may collect and process certain device information to display relevant advertisements (banner ads, app open ads, or interstitial ads) and prevent fraudulent clicks.

- **Data collected by Google AdMob:**
  - Google Advertising ID (GAID / AAID)
  - IP address (used to infer general non-precise city/country-level region)
  - Diagnostic, crash logs, and ad interaction events (impressions, clicks)
  - Device information (screen size, operating system version, carrier)
- **Google's Privacy Policy:**  
  You can review how Google handles data in advertising by visiting:  
  [https://policies.google.com/privacy](https://policies.google.com/privacy)  
  [https://policies.google.com/technologies/partner-sites](https://policies.google.com/technologies/partner-sites)
- **Opting Out of Personalized Advertising:**  
  You can opt out of interest-based ads or reset your advertising identifier directly from your Android device settings:
  1. Open your device **Settings**.
  2. Navigate to **Google** > **Ads** (or **Privacy** > **Ads**).
  3. Select **"Reset advertising ID"** or **"Delete advertising ID"**.

### Supabase (Backend Cloud Infrastructure)
We use Supabase for hosting anonymous remote configuration parameters (such as minimum supported version and maintenance flags). Supabase operates under industry-standard security and compliance standards.  
Review Supabase’s Privacy Policy: [https://supabase.com/privacy](https://supabase.com/privacy).

---

## 5. Android Permissions Used

Level Meter only requests minimal permissions strictly necessary for its functionality:

| Permission | Technical Name | Purpose |
| :--- | :--- | :--- |
| **Vibration** | `android.permission.VIBRATE` | Used solely to deliver tactile haptic vibration pulses when a measured surface reaches a perfect 0.0° level. Can be toggled on/off in the app settings. |
| **Internet Access** | `android.permission.INTERNET` | Required by Google AdMob to fetch ad banners and by our remote configuration manager to check for critical app updates. |
| **Network State** | `android.permission.ACCESS_NETWORK_STATE` | Allows the app to verify whether an active network connection exists before attempting network calls, conserving battery and data. |

We do not request runtime permissions for camera, microphone, contacts, location, or external storage.

---

## 6. Children's Privacy (COPPA & GDPR-K Compliance)

Our application is not targeted towards children under the age of 13 (or under 16 for individuals residing in the European Economic Area / UK).

We do not knowingly collect or solicit personal information from children. If you are a parent or guardian and believe that your child has provided personal information to us, please contact us immediately at [darkdotdarkline@gmail.com](mailto:darkdotdarkline@gmail.com). We will promptly take steps to delete any such data.

---

## 7. Your Privacy Rights (GDPR & CCPA/CPRA)

Depending on your jurisdiction (such as the European Economic Area, United Kingdom, or State of California), you have certain statutory privacy rights:

- **Right to Know / Access:** You have the right to know what personal data is collected and processed. (As stated, we collect no personal data).
- **Right to Deletion:** Because we do not store personal profiles or user account records on our servers, there is no personal user profile to delete. Any local application data can be cleared instantly by clearing app cache/storage or uninstalling the app.
- **Do Not Sell or Share My Personal Information:** We do not sell, rent, or trade your personal information.
- **Right to Non-Discrimination:** You will not receive discriminatory treatment from us for exercising any of your privacy rights.

---

## 8. Security of Your Data

The security of your information is paramount to us. All network communication between the App and third-party APIs (Google AdMob, Supabase) is conducted using secure, encrypted Transport Layer Security (HTTPS / TLS). However, no method of transmission over the internet or electronic storage is 100% secure, and we strive to use commercially acceptable means to protect any transmitted diagnostic data.

---

## 9. Changes and Updates to this Privacy Policy

We may update this Privacy Policy periodically to reflect changes in our operational practices, app features, or legal requirements. When changes are made:

- The updated policy will be posted on this page with a revised **"Last Updated"** date.
- We encourage you to review this policy periodically for any updates.
- Continued use of the App after modifications constitutes acceptance of the revised policy.

---

## 10. Contact Us

If you have any questions, concerns, feedback, or requests regarding this Privacy Policy or our data practices, please reach out to us at:

- **Contact Email:** [darkdotdarkline@gmail.com](mailto:darkdotdarkline@gmail.com)
- **Developer Name:** Dimension
- **Application:** Level Meter (`com.dimension.levelmeter`)

---
*This Privacy Policy is effective as of November 2, 2026.*
