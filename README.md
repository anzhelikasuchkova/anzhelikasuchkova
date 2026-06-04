# Hi, I'm Anzhelika

I build internal automation for a materials testing lab at SOCOTEC (Denver). Most of my recent work is a Python toolchain that turns multi-hour weekly report workflows into a handful of `.bat` launches — PDF parsing, Outlook draft generation, file-share routing, and per-PM state tracking.

The repos that matter live in private but I'm happy to walk through architecture and design decisions on request.

---

## 🔧 Current Projects

### 📋 [CMT Report Automation](https://github.com/anzhelikasuchkova/CMT-report-automation) `PRIVATE`
Cuts a ~20-hour weekly reporting workflow to minutes. Orchestrates report collection, Word template filling, PDF generation, Outlook draft creation, and per-PM state tracking via a five-stage JSON state machine (Needs Summary → Compiled → Digest Sent → Draft Created → Archived).

**Tech:** Python, Word/Excel automation, JSON, Git  
**Features:** schedule-based filtering, incremental processing, live status tracking

---

### 🔄 [Kordata Sync](https://github.com/anzhelikasuchkova/kordata_automation) `PRIVATE`
Automated report download from Kordata API, replacing manual browser workflows.

**Supports:**
- LAB (materials testing samples)
- SIR (special inspections)
- DFR (daily field reports)
- FDT (field density tests)
- SCHEDULE (weekly dispatch summary)

**Tech:** Python, Requests, Kordata API, session-based auth  
**Features:** smart filtering, date-range queries, file overwrite detection, folder structure auto-nesting

---

### 📄 [Concrete Break Report Automation](https://github.com/anzhelikasuchkova/break_report_automation) `PRIVATE`
Automates processing and distribution of concrete compressive strength reports. Reads PDFs from Outlook, renames and files them to project folders, creates ready-to-send Outlook drafts, and tracks lab hours.

**Report Processing:**
- Scans Outlook for break report emails
- Extracts project number, test date, lab number, and strength results using pdfplumber
- Merges PDFs by project and date
- Renames files consistently
- Copies to G:\\ project folder structure
- Auto-creates Outlook draft with attachments

**Lab Hours Tracking:**
- Maintains Excel-based lab tracker (weekly updated)
- Logs testing hours by project and technician
- Tracks concrete cylinder information and test results
- Generates reconciliation reports for accuracy

**Tech:** Python, pdfplumber, Outlook COM, Excel Interop, PDF processing  
**Features:** manual input fallback for scanned PDFs, project reconciliation, automated contact routing, lab hours tracking

---

## 💡 Stack I reach for

Python, pdfplumber, python-docx, COM automation (Outlook + Word), Kordata API, JSON-as-state, SQL, Bash/PowerShell.

---

## 📌 Recent focus

Turning brittle Excel-tracker workflows into idempotent state machines. Building automated API data extraction pipelines (Kordata) to eliminate manual report downloads and feed structured data into downstream workflows.

---

*Last updated: June 2026*
