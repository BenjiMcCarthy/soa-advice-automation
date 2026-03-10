# SOA Automation Platform

### Intelligent Statement of Advice Generation for Insurance Brokerages

---

<br>

## Overview

Your team spends hours writing Statements of Advice — pulling data from Trail, researching products, drafting recommendations, formatting documents, and checking compliance. It's the single biggest admin bottleneck in your business.

We're building a system that connects directly to your Trail CRM, understands your client's situation, and produces a **complete, compliance-ready SOA draft in minutes** — not hours. Your advisers review, refine, and approve. That's it.

The person currently dedicated to SOA production gets freed up for higher-value work. Your advisers spend more time advising, less time writing.

<br>

---

<br>

## How It Works

<br>

### The Flow

```
┌─────────────┐     ┌──────────────────┐     ┌─────────────────┐     ┌──────────────┐
│             │     │                  │     │                 │     │              │
│  Trail CRM  │────▶│  SOA Engine (AI) │────▶│ Adviser Review  │────▶│  Final SOA   │
│             │     │                  │     │                 │     │              │
└─────────────┘     └──────────────────┘     └─────────────────┘     └──────────────┘
  Client data         Analyses needs           Edit, adjust,          Branded PDF
  Fact find           Matches products         approve/reject         saved to Trail
  Financials          Generates SOA
  Policies            Checks compliance
```

<br>

### Step by Step

| Step | What Happens | Time |
|:-----|:-------------|:-----|
| **1. Trigger** | Adviser selects a client and clicks "Generate SOA" | 10 sec |
| **2. Data Pull** | System pulls fact find, financials, existing policies, and dependents from Trail via API | ~5 sec |
| **3. Analysis** | AI analyses the client's situation — calculates cover needs, identifies gaps, assesses priorities | ~15 sec |
| **4. Product Match** | Searches NZ insurer product database, compares premiums, features, and exclusions | ~10 sec |
| **5. SOA Draft** | Full document generated — recommendations, reasoning, alternatives, disclosures, compliance sections | ~30 sec |
| **6. Adviser Review** | Adviser reviews the draft in a clean web dashboard, edits any section, adds personal notes | 15-30 min |
| **7. Finalise** | Approved SOA exported as branded PDF and saved back to the client's Trail profile | 10 sec |

**Total: ~30 minutes** (adviser review time) vs 3-5 hours today.

<br>

---

<br>

## The SOA Document

Every generated SOA includes all FMA-required sections:

| Section | Description |
|:--------|:------------|
| **Scope of Advice** | What the client asked for and what advice covers |
| **Client Objectives** | Goals, priorities, and concerns in the client's own words |
| **Current Situation** | Income, assets, liabilities, dependents, existing cover — pulled from Trail |
| **Needs Analysis** | Calculated cover requirements across life, trauma, TPD, income protection, medical |
| **Gap Analysis** | Visual comparison of current cover vs recommended cover |
| **Recommendations** | Specific products recommended with clear reasoning for each |
| **Alternatives Considered** | Products that were assessed but not recommended, and why |
| **Replacement Analysis** | If replacing existing cover — comparison, risks, and justification |
| **Risks & Limitations** | Exclusions, stand-down periods, and limitations the client should know |
| **Fee & Commission Disclosure** | Full transparency on how the adviser is remunerated |
| **Adviser Disclosure** | Licence details, complaints process, and regulatory information |

All formatted with your company branding — logo, colours, fonts, professional layout.

<br>

---

<br>

## Return on Investment

<br>

### The Numbers

| Metric | Current | With Automation |
|:-------|:--------|:----------------|
| **Time per SOA** | 3-5 hours | ~30 minutes |
| **SOAs per week** (estimate) | 5-8 | 5-8 |
| **Weekly hours on SOA work** | 15-40 hrs | 2.5-4 hrs |
| **Annual hours on SOA work** | 780-2,080 hrs | 130-208 hrs |
| **Hours saved per year** | — | **650-1,870 hrs** |

<br>

### Cost Savings

Assuming a full-time employee dedicated primarily to SOA production:

| | Annual Cost |
|:--|:-----------|
| **Current: FTE salary + overhead** | $65,000 - $85,000 |
| **SOA platform build (one-off)** | $18,000 - $22,000 |
| **Ongoing maintenance + support** | $9,000/year ($750/mo) |
| **Year 1 net saving** | **$34,000 - $54,000** |
| **Year 2+ annual saving** | **$56,000 - $76,000** |

<br>

### ROI Timeline

```
Month 1-2    ██████████░░░░░░░░░░  Build phase — platform in development
Month 3      ████████████████████  Go live — SOA automation active
Month 4-6    $$$$$$$$$$$$$$$$$$$$  Break-even on build cost reached
Month 7-12   $$$$$$$$$$$$$$$$$$$$  Pure savings — $4,500-6,300/month
Year 2+      $$$$$$$$$$$$$$$$$$$$  $56,000-76,000 annual saving
```

