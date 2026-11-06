# ScreenShotJoe

**Store-ready App Store and Google Play screenshots, made on your Mac.**

ScreenShotJoe turns raw screenshots of your app into polished store images: device mockups, backgrounds and headlines, exported at the exact pixel sizes each store requires, in every language you ship.

> **Status:** private test build.

## Features

- **Device mockups** for iPhone 17 / 17 Pro Max / 16 / 15, iPhone Duo, iPad, Pixel 8 Pro, generic Android phones and tablets, MacBook and Windows PC, in realistic, clay or minimal style, with optional 3D tilt.
- **Backgrounds**: solid, linear or radial gradient, split color or image, with overlays and decorative patterns.
- **Headlines and subtitles** with automatic line wrapping, a free-position text block, a bubble card and other text effects.
- **Extras**: floating trust badges and rating cards, a hero feature list, and a magnified detail of the screenshot.
- **Multi-device layouts**: single, dual or triple devices in one image, and panoramic sets that span several screenshots.
- **12 content languages** (English, Italian, German, French, Spanish, Portuguese, Japanese, Korean, Chinese, Arabic, Greek, Russian), each with its own texts and, optionally, its own screenshots. On-device translation through Apple's Translation framework.
- **Exact export sizes** for App Store (iPhone, iPad, Mac, Apple TV, Apple Vision Pro, Apple Watch) and Google Play, as PNG, JPEG or ZIP. A `fastlane` folder layout is available for automated uploads.
- **Store readiness check** that flags missing sizes, wrapping problems, low contrast and untranslated copy before you export.
- **Store listing text** (name, subtitle, keywords, description and more) per language, saved with the project.
- **Templates and art directions** to restyle a whole deck in one click, with full undo/redo.

## AI agents (optional)

ScreenShotJoe can be driven by AI coding agents through a local [MCP](https://modelcontextprotocol.io) server: the agent imports screenshots, writes and translates headlines, applies a style, reviews the result and exports, while every change appears live in the app and can be undone with ⌘Z.

- Off by default. Turn it on in **Settings → AI agents**, which also shows the ready-made configuration for Claude Code, Codex, OpenCode, Antigravity, Gemini CLI, Cursor, VS Code, Claude Desktop and other MCP clients.
- Listens only on `127.0.0.1` and requires a private token.
- Agents can read and write only the folders you explicitly share with them.

## Requirements

- macOS 15 (Sequoia) or later, on Apple silicon or Intel.
- App interface in English and Italian.

## Install

1. Download `ScreenShotJoe-1.0.dmg` from the [latest release](../../releases/latest).
2. Open the disk image and drag **ScreenShotJoe** to **Applications**.
3. Launch it from Applications.

The app is signed with an Apple Developer ID and notarized by Apple, so macOS opens it without warnings.

### Verify the download (optional)

```bash
shasum -a 256 -c ScreenShotJoe-1.0.dmg.sha256
```

## Privacy

Your projects stay on your Mac. ScreenShotJoe has no account, no analytics and no tracking, and it does not upload your screenshots anywhere. It runs in the macOS App Sandbox and can only open the files and folders you choose.

## Feedback

Found a bug or have an idea? Please open an [issue](../../issues).
