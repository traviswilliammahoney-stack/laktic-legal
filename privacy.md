# Laktic Privacy Policy

_Last updated: 2026-05-06_
_Effective date: 2026-05-06_

## Plain-language summary

Laktic collects the data you give us (your name, email, race times, current mileage, and race calendar) so we can build training plans tailored to you. We send your training context to Anthropic to generate plan content and coach responses, then store the results for you to read in the app. We do not sell your data. We do not share it with advertisers. We do not track you across other apps or websites.

If you delete your account, we delete your data.

This summary is intentional. The legal text below is what governs the relationship, but if anything reads inconsistently with this summary, please contact us — that's a bug we want to fix.

---

## 1. Who we are

This privacy policy describes how Laktic (the "Service," "we," "us," or "our") collects, uses, and protects your information.

Laktic is operated by:

- **Travis Mahoney** (sole proprietor)
- **Contact:** travis.william.mahoney@gmail.com

This policy applies to the Laktic mobile applications for iOS and Android, distributed through the Apple App Store and Google Play Store.

---

## 2. What we collect

We collect only the data needed to deliver the Service. There is no behavioral tracking, no cross-app tracking, and no advertising identifier collection.

### 2.1 Information you provide directly

When you create an account or use the app, you give us:

- **Account information:** email address (used as your login identifier), password (stored hashed by our authentication provider, never visible to us in plaintext)
- **Profile information:** full name, your event focus (e.g., 1500m/Mile), days per week available to train, preferred time of day, weekly mileage (current and goal), self-rated current fitness percentage, training age in years, track access availability, and any injury notes you choose to share
- **Personal records (PRs):** your race times (Mile, 1500m, 3200m, 5K, 3000m, 800m) and your goal time. These are optional — you can skip them at signup.
- **Race calendar:** dates of your A/B/C races
- **Training preferences:** your preferred unit (miles or kilometers)
- **Coaching messages:** the questions you ask the in-app Coach, and the Coach's responses

### 2.2 Information collected automatically

When you use the app, we collect:

- **Authentication tokens** (used to keep you logged in across sessions)
- **Trial and subscription state** (when you started your free trial, whether you have an active paid subscription)
- **Usage counters** (how many training plans you've generated and how many coach messages you've sent on a given day, used to enforce rate limits)

We do **not** collect:

- Your phone's IDFA, advertising ID, or device fingerprint
- Your location
- Your contacts, photos, or any data outside the app
- Your network or browsing activity
- Cross-app or cross-website behavior

### 2.3 Information we do not collect from you

We do not request, store, or process: payment card details (subscription billing is handled by Apple App Store and Google Play Store directly — Laktic never sees your card number), Health app data (we do not request permission to read or write to Apple Health or Google Fit), GPS or location data, photos or media, or contacts.

---

## 3. How we use your information

We use your information solely to provide and improve the Service.

- **To build your training plans:** we send your profile, PRs, race calendar, and current training context to Anthropic (a third-party AI provider — see Section 4). Anthropic returns the plan content. We store that content for you to view in the app.
- **To respond to coaching questions:** when you message the in-app Coach, we send your question along with your training context to Anthropic. We store the conversation so you can refer back to it.
- **To maintain your account:** authentication, trial duration tracking, subscription status, and rate limit enforcement.
- **To improve the Service:** we may review aggregate usage patterns (e.g., "what proportion of users ask coaching questions in their first week") to identify product improvements. We do not analyze individual user data for marketing or profiling purposes.

We do **not** use your information to:

- Build a profile of you for advertising
- Train AI models (your data does not become training data — Anthropic does not retain your inputs after generating responses, per their commercial terms)
- Sell to data brokers or third parties
- Make automated decisions about you that produce legal effects

---

## 4. Who we share your information with

We share data only with the service providers we need to deliver the app. These are called "subprocessors."

### 4.1 Subprocessors

| Provider | Purpose | Data shared |
|---|---|---|
| **Supabase** | Authentication, database, file storage | Account info, profile, training plans, coaching messages |
| **Anthropic** | Plan generation and Coach responses (Claude API) | Profile context (name, PRs, race calendar, current training week), coaching messages |
| **Apple / Google Play** | Subscription billing and app distribution | Subscription status (Apple/Google handle payment processing; Laktic does not see your payment details) |

Each of these providers has their own privacy policy that governs how they handle data we send them. We have selected them because they meet industry-standard security and privacy practices.

