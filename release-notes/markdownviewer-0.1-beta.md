# Release Notes – MarkdownViewer 0.1.0-beta (2025-09-03)

## First Public Beta

Welcome to the first public beta of **MarkdownViewer**, a fast, cross‑platform viewer for Markdown files. This beta focuses on core viewing performance and simplicity and is intended for early adopters and testers.

## New Features

- Open files: Drag and drop onto the window or choose File > Open to load .md files.
- Themes: Choose Classic, Solarized, or Monochrome from the toolbar.
- Preview toggle: Switch between raw Markdown and formatted preview with one click.
- Cross-platform: Available for Windows, macOS, and Linux (Electron), and as a web app.

## Known Issues (Beta)

- Large files (>5 MB): Rendering may slow or freeze temporarily. **Severity**: Medium. **Workaround**: Split files or close other heavy apps.
- Relative image paths: Only same‑folder images resolve; subfolders aren’t supported. **Severity**: Low. **Workaround**: Use absolute paths or move images.
- Theme persistence: Resets on restart. **Severity**: Low. No **workaround**.
- Export to HTML: Disabled in this beta. **Severity**: Medium. No **workaround**. **ETA**: 0.2.
- Keyboard shortcuts: Only basic copy/paste available. **Severity**: Low. No **workaround**.

## Installation

**Windows**: Download the .exe from Releases, run the installer, then launch MarkdownViewer.

**MacOS**: Download the .dmg, drag to Applications, then open via Finder (right‑click > Open on first run).

**Linux**: Download the AppImage, make it executable (chmod +x MarkdownViewer.AppImage), then run it.

**Web**: Open https://example.com/markdownviewer.

**Requirements**: 64‑bit OS. Internet optional. Auto‑update disabled in this beta.

## Feedback

Your feedback is essential as we continue to develop the app. We're already working on new features for upcoming releases, including a built-in editor and more advanced customization options.

Please report bugs or suggestions via our GitHub Issues page or email beta@markdownviewer.example.com.
