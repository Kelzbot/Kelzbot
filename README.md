## Fawehinmi Oreoluwa Kelvin

I build software for Nigerian small businesses and African grant offices, and I manage
**$50M+ donor-funded grant portfolios** for a living.

Self-taught developer. B.Sc. Industrial Mathematics (Computer Option), University of Lagos.
Based in Abuja, Nigeria.

---

### Live products

#### [TailorDesk](https://tailordesk.ng) · the app that runs a tailoring business from a phone

Nigerian tailors keep their entire business in a paper measurement notebook. It tears, it soaks,
it gets lost — and with it go the measurements, the agreed prices, and the record of who still
owes money. TailorDesk replaces that notebook: permanent client measurements, order and balance
tracking, and branded receipts sent straight into the customer's WhatsApp. The customer installs
nothing.

`React 18` `TypeScript (strict)` `Vite` `TailwindCSS` `TanStack Query` `Supabase` `PostgreSQL` `Deno` `Paystack` `PWA`

Per-tailor isolation is enforced by Postgres row-level security at the database level, not in
application code. Installable offline-first PWA. All money is stored as integer kobo, with
server-side Paystack verification in an edge function.

#### [NofoDesk](https://nofodesk.com) · the app that reads a funding call so nobody has to retype it

A funding call arrives as forty pages of PDF. The deadline, the award ceiling, who is eligible
and which attachments are mandatory are all buried in it, and every grant office I know pays
someone to find them and retype them into a spreadsheet. NofoDesk reads the call instead — paste
the URL or drop the PDF and it returns the whole record in about thirty seconds, then tracks the
deadline, generates the application checklist, assesses your organisation against the eligibility
criteria, and drafts proposal sections in the funder's own language.

`React` `Node + Express` `Supabase` `PostgreSQL` `Gemini 2.5 Flash` `Brave Search` `Tesseract OCR` `Server-Sent Events` `Zod` `ExcelJS + PptxGenJS`

Scanned documents with no text layer are rasterised and run through OCR rather than failing.
Every extraction is validated against a strict schema and reviewed by a person before it reaches
the tracker — a confidently wrong deadline is worse than no deadline.

---

### Day job

**Grants & Contracts Management Specialist** — Institute of Human Virology Nigeria (IHVN), Abuja.

Three years of pre-award and post-award management across USAID, CDC and Global Fund portfolios:
2 CFR 200 / Uniform Guidance compliance, 100+ subawards and modifications, 900+ compliance
documents with zero audit findings, and a 100% on-time donor reporting rate. It is not software
work, but it is where I learned to ship things that get audited — and it is where NofoDesk came
from.

---

### About the source

Both products are closed-source and running in production. I am happy to walk through the
codebase or arrange read access as part of a hiring conversation — just ask.

**[fawehinmioreoluwa@gmail.com](mailto:fawehinmioreoluwa@gmail.com)** · Abuja, Nigeria
