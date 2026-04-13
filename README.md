# Wait — Copilot can do that?

An interactive booth activity for **Transformation Day 2026**, designed to showcase the practical capabilities of Microsoft Copilot across the M365 suite.

---

## What this is

A single-page web app that runs a hands-on guessing game at an event booth. Participants are shown a polished, realistic output — a document, spreadsheet, deck, email, or meeting recap — and challenged to figure out two things:

1. **Which Microsoft app** produced it?
2. **What prompt** was used to generate it?

They can then open Copilot on a nearby device, type in a prompt, and see whether they can recreate it. The twist: every output was generated not from a prompt alone, but from a prompt combined with real reference files — just like the files that already exist inside any organisation.

---

## The main takeaway

> *Every output in this activity was produced by combining a clear prompt with real source material that already existed inside the organisation. No challenge required Copilot to make things up or work from scratch.*

The pattern is always the same:

**Identify the task → gather the relevant files → write a specific prompt → let Copilot synthesise**

The expertise that makes the output useful is yours. The hours it saves are Copilot's contribution. That is what working smarter looks like in practice.

---

## How the activity works

| Step | What participants do |
|------|----------------------|
| **Pick a mystery output** | Hit *Start Challenge* to be randomly assigned one of 8 outputs, or tap an app name to jump to a specific one |
| **Study the output** | Read the output carefully — what type of document is it? What clues does it contain? |
| **Try the multiple choice** | Two questions: which app made it, and which prompt produced it — with instant feedback and explanations |
| **See the answer** | The reveal section (unlocked after answering both questions) shows the app used, the exact prompt, and why the output is impressive |
| **Try it yourself** | Copy the prompt, open Copilot on a nearby device, and see what you get |

---

## Page structure

### Landing page
- **Hero section** — title, activity description, and *Start Challenge* button
- **How it works** — three-step guide: pick an output, make your case, face the truth
- **The Suspects** — app filter buttons (Word, Excel, PowerPoint, Teams, Outlook, Copilot Notebook) to jump directly to a challenge for that app

### Challenge pages (×8)
Each challenge page contains four sections:

1. **Mystery output** — a realistic simulation of Copilot-generated content (document, spreadsheet, deck, chat message, or email)
2. **Reference files** — the source documents that were uploaded alongside the prompt
3. **Multiple choice quiz** — two questions with instant feedback; the reveal section is hidden until both are answered
4. **The answer** — app used, difficulty, the exact prompt (with one-click copy), bullet points on why the output is impressive, and a key takeaway

---

## The 8 challenges

| # | App | Difficulty | Output | Prompt used |
|---|-----|------------|--------|-------------|
| 1 | Word | Easy | New employee onboarding guide for Apex Corporate Solutions, synthesised from three source documents in different formats | *"I have three files — a welcome letter, an IT setup guide, and a culture deck. Synthesise all of them into a single, well-structured onboarding guide for a new employee joining Apex Corporate Solutions."* |
| 2 | Excel | Medium | Department budget tracker showing budgeted vs actual spend, variance, and overspend flags across Q1 2025 | *"Based on this data, create a monthly budget tracker by department showing budgeted vs actual spend, variance, and a flag for any category that has overspent by more than 10%."* |
| 3 | Excel | Hard | Written sales performance analysis for FY2023 — deliberately styled to look like a Word document, generated in Excel's Sheet 2 | *"Analyse this sales data. Identify the top 3 performing regions, flag any months with more than 15% drop in revenue, and summarise the key trends."* |
| 4 | PowerPoint | Easy | 5-section deck on the business case for hybrid working, combining external research and internal survey data | *"I have three files — an academic study, a consulting research digest, and our own staff survey. Synthesise them into a 5-section deck on the benefits of hybrid working, using both external evidence and our internal data."* |
| 5 | PowerPoint | Hard | Detailed talking points for a 10-minute senior leadership address on digital transformation — generated in Notes view, contains no slide structure | *"Based on these three files, generate detailed talking points for a 10-minute address to senior leadership on our digital transformation strategy."* |
| 6 | Teams | Medium | Full meeting recap posted to a Teams channel — including decisions and action items sourced from pre-meeting emails, the live transcript, and a post-meeting chat log | *"Summarise this meeting and the related communications. List the key decisions made, and provide all action items with owners and due dates."* |
| 7 | Outlook | Medium | Professional reply to a client complaint email, grounding specific commitments in internal documents while explicitly withholding confidential detail | *"Draft a professional reply to this client complaint. Acknowledge the delay, apologise sincerely, give a firm revised delivery date, and outline three specific steps we are taking. Do not reference any internal documents."* |
| 8 | Copilot Notebook | Hard | Structured AI productivity briefing for Apex, synthesising 6 sources across 3 files — academic papers, corporate reports, and an internal pulse survey — with inline citations | *"Using these three files — academic research, corporate reports, and our own internal survey — create a structured briefing on AI and office productivity with sections on: Overview, Key Benefits, Risks and Concerns, and Recommended Next Steps for our organisation."* |

