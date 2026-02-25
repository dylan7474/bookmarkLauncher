# bookmarkLauncher

bookmarkLauncher is a single-page, browser-based launchpad for your favorite websites. It gives you a clean dashboard with primary and secondary bookmark grids, optional background customization, and local configuration controls (edit, import, export) so your setup is easy to maintain.

## What the application is

- A lightweight start-page style web app (no build tooling required).
- A configurable bookmark launcher with two sections:
  - **Primary Sites** for frequently used links.
  - **Secondary Sites** for everything else.
- A local-first experience where your bookmark layout and settings persist in the browser.

## Build / run instructions

This project is static HTML/CSS/JS, so there is no compilation step.

### Option 1: Open directly

1. Clone this repository.
2. Open `index.html` in your browser.

### Option 2: Serve locally (recommended)

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Basic controls

- **Edit Mode**: Toggle edit mode from the header to modify bookmark entries.
- **Bookmark editing**:
  - Click a tile while in edit mode to set title and URL.
  - Optionally upload a custom icon.
  - Use “Clear Link” to reset a slot.
- **Drag and drop**: Reorder bookmarks while edit mode is active.
- **Export Config**: Download your current configuration for backup.
- **Import Config**: Restore bookmarks/settings from a previously exported file.
- **Background settings**: Apply or remove a custom background image.

## Roadmap

- Add optional bookmark categories/tags and quick filtering.
- Add keyboard shortcuts for faster navigation and editing.
- Add optional sync adapters (for users who want multi-device config sync).
- Improve accessibility with additional ARIA and focus-management refinements.
