## Oreoluwa Kelvin Fawehinmi

**Grants & Program Operations · Systems Automation**

I administer donor-funded grant portfolios exceeding **$50M** across Global Fund, PEPFAR, USAID,
NIH and WHO - and I build the software that removes the manual work from them. I audit budgets,
run sub-recipient assessments, brief senior management, and write the automation that turns
multi-day reconciliation jobs into minutes.

> Donor compliance fluency, plus the ability to design and build the systems that enforce it.

B.Sc. Industrial Mathematics (Computer Option), University of Lagos. Based in Abuja, Nigeria.

---

### Live products

#### [NofoDesk](https://nofodesk.com) · the app that reads a funding call so nobody has to retype it

A funding call arrives as forty pages of PDF. The deadline, the award ceiling, who is eligible
and which attachments are mandatory are all buried in it, and every grant office I know pays
someone to find them and retype them into a spreadsheet. NofoDesk reads the call instead - paste
the URL or drop the PDF and it returns the whole record in about thirty seconds, then tracks the
deadline, generates the application checklist, assesses your organisation against the eligibility
criteria, and drafts proposal sections in the funder's own language.

`React` `Node + Express` `Supabase` `PostgreSQL` `Gemini 2.5 Flash` `Brave Search` `Tesseract OCR` `Server-Sent Events` `Zod` `ExcelJS + PptxGenJS`

Scanned documents with no text layer are rasterised and run through OCR rather than failing.
Every extraction is validated against a strict schema and reviewed by a person before it reaches
the tracker - a confidently wrong deadline is worse than no deadline.

This is the job I do during the day, so I am also the user. Every field it pulls out is a field
I have retyped by hand.

#### [TailorDesk](https://tailordesk.ng) · the app that runs a tailoring business from a phone

Nigerian tailors keep their entire business in a paper measurement notebook. It tears, it soaks,
it gets lost - and with it go the measurements, the agreed prices, and the record of who still
owes money. TailorDesk replaces that notebook: permanent client measurements, order and balance
tracking, and branded receipts sent straight into the customer's WhatsApp. The customer installs
nothing.

`React 18` `TypeScript (strict)` `Vite` `TailwindCSS` `TanStack Query` `Supabase` `PostgreSQL` `Deno` `Paystack` `PWA`

Per-tailor isolation is enforced by Postgres row-level security at the database level, not in
application code. Installable offline-first PWA. All money is stored as integer kobo, with
server-side Paystack verification in an edge function.

---

### Day job

**Grants & Contracts Management Assistant** - Institute of Human Virology Nigeria (IHVN), Abuja.

Multi-donor portfolio exceeding $50M: Global Fund GC7 (N-THRIP), PEPFAR, USAID, NIH, WHO.

**100+** subawards and modifications processed · **900+** compliance documents with **zero audit
findings** · **100%** on-time donor reporting · **267%** of annual proposal submission target ·
**₦120M** in cost efficiencies identified · SAM.gov verification and pre-award risk assessment
for **70+** sub-recipients · 2 CFR 200 / Uniform Guidance compliance across federal cooperative
agreements.

- Audited the EQUAL 2 project budget and identified formula defects across salary subtotals,
  fringe rates and indirect cost rows affecting allocations in the hundreds of millions of naira,
  preventing misstatement in donor reporting.
- Conducted six sub-recipient assessment visits, producing gap analyses, remediation trackers
  and formal reports.
- Analysed Global Fund GC7 closure requirements and GC8 grant-making architecture ahead of
  IHVN's confirmation as Principal Recipient 3 for the 2027-2029 cycle, and briefed senior
  management on obligations, timelines and transition risk.
- Served as focal point for three concurrent WHO HIV Drug Resistance proposals, coordinating
  technical, finance and compliance inputs to on-time submission.
- Reformatted and reissued the IHVN Grants Management Manual (Fifth Revision) as the
  organisation's controlling procedural document.

**Built in-house, not commissioned:**

- `LoE_Compare` - a VBA reconciliation tool comparing ~625 rows of monthly staff level-of-effort
  data across source systems, replacing a manual line-by-line review.
- A bulk Word document generation system producing modification letters for health facilities
  from structured data, with per-row error isolation, run-mode toggles and a generation log.
- Automated ASPIRE project document processing: programmatic PDF signature replacement,
  extension letter sorting and tracker updates.
- A Power Automate workflow for the organisation-wide Employee of the Month nomination process.

It is not software work, but it is where I learned to ship things that get audited - and it is
where NofoDesk came from.

---

### Independent practice

**FOKT Consulting LLC (US)** - Principal. Custom applications for paying clients on a 50% deposit
/ milestone structure, from scope definition and pricing through to delivery, plus proposal
development and grants advisory for development-sector clients.

---

### Also built

A LangGraph routing system directing tasks between a hosted coding agent and a locally-hosted
DeepSeek model via Ollama, balancing capability against inference cost. Excel and Power Query
dashboards for KPI tracking and variance reporting, including a multi-period fund performance
tracker reconciling time-weighted returns across contributors.

**Languages** JavaScript/TypeScript, Python, SQL, VBA, MQL5
**Frontend** React, Vite, Tailwind CSS, Progressive Web Apps
**Backend** Node.js/Express, Supabase, PostgreSQL, REST APIs
**AI** LLM API integration (Anthropic, Gemini), structured extraction, LangGraph orchestration,
local model deployment (Ollama)
**Deployment** Render, Vercel, Git/GitHub

---

### About the source

Both products are closed-source and running in production. I am happy to walk through the
codebase or arrange read access as part of a hiring or funding conversation - just ask.

[fawehinmioreoluwa@gmail.com](mailto:fawehinmioreoluwa@gmail.com) ·
[LinkedIn](https://www.linkedin.com/in/oreoluwa-fawehinmi/) ·
[Portfolio](https://tailordesk.ng/cv) · Abuja, Nigeria
