# T-42 skill registry

The list of optional skills for T-42, a personal AI agent that runs on your computer.

T-42 reads `registry.json` from this repository to offer these skills in Settings → Skills, and
downloads them from this repository's releases. Each download is checked against the SHA-256 in the
index before it is installed. Each skill runs inside T-42's sandbox with only the access its manifest
declares and you allow, unless you turn the sandbox off in Settings.

You don't need to download anything here by hand: install skills from inside T-42.

## Skills

| Skill | What it does |
|-------|--------------|
| `core.google.workspace` | Calendar, Gmail, Drive, Sheets, Docs, Tasks, People and Chat, through one Google sign-in |
| `data.analyze` | CSV, Excel, JSON: summarize, filter, sort, pivot |
| `data.visualize` | Bar, line, pie and scatter charts from your data |
| `doc.create` | PDF, DOCX and HTML from Markdown |
| `scheduler` | Reminders, recurring tasks, time-based triggers |
| `notify` | Push notifications through ntfy.sh or Pushover |
| `summarize` | Summaries of web pages, files or text |

Each skill is built for macOS (Apple Silicon and Intel) and Linux (x86-64 and ARM64).

## What's here

- `registry.json`: the index, with each skill's version, platforms, download address and SHA-256.
- Releases: the skill packages.

The skills' source code is not published. Only T-42's own skills are listed; outside submissions are
not open.

## Licence

Free to use with T-42; all rights reserved. This is not an open-source licence. See
[LICENSE](LICENSE). The open-source components inside the packages, and their licences, are listed in
[THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt).
