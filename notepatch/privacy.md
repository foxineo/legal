---
title: NotePatch Privacy Policy
---

# NotePatch Privacy Policy

**Effective Date:** 2026-04-07
**Last Updated:** 2026-05-06

This Privacy Policy describes how NotePatch ("we", "our", or "the app") handles information when you use the NotePatch iOS application.

## Our Position on Privacy

NotePatch is designed to be **private by default**. Core features — scanning, cropping, masking, and printing — work entirely offline with no account required. We do not collect, transmit, or share any personal data unless you explicitly choose to use a feature that requires it.

## Information We Do NOT Collect

- We do **not** collect personal identifiers (name, email, phone number, account ID).
- We do **not** collect device identifiers (IDFA, IDFV, advertising ID).
- We do **not** track your usage of the app.
- We do **not** use analytics, crash reporting, or telemetry services.
- We do **not** include any advertising or tracking SDKs.
- We do **not** access your contacts, calendar, location, microphone, or any data unrelated to core features.

## Information You Provide to the App (Stored Locally Only)

To function, NotePatch needs access to certain device features. All resulting data stays exclusively on your device:

| Permission | Why It Is Needed | Where the Data Goes |
|---|---|---|
| **Camera** | To scan handwritten notes or pages using the document scanner | Processed entirely on-device. Never uploaded. |
| **Photo Library (Read)** | To import existing photos and screenshots to turn into patches | NotePatch references the original asset by its Photos library identifier. |
| **Photo Library (Add)** | (Optional) To save processed patches back to your Photos library | Only happens when you explicitly trigger an export action. |
| **Printer (AirPrint)** | To send the generated PDF to a nearby printer over your local network | Sent only to the printer you select. |

## Smart Text Recognition

NotePatch offers two text recognition modes:

### On-Device OCR

On-device OCR uses Apple's built-in Vision framework to extract text from images. All processing happens locally on your device. **No data is transmitted.**

### AI Recognition (and Smart Fix)

When you explicitly choose AI recognition — or use Smart Fix to re-recognize a source image with a hint — the selected image is sent to a secure third-party cloud API for text extraction. Free users have a lifetime quota of free AI recognitions; Pro subscribers have unlimited access.

- **What is sent:** The image you selected for recognition. When you use Smart Fix, the optional hint text you provide (a short label such as "this is a math formula", or one of the preset choices like "🎨 Whole thing is an illustration") is sent alongside the image.
- **How it is processed:** The image and any provided hint are used solely for text extraction.
- **Data retention:** Neither the image nor the hint is **stored, logged, or used for model training** by the API provider.
- **When it happens:** Only when you explicitly tap the AI recognition option or pick / type a Smart Fix hint. It never happens automatically or in the background.

No other network requests are made by the app. NotePatch functions normally in airplane mode — AI recognition simply shows an offline message.

## Subscription and Billing

NotePatch Pro subscriptions are processed entirely by Apple through the App Store. We do not collect or have access to your payment information, credit card details, or Apple ID.

## How We Store Your Data

- All notes, patches, edit history, and preferences are stored **on your device only**, using Apple's local storage frameworks (SwiftData and UserDefaults).
- Nothing leaves your device except when:
  - You print to a printer you have selected (sent over your local network only).
  - You explicitly share a generated PDF using iOS's standard share sheet.
  - You explicitly use AI recognition (Pro), which sends the selected image to a cloud API as described above.

## Children's Privacy

NotePatch does not knowingly collect any information from anyone, including children under the age of 13. The app is suitable for general audiences.

## Your Rights

Because NotePatch does not collect or store any personal data on our side, there is no data for us to access, export, correct, or delete. Deleting the app from your device removes all locally stored NotePatch content.

## Changes to This Policy

If we change how the app handles data, we will update this policy and indicate the change with a new "Last Updated" date. Material changes will be reflected in the App Store update notes.

## Contact

If you have any questions about this privacy policy, you can reach us at:

**Email:** ai.neocai@gmail.com

---

*NotePatch's core features remain fully offline and private. The only time data leaves your device is when you explicitly choose to print, share, or use AI recognition.*

[← Back to NotePatch](./) · [foxineo Legal](../)
