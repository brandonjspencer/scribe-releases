## Scribe 0.13.0

**Claude Desktop extension.** Settings → Meeting Minutes now has *Install Claude Desktop Extension…*. One click opens the extension in Claude Desktop, which asks where your transcripts and minutes folders are (leave them blank to use Scribe's own), plus an optional Slack channel and calendar, and installs it. No Node, no Python, no config files.

Claude Desktop then gets tools to search across every transcript and minutes file using Scribe's index, read them, find meetings that don't have minutes yet, and save minutes into your folder where Scribe's reader and search pick them up. Three commands carry the meeting-minutes workflow: `/write_minutes`, `/catch_up`, and `/weekly_digest`, configured for you rather than by editing a skill file.

The extension reads and writes only the two folders you choose. The Claude Code skill export remains available alongside it.
