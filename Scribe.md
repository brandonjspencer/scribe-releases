## Scribe 0.10.0

**Ask your meetings.** A new *Ask Your Meetings…* window searches everything said or decided across all your transcripts and minutes, grouped by meeting with the timestamp or section for each passage. Minutes hits open the reader at that section with the words highlighted; transcript hits open a built-in viewer at the moment it was said. Quote a phrase to match it exactly. The index is a local SQLite database that updates whenever a recording finishes, and every 45 seconds while one is running. Nothing leaves your Mac.

If you have [Ollama](https://ollama.com) installed with an embedding model (`ollama pull nomic-embed-text`), results are also ranked by meaning — passages found that way are marked *related*. Without Ollama, search is words-only and the window says so.

**Minutes Reader search.** ⌘F finds within the open document (⌘G / ⇧⌘G to step through matches). The Files tab has a search box that finds passages across every minutes file in the folder.

**Action-items checklist.** Action items in the reader are tickable, the status bar shows how many are done, and ticks are saved back into the Markdown file as `- [x]`.

**Calendar titles.** Turn on *Name recordings after the current calendar event* in Settings → Recording Options and untitled recordings are named after the meeting on your calendar right now. The Zoom "meeting detected" prompt pre-fills the same title. Calendar access is requested once, when you enable it.
