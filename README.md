# Hi, I'm Anzhelika 👋

**Construction Services Coordinator** at SOCOTEC Denver, with a passion for **automation and standardization**.

Building tools to eliminate manual processes in materials testing and construction reporting. Working toward becoming an **AI & Automation Specialist** — turning repetitive workflows into intelligent, scalable systems.

---

## 🔧 Current Projects

### 📋 [CMT Report Automation](https://github.com/anzhelikasuchkova/CMT-report-automation) `PRIVATE`
Weekly materials testing summary compilation pipeline. Orchestrates:
- Report collection and organization
- Word template compilation with custom dividers
- PM digest summaries and Outlook integration
- Email draft generation with intelligent contact routing

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

## 💡 Skills & Tech Stack

**Languages:** Python, SQL, Bash/PowerShell  
**APIs & Integration:** Kordata, Outlook COM, Word/Excel Interop, REST  
**Workflow:** Git, JSON config, automation scripting, data pipelines  
**Tools:** pypdf, pdfplumber, pandas, logging, atomic file operations

---

## 📌 Mission

Standardize materials testing and construction workflows through automation. Every manual, repetitive process is a candidate for intelligent, reliable tooling.

---

*Last updated: June 2026*
