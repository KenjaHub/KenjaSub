# KenjaSub Privacy Policy

**Effective date: September 16, 2026**

KenjaSub is a video subtitle editor for macOS, developed by Kenja ("we", "us"). This policy explains what happens to your data when you use the app.

**The short version: KenjaSub collects nothing.** There are no accounts, no analytics, no ads, and no tracking. Your videos and audio never leave your Mac. If you choose to connect your own AI provider, only subtitle text is sent — directly from your Mac to the provider you configured. We never see any of it.

## 1. Data we collect

None. KenjaSub does not transmit any personal data to us, and does not share data with any third party on our behalf.

In particular, KenjaSub does **not** include:

- user accounts or sign-in
- analytics, telemetry, or crash-reporting SDKs
- advertising or ad tracking of any kind
- third-party trackers

This matches our App Store privacy declaration: *Data Not Collected*.

## 2. Media stays on your Mac

All media processing happens locally on your Mac:

- **Video and audio never leave your machine.** Import, playback, audio extraction, and export all run on your Mac.
- **Speech recognition is fully on-device**, using Apple's SpeechAnalyzer framework.
- **Translation is on-device** when you use the built-in Local engine (Apple's Translation framework).

## 3. Data stored on your Mac

The following data is stored only on your Mac, under your full control:

- **Subtitle projects** — videos (by reference), cues, source and translated text, glossaries
- **App settings** — languages, styles, output folder, batch configuration
- **AI provider configuration** — Base URL, model name, and other options (except the API key, see below)

You can delete this data at any time: remove projects inside the app, and delete exported subtitle files in the Finder like any other file.

## 4. AI providers you configure (bring your own key)

KenjaSub's AI features — AI translation, polishing, and the assistant — are strictly bring-your-own-key. They are inactive until you configure a provider yourself, such as OpenAI, DeepSeek, OpenRouter, Ollama, LM Studio, or a custom OpenAI-compatible endpoint.

If and only if you configure a provider and choose an AI engine:

- **Only subtitle text is sent** — never your video, never your audio, and no timestamps or other media data.
- Requests go **directly from your Mac to the endpoint you configured** over HTTPS. We never receive this data and have no access to it.
- Your **API key is stored only in your Mac's Keychain**, never in plain files.
- Data sent to your chosen provider is processed under **that provider's own privacy policy** — please review it on their website.
- If you point KenjaSub at a local endpoint (Ollama, LM Studio), subtitle text never leaves your machine at all.

## 5. Network access

The only outbound network traffic KenjaSub initiates is:

- requests to the AI endpoint **you** configured, when you invoke AI features (or run the connection test in Settings)

App updates are delivered by the App Store, not by us. On-device speech and translation assets may be downloaded by macOS itself; that is managed by the operating system, not by KenjaSub.

## 6. Children

KenjaSub is rated 4+ and is not directed at children. Since the app collects no data at all, no data of children is collected either.

## 7. Your control

Because everything lives on your Mac, you are in full control at all times: export, copy, or delete your projects and files whenever you like, and remove your API key from the Keychain (or the Models tab) at any time. Uninstalling the app removes the app and its local settings.

## 8. Changes to this policy

If we change this policy, we will post the updated version on this page with a new effective date.

## 9. Contact

- Email: [kenjasoft@kofukuai.com](mailto:kenjasoft@kofukuai.com)
- GitHub: [https://github.com/KenjaHub](https://github.com/KenjaHub)
