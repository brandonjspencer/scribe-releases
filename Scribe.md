## Scribe 0.14.0

**Ready for Scribe Remote, the iPhone app coming soon to the App Store.** Settings → iPhone Remote prepares this Mac for the companion app: once paired with a six-digit code, your phone can start, pause, resume, stop, snapshot, or mark a recording, follow the live transcript, and ask the Mac to check for updates. It is off by default and does nothing until you turn it on. It uses peer-to-peer Wi-Fi and Bluetooth, so it works even where office Wi-Fi blocks device discovery. macOS asks for Local Network permission the first time.

**Screen Recording permission always offers Open Settings.** macOS shows its Screen Recording prompt only once per app; when Request can't prompt again, the Permissions row and the welcome guide now take you straight to the right System Settings pane.

Under the hood, the transcript format, search chunking, checklist logic and the remote protocol moved into a shared package used by both the Mac app and the upcoming iPhone app.
