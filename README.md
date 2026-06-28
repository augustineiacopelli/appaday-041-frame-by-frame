# 041 · Frame by Frame

**AppADay · Day 041**

A photo slideshow app with five decorative frame styles. Load photos from your device, pick a frame, set your interval, and let it run. Photos stay on your device — nothing is uploaded.

## Features

- Load multiple photos via file picker or drag-and-drop
- Five frame styles: Polaroid, Gallery Mat, Film Strip, Gilded, Borderless
- Photos are automatically resized to 1920px on the long edge before storage, keeping localStorage usage lean enough for 15–20 typical phone photos
- Adjustable slide interval (2–30 seconds) via Settings
- Smooth crossfade transition between slides
- Thumbnail tray for quick navigation — tap to jump, tap × to remove a photo
- Hide UI / Show UI toggle for a clean full-screen view with no chrome
- Swipe left/right to advance manually on touch devices
- Loading progress overlay with per-photo counter while photos process
- Graceful error handling — corrupt or unsupported files are skipped with a toast notification; localStorage quota errors are caught and reported without crashing
- Photos, frame choice, and interval persist across sessions via localStorage
- Keyboard shortcuts: ←/→ to navigate, Space to play/pause, C to toggle cinema mode, F for fullscreen

## Stack

Single-file HTML/CSS/JS — no frameworks, no build step, no external dependencies beyond Google Fonts.

## AppADay
Part of the [AppADay portfolio](https://augustineiacopelli.github.io/appaday/) — one complete web app built and shipped every day.
