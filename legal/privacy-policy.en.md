# Woolwink — Privacy Policy

Last updated: 2026-06-07

## 1. Core principle — Woolwink collects no personal data

Woolwink (the "Software") **collects, transmits, and stores no personal data**, including your screen captures, voice, and the text you enter.

- All processing (screen capture, local speech-to-text) happens **entirely on your own PC**.
- We **operate no server** and use no telemetry, analytics, tracking, or advertising identifiers.
- The Software's core features work even with network access blocked.

## 2. On-device processing

- **Speech-to-text** runs on a local model (Whisper) on your PC; audio is never uploaded.
- The **configuration file** (config.json) and the **audit log** (a record of sends) are stored **only on your PC**.
- The audit log records only the *kind* of send, timestamp, image count, and character count — **never the contents** of images or text.

## 2.5 Network connections (full transparency)

The Software connects to the internet in only **two** situations. **Neither sends your screen, voice, or text.**

1. **Update check (optional, can be turned off).** The Software fetches a small manifest file (a version number only) from GitHub. The request carries no information that identifies you. You can disable the automatic check in settings, or remove the update URL entirely.
2. **One-time speech-model download.** The first time you use the voice feature, the Software downloads the open-source Whisper model (used for fully local speech-to-text) once from its distributor (Hugging Face). After that it runs offline; your voice is never sent during this download.

Beyond these two, the Software makes no outbound connections — no telemetry, analytics, or tracking.

## 3. Hand-off to your AI app (Claude / ChatGPT / Gemini)

- The Software passes the content you choose into the input box of **your own AI app** (Claude / ChatGPT / Gemini, desktop app or browser tab) on your own PC.
- Once handed off, that content is governed by the **privacy policy and terms of the respective AI provider** (Anthropic, OpenAI, Google, etc.). The Software is not a party to that processing.
  - Example (Anthropic) Privacy Policy: https://www.anthropic.com/legal/privacy / Consumer Terms: https://www.anthropic.com/legal/consumer-terms

## 4. No sharing with third parties

The developer **receives none of your data and shares nothing** with third parties (there is no developer-held data to share).

## 5. Permissions (microphone, screen, clipboard)

The Software accesses your microphone, screen capture, and clipboard solely to perform the functions above (on-device processing and hand-off to your AI app). You can change microphone permission anytime in Windows Settings → Privacy → Microphone.

## 6. Purchase & license data

When you buy a license, the payment processor **Stripe** handles your name, email, and payment information (subject to Stripe's privacy policy). **Woolwink never receives your card or payment details.** To issue and verify your license, the Software processes only your **email** and an **irreversible device ID (a hash)** at purchase.

- The **device ID** identifies the machine only and contains **none of your screen, voice, or text** (it cannot be reversed back to your machine details).
- **Purpose:** issuing and delivering your license key, matching it to the purchasing device (to prevent unauthorized copying), and support.
- **Retention:** kept for as long as needed to verify the validity of your license.
- **Your rights:** to access, correct, or delete this data, contact us at the address below.

## 7. Contact

Questions: **germantiger16@gmail.com**

## 8. Changes

We may update this policy. Material changes will be announced in the Software or on the distribution page.

Effective date: 2026-06-07
