# Tadacity

**On-demand web data capture for AI workflows.**  
Capture once. Reuse everywhere. Serve fresh web data locally via MCP.

---

## What is Tadacity?

Tadacity is a **local-first web data capture and serving platform** designed for AI workflows.

Instead of writing scrapers, maintaining crawlers, or relying on stale datasets, Tadacity lets you:

- Visually define **how to extract structured data** from web pages
- Reuse those definitions across similar pages
- Fetch data **on demand**, exactly when your AI needs it
- Serve results locally to AI tools via **MCP (Model Context Protocol)**

Tadacity focuses on **intentional, one-off data retrieval**, not continuous crawling or monitoring.

---

## How Tadacity Works (Mental Model)

1. **Capture once**  
   Use the browser extension to visually define how to extract data from a page.

2. **Store the definition, not the data**  
   Capture definitions (selectors, fields, URL patterns) are stored in Tadacity’s cloud so they can sync across devices.

3. **Fetch locally, on demand**  
   When requested, the CLI fetches the page and extracts data **locally on your machine**.

4. **Serve to AI via MCP**  
   The CLI runs a local MCP server so AI tools (Claude, Cursor, etc.) can request fresh data when needed.

> Tadacity never stores or processes the actual web page content or extracted data on its servers.

---

## What Tadacity Is (and Isn’t)

### ✅ Tadacity is
- Local-first
- On-demand
- AI-oriented
- MCP-compatible
- Capture-definition driven

### ❌ Tadacity is not
- A crawler
- A scraping farm
- A real-time monitoring system
- A hosted data API
- A background data harvester

---

## Components

### Browser Extension
- Visually create **captures**
- Define structured fields from web pages
- Generalize captures to similar URLs

### CLI
- Authenticate and sync capture definitions
- Fetch pages and extract data locally
- Run a local MCP server for AI tools

> The MCP server runs **locally** via the CLI. There is no hosted MCP backend.

---

## Installation & Usage

### CLI & Browser Extension

CLI binaries and browser extension builds are published via **GitHub Releases**.

➡️ **Go to the Releases page to install:**  
https://github.com/tadacity/tadacity/releases

Each release includes:
- Installation instructions
- Platform-specific binaries
- Browser extension builds
- Changelog and notes

---

## Documentation

Full documentation lives in a separate repository and is published at:

📘 **https://www.tadacity.com/docs**

This includes:
- Installation guides
- Capture concepts
- MCP integration
- Examples and workflows

---

## Feedback & Community

- Website: https://www.tadacity.com
- Docs: https://www.tadacity.com/docs
- Subreddit: https://www.reddit.com/r/TadacityAI
- X (Twitter): https://x.com/TadacityAI

Feedback is welcome via:
- GitHub Issues
- Reddit discussions
- Website feedback form

---

## License

Tadacity is released under the license specified in this repository.

---

*Tadacity*  
*Capture the ~~data~~ tada.*
