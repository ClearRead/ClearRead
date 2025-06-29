# ClearRead

ClearRead is a browser extension designed to make web content easier to read, especially for individuals with dyslexia or anyone who prefers a clearer, simplified reading experience.  
It enhances accessibility by applying customizable fonts, spacing, color filters, focus tools, and AI-powered text simplification—all while respecting user privacy.

---

## ✨ Features

- **Dyslexia-Friendly Fonts** – Switch to fonts that improve readability.
- **Adjustable Spacing** – Change letter and line spacing using an intuitive slider.
- **Sepia Filter** – Reduce glare and eye strain with a soft background filter.
- **Reader Line** – A horizontal guide that helps keep your place while reading.
- **Read Aloud** – Listen to page content spoken out loud.
- **AI Text Simplification** – Instantly simplify complex text into shorter, clearer summaries.
- **Recommended Settings** – Apply pre-configured, balanced settings for dyslexia support.
- **Reset** – Revert any changes and return to the original webpage view.

All features are designed to be toggled on/off easily to create a personalized, dyslexia-friendly browsing experience.

---

## 🔒 Privacy & Data Handling

ClearRead places **privacy first** and is built to respect and protect user data:

- The extension does **not** collect, store, track, or sell any personal data, browsing history, or usage information.
- All visual adjustments (fonts, spacing, filters, reader line) are applied **locally in the user's browser** without transmitting data externally.
- When users choose to simplify text using the AI feature, the selected webpage text is **temporarily sent to the Hugging Face Inference API** solely to receive a simplified version.
- **Hugging Face Inference API does *not* store, log, track, or reuse this text.** It processes the text in real time and returns the simplified content without retaining user data.
- No user-identifiable data, metadata, or browsing history is ever shared with Hugging Face or any other third party.
- ClearRead does **not** use any data for advertising, analytics, or resale.

This approach ensures a secure, private experience while still offering advanced AI-based simplification.

---

## ⚙️ Permissions & Why They’re Needed

| Permission                                            | Purpose                                                                                                        |
|------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| `scripting`                                          | To inject scripts and styles that apply fonts, spacing adjustments, filters, and reader lines.                |
| `activeTab`                                          | To modify and apply changes only on the currently active browser tab, based on user actions.                   |
| `tabs`                                               | To identify the correct tab for applying features like Read Aloud and resetting changes.                       |
| `storage`                                            | To save user preferences (e.g., chosen font, spacing settings) so they persist across sessions.                |
| `host_permissions` to `https://api-inference.huggingface.co/` | Required to securely send selected text to Hugging Face for AI text simplification.                            |

All permissions are strictly limited to the functionalities users request and do not enable background tracking or data collection.

---

## 📦 Installation

1. Download or clone this repository.
2. Open your browser and navigate to `chrome://extensions/`.
3. Enable **Developer mode** in the top right.
4. Click **Load unpacked** and select the folder containing this extension.

---

## 📜 License

MIT License – free to use, modify, and distribute for personal or educational purposes.

---

## 🛡 Product Disclosure

ClearRead does **not** collect or store any personal data or browsing history.  
For text simplification only, selected webpage text is processed by the [Hugging Face Inference API](https://huggingface.co/) to generate simpler content.  
This data is processed in real time and **not stored or logged** by Hugging Face. No personal information is ever shared, sold, or used for advertising.

---

## 📩 Contact

For questions, feedback, or support, please contact:  
📧 projectclearread@gmail.com

---

