# Sendo — App Store Connect submission package

All assets ready for when your Apple Developer account activates. Files in this folder:

| File | Where it goes in App Store Connect | Char count |
|---|---|---|
| `subtitle.txt` | App Information → Subtitle | 27 / 30 |
| `keywords.txt` | App Information → Keywords | ~95 / 100 |
| `app-description.txt` | App Information → Description | ~3300 / 4000 |
| `privacy-policy.html` | Host on GitHub Pages → paste URL into App Information → Privacy Policy URL | — |
| `support.html` | Host on GitHub Pages → paste URL into App Information → Support URL | — |
| `screenshot-guide.md` | Reference for when you're capturing screenshots | — |

## How to host the privacy policy & support page (free, 5 minutes)

1. Create a free GitHub account if you don't have one: https://github.com/signup
2. Create a new public repo named `sendo-site` (or similar)
3. Upload both `privacy-policy.html` and `support.html` to the repo root
4. In repo Settings → Pages → set Source to "Deploy from a branch" → Branch: `main` → Folder: `/ (root)` → Save
5. Wait 1–2 minutes. Your URLs will be:
   - `https://YOURUSERNAME.github.io/sendo-site/privacy-policy.html`
   - `https://YOURUSERNAME.github.io/sendo-site/support.html`
6. Paste those URLs into App Store Connect.

That's it. Free forever, no server to maintain.

## Suggested App Store Connect form values

| Field | Value |
|---|---|
| **App Name** | Sendo |
| **Subtitle** | SMS messenger · no internet |
| **Primary Category** | Social Networking |
| **Secondary Category** | Utilities |
| **Content Rights** | I do not own or have licensed third-party content |
| **Age Rating** | 4+ (no objectionable content — answer "No" to all questions) |
| **Pricing** | Free OR Tier 10 ($9.99) — your choice |
| **Availability** | Choose countries: at minimum US, UK, Canada, Sweden, Norway, UAE, Saudi Arabia, Kenya, Ethiopia, Djibouti (and Somalia if available) |
| **Copyright** | 2026 Sendo |

## App review information (Apple needs this to test your app)

When you submit for review, Apple asks for "Notes for the App Reviewer." Use this:

> Sendo is an SMS/MMS messaging app for users who want to message contacts without internet. The app uses Apple's MFMessageComposeViewController to compose and send messages through the device's standard SMS/MMS service. Sendo does not access incoming SMS (Apple does not allow this for third-party apps) — replies arrive in the user's regular Messages app, which is the expected and documented behavior. Sendo does not run any servers; all data is stored locally. No login or test credentials are required to review the app.

## Demo account

Sendo has no login. Leave demo account fields blank or write: "No login required — open the app, tap the green + to add a contact, then start messaging."

## Pricing recommendation

- **Free with no in-app purchase** — easiest review, larger audience, no revenue
- **$9.99 paid** (Tier 10) — Apple takes 30% (15% if you're in the Small Business Program — apply at https://developer.apple.com/app-store/small-business-program). You keep ~$7 per sale.

**My suggestion**: launch as **paid $9.99**, since you've already validated price expectations with your manual workflow. Switch to free later if it doesn't convert.
