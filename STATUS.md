# STATUS

## What was built

A beginner manual for healthcare workers on using GitHub, produced by
Asdale Dynamics, LLC (Indiana, formed October 2026). Plain English, step by
step, privacy-safe, no code required. Topics: documenting protocols, sharing
templates, version-controlling shift sheets.

### Delivered files

- `README.md` — overview, contents, privacy notice, Asdale Dynamics, LLC credit, MIT license pointer
- `LICENSE` — MIT License, copyright line exactly `Copyright (c) 2026 Asdale Dynamics, LLC`
- `STATUS.md` — this file
- `docs/` — Markdown manual (7 files):
  - `01-getting-started.md` — what GitHub is, repos/commits/branches in plain English
  - `02-github-account.md` — creating an account, 2FA, profile privacy
  - `03-documenting-protocols.md` — protocol repo, Markdown files, commits, history
  - `04-sharing-templates.md` — template repo, sharing with teammates, blank fields
  - `05-version-controlling-shift-sheets.md` — Markdown and CSV shift sheets, compare versions, fix mistakes
  - `06-privacy-and-safety.md` — no patient data, newspaper test, private repos
  - `glossary.md` — plain-English GitHub terms
- `site/` — static HTML version of the same manual (8 pages + CSS), openable in any browser with no server or internet:
  - `site/index.html` — home with chapter cards
  - `site/pages/getting-started.html`, `account.html`, `protocols.html`, `templates.html`, `shift-sheets.html`, `privacy.html`, `glossary.html`
  - `site/css/style.css` — shared warm, high-contrast stylesheet

## How to run it

1. Open `site/index.html` in any web browser (Chrome, Firefox, Safari, Edge).
2. Navigate chapters via the top menu or the sidebar on each page.
3. The Markdown files in `docs/` can be read in any text editor or Markdown viewer.

No build step, no install, no server, no internet required once the files are
on your computer. No code is required to use the manual itself.

## Verification results

Ran `python3 /tmp/kilo/verify_guide.py` (223 checks): **223/223 passed**.

- All expected files exist (`docs/`, `site/`, `LICENSE`, `README.md`, `STATUS.md`)
- LICENSE contains the exact copyright line: `Copyright (c) 2026 Asdale Dynamics, LLC`
- README credits Asdale Dynamics, LLC
- All 8 HTML pages parse cleanly (no unclosed tags)
- Every internal link resolves to an existing file; no broken links
- No `.github/workflows` directory
- No secret patterns (API-key-like strings) in any file

## Known gaps

- No screenshots of the GitHub website (kept text-only so the manual stays accurate as GitHub's UI changes)
- No GitHub Desktop walkthrough (website steps only; Desktop noted as an option)
- Static site is not hosted anywhere (intentionally: never push, never create remote repos, never publish)
- No search function or JavaScript (pure HTML/CSS, works offline)
- Readers must create their own GitHub account following Chapter 2; the manual cannot do that for them
- This is education only, not medical advice, and not a substitute for workplace privacy policies or HIPAA training
