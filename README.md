# Precut Pro

**Precut Pro** is a Windows desktop application for browsing, previewing, and downloading short anime editing clips (“precuts”) from a shared Google Drive catalog.

Built with WPF on .NET 8, the app provides a fast local catalog view of a structured Drive library with cover support, search, favorites, and in‑app playback.

---

## Features

- Cover-based anime library browser
- Fast title search
- Episode / clip navigation per show
- In‑app preview playback (Drive embed player via WebView2)
- Favorites system
- Recently uploaded section
- Centralized metadata sync from Drive
- NSFW / spoiler tag awareness (metadata-controlled)
- Download queue with local history
- Local caching for faster startup

---

## How it works

Precut Pro connects to a shared Google Drive catalog and builds a local index of:

- anime titles
- precut files
- published metadata
- cover artwork

Metadata updates are published centrally and synced automatically by clients.

---

## Requirements

- Windows
- .NET Desktop Runtime 8
- Microsoft Edge WebView2 Runtime
- Network access to Google Drive

---

## Scope

Precut Pro is a catalog + preview + download client for a curated precut archive.

It does not manage the library itself. Publisher-side metadata and catalog management are handled separately by admin tooling.