---

## Reference files

### Challenge 1 — Word (Easy)
| File | Description |
|------|-------------|
| `Welcome_Letter.docx` | HR welcome letter covering culture, values, and first-day logistics |
| `IT_Setup_Quickstart_Guide.pdf` | IT setup checklist covering device collection, account activation, MFA, VPN, and security training |
| `Culture_Deck_Talking_Points.pptx` | New joiner orientation talking points covering values, working norms, facilities, and support networks |

### Challenge 2 — Excel (Medium)
| File | Description |
|------|-------------|
| `Raw_Dept_Spend_Q1_2025.csv` | 63 rows of raw expenditure data across 5 departments and 3 months, with columns for cost centre, category, vendor, PO number, approver, and notes |

### Challenge 3 — Excel (Hard)
| File | Description |
|------|-------------|
| `Sales_Raw_Data_FY2023.csv` | 60 rows of unprocessed sales transactions across 5 regions, 5 salespeople, 4 product categories, and 12 months — including units sold, pricing, returns, channels, and discounts |

### Challenge 4 — PowerPoint (Easy)
| File | Description |
|------|-------------|
| `Bloom_et_al_2024_Nature_Article.docx` | Full academic article from Nature (2024) reporting a 6-month randomised trial on hybrid working — productivity, retention, and job satisfaction findings |
| `McKinsey_HBS_Hybrid_Research.pdf` | McKinsey's global analysis of office attendance patterns and an HBS field experiment on how in-office days affect output novelty and collaboration |
| `Apex_Staff_Survey_Q4_FY2024.csv` | Internal pulse survey of 287 Apex employees on hybrid working attitudes, satisfaction scores by department, and preferred working arrangements |

### Challenge 5 — PowerPoint (Hard)
| File | Description |
|------|-------------|
| `Board_Strategy_Briefing_Talking_Points.pptx` | Board talking points covering strategic rationale, three pillars, financial summary, and governance for the FY2025–2027 transformation programme |
| `Digital_Readiness_Diagnostic_Report.docx` | Internal diagnostic report covering process fragmentation, data silo risks, AI readiness gaps, technology debt, and change readiness scores by department |
| `Leadership_Email_Thread_March2025.pdf` | Email exchange between five senior leaders discussing AI rollout priorities, Finance migration concerns, the AI Champions programme design, and Q2 planning |

### Challenge 6 — Teams (Medium)
| File | Description |
|------|-------------|
| `Pre_Meeting_Email_Thread.pdf` | Pre-meeting email exchange including the agenda and issues flagged for discussion |
| `Meeting_Transcript_8Apr2025.txt` | Full verbatim transcript of the Q3 Planning & Budget Review meeting (6 attendees) |
| `Post_Meeting_Chat_Log.txt` | Post-meeting chat confirming vendor decisions, revised scope, licence costs, and headcount next steps — some action items only finalised here |

### Challenge 7 — Outlook (Medium)
| File | Description |
|------|-------------|
| `Client_Complaint_Email_Hartley.msg` | Formal complaint from Pine Street Group's COO demanding acknowledgement of a project delay, a revised schedule, and senior escalation |
| `Internal_Escalation_Email_JasonOng.msg` | Internal email from the project manager explaining root causes and the revised internal delivery timeline — not intended for the client |
| `Project_Phoenix_Briefing_Note.docx` | Internal briefing note covering contract value, penalty clause exposure, client relationship context, and recommended tone for the response |

### Challenge 8 — Copilot Notebook (Hard)
| File | Description |
|------|-------------|
| `Academic_Research_Articles.docx` | Two academic articles: a QJE study on generative AI's productivity impact on customer support agents (14–34% gains) and a St. Louis Fed paper on AI adoption rates and time savings |
| `Corporate_Research_Reports.pdf` | Three corporate reports: Microsoft's 2024 Work Trend Index on AI adoption and BYOAI risk, and two McKinsey reports on generative AI economic value and agentic AI |
| `Apex_AI_Pulse_Survey_Q1FY2025.xlsx` | Internal survey of 287 Apex staff covering AI tool usage, confidence levels, ungoverned usage risks, and an estimated 8.65 hours/week of automatable tasks per person |

---

## Technical notes

- Single HTML file — no build step, no dependencies, no server required. Open directly in a browser.
- All 8 challenges are pre-rendered in the page; JavaScript handles navigation between them.
- The answers section on each challenge is hidden until both multiple choice questions have been answered.
- The prompt on each challenge's answer card has a one-click copy button.
- Layout is responsive — optimised for fullscreen on a 24" monitor, scales down to tablet using fluid `clamp()` sizing and a responsive grid.
