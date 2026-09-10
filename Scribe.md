## Scribe 0.11.0

**Zoom chat notice works again on Zoom 7.1.5.** Zoom's latest update relabelled its chat composer, which made the written recording disclosure fail with "chat UI not found". Scribe now finds the composer regardless of its label, with a fallback if Zoom renames it again.

**Answers in Ask your meetings.** Press Return (or click *Answer*) and Scribe asks Claude Code for a short answer built only from the top matching passages, with `[n]` citations you can click to open the exact passage in the reader or transcript viewer. Off by default: the first time, the window explains that the question and the top 12 passages are sent to Claude and nothing else leaves the Mac. Tools are disabled for the run, so Claude reads only what Scribe hands it. Needs the Claude Code CLI, like minutes generation.
