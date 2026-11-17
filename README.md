# HOUSE mobile foundation v0.1

Minimal dark, liquid-glass-inspired installable web app (PWA).

## Works now
- Responsive mobile dashboard and navigation
- Local quiet-mode preference
- Prototype chat UI that clearly says the AI backend is not connected
- Memory, Devices, Vision and Preferences panels
- Offline app shell after first successful load

## Not connected yet
No AI model/API, account, cloud sync, camera, PTZ, microphone, speaker, light, smart-home, finance, WhatsApp or Mac control. Devices are labelled Planned.

## Install on Poco
A PWA needs HTTPS hosting. Upload this folder to an HTTPS static host, open its URL in Chrome on the Poco, then Chrome menu > Install app (or Add to Home screen).

The prototype stores only the quiet-mode toggle in browser localStorage. It does not access camera/microphone or save footage.
