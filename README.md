<h1 align="center">Foma</h1>

<p align="center">
  The "subtle magic" writer's tool that gets you writing immediately<br/>
  with as little friction and as much power as you wish to wield.
</p>

<p align="center">
  <a href="https://github.com/Piaomu/foma-app/releases/latest"><img alt="Latest Release" src="https://img.shields.io/github/v/release/Piaomu/foma-app?include_prereleases&style=flat-square" /></a>
  <img alt="Platforms" src="https://img.shields.io/badge/platforms-Windows%20%7C%20macOS%20%7C%20Linux-blue?style=flat-square" />
  <a href="EULA.md"><img alt="License" src="https://img.shields.io/badge/license-Sovereign-green?style=flat-square" /></a>
</p>

<!-- 📸 HERO SCREENSHOT — full-window shot showing the editor with sidebar + worldbuilding open -->
![Image](https://github.com/user-attachments/assets/733327c3-287c-4aaf-b84d-3fb6d9e47c54)

## What is Foma?

Foma is a **local-first desktop writing app** for novelists, game writers, and worldbuilders. Your manuscripts, your worldbuilding, your version history — all stored as transparent markdown files on your machine. No accounts. No subscriptions. No cloud lock-in.

Write in a modern distraction-free editor. Organize your world alongside your manuscript. Let built-in version control remember every draft so you never lose a word.

Foma is actively designed to help writers start committing words to the page immediately every single time they sit down to write. Virtually anything writers wish to do is available at a keystroke, which means you're writing sooner, switching "windowed contexts" less frequently, and helping you write more words more often without breaking focus or fussing with settings. 

---

## Features

### Manuscript Editor

A clean, block-based markdown-backed text editor built for long-form writing. Chapters and scenes in the sidebar, content in the main pane. Drag-and-drop reordering, inline rename, and keyboard-first navigation.

- Rich text formatting, headings, lists, blockquotes, code blocks
- Auto first-line paragraph indentation (optional)
- Slash commands for quick actions
- Markdown syntax resolves to rich-text display in the editor
- Formatting marks (pilcrow toggle) for precise layout control

<!-- 📸 SCREENSHOT — editor pane with a few paragraphs, sidebar showing chapters/scenes -->
<img width="2735" height="1723" alt="Image" src="https://github.com/user-attachments/assets/4ccea896-9bee-45cc-a47f-3d73099c01da" />

### Focus Mode & Writing Sprints

Shut out the noise. Focus mode hides everything except your text. Set a timed sprint to push through a writing session with a live word-count pill. The "Typewriter focus" feature allows you to adjust your "typewriter ribbon" to your eye level no matter your screen size or orientation. You always type comfortably and distraction-free.

<!-- 📸 GIF — entering focus mode, starting a sprint, the timer pill counting -->
![Image](https://github.com/user-attachments/assets/0315e99c-e4c6-4439-8ed5-f0c0a4867954)

### Worldbuilding

A full sidebar section for characters, locations, lore, and any entity type you invent. Nested groups, notes, and actants with rich-text editing — organized your way.

- **Custom actant classes** — define your own entity types (factions, quests, magic systems) with custom icons
- **Project templates** — start with an Empty, Novel, or Game template that pre-populates your worldbuilding structure

<!-- 📸 SCREENSHOT — worldbuilding sidebar expanded, showing groups/characters/notes -->
<img width="2343" height="883" alt="Image" src="https://github.com/user-attachments/assets/6fab5966-f121-4bfd-a4a0-9aa08c2220cb" />

### Cross-References & Auto-Linking

Type `@` in the editor to mention any worldbuilding entry. Foma automatically detects character and entity names in your manuscript and highlights them — connecting your story to your world without manual work.

<!-- 📸 GIF — typing @ to mention a character, auto-link highlight appearing on a name -->
![Image](https://github.com/user-attachments/assets/437c613b-2c60-408c-a23f-b899b701b78d)

### Inline Comments

Highlight text and press `Ctrl+Alt+M` to add a comment. A slide-out panel lists all comments for the current document with resolve, delete, and click-to-navigate.

<!-- 📸 SCREENSHOT — editor with highlighted comment, comments panel open on the right -->
<!-- <p align="center"><img src="docs/screenshots/comments.png" alt="Inline comments" width="800" /></p> -->

### Loremaster's Memory (Version Control)

Built-in Git version control, simplified for a writer's workflow so that you don't have to learn the complexities of Git. Create named snapshots of your entire project, browse your version history, compare any two versions side by side, and restore earlier drafts — all from a simple panel.

- **Snapshots** — save the state of your project at any point
- **Auto-sync** — Settings for auto-sync to GitHub at timed intervals or whenever you take a snapshot
- **Diff view** — see exactly what changed between any two versions
- **Discard changes** — revert uncommitted edits per-file or project-wide
- **Sync indicators** — sidebar badges show uncommitted and unsynced changes at a glance
- **Git terminal** — power users can run raw Git commands via the `/git` slash command

<!-- 📸 GIF — creating a snapshot, then viewing the diff of a scene between two snapshots -->
![Image](https://github.com/user-attachments/assets/53c7a3ad-ef64-4642-8a1f-7cd36a9a2470)

### Writing Stats & Goals

Track your word count by manuscript, worldbuilding, or both. Set daily or project goals and watch your progress.

<!-- 📸 SCREENSHOT — stats bar / goals panel -->
![Image](https://github.com/user-attachments/assets/13658fba-8e68-4588-a036-e540a30bb2b3)

### Project-Wide Search

Search across scenes, chapters, and all content with a four-scoped search panel.

### Spellcheck

Context-menu corrections, per-project custom dictionary, and configurable spellcheck language.

### Themes, Modes
Foma displays in dark mode out-of-the-box, but it also comes in three color palettes that each have a light and dark mode so that you can write in the editor that makes you feel most at home.
<img width="888" height="479" alt="Image" src="https://github.com/user-attachments/assets/af614d8f-11fd-4dce-abda-96b6abd0e125" />

---

## Why Foma?

| | Foma | Scrivener | Google Docs | Notion |
|---|---|---|---|---|
| **Local-first** | ✅ Plain Markdown + JSON on your disk | ✅ Proprietary binary | ❌ Cloud-only | ❌ Cloud-only |
| **Free** | ✅ For Alpha testers! | ❌ Paid license | ✅ Free tier | ✅ Free tier |
| **Version control** | ✅ Git-powered snapshots | ⚠️ Manual backups | ⚠️ Revision history | ⚠️ Page history |
| **Worldbuilding** | ✅ Integrated + auto-linked | ⚠️ Research folder | ❌ Separate docs | ⚠️ Separate databases |
| **Cross-platform** | ✅ Windows, macOS, Linux | ⚠️ Windows + macOS | ✅ Browser | ✅ Browser |
| **No account required** | ✅ | ✅ | ❌ | ❌ |
| **Your files, your format** | ✅ Markdown you can read anywhere | ❌ `.scriv` bundle | ❌ Proprietary | ❌ Proprietary |

---

## Download

Grab the latest release for your platform:

| Platform | Installer |
|----------|-----------|
| **Windows** | `FomaSetup.exe` |
| **macOS** | `Foma-darwin-*.zip` |
| **Linux** | `.deb` or `.rpm` |

👉 **[Download the latest release](https://github.com/Piaomu/foma-app/releases/latest)**

### System Requirements

- **Windows** 10 or later
- **macOS** 12 (Monterey) or later
- **Linux** — Ubuntu 20.04+, Fedora 36+, or equivalent

### Disclaimer
Foma is built and maintained by a single developer with a creative writing degree. It is still in Alpha, and as such, I can't guarantee that every feature is stable and functioning as intended across different users's workflows, use cases, and project scopes. Please report any bugs you may encounter to [GitHub Issues](https://github.com/Piaomu/foma-app/issues) and I'll resolve each bug as soon as humanly possible. Thanks for your patience, understanding, and support. Happy writing!

---

## Getting Started

1. **Download and install** Foma for your platform.
2. **Create a project** — choose Empty, Novel, or Game to scaffold your workspace.
3. **Start writing** — click a scene in the sidebar and type. That's it.

<!-- 📸 GIF — creating a new project, picking "Novel" template, typing the first sentence -->
<!-- <p align="center"><img src="docs/screenshots/getting-started.gif" alt="Getting started" width="800" /></p> -->

### Quick Tips

- **`/` commands** — type `/` in the editor for focus mode, sprints, comments, auto-links, and more
- **`@` mentions** — type `@` to reference any worldbuilding entry inline
- **`Ctrl+Shift+8`** — toggle formatting marks
- **`Ctrl+Alt+M`** — comment on selected text
- **Drag & drop** — reorder chapters, scenes, and worldbuilding entries in the sidebar

---

## Roadmap

Foma is in active alpha development. Here's what's coming:

- [x] Export to DOCX, PDF, EPUB (**released MVP in v0.3.0-alpha.3!**)
- [x] Collation — get your manuscript print-ready to bind by yourself
- [x] Quest Management — for game designers, a system that helps map quests, objectives, and rewards to your plot, subplots, and characters (coming soon!)
- [x] Visual Storyboarding — leverage auto-linked worldbuilding blocks to scaffold your plot and character development with ease
- [ ] Templates — use bre-built templates based on your needs, or create your own for re-use!
- [ ] Corkboard — visual card-based story planning
- [ ] Character & location profile sheets with structured fields
- [ ] Database blocks — structured relational data to connect your characters, locations, and events
- [ ] Enriched "Loremaster" — a virtual companion who helps manage version control, worldbuilding, and more
- [ ] Theming and plugin system
- [ ] Mobile app (iOS/Android) — sync your work across devices (if time and resources allow)

See the [Changelog](CHANGELOG.md) for what shipped in recent releases.

---

## Community & Support

- **Issues & feature requests** — [GitHub Issues](https://github.com/Piaomu/foma-app/issues)
- **Discussions** — [GitHub Discussions](https://github.com/Piaomu/foma-app/discussions)

---

## Contributing

Foma's source code is developed in a private repository. The public repo hosts releases and community discussion. If you're interested in contributing, open an issue or discussion to start a conversation.

---

## License

[End User License Agreement](LICENSE) 

---

<p align="center">
  <sub>Built with Electron, React, BlockNote, and isomorphic-git.</sub><br/>
  <sub>Made by <a href="https://github.com/Piaomu">Driftwood</a>.</sub>
</p>
