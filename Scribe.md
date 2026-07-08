# Scribe 0.4.0

The biggest Scribe release yet — faster transcription, cleaner transcripts, self-updating, and a proper welcome experience.

## New

- **In-process transcription engine.** Whisper now runs inside Scribe with Metal GPU acceleration. The model loads once per recording instead of once per chunk — chunks that used to take several seconds now transcribe in a fraction of a second. The legacy whisper-cli mode is still available in Settings → Local Whisper.
- **Smarter chunking.** Chunk boundaries now land on natural speech pauses instead of fixed 20-second cuts, so sentences are no longer sliced mid-word at chunk seams.
- **Auto-updates.** Scribe checks a signed update feed and updates itself in place. See Settings → Updates.
- **Welcome guide.** First launch walks through the menu-bar icon, the two permissions (including the Screen Recording quit-and-reopen step), and a quick tour. Reopen anytime via Settings → Show Welcome Guide.

## Requirements

- macOS 13+, Apple Silicon
- Notarized by Apple — download, open, drag to Applications
