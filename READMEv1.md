# Wait — Copilot can do that?

An interactive booth activity for **Transformation Day 2026**, designed to showcase the practical capabilities of Microsoft Copilot across the M365 suite.

---

## What this is

A single-page web app that runs a hands-on guessing game at an event booth. Participants are shown a polished, realistic output — a document, spreadsheet, deck, email, meeting recap, or briefing — and challenged to figure out two things:

1. **Which Microsoft app** produced it?
2. **What prompt** was used to generate it?

Every output was generated not from a prompt alone, but from a prompt combined with real reference files — just like the files that already exist inside any organisation.

---

## The main takeaway

> *Every challenge here follows the same pattern: a clear prompt, your M365 data, and Copilot doing the synthesis. The expertise that makes the output useful is yours — the hours it saves are Copilot's contribution.*

---

## How the activity works

| Step | What participants do |
|------|----------------------|
| **The mystery** | Hit *Start Challenge* to be randomly assigned one of 8 outputs — or tap an app name to jump to a specific challenge |
| **Your verdict** | Answer two multiple choice questions: which app made it, and which prompt produced it — with instant feedback |
| **Face the truth** | The reveal shows the app, the exact prompt, why it's impressive, and step-by-step instructions to try it on Copilot themselves |

---

## Page structure

### Landing page
- **Hero section** — title, tagline, and *Start Challenge* button
- **How it works** — three steps: The mystery / Your verdict / Face the truth
- **The Suspects** — app buttons (Word, Excel, PowerPoint, Teams, Outlook, Copilot Notebook) to jump directly to a challenge for that app

### Challenge pages (×8)
Each challenge page contains three sections:

1. **Mystery output** — a realistic simulation of Copilot-generated content (document, spreadsheet, deck, email, meeting recap, or briefing)
2. **Multiple choice quiz** — two questions with instant feedback; the reveal section is hidden until both are answered
3. **The answer** — app used, difficulty rating, the exact prompt (with one-click copy), bullet points on why the output is impressive, a key takeaway, step-by-step instructions to try it yourself, and the reference files required

---

## The 8 challenges

| # | App | Difficulty | Output | Prompt used |
|---|-----|------------|--------|-------------|
| 1 | Word | Easy | New employee onboarding guide for Apex Corporate Solutions, synthesised from three source documents in different formats | *"Synthesise these three files into a concise new employee onboarding guide in bullet form, within 1–2 pages. Include sections on culture, IT setup, key contacts and first-week tips."* |
| 2 | Excel | Medium | Department budget tracker showing budgeted vs actual spend, variance, and overspend flags across Q1 2025 | *"Based on this data, create a monthly budget tracker by department showing budgeted vs actual spend, variance, and a flag for any category that has overspent by more than 10%."* |
| 3 | Excel | Hard | Written survey analysis report — deliberately styled to look like a Word document, generated in Excel's Sheet 2 | *"Analyse this survey data. Identify the top 3 areas of strongest agreement, flag any items where disagreement is significant as items warranting attention and note what each signals for the organisation, and summarise the key themes from the open responses."* |
| 4 | PowerPoint | Hard | 5-section deck on the business case for hybrid working, synthesising external academic research and internal survey data | *"Create a 5-section deck on the benefits of hybrid working covering: an opening, external research evidence, internal survey findings, key benefits of hybrid working, and recommendations."* |
| 5 | Copilot Notebook | Hard | Detailed talking points for a 10-minute senior leadership address on digital transformation — five structured sections of spoken-word content | *"Generate detailed talking points for a 10-minute address to senior leadership on our digital transformation strategy."* |
| 6 | Teams | Medium | Full meeting recap including decisions and action items sourced from pre-meeting emails, the live transcript, and a post-meeting chat log | *"Summarise this meeting and the related communications. List the key decisions made, and provide all action items with owners and due dates."* |
| 7 | Outlook | Medium | Professional reply to a client complaint, grounding specific commitments in internal documents while explicitly withholding confidential detail | *"Project Phoenix — draft a professional reply to this client complaint. Acknowledge the delay, apologise sincerely, and address each of their four requests directly: root cause, a firm revised delivery date, steps to prevent recurrence, and senior escalation. Draw on the internal documents for context, but do not name, cite, or quote from them in the reply."* |
| 8 | Copilot Notebook | Hard | Structured AI productivity briefing for Apex, synthesising two academic papers, a corporate research report, and an internal pulse survey — with inline citations | *"Using all four uploaded files — two academic research papers, a corporate research report, and our own internal AI pulse survey — create a structured briefing on AI and office productivity for Apex with sections on: Overview, Key Benefits, Risks and Concerns, and Recommended Next Steps."* |

---

## Reference files

