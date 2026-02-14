# Winclone

**Winclone** is a single-file **Windows-style desktop UI clone** built in plain **HTML/CSS/JS** (with jQuery + jQuery UI for drag/drop). It’s a front-end sandbox for experimenting with a “desktop in the browser” experience: centered taskbar, start menu, draggable icons, context menus, sticky notes, simple storage lists, notifications, theming, and more.

> Not affiliated with Microsoft or Windows — this is a UI/interaction experiment.

---

## What’s in this repo

- `winclone.html` — the entire app (layout + styles + scripts in one file). :contentReference[oaicite:1]{index=1}

If you want GitHub Pages preview, you can rename `winclone.html` to `index.html`.

---

## Features

### Desktop + icons
- **Desktop icons** (initial example shortcuts)
- **Drag to reposition icons** (positions saved per “desktop”)
- **Right-click icon context menu**:
  - Rename
  - Delete
  - “Pin to taskbar” (see Known issues)
- **Icon search** (filters icons by label)

### Taskbar / shell
- **Centered taskbar layout** (left / center / right sections)
- **Start button** with a start menu:
  - Documents / Downloads
  - Settings
  - New Shortcut
  - Toggle Theme
  - Cycle Wallpaper
- **Date & time display** + **12/24h toggle**
- **Virtual desktop navigation** (Prev/Next + “Desktop N” indicator)

### Notes + “storage”
- **Sticky Notes**:
  - Create and persist notes
  - Notes are draggable on the desktop
  - Save / Clear All
- **Downloads/Documents panel**:
  - Add items to a persistent list
  - Remove items

### UX extras
- **Toast notifications** (with optional voice)
- **Click sound** toggle
- **Theme toggle** (dark/light)
- **Wallpaper cycling** (URL-based)
- **Desktop right-click menu**:
  - New Shortcut
  - Change Background
- **Shutdown overlay** animation (then reloads the page)
- **Virtual Assistant modal** (simple local responses)
- **Top “news ticker” banner**
- **Weather widget placeholder** (“Weather: Loading…”)

---

## Quick start

### Option A — open directly
1. Clone:
   ```bash
   git clone https://github.com/kai9987kai/Winclone.git
   cd Winclone
