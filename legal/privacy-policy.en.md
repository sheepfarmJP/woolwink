# Woolwink — Privacy Policy

Last updated: 2026-06-05

> ⚠️ This is a working draft. **Have it reviewed by qualified counsel before you launch a paid (Pro) tier or take payment.**

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

## 3. Hand-off to Claude Desktop (Anthropic)

- The Software passes the content you choose into the input box of **Claude Desktop installed on your own PC**.
- Once handed off, that content is governed by **Anthropic's privacy policy and terms**. The Software is not a party to that processing.
  - Anthropic Privacy Policy: https://www.anthropic.com/legal/privacy
  - Anthropic Consumer Terms: https://www.anthropic.com/legal/consumer-terms

## 4. No sharing with third parties

The developer **receives none of your data and shares nothing** with third parties (there is no developer-held data to share).

## 5. Permissions (microphone, screen, clipboard)

The Software accesses your microphone, screen capture, and clipboard solely to perform the functions above (on-device processing and hand-off to Claude Desktop). You can change microphone permission anytime in Windows Settings → Privacy → Microphone.

## 6. Future paid (Pro) tier

When we process payments for the Pro tier, the payment processor **Stripe** will handle your name, email, and payment information (subject to Stripe's privacy policy). To issue and verify your license, we process your email and an **irreversible device ID (a hash)** at purchase. The device ID identifies the machine only and contains none of your screen, voice, or text. We will update this policy to state the **data, purposes, retention, and your rights** at that time.

## 7. Contact

Questions: **germantiger16@gmail.com**

## 8. Changes

We may update this policy. Material changes will be announced in the Software or on the distribution page.

Effective date: 2026-06-05
