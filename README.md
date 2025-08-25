# UUID v7 Online Generator

A simple web-based generator for **UUID version 7** (time-ordered, RFC 9562 compliant).  
Built as a single static HTML file — no backend, no dependencies, no ads!

---

## Features
- Generates RFC 9562 compliant UUID v7 identifiers.
- Uses **cryptographically secure random values** (`crypto.getRandomValues`).
- Supports generating multiple UUIDs at once (1–100).
- Copy-to-clipboard with a single click.
- Responsive, works on desktop and mobile.
- 100% client-side — no data leaves your browser.

---

## What is UUID v7?
UUID v7 is a **time-ordered universally unique identifier**, standardized in [RFC 9562](https://www.rfc-editor.org/rfc/rfc9562.html).  
It improves database indexing performance compared to random UUID v4, while still being globally unique and collision-resistant.

Structure:
- 48-bit Unix timestamp (milliseconds)
- 12-bit random entropy
- 62-bit random entropy with variant bits

---

## Development
This project is just one HTML file:

- `index.html` → main application

Run it locally by opening the file in any modern browser:
```bash
open index.html
