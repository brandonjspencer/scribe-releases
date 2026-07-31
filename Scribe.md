# Scribe 0.6.0

## Zoom chat disclosure (opt-in)

Scribe can now post a written notice into the meeting's group chat the moment recording starts — so participants see the disclosure in writing, not just hear it.

- **Off by default.** Turn it on in Settings → Recording Options.
- **Editable message**, defaulting to: *"Scribe Notification: this meeting is being transcribed locally."*
- **Send Test Message** button lets you try it in a live meeting before relying on it.
- Requires **Accessibility permission** — Scribe types into Zoom's own chat box, since there's no Zoom API for this. Recording and transcription never need that permission; it's used only for this optional feature.
- Fails silently if Zoom's chat can't be found (no meeting, permission not granted, etc.) — a recording never depends on this working.
