<div align="center">

# 🌅 SubFetch — Reddit Wallpaper Fetcher

**A fast, single-file web app that pulls high-quality wallpapers from any Reddit communities, with bulk download, sorting, and a clean gallery — zero dependencies, instant load.**

![Status](https://img.shields.io/badge/status-live-success)
![Type](https://img.shields.io/badge/type-Web%20App-00b894)
![Size](https://img.shields.io/badge/footprint-single%20file-blue)

[![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-fetch%20API-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)

</div>

---

## Overview

**SubFetch** is a self-contained web app — one HTML file, no build step, no dependencies — that turns Reddit into an infinite wallpaper gallery. Enter any subreddits, browse a responsive image grid, sort by hot/top/new, toggle NSFW, and bulk-download what you like. It loads instantly and runs anywhere.

The web companion to the native **WallReddit** Android app, SubFetch demonstrates clean API integration and a polished UX in the smallest possible footprint.

> Built by **[DG Technology](https://dgtechnology.com)** — engineered by Faiz Ullah.

---

## Key Features

- 🔍 **Multi-subreddit fetching** — pull from any combination of communities at once
- 🖼️ **Responsive gallery** — fluid image grid that adapts to any screen
- ⬇️ **Bulk download** — grab multiple wallpapers in one action
- 🔃 **Sort modes** — hot, top, new
- 🔞 **NSFW toggle** — show or hide mature content
- 📱 **Mobile-optimized** — works great on phones
- ⚡ **Instant load** — single file, zero dependencies, no framework overhead

---

## Tech Stack

| Component | Technology |
|-----------|-----------|
| **Core** | Vanilla JavaScript (ES6+) |
| **Data** | Reddit JSON API via `fetch` |
| **UI** | Single-file HTML + CSS |
| **Build** | None — open and run |

---

## How It Works

SubFetch queries Reddit's public JSON endpoints (`r/{subreddit}/{sort}.json`), parses the media from each post, filters by type and NSFW preference, and renders everything into a responsive gallery — all client-side. Downloads are handled directly in the browser.

```
subfetch/
└── index.html      # The entire app — markup, styles, and logic in one file
```

---

## Usage

Just open the file in any browser, or host it anywhere static (it's one file):

```bash
# Serve locally
python3 -m http.server 8000
# → open http://localhost:8000
```

Enter subreddit names, pick a sort order, browse, and download.

---

<div align="center">

**Designed & engineered by Faiz Ullah**
Frontend Developer · Full-Stack Engineer · Founder of [DG Technology](https://dgtechnology.com)

📧 contact@faizullah.pk · 🌐 [faizullah.pk](https://faizullah.pk)

*Built with precision by DG Technology* 💙

</div>
