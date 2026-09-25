# 🔒 Privacy Policy — ClearRead

**Effective date:** 25 September 2026 · **Last updated:** 25 September 2026

ClearRead is a browser extension that makes web pages easier to read. This policy explains exactly what the extension does — and does not do — with your information.

---

## 📌 The short version

> ClearRead does **not** collect, sell, or share your personal data, browsing history, or usage analytics.
> Everything the extension does to a page happens **in your browser**.
>
> Two features can send data off your device, and both are described in full below:
> signing in to sync your settings, and cloud text simplification when your device can't do it locally.

---

## 💾 What ClearRead stores

**Your reading settings**

Font, letter and line spacing, line width, colour overlay, reading mode, reader line, and text-to-speech voice and speed. These are saved through the browser's own extension storage so your setup is there next time you read.

If you are not signed in, **these never leave your browser.**

**Your account — only if you create one**

Signing in is optional, and ClearRead works fully without an account. If you do sign in, we store your email address, an account identifier, and your reading settings on our database provider, Supabase, so your settings follow you between devices.

Authentication uses OAuth. **ClearRead never sees or stores your password.**

---

## 🚫 What ClearRead does *not* store

- Page content, page text, or page URLs
- Browsing history or the sites you visit
- Text you have spoken aloud or simplified
- Cookies, advertising identifiers, or device fingerprints
- Analytics, telemetry, or usage tracking of any kind

---

## 🧠 Text simplification

When you select text and ask ClearRead to simplify it, the extension **first tries the model built into your browser.** In that case the text never leaves your device.

If your browser doesn't support on-device simplification, ClearRead **asks you before sending anything.** Only the text you selected is sent, over an encrypted connection, to Google's Gemini API, which returns the simplified version.

| | |
|---|---|
| Sent | Only the text you selected |
| Linked to your account | No |
| Stored by ClearRead | No |
| Used for model training | No |

Google's handling of that request is governed by its own API terms. If you decline, the feature is simply unavailable and nothing is sent.

---

## 🔊 Reading aloud

Text-to-speech uses the voices already installed in your browser or operating system. **The text stays on your device.**

## 📄 PDFs

PDFs you open in ClearRead's viewer are rendered locally in your browser. **The file is never uploaded anywhere.**

---

## ⚙️ Permissions

Each permission ClearRead requests exists to deliver a feature you asked for.

| Permission | Why it's needed |
|---|---|
| `scripting` | Applies your fonts, spacing, colours, and reader line to the page |
| `activeTab` | Acts on the one tab you're reading, only after you click |
| `storage` | Saves your reading settings |
| `sidePanel` | Shows the controls beside the page while you read |
| `contextMenus` | Right-click access to read aloud and apply your settings |
| `webNavigation` | Re-applies your settings when a site changes page without reloading |
| `alarms` | Refreshes your sign-in session and retries failed settings syncs |

**No permission is used for tracking, advertising, or background collection.**

---

## 🎛 Your control over your data

Your settings are yours.

- Reset them at any time from the extension.
- Removing ClearRead from your browser deletes everything stored locally.
- If you have an account and want it deleted, email us. We'll delete your account record and all settings associated with it **within 30 days.**

---

## 👶 Children

ClearRead is not directed at children under 13, and we do not knowingly collect information from them.

<!-- If ClearRead will be used in schools, state your position on student data here. IRIS reviewers and school IT both look for it. -->

## 📝 Changes to this policy

If this policy changes in a way that affects what ClearRead does with your data, we'll update the effective date above and note the change in the extension's release notes.

## 📩 Contact

**projectclearread@gmail.com**

<!-- Add a postal or organisational address if your store listing requires one. -->
