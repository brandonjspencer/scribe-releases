## What's new in 0.8.0

- **Active speaker tracking (Experimental)** — when enabled, Scribe reads Zoom's own "active speaker" indicator and tags transcript lines with who was talking, instead of just "System"/"Mic". Attribution is confidence-gated: a line only gets a name when a speaker was clearly known for its entire span — fast-changing or ambiguous stretches fall back to the plain source label rather than guessing.
- **"Multiple people are in the room"** — a per-recording option, shown when active speaker tracking is on, that keeps microphone audio labeled "Mic" instead of a Zoom participant's name. Useful when more than one person shares a local microphone, since Zoom's active-speaker signal only reflects which Zoom tile is talking.
- **Zoom window snapshot button** — a camera icon next to Pause/Resume captures a still image of Zoom's meeting window and saves it alongside the transcript, with a reference line noting when it was taken. Requires macOS 14 or later.

Both Zoom features reuse the existing Accessibility/Screen Recording permissions already used for the optional Zoom chat notice — no new permission prompts.
