# FallProfile v2026 - sovereign professional-service workflow tool 2026

> **FallProfile is a browser-based, single-file identity and skills passport built around Ed25519, signed manifests, and offline-first HTML delivery, giving you a portable way to present verified provenance and benchmark-backed credentials in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/tomwood28/fallprofile-offline-html?style=flat-square)](https://github.com/tomwood28/fallprofile-offline-html)

---

<p align="center">
  <a href="https://tomwood28.github.io/fallprofile-offline-html/">
    <img src="https://img.shields.io/badge/Download-FallProfile%20Latest-brightgreen?style=for-the-badge" alt="Download FallProfile">
  </a>
</p>

> **[Direct Download - FallProfile v2026](https://tomwood28.github.io/fallprofile-offline-html/)**

---

[Download Latest Build](https://tomwood28.github.io/fallprofile-offline-html/)

---

## About FallProfile

FallProfile packages a professional identity into a compact, public-facing passport page you can share anywhere. The project is built as a single HTML file that opens directly in a browser, so the profile stays self-contained and can travel with you instead of depending on a hosted platform.

It is aimed at users who want identity, skills, and provenance presented together in one place. By combining Ed25519 identity support, signed manifests, and local-first storage, it keeps profile data organized while still being simple to open, copy, and distribute.

---

## Features

- Public passport page for sharing a professional profile
- Ed25519 identity support for cryptographic identity workflows
- Structured registry for verified skills and benchmark scores
- Provenance graph and bond history for relationship and context tracking
- Signed manifest support for portable and verifiable profile data
- Single HTML file layout for easy distribution and archiving
- Works offline from disk with no external requests
- Service worker support plus IndexedDB local storage for browser-side persistence

---

## Installation

1. Download or clone the repository:
   - `git clone https://github.com/tomwood28/fallprofile-offline-html.git
2. Open the main `HTML` file in a modern web browser.
3. If you prefer a local server during development, serve the folder with any static file server and load the page in the browser.

Example:
- `cd fallprofile`
- Open the main HTML file, or run a simple local server and navigate to it

---

## Usage

In normal use, you open the profile page, fill in identity details, and inspect the resulting passport-style view.

Common workflow:
1. Open the single-file app in a web browser.
2. Add or revise identity information, skills, and provenance details.
3. Sign or export the manifest if needed.
4. Share the generated passport page with others.
5. Reopen the file later to continue using local browser storage.

If you are offline, keep the HTML file and any related assets in the same folder so the page can be accessed directly from disk.

---

## Configuration

Most of the configuration lives inside the HTML file and browser storage rather than in external dependencies. Data may persist in IndexedDB, while service worker behavior depends on browser support and on how the file is served.

When customizing the page, the main areas to check are:
- Embedded HTML content
- Scripted identity and manifest logic
- Browser storage state
- Any service worker registration logic

---

## Requirements

- A modern web browser with WebCrypto support
- Support for HTML and JavaScript execution in the browser
- Local disk access if you want to run the single-file version offline
- IndexedDB support for local persistence
- Service worker support if you plan to use that feature in a served environment

---

## FAQ

**Does it work offline?**  
Yes. The project is meant to run from disk and does not depend on external requests.

**What kind of identity model does it use?**  
It uses Ed25519 and DID-related identity concepts as part of its profile and verification workflow.

**Where is the data stored?**  
Local browser storage through IndexedDB is part of the design, along with the single-file HTML structure.

**How do I update it?**  
Download the latest build from the project page and replace your current copy, then reopen the HTML file in your browser.

**What if something does not load correctly?**  
Try a current browser, confirm WebCrypto support, and reopen the file from a local server if your browser restricts direct file access.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