**Payback period: 3-5 months.** After that, it's straight savings every month.

<br>

### Beyond Cost Savings

| Benefit | Impact |
|:--------|:-------|
| **Faster turnaround** | Clients get their SOA same-day instead of waiting days |
| **Consistency** | Every SOA follows the same high standard — no variance between writers |
| **Compliance confidence** | Automated checks mean nothing gets missed before FMA audits |
| **Scalability** | Take on more clients without hiring more admin staff |
| **Staff redeployment** | SOA writer can focus on client relationships, renewals, or business development |

<br>

---

<br>

## Platform Features

<br>

| Feature | Detail |
|:--------|:-------|
| **Trail CRM Integration** | Direct API connection — pulls client data automatically, pushes completed SOAs back |
| **AI-Powered Generation** | Uses advanced AI (Claude by Anthropic) to analyse situations and generate personalised advice reasoning |
| **NZ Product Database** | Insurance products from major NZ insurers — premiums, features, exclusions, all searchable |
| **Adviser Dashboard** | Clean web interface to review, edit, and approve SOA drafts |
| **Compliance Engine** | Validates every SOA against FMA requirements before finalisation |
| **Branded PDF Export** | Professional documents matching your company branding |
| **Audit Trail** | Full logging of every generated document — who, when, what was changed |
| **Role-Based Access** | Advisers, paraplanners, and admins each see only what they need |

<br>

---

<br>

## Data Privacy & Security

Insurance SOAs contain highly sensitive personal information. We take this seriously.

| Area | Approach |
|:-----|:---------|
| **NZ Privacy Act 2020** | Fully compliant — data used only for its stated purpose |
| **Encryption** | All data encrypted at rest (AES-256) and in transit (TLS 1.3) |
| **AI Processing** | Client identifying details are anonymised before AI processing. No client data is stored by the AI provider. |
| **Access Control** | Role-based permissions — only authorised users access client data |
| **Audit Logging** | Every action logged with timestamp and user — FMA audit-ready |
| **Data Retention** | 7-year SOA retention as required by FMA regulations |
| **Client Consent** | Clause added to your engagement agreement covering AI-assisted advice preparation |
| **Hosting** | Hosted on secure cloud infrastructure with NZ/AU data residency |

<br>

---

<br>

## Build Timeline

| Phase | Weeks | Deliverables |
|:------|:------|:-------------|
| **Phase 1 — Foundation** | 1-2 | Trail API integration, client data sync, database setup |
| **Phase 2 — SOA Engine** | 3-5 | Needs analysis, product database, AI recommendation engine, document generator, compliance checks |
| **Phase 3 — Dashboard** | 6-7 | Adviser review interface, branding, PDF export, Trail sync |
| **Phase 4 — Launch** | 8 | Testing with real scenarios, team training, go live |

<br>

---

<br>

## What We Need From You

To build this right, we need a few things upfront:

<br>

### 1. Your Current Process
Walk us through how your team produces an SOA today, start to finish:
- What's the step-by-step flow?
- Where are the biggest time sinks?
- What happens inside Trail vs outside Trail (Word, spreadsheets, etc.)?
- Which steps must stay manual (adviser judgment calls, specific sign-offs)?

### 2. Sample SOA Documents
2-3 completed SOAs (client names redacted) so we can match:
- Document structure and section ordering
- Tone and language style
- Branding (logo, colours, fonts)
- Any custom sections specific to your brokerage

### 3. Insurer Panel
Which insurers do you primarily work with? We'll load these first:
- AIA, Partners Life, Fidelity Life, Asteron Life, Cigna/Chubb, nib, others?

### 4. Trail API Access
Email **farran@gettrail.com** to request API access. Mention you're building an internal automation tool that connects via their official API.

### 5. Team Details
- How many advisers will use the system?
- Do paraplanners or assistants also need access?
- Any specific internal sign-off or compliance review process?

### 6. Edge Cases
- Do you handle policy replacements (switching insurers)? Extra disclosure required.
- Personal insurance only, or also business (key person, shareholder protection)?
- Non-standard client situations — trusts, business owners, partnerships?

<br>

---

<br>

## Next Steps

| # | Action | Who |
|:--|:-------|:----|
| 1 | Review this proposal and send through the info listed above | Mat |
| 2 | Email farran@gettrail.com for Trail API access | Mat |
| 3 | Confirm scope, timeline, and pricing | Both |
| 4 | Build begins | Benji |

<br>

---

<br>

<p align="center"><em>Built by Benji McCarthy</em></p>
