# SyncWise AI

**AI-powered academic dashboard that syncs D2L Brightspace assignments and Outlook calendar events into one smart interface.**

SyncWise AI is a productivity tool built for students and instructors at Colorado Mesa University. Students see all their deadlines in one place with AI-powered prioritization. Instructors can create assignments, edit due dates, and manage course content from a single dashboard — no more navigating through multiple D2L menus.

## Features

- **D2L Brightspace Integration** — Automatically pulls assignments, due dates, and grades via OAuth 2.0
- **Outlook Calendar Sync** — Imports classes, meetings, and events from your university Outlook calendar and auto-syncs new due dates
- **AI Prioritization** — Ranks tasks by due date, point value, and workload so you know what to tackle first
- **Instructor Dashboard** — Lets instructors post assignments and edit due dates from one interface (with confirmation on every action)
- **FERPA Compliant** — Individual OAuth consent, read-only student access, full audit logging

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript (single-page landing)
- **Hosting:** Vercel (auto-deploys from this repo)
- **APIs:** D2L Brightspace Valence API (OAuth 2.0), Microsoft Graph API (Azure AD)
- **AI Engine:** Claude / OpenAI API for task prioritization
- **Waitlist:** Formspree (email collection)

## Live Site

[syncwise-landing.vercel.app](https://syncwise-landing.vercel.app)

## Local Development

```bash
git clone https://github.com/troysfields/syncwise-landing.git
cd syncwise-landing
open index.html
```

No build step required — it's a single HTML file with embedded CSS and JS.

## Status

Currently in pre-launch. Beta pilot planned for Spring 2026 at Colorado Mesa University with one ENTR 450 class section (~30 students, 1 instructor). Awaiting API access approval from CMU IT.

## Contact

Troy Fields — [troysfields@gmail.com](mailto:troysfields@gmail.com)
ENTR 450 — Professor Jouflas, Colorado Mesa University
