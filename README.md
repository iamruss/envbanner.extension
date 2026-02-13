# EnvBanner

A Chrome extension that adds visual environment indicators — color-coded banners and CSS overrides — to web pages, so developers never accidentally work in the wrong environment.

![ScreenShot](demo.webp)

## Features

- Auto-detection of environments by hostname patterns (localhost, dev, uat, stage) — works out of the box
- Explicit URL pattern matching for precise control over specific sites
- Color-coded floating banners (overlay or injected into page flow)
- CSS override mode for custom element styling
- Hostname exclusion lists for auto patterns
- Per-pattern enable/disable and debug logging
- Badge indicator showing current environment on the extension icon
- Full-page editor for detailed configuration
- Both strategies (auto + explicit) active simultaneously — explicit always takes priority

## Tech Stack

- TypeScript 5.7, React 19, Material UI 6, Vite 7
- Chrome Extension Manifest V3



Copyright © 2026 ParkBridge.App. All rights reserved.
