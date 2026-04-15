# Privacy Policy for Gita AI

**Effective date:** April 15, 2026
**Last updated:** April 15, 2026
**Publisher:** Innovisora (innovisora.com)
**Contact:** atharva@innovisora.com

Gita AI ("the app", "we", "us") is a Bhagavad Gītā study companion published by Innovisora. It that offers AI-guided verse explanations, chapter browsing, bookmarks, and a daily verse widget. This policy explains what information the app collects, how it is used, and the rights you have over your data.

We designed Gita AI to collect as little as possible. Most of your data lives on your own device. Only a few specific features require sending data to external services, and each is explained below.

---

## 1. Information We Collect

### 1.1 Account information (only if you sign in)

If you choose to sign in with Google, we receive your **name, email address, and profile photo URL** from Google's authentication service. You can also use the app as a guest, in which case no account information is collected.

Your account information is used solely to identify you across devices so your subscription status and bookmarks can be restored when you sign back in. We do not sell, share, or use this information for advertising.

### 1.2 Chat messages

When you ask a question in the in-app chat, your message is sent to **Google's Gemini API** so the AI can generate a response. The conversation history is stored **only on your device** in a local database (Room/SQLite). We do not keep a copy on our servers.

You can delete your entire chat history at any time from **Settings → Clear chat history**.

### 1.3 Subscription data

If you purchase the Premium subscription, the payment is processed by **Google Play Billing** (or Razorpay in earlier builds). We receive a transaction identifier and subscription expiry date, which are stored in Firebase Firestore associated with your signed-in account so the subscription follows you across devices.

We never see or store your card number, UPI ID, or any other payment credentials. Those are handled entirely by the payment provider.

### 1.4 Advertising identifiers

If you are on the free tier, the app shows banner and interstitial ads served by **Google AdMob**. AdMob uses your device's advertising ID to serve relevant ads and measure ad performance. You can reset or opt out of personalized ads at any time from your Android **Settings → Google → Ads**.

Premium subscribers do not see ads, and their advertising ID is not used by the app.

### 1.5 Diagnostic data

The app does not include crash reporting or analytics SDKs beyond what Google Play itself collects from all apps. We do not run Firebase Analytics, Crashlytics, or any custom telemetry.

---

## 2. How We Use Your Information

- **To provide AI chat responses** — your questions and recent conversation context are sent to Google Gemini.
- **To deliver your subscription** — Google Play Billing processes your purchase; Firebase stores your subscription state so it persists across devices.
- **To show ads (free tier only)** — Google AdMob uses your advertising ID to serve ads. You can opt out in Android settings.
- **To save your preferences and bookmarks** — stored locally on your device.

We do not:
- Sell your personal information to third parties.
- Profile you for marketing.
- Use chat content to train AI models (Google's Gemini API terms govern their retention; see their policy below).

---

## 3. Third-Party Services

The following services receive data from the app. Each has its own privacy policy:

| Service | Purpose | Data sent | Privacy Policy |
|---|---|---|---|
| Google Gemini API | Generate AI responses | Your chat message + recent history | https://policies.google.com/privacy |
| Google Firebase (Auth + Firestore) | Sign-in + subscription state | Email, name, photo URL, subscription dates | https://firebase.google.com/support/privacy |
| Google Play Billing | Process subscription | Play account + purchase token | https://policies.google.com/privacy |
| Google AdMob | Show ads (free tier only) | Advertising ID, device info | https://policies.google.com/privacy |
| Razorpay (earlier builds only) | Process subscription | Payment details | https://razorpay.com/privacy |

---

## 4. Data Retention

- **On your device:** chat history and bookmarks remain until you clear them or uninstall the app.
- **Firebase:** subscription records remain tied to your account until you delete the account. To delete, email us at atharva@innovisora.com and we will remove your Firestore record within 30 days.
- **Gemini API:** Google's retention policy applies. As of this writing, Google retains Gemini free-tier prompts for up to 55 days for abuse monitoring. See https://ai.google.dev/gemini-api/terms for the current terms.

---

## 5. Your Rights

You can:
- **Access your data** — view your bookmarks and chat history directly in the app.
- **Delete your data** — clear chat from Settings, delete individual bookmarks, or email us to delete your Firebase record.
- **Opt out of personalized ads** — Android Settings → Google → Ads → Reset advertising ID / Opt out.
- **Sign out** — removes your account reference from the device; data syncs back on next sign-in.
- **Uninstall the app** — removes all on-device data.

If you are in the EU, UK, or California, you have additional rights under GDPR or CCPA (right to access, rectify, erase, restrict, or port your data). Email atharva@innovisora.com to exercise these rights.

---

## 6. Children's Privacy

Gita AI is not directed at children under 13. We do not knowingly collect information from children under 13. If you believe a child has provided us information, email us and we will delete it.

---

## 7. Security

Data in transit is encrypted (HTTPS/TLS). On-device data is stored in Android's sandboxed app storage and inherits the device's at-rest encryption. We do not operate our own servers beyond Firebase, which is managed by Google and holds SOC 2 and ISO 27001 certifications.

No method of transmission or storage is 100% secure. We cannot guarantee absolute security but we follow standard industry practices.

---

## 8. Changes to This Policy

If we update this policy we will post the new version at the same URL and update the "Last updated" date. Material changes will be announced in-app.

---

## 9. Contact

Questions, requests, or concerns:

**Innovisora**
Website: https://innovisora.com
Email: atharva@innovisora.com

---

*Gita AI is an independent project and is not affiliated with any religious institution. The Bhagavad Gītā verse translations used in the app are from public-domain sources credited in the app's Settings screen.*
