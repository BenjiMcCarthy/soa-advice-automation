# SOA Advice Automation — Project Outline

## For: Mat's Insurance Brokerage

---

## The Problem

Every time a client needs insurance advice, your team manually:

1. Pulls the client's fact find and financial data from Trail
2. Runs a needs analysis to identify cover gaps
3. Researches suitable products across insurers
4. Writes a full Statement of Advice document (SOA) — often 10-20+ pages
5. Formats it, checks compliance, and sends to the client

This takes **3-5 hours per client** and you're paying a full-time salary for it.

---

## The Solution

An automated system that connects directly to your Trail CRM, pulls client data, and generates a **draft SOA in minutes** — ready for your adviser to review, tweak, and approve.

### How It Works (Simple Version)

```
Trail CRM  →  Our System  →  Draft SOA  →  Adviser Reviews  →  Final SOA to Client
```

### How It Works (Detailed)

**Step 1: Adviser triggers SOA generation**
- Adviser clicks "Generate SOA" from the review dashboard
- Selects the client from Trail (or it auto-syncs when a pipeline stage changes)

**Step 2: System pulls data from Trail**
- Client personal details (contacts, dependents)
- Fact find data (health, occupation, smoking status, etc.)
- Statement of position (income, assets, liabilities, existing policies)
- KiwiSaver, mortgages, investments

**Step 3: AI analyses the client's situation**
- Calculates cover needs (life, trauma, income protection, TPD, medical)
- Compares existing cover vs recommended cover
- Identifies gaps and priorities

**Step 4: Product matching**
- Searches our product database for suitable policies across NZ insurers
- Compares premiums, features, exclusions
- Selects best-fit products with clear reasoning

**Step 5: SOA document generated**
- Professional, branded document with all required sections:
  - Client objectives and scope of advice
  - Current situation summary
  - Needs analysis results
  - Recommended products and **why** they were chosen
  - Alternatives considered and **why** they weren't chosen
  - Risks, limitations, and exclusions
  - Replacement policy analysis (if applicable)
  - Fee and commission disclosure
  - Adviser disclosure statement

**Step 6: Adviser reviews and approves**
- Adviser opens the draft in a simple web dashboard
- Can edit any section, adjust recommendations, add personal notes
- Once approved, the final SOA is generated as a branded PDF
- Optionally pushed back to Trail against the client's profile

---

## What You Get

| Feature | Description |
|---|---|
| **Trail Integration** | Connects directly to your Trail CRM via their API — no manual data entry |
| **AI-Powered Drafts** | Generates full SOA documents with personalised recommendation reasoning |
| **Product Database** | NZ insurance products from major insurers (AIA, Partners Life, Fidelity Life, etc.) |
| **Compliance Built-In** | Every SOA checked against FMA requirements before it's finalised |
| **Adviser Dashboard** | Clean web interface to review, edit, and approve SOAs |
| **Audit Trail** | Full logging of every generated document for FMA compliance |
| **Branded Output** | PDFs match your company branding — logo, colours, fonts |

---

## What Changes for Your Team

| Before | After |
|---|---|
| 3-5 hours per SOA | ~30 minutes (review + approval) |
| Manual data entry from Trail | Auto-pulled from Trail API |
| Product research across insurer websites | Pre-loaded product database |
| Formatting and compliance checking by hand | Automated compliance checks |
| Full-time salary dedicated to SOA writing | Staff redeployed to higher-value work |

---

## Data Privacy & Security

Your client data is sensitive. Here's how we handle it:

- **NZ Privacy Act 2020 compliant** — data only used for its intended purpose
- **Encrypted at rest and in transit** — all data secured with industry-standard encryption
- **AI processing** — client names and identifying details are anonymised before being sent to the AI engine. The AI never stores your client data.
- **Access control** — only authorised advisers can view client data and generated SOAs
- **Audit logging** — every action is logged for FMA audit readiness
- **7-year retention** — SOA records stored as required by FMA
- **Client consent** — we'll add a clause to your engagement agreement covering AI-assisted advice

---

## Tech Overview (Non-Technical)

- The system is a **web application** your team accesses via browser
- It talks to Trail through their **official API** (approved by Trail)
- Uses **AI (Claude by Anthropic)** to generate advice reasoning — the same type of AI used by major financial institutions globally
- Documents generated as **PDF** or **Word** files
- Hosted securely on cloud infrastructure

---

## Build Phases

### Phase 1 — Foundation (Week 1-2)
- Trail API connection
- Client data sync (profiles, contacts, fact finds, statement of position)
- Basic database setup

### Phase 2 — SOA Engine (Week 3-5)
- Needs analysis calculator
- Product database (initial set of major NZ insurers)
- AI recommendation engine
- SOA document template and generator
- Compliance validation

### Phase 3 — Dashboard & Polish (Week 6-7)
- Adviser review/edit dashboard
- Branding and PDF output
- Push completed SOA back to Trail
- Testing with real client scenarios

### Phase 4 — Go Live (Week 8)
- Final testing with Mat's team
- Training session
- Go live

---

## Ongoing Support

After launch:
- Product database updates as insurers change products/pricing
- Bug fixes and minor enhancements
- Trail API compatibility maintenance
- System monitoring and uptime

---

## What We Need From You

To get this right, we need a few things before we start building:

### 1. Your Current SOA Process (Priority)
Walk us through how your team currently produces an SOA from start to finish. Specifically:
- What does the step-by-step flow look like today?
- Where are the biggest time sinks?
- What does your team do in Trail vs outside of Trail (Word docs, spreadsheets, etc.)?
- Are there any steps that *must* stay manual (e.g., adviser sign-off, specific judgment calls)?

### 2. Sample SOA Documents
Send us 2-3 completed SOAs (client names redacted) so we can match:
- Your document structure and section ordering
- Tone and language style
- Branding (logo, colours, fonts)
- Any custom sections specific to your brokerage

### 3. Insurer Panel
Which insurers do you work with most? We'll prioritise loading their products first. For example:
- AIA
- Partners Life
- Fidelity Life
- Asteron Life
- Cigna / Chubb
- nib
- Others?

### 4. Trail API Access
Email **farran@gettrail.com** to get API access approved. Mention you're building an internal SOA automation tool that will connect via their API.

### 5. Team & Access
- How many advisers will use the system?
- Do assistants/paraplanners also need access?
- Any specific compliance sign-off process we should build in?

### 6. Edge Cases
- Do you handle policy replacements (switching a client from one insurer to another)? These have extra disclosure requirements.
- Do you advise on business insurance (key person, shareholder protection) or just personal?
- Any clients with non-standard situations we should know about (trusts, business owners, etc.)?

---

## Next Steps

1. **Mat sends through the info above** (process flow, sample SOAs, insurer list)
2. **Mat emails farran@gettrail.com** to get Trail API access
3. We review everything, confirm scope, and agree on timeline + pricing
4. Build begins

---

*Built by Benji*
