### Hi, I'm Anzhelika
I build internal automation for a materials testing lab at SOCOTEC (Denver). Most of my recent work is a Python toolchain that turns multi-hour weekly report workflows into a handful of `.bat` launches — PDF parsing, Outlook draft generation, file-share routing, and per-PM state tracking.

The repos that matter live in private but I'm happy to walk through architecture and design decisions on request.

| Project | What it does |
|---|---|
| **CMT-report-automation** | Cuts a ~20-hour weekly reporting workflow to minutes — Word template filling, PDF generation, Outlook draft creation, and per-PM state tracking via a five-stage JSON state machine |
| **break-report-automation** | Automates concrete break report intake — extracts data from PDFs, renames and routes files to the project share, creates Outlook drafts from the lab email, and updates the lab hours tracker |

**Stack I reach for:** Python, pdfplumber, python-docx, COM automation (Outlook + Word), Microsoft Graph API, JSON-as-state.

**Recent focus:** turning brittle Excel-tracker workflows into idempotent state machines.