### 4.2 Anthropic specifically

When you generate a plan or send a coach message, we send the relevant context (your profile, PRs, current training state, and your message) to Anthropic via their API. Anthropic processes the input to generate a response, then returns it to us. Per Anthropic's commercial terms, they do not retain your inputs to train AI models, and they do not use your inputs for purposes other than fulfilling our API requests.

### 4.3 Disclosure for legal reasons

We may disclose your information if required by valid legal process (subpoena, court order, lawful government request) or to protect against fraud, abuse, or threats to safety. If we receive such a request, we will (where legally permitted) notify you before complying.

### 4.4 What we do not do

We do not:
- Sell your data to anyone
- Share your data with advertisers
- Allow third parties to track you across other apps or websites through our app
- Provide your data to data brokers, marketing networks, or analytics platforms beyond what is necessary to operate the Service

---

## 5. How we secure your information

- All data is transmitted over HTTPS (TLS).
- Passwords are stored hashed (not in plaintext).
- Database access is protected by row-level security: your data is isolated from other users' data.
- We follow industry-standard practices for API key management, including never embedding API credentials in the app.

No system is perfectly secure. If we discover a data breach affecting your information, we will notify you within 72 hours of discovery via the email address on your account, in compliance with applicable breach notification laws.

---

## 6. Your rights

You have the following rights regarding your data, regardless of where you live. We honor these rights for all users.

- **Right to access:** you can request a copy of all data we have about you. Email us and we will provide it within 30 days.
- **Right to correction:** if any information is inaccurate, you can correct it directly in the app (most fields) or by contacting us.
- **Right to deletion:** you can delete your account at any time from within the app. Deletion is permanent and removes your profile, training plans, and coaching messages from our database within 30 days. Backup copies are purged within 90 days.
- **Right to data portability:** you can request your data in a machine-readable format (JSON).
- **Right to restrict processing:** you can ask us to pause processing of your data while you investigate concerns.
- **Right to object:** you can object to specific uses of your data, including any future change to how we process it.

To exercise any of these rights, email travis.william.mahoney@gmail.com with the subject line "Privacy Request." We respond within 30 days.

### 6.1 California residents (CCPA)

If you are a California resident, the California Consumer Privacy Act (CCPA) gives you additional rights, including the right to know what personal information we collect, the right to delete it, and the right to opt out of the sale of personal information. **We do not sell personal information**, so the opt-out right does not apply, but the access and deletion rights do, and we honor them as described above.

### 6.2 European and UK residents (GDPR / UK GDPR)

If you are in the European Economic Area, the United Kingdom, or Switzerland, you have rights under the GDPR. Our legal basis for processing your data is **contractual necessity** (we need this data to provide the Service you requested). You have the right to lodge a complaint with your local data protection authority if you believe we have not handled your data appropriately.

---

## 7. Children's privacy

Laktic is not intended for children under 13 (or under 16 in jurisdictions where that is the digital consent age). We do not knowingly collect data from children under those ages. If you become aware that a child has created an account, please contact us and we will delete the account.

---

## 8. Data retention

We retain your data for as long as your account is active. If you delete your account, we delete your data within 30 days, and backup copies are purged within 90 days.

If you stop using the app without deleting your account, we retain your data indefinitely so that you can return to your training without losing progress. You can delete your account at any time.

We retain certain billing and subscription records as required by tax and consumer protection laws (typically 7 years) — these records do not include your training data.

---

## 9. International data transfers

Our infrastructure providers (Supabase, Anthropic) may process your data on servers located in the United States and other countries. By using the Service, you consent to your data being transferred to and processed in these countries. We rely on standard contractual clauses and equivalent legal mechanisms where required (e.g., for transfers from the EU to the US).

---

## 10. Changes to this policy

If we make material changes to this policy (such as adding a new subprocessor, changing what data we collect, or changing how we use it), we will notify you through the app or by email at least 30 days before the changes take effect. The "Last updated" date at the top of this policy will reflect the most recent revision.

For minor clarifications that do not change the substance of how we handle your data, we may update the policy without prior notice, but the "Last updated" date will still reflect the change.

---

## 11. Contact

For any privacy questions, requests, or concerns:

- **Email:** travis.william.mahoney@gmail.com
- **Subject line for formal requests:** "Privacy Request — Laktic"

We respond to all privacy requests within 30 days.