### Challenge 1 — Word (Easy)
| File | Description |
|------|-------------|
| `REF 1A Welcome Letter.docx` | HR welcome letter covering culture, values, and first-day logistics |
| `REF 1B IT Onboarding Quickstart Guide.pdf` | IT setup checklist covering device collection, account activation, MFA, VPN, and security training |
| `REF 1C Culture Deck.pptx` | New joiner orientation talking points covering values, working norms, facilities, and support networks |

### Challenge 2 — Excel (Medium)
| File | Description |
|------|-------------|
| `REF 2 Multi Dept Raw Budget Data.xlsx` | 66 rows of raw expenditure data across 5 departments and 3 months, with columns for cost centre, sub-category, vendor, PO number, approver, and notes |

### Challenge 3 — Excel (Hard)
| File | Description |
|------|-------------|
| `REF 3 Internal Staff Survey Results.xlsx` | Apex staff pulse survey on hybrid working — 287 respondents across 5 departments, covering 10 Likert-scale questions, department satisfaction scores, and open-response themes |

### Challenge 4 — PowerPoint (Hard)
| File | Description |
|------|-------------|
| `REF 4A Bloom et al (2024) Nature How hybrid working from home works out.pdf` | Full academic article from Nature (2024) reporting a 6-month randomised trial on hybrid working — productivity, retention, and job satisfaction findings |
| `REF 4B McKinsey (2023) Empty spaces and hybrid places.pdf` | McKinsey's global analysis of office attendance patterns and the economics of hybrid working |
| `REF 4C Choudhury (2022) HBS Hybrid Work the Best of Both Worlds.pdf` | HBS field experiment on how in-office days affect output novelty, collaboration, and career outcomes |
| `REF 4D Internal Staff Survey Results.xlsx` | Apex internal hybrid work survey (Q4 FY2024) — 287 respondents across five departments, covering satisfaction scores, productivity impact, and retention intent |

### Challenge 5 — Copilot Notebook (Hard)
| File | Description |
|------|-------------|
| `REF 5A Board Strategy Presentation.pptx` | Board talking points covering strategic rationale, three pillars, financial summary, and governance for the FY2025–2027 transformation programme |
| `REF 5B Digital Readiness Diagnostic Report.docx` | Internal diagnostic report covering process fragmentation, data silo risks, AI readiness gaps, and change readiness scores by department |
| `REF 5C Leadership Email Thread.msg` | Internal email exchange between senior leaders discussing AI rollout priorities, Finance migration concerns, and the AI Champions programme design |

### Challenge 6 — Teams (Medium)
| File | Description |
|------|-------------|
| `REF 6A Pre-Meeting Email Thread.msg` | Pre-meeting email exchange including the agenda and issues flagged for discussion |
| `REF 6B Meeting Transcript.msg` | Full verbatim transcript of the Q3 Planning & Budget Review meeting (5 attendees) |
| `REF 6C Post-Meeting Chat Log.msg` | Post-meeting chat confirming vendor decisions, revised scope, licence costs, and action items — some only finalised after the meeting ended |

### Challenge 7 — Outlook (Medium)
| File | Description |
|------|-------------|
| `REF 7A Customer Complaint.msg` | Formal complaint from Pine Street Group's COO demanding acknowledgement of a project delay, a revised schedule, and senior escalation — with a response deadline of Wednesday 9 April |
| `REF 7B Internal Coord.msg` | Internal email thread: the project manager flags root causes and revised delivery estimate; the senior leader replies with instructions on how to handle the complaint — not intended for the client |

### Challenge 8 — Copilot Notebook (Hard)
| File | Description |
|------|-------------|
| `REF 8A Generative AI at Work.pdf` | NBER working paper (Brynjolfsson, Li & Raymond, 2023) — randomised study of 5,179 customer support agents reporting 14–34% productivity gains from AI assistance |
| `REF 8B Generative AI FRBSL.pdf` | St. Louis Fed article (2025) summarising Bick et al. research on AI adoption rates — approximately 40% of the US working-age population within two years, and average 5.4% time savings per worker |
| `REF 8C 2024 Work Trend Index Annual Report.pdf` | Microsoft's 2024 Work Trend Index — 75% of knowledge workers use AI, 78% bring their own tools to work, and 60% of leaders say their organisation lacks a plan |
| `REF 8D Apex AI Pulse Survey.xlsx` | Apex internal AI readiness survey (Q1 FY2025, n=287) — confidence scores by department, top use cases, estimated 8.65 automatable hours per staff member per week, and barriers to adoption |

---

## Technical notes

- Single HTML file — no build step, no dependencies, no server required. Open directly in a browser.
- All 8 challenges are pre-rendered in the page; JavaScript handles navigation between them.
- The reveal section on each challenge is hidden until both multiple choice questions have been answered.
- The prompt on each challenge's answer card has a one-click copy button.
- Layout is responsive — optimised for fullscreen on a large monitor, scales down to tablet and mobile using fluid `clamp()` sizing.
- Copilot Notebook challenges (5 & 8) have a collapsible References sidebar on mobile — hidden by default, expandable via a toggle button.
