## Scribe 0.15.2

- Fixed a bug where a recording could silently capture nothing and later crash. It happened when the microphone in use had changed since the previous recording — for example, switching between a Bluetooth headset and the built-in mic.
- If the microphone can't be started, or stops working mid-meeting, Scribe now keeps recording system audio and tells you, instead of losing the meeting.
