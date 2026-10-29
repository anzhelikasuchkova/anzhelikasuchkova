# Hi, I'm Anzhelika

I build the automation behind materials-testing operations at SOCOTEC's Denver office. My tools take field and lab reports from Kordata (our testing data system) to clients, run day-to-day dispatching, and turn multi-hour weekly workflows into scheduled jobs.

The repositories are private. I'm happy to walk through the architecture and design decisions.

---

## 🔧 Current work

### 📋 [CMT Report Automation](https://github.com/socotec-denver-automation/CMT-report-automation) `PRIVATE`
Weekly Materials Testing Summaries now assemble themselves as project managers approve reports. An hourly loop downloads approved reports from Kordata, stages them for review, compiles each finished week into a client-ready PDF, and drafts the PM digest. It replaced up to 20 hours a week of manual work.

It also feeds a **client report portal** on SharePoint, now rolling out: approved reports wait in a review library, a principal engineer approves them in batches, and a Power Automate flow files each one into that client's own project library. Reports corrected after they were sent are detected and flagged for another review.

**Tech:** Python, python-docx, PyMuPDF, Outlook automation, SharePoint, Power Automate, JSON state

---

### 🔄 [Kordata Automation](https://github.com/socotec-denver-automation/kordata_automation) `PRIVATE`
Day-to-day dispatching through Kordata's web API: creating, copying and editing work orders, daily sample pickups, the daily schedule, and hours reconciliation against Deltek Vision. Every dispatch is checked against a project registry before it's saved and read back afterwards.

It also turns Kordata firestop inspection reports into the City of Aurora's ASTM E2174 inspection forms.

**Tech:** Python, Requests, Kordata web API, Windows Task Scheduler

---

### 📄 [Concrete Break Report Automation](https://github.com/socotec-denver-automation/break-report-automation) `PRIVATE`
Reads concrete compressive-strength reports, files them to project folders, prepares the client emails, and keeps the lab-hours tracker in step with Kordata. Automatic sending of routine emails is in a dry-run trial: every rule is checked before anything goes out.

**Tech:** Python, pdfplumber, Outlook automation, Excel

---

## 💡 Stack I reach for

Python, Requests, pdfplumber, python-docx, PyMuPDF, Outlook and Word automation, SharePoint, Power Automate, JSON-as-state, SQL, PowerShell.
