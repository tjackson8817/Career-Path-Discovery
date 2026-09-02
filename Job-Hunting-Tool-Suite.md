**Sale Fish Marketing and Consulting**

**Job Hunting Tool Suite**

User Guide

*A Getting Started walkthrough, plus a detailed guide to all ten
tools*

Live Suite URL (click below):

[<u>https://tjackson8817.github.io/Job-Hunting-Tool-Suite/</u>](https://tjackson8817.github.io/Job-Hunting-Tool-Suite/)

Created By: Tom Jackson

August 10, 2026 (Target Company Prompt Builder section updated August
11-12, 2026 for its Bulk Company Pull step, competitor-cascade discovery
method, and NAICS-search reference link, and August 13, 2026 to remove
the Templates feature (session-only saving was confusing users into
thinking it persisted); Outreach Message Builder and Recruiter Message
Sanity Check sections updated August 12, 2026 for Message Goal/Context
Notes and the new Job Posting mode, respectively; Interview Prep Guide
Builder added as Step 4 and Steps 3a/3b renumbering applied August 12,
2026; Salary Negotiator added as Step 5 August 12-13, 2026; Career Path
Discovery Prompt Builder added as Step 0 August 17, 2026, with Pivot
Positioning Notes added to Resume & Cover Letter Tailoring and Objection
Reframing added to Interview Prep Guide Builder the same day; LinkedIn
Profile Builder added as a third ongoing tool August 17, 2026; Target
Company Prompt Builder section updated August 18, 2026 to add the
Department Contact Finder step; Interview Prep Guide Builder section
updated September 1, 2026 to add the Candidate SWOT Analysis and the
optional STAR Stories field)

> **Before You Start — One Claude Setting**
>
> In Claude, go to **Settings → Capabilities** and toggle **"Code execution and file creation"** on. This is what lets Claude actually build the Excel or Word file a tool asks for, instead of just describing it in the chat. Available on Free, Pro, Max, Team, and Enterprise plans — on web, desktop, and mobile. (Web search is the other setting you'll need; see the full settings table below.)

## What This Suite Is

This is a set of ten free, standalone web tools that turn a job search
— or just staying visible in your field, or protecting yourself from
scams while you search — into a repeatable process instead of a blank
page every time. Seven of them cover the job-search funnel end to end:
figuring out which direction to target if you're not sure yet, finding
and ranking the right companies, checking who’s actually hiring right
now, tailoring a resume and cover letter to a real posting, drafting the
outreach messages to actually reach someone, building a real prep guide
once an interview actually lands, and negotiating the actual offer once
one comes in. The remaining three are ongoing tools, independent of
where you are in the funnel: one optimizes your LinkedIn profile itself
for the job search, another finds and drafts on-brand articles to keep
you visible on LinkedIn, and the third screens incoming recruiter
messages or job postings for known scam patterns, since fake recruiter
outreach and fake job listings have both become common.

Eight of the ten tools work the same simple way: you fill in a short
form on a web page, it builds a complete, ready-to-use prompt, you copy
that prompt into a conversation with Claude, and Claude does the actual
research, writing, or drafting. The tenth — Recruiter Message & Job
Posting Sanity Check — is different on purpose: it runs the entire check
in your browser and hands you a finished result immediately, with no
separate Claude conversation required.

**Disclaimer:** These tools are aids, not authorities. The nine
prompt-building tools hand off to Claude for the actual research,
writing, or drafting — review every output before relying on it, since
researched facts (company details, job postings, interviewer
backgrounds, salary data, and similar) can be incomplete, outdated, or
wrong. The Recruiter Message & Job Posting Sanity Check is a
pattern-matching screen only; it cannot verify anyone’s identity, a
company’s legitimacy, or a listing’s legitimacy, and neither a clean nor
a flagged result is a final answer. Treat every result across the suite
as a starting point for your own judgment, not a substitute for it.

## Getting Started

## The Two Workflows

Everything in this suite falls into one of two groups, and it helps to
know which before you open anything:

- **The 7-step funnel (Steps 0–5):** Career Path Discovery Prompt
  Builder (Step 0, Discover) is optional and comes first only if you
  need it — skip straight to Step 1 if you already know your target.
  Target Company Prompt Builder (Step 1, Research) is where the funnel
  actually starts for most people — everything downstream depends on the
  ranked tracker it produces. Job Posting Finder (Step 2, Verify) needs
  that tracker’s Suggested Priority Rank to know which companies are
  worth searching. Resume & Cover Letter Tailoring (Step 3a) and
  Outreach Message Builder (Step 3b) — both Apply/Connect — have no
  fixed order between them — network first and tailor your resume once a
  real opening exists, or find a posting first and tailor immediately,
  then follow up with outreach. Both are legitimate. Interview Prep
  Guide Builder (Step 4, Interview) comes after Step 3 actually lands an
  interview, whichever path got you there. Salary Negotiator (Step 5,
  Negotiate) comes after Step 4 actually produces an offer — it’s the
  direct sequel to the salary-range coaching in Interview Prep’s
  Recruiter Screen mode, for once a real number is on the table.

- **The 3 ongoing tools:** LinkedIn Profile Builder (optimizing your
  profile itself for the job search), LinkedIn Article Share Builder
  (staying visible), and Recruiter Message & Job Posting Sanity Check
  (screening incoming messages or postings) aren’t steps in the funnel —
  use them any time, whether or not you’re actively job hunting.

## How Eight of the Ten Tools Work

Every tool except Recruiter Message & Job Posting Sanity Check follows
the identical mechanical pattern, so it’s worth understanding once
rather than per tool:

- Open the tool’s .html file in any browser — no install, no account.
  Fill in a short form.

- The tool assembles a complete, detailed prompt entirely in your
  browser as you type — nothing you enter is sent anywhere.

- Click Copy prompt (or Download .txt), then paste it into a new Claude
  conversation.

- Claude executes the actual work — live web research, writing, or
  file-building — and returns the result in that conversation.

- Review the result before relying on it. Every generated prompt
  includes an explicit "execute this directly, don’t ask clarifying
  questions first" instruction, aimed at heading off tools (e.g.
  ChatGPT) that sometimes respond with a plan or questions instead of
  just running the task.

*Recruiter Message & Job Posting Sanity Check breaks this pattern on
purpose — it runs the entire scan client-side and shows you a finished,
scored result immediately. No prompt, no Claude conversation, no
waiting.*

## Claude Settings You’ll Need

Two Claude capabilities cover every requirement across all ten tools —
check this once rather than hunting per tool:

| **Setting**                      | **Needed For**                                                                                                                                                                                                                                                                                                                                                   | **Where to Find It**                                                                                                                                         |
|----------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Web search                       | Job Posting Finder (always), LinkedIn Article Share Builder (always), Target Company Prompt Builder (for live research), Interview Prep Guide Builder (for company/interviewer/salary research), Salary Negotiator (for market and company-specific compensation research, always), Resume & Cover Letter Tailoring (only if recruiter identificatio is left on), Career Path Discovery Prompt Builder (recommended, not required — for checking current role and salary norms), LinkedIn Profile Builder (recommended, not required — for researching current in-demand skills) | Click the + (or slider) icon in the chat input, find Web search, toggle it on. Team/Enterprise accounts may need an admin to enable it workspace-wide first. |
| Code execution and file creation | Any tool where you choose an Excel or Word document output (Target Company Prompt Builder, Resume & Cover Letter Tailoring, Outreach Message Builder, Interview Prep Guide Builder, Salary Negotiator, Career Path Discovery Prompt Builder if Word document output is chosen), plus LinkedIn Article Share Builder if artwork generation is on, plus LinkedIn Profile Builder if the profile banner images are on or if Downloadable Word document output is chosen                                                                                          | Settings → Capabilities, toggle it on.                                                                                                                       |
| Neither                          | Recruiter Message & Job Posting Sanity Check — it never leaves your browser                                                                                                                                                                                                                                                                                      | N/A — nothing to enable                                                                                                                                      |

## Your First Run

If this is your first time through the suite, here’s the fastest path to
a genuinely useful result:

- Have ready: your target industry or a few companies you already know,
  your resume text, and (optionally) a LinkedIn contacts export if you
  want warm-introduction matching later.

- Not sure what to target yet? Start with Career Path Discovery Prompt
  Builder instead — it analyzes your real background and surfaces
  realistic alternative paths, then points you back to Step 1 once
  you've picked one. Already know your target? Skip straight to the next
  bullet.

- Start with Target Company Prompt Builder. Fill in your starting point
  and purpose, generate the prompt, run it in Claude with Web search on,
  and save the resulting tracker.

- Open that tracker and look at the Suggested Priority Rank column —
  that’s your shortlist for everything downstream.

- Take your top companies into Job Posting Finder to see who’s actually
  hiring right now. Standard mode (title-driven search, the default)
  works best at 15 companies or fewer; if you’re hunting Director-level
  or above, turn on Senior/Executive Search instead — it runs a fast
  broad Triage pass first (up to ~30 companies), then a focused Deep
  Dive on the 5 or fewer companies worth the real effort.

- For a company with a real, current opening, use Resume & Cover Letter
  Tailoring (Step 3a) on that specific posting, and/or Outreach Message
  Builder (Step 3b) to reach out using the Key Contact and Warm
  Introduction Path your tracker already found.

- Once an interview actually lands, use Interview Prep Guide Builder
  (Step 4) — pick whichever of its three modes matches the interview
  you’re prepping for.

- Once a real offer actually comes in, use Salary Negotiator (Step 5) —
  give it the offer details you actually have, and only fill in a
  competing offer if you genuinely have one.

- Whenever your LinkedIn profile itself needs work, or you want to post
  something, or a recruiter message or job posting looks off, the three
  ongoing tools are there independent of where you are in the funnel
  above.

## Quick Reference

| **Tool**                                         | **Step**                | **Description**                                                                                                                                                                                                                                                                                                                                                                                                                                                | **Output**                                                                      | **Key Claude Setting**                                           |
|--------------------------------------------------|-------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|------------------------------------------------------------------|
| **Career Path Discovery Prompt Builder**         | Step 0 · Discover       | Optional, for when you're not sure what to target yet. Analyzes your real career background like a strategist and executive recruiter would, and surfaces alternative paths (1-4 by default, adjustable) — ranked on transferability, credibility, comp potential, and more — pointing you to Step 1 once you've picked one.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Prompt → paste into Claude → ranked paths (chat, or downloadable Word doc)                  | Web search recommended, not required                             |
| **Target Company Prompt Builder**                | Step 1 · Research       | Four linked prompts on one page: an optional wide-net **Bulk Company Pull** (cheap, flat candidate list to prune by hand), the main **Full Research Tracker** (researches and ranks companies via a competitor-cascade discovery method — not NAICS-code search; builds a formatted Excel tracker, 31–36 columns, with a computed Suggested Priority Rank; optional manual two-tier output), **LinkedIn Contact Enrichment** for warm introduction paths, and **Department Contact Finder** for named, tier-ranked contacts at a company via live web search. | Prompt(s) → paste into Claude → .xlsx tracker (+ optional flat bulk-pull .xlsx / department-contacts .xlsx) | Web search; Code execution for the .xlsx                         |
| **Job Posting Finder**                           | Step 2 · Verify         | Finds real, current job postings — real titles, real URLs. Standard mode (default) title-searches up to 15 companies at once; Senior/Executive Search mode instead runs a broad Triage pass (~30 companies, status only) then a verified 5-company Deep Dive. Every mode now verifies any promising lead by direct link check before reporting it, and auto-flags KPMG/Accenture/EY leads as needing extra scrutiny.                                           | Prompt → paste into Claude → postings table or .xlsx                            | Web search (required); Code execution if .xlsx chosen            |
| **Resume & Cover Letter Tailoring**              | Step 3a · Apply/Connect | Tailors your actual resume and cover letter to one posting — keyword gap analysis, bullet rewrites, traditional letter and/or a two-column Qualifications Match Letter, plus optional Pivot Positioning Notes for a genuine career-direction change. Can also produce an updated resume with the suggestions actually applied.                                                                                                                                                                                                              | Prompt → paste into Claude → tailored documents                                 | Web search if recruiter ID is on; Code execution if .docx chosen |
| **Outreach Message Builder**                     | Step 3b · Apply/Connect | Drafts the actual outreach messages — tailored per company, per stage of the relationship (first outreach, follow-up, thank-you, staying in touch), from your real Warm Introduction Path and Target Audience, never one generic template swapped with a name.                                                                                                                                                                                                 | Prompt → paste into Claude → draft messages                                     | Code execution only if .docx chosen                              |
| **Interview Prep Guide Builder**                 | Step 4 · Interview      | Three modes — Recruiter Screen, Hiring Manager Interview, General/Other — each with genuinely different fields and content, not just a depth adjustment. Builds a real, grounded prep guide from your resume and the job description, including honest Objection Reframing for any concerns you name and a Candidate SWOT Analysis with weakness-mitigation talking points (Hiring Manager and General/Other modes); never writes your actual behavioral stories or invents detail about a named interviewer — will use your own STAR Stories as-given if you provide them.                                                                                                                                                 | Prompt → paste into Claude → prep guide (table or .docx)                        | Web search; Code execution if .docx chosen                       |
| **Salary Negotiator**                            | Step 5 · Negotiate      | Turns a real offer, sourced market and company-specific compensation data, and your real qualifications into an actual negotiation plan and counter-offer draft. Never invents or exaggerates a competing offer — leaving that field blank is the honest default, not a weaker use of the tool.                                                                                                                                                                | Prompt → paste into Claude → negotiation guide (table or .docx)                 | Web search; Code execution if .docx chosen                       |
| **LinkedIn Profile Builder**                     | Ongoing · Profile       | Optimizes your headline, About section, experience, and skills for the job search specifically — recruiter-searchable, ATS-ready, built around LinkedIn's real character limits. For mid-level and upper-level managers. Skills are researched against real current demand, never a canned list; every quantified bullet uses a real number or falls back to a strong qualitative one.                                                                                                                                                                                                                                                                                                                                                                                                                                              | Prompt → paste into Claude → profile text (+ optional .png banners)             | Web search recommended, not required; Code execution if banners or Word doc output chosen |
| **LinkedIn Article Share Builder**               | Ongoing · Brand         | Finds the 5 most on-brand, recent, real articles — ranked automatically — drafts the post for whichever you pick, and optionally builds matching artwork.                                                                                                                                                                                                                                                                                                      | Prompt → paste into Claude → post copy (+ optional .png)                        | Web search (required); Code execution if artwork is on           |
| **Recruiter Message & Job Posting Sanity Check** | Ongoing · Safety        | Screens a recruiter message OR a job posting (pick a mode) against known scam patterns in-browser — flags unnamed intermediaries, upfront fees, reshipping/payment-processing scams, employer mismatches, AI-generated photos, and more, plus a mode-appropriate follow-up (a reply draft for messages, a pre-application checklist for postings) on borderline results.                                                                                       | Finished result immediately — no Claude chat needed                             | None — runs entirely client-side                                 |

## 0. Career Path Discovery Prompt Builder

**STEP 0 · DISCOVER (OPTIONAL)**

For when you're not sure what to target yet — every other tool in the
suite assumes you already know the role you're chasing. Paste your
career background, and the generated prompt asks Claude to analyze it
like a career strategist and executive recruiter would: identifying your
real strengths and transferable skills, then surfacing realistic
alternative career paths grounded in evidence, not generic advice. Once
you've picked a direction, it hands off cleanly to Step 1 — it doesn't
try to also rewrite your resume or coach you through objections, since
Resume & Cover Letter Tailoring and Interview Prep Guide Builder already
do that well.

### Key Sections & Options

- **Your background (required):** paste your resume, LinkedIn
  About/Experience sections, or a written summary — not a file upload,
  and no length limit. Real detail (specific accomplishments, numbers,
  technologies, team sizes) produces a sharper analysis than
  resume-objective boilerplate.

- **Constraints and scope (all optional):** hard constraints Claude
  filters every recommendation through (not just weighs loosely), a
  minimum compensation floor, whether to restrict paths to your current
  industry, and whether to rule out paths needing years of additional
  schooling or an entry-level restart (on by default, but an unusually
  compelling exception can still be flagged).

- **Output scope toggles:** how many paths to surface (1–4 by
  default — the tool's own hint suggests 8–12 as a deeper alternative),
  and independent on/off switches for a ranked fit table, a "Hidden
  Opportunities" section (roles at the intersection of two or more of
  your capabilities, not just title-matching), a Final Recommendation
  summary, and next-step routing to the rest of the suite. Output format
  defaults to chat text; a downloadable Word document is available too.

### Claude Settings Required

- Web search — recommended, not required, for checking current role and
  salary norms

- Code execution and file creation — only needed if you choose the
  downloadable Word document output; the default chat-text output
  doesn't require it

### What You Get Back

A Career Profile Assessment and Career Capital breakdown grounded in
your pasted background, alternative career paths (1–4 by default,
adjustable — mixing adjacent moves, less-obvious transferable roles,
leadership and IC options, and paths outside your current industry
unless restricted), and — depending
on which toggles you left on — a ranked fit table, a Hidden Opportunities
section, a Final Recommendation summary, and a pointer for your top 3
paths toward the specific suite tool to run next.

### Worth Knowing

- This tool deliberately stops at "here's what to go after and why" — it
  doesn't rewrite your resume or LinkedIn (that's Resume & Cover Letter
  Tailoring) and doesn't prep you for objections about a pivot (that's
  Interview Prep Guide Builder's Objection Reframing).

- If a recommended path doesn't trace back to specific evidence in what
  you pasted, push back on it directly in the conversation — the
  generated prompt instructs Claude to tie every recommendation to real
  evidence, not generic career advice.

**Open the tool:**
<https://tjackson8817.github.io/Career-Path-Discovery/prompt_builder.html>

**Full user guide:**
<https://github.com/tjackson8817/Career-Path-Discovery/blob/main/Prompt_Builder_User_Guide.md>

## 1. Target Company Prompt Builder

**STEP 1 · RESEARCH**

One page, four linked prompts, each with its own Copy/Download buttons
and output panel: an optional **Bulk Company Pull**, the main **Full
Research Tracker**, **LinkedIn Contact Enrichment**, and **Department
Contact Finder**. Together they turn a starting point — company names
you know, an industry description, NAICS codes, or any combination —
into ranked, researched target companies with real named contacts. The
Full Research Tracker’s output (a fully formatted Excel tracker) is the
foundation everything else in the funnel depends on.

### Key Sections & Options

- **Shared Inputs:** company names, industry description, and/or NAICS
  codes — feeds all three prompts on the page. The industry field links
  directly to the [Census NAICS Search](https://www.census.gov/naics/)
  if you want to borrow official industry wording rather than guess. A
  live hint under “Company(s) you know” flags when your seed list is
  getting large (past 20 the discovery cascade runs noticeably slower;
  past 50 it suggests Claude’s Research feature instead). Choose “Find
  new companies” in the Full Research Tracker to let Claude do its own
  modest discovery, or “Just enrich these” to restrict research to only
  the exact companies you typed — the second option also hides the
  discovery-only fields below it, since none of them apply.

- **How companies actually get discovered:** not a NAICS-code search —
  NAICS codes are far too broad to filter by, and the one government
  source that can (SAM.gov) blocks automated access. Discovery instead
  runs a competitor/alternative cascade off your named companies, checks
  analyst and category sources (Gartner, Forrester, G2), scans
  industry-conference exhibitor lists, and searches live job postings.
  NAICS is applied afterward as a classification tag (up to 5 codes per
  company), not the discovery engine.

- **Bulk Company Pull (optional, run first):** a separate, cheap prompt
  for casting a wide net before committing to full research on anyone —
  a flat list (Company, Website, Inferred NAICS Code, one-line
  description, Source) using the same discovery method above, sized as
  wide as you want (no per-company research cost). Prune the result by
  hand, then paste the survivors’ Company column into Shared Inputs and
  set Discovery scope to “Just enrich these.”

- **Scope & purpose:** optional company-size and location-radius
  filters, plus the single most important field — what the list is for —
  since it drives how Claude judges fit, category, and contacts for
  every company.

- **Two-tier output (optional, manual):** turn on “Use a two-tier target
  list?” and set your own Tier 1 / Tier 2 sizes to get a
  fully-researched Tier 1 plus a lighter Tier 2 for a larger discovered
  pool. Only takes effect when Discovery scope is “Find new companies” —
  the toggle and its size fields are hidden entirely in “Just enrich
  these” mode, since there’s no discovered pool to rank.

- **Optional add-on tabs:** M&A research columns, Job Posting Quick
  Links (pre-built search links), Job Post Finder (a plain Company +
  Suggested Job Title Keywords reference tab), Outreach Contacts (a
  four-column tab formatted for the Outreach Message Builder tool),
  Industry Events & Forums, and Company Activity & Events.

- **LinkedIn Contact Enrichment:** the third prompt on the page —
  cross-references a LinkedIn contacts export against a shortlist of
  target companies (25 or fewer) to surface warm introduction paths.
  Doesn’t touch or require the main tracker; run it as a follow-up once
  you have a shortlist.

- **Department Contact Finder:** the fourth prompt on the page — finds
  *named individuals* at a target company (15 or fewer) who work in or
  near a role/department you specify, sourced from live web search
  rather than your own contacts. Every result is labeled Tier 1 (Exact),
  Tier 2 (Adjacent), or Tier 3 (Umbrella) so a loosely-related match is
  never presented as if it's the exact team. This is the fulfillment
  step for the main tracker's Key Contacts / Priority Titles column,
  which often comes back as a placeholder rather than a real name.

### Claude Settings Required

- Web search — for live company research

- Code execution and file creation — to build the actual .xlsx
  tracker(s)

### What You Get Back

Whichever prompt(s) you run, each returns a downloadable Excel workbook.
The Bulk Company Pull returns a plain, unformatted list for pruning. The
Full Research Tracker returns a fully formatted workbook — one row per
company, 31–36 research columns, computed Suggested Priority Rank, plus
whichever optional tabs you selected — split into Tier 1 and Tier 2
sheets if you turned two-tier output on and chose “Find new companies.”
The Department Contact Finder returns a tiered table of named people —
Company, Name, Title, Department/Team, Match Tier, Source, and
Confidence — laid out to paste directly back into the main tracker’s
Key Contacts / Priority Titles column.

### Worth Knowing

- There’s no automatic company cap or qualification pass — you control
  research depth directly via Discovery scope and (optionally) Tier
  1/Tier 2 sizes. As a practical guide, totals above roughly 50–75
  companies in one Full Research Tracker run tend to come back thinner
  per company; use Bulk Company Pull plus “Just enrich these” for
  anything larger.

- Size and location filters are instructions to Claude’s research
  judgment, not a guaranteed hard filter against a live database —
  spot-check a sample of results.

- The Job Post Finder tab is deliberately simple (no formulas, no
  hardcoded job boards) — it exists so you can copy a company and its
  keyword variants into whatever search tool you actually want to use,
  complementing the link-based Quick Links tab rather than replacing it.

**Open the tool:**
<https://tjackson8817.github.io/Target-Company-Prompt-Builder/prompt_builder.html>

**Full user guide:**
<https://github.com/tjackson8817/Target-Company-Prompt-Builder/blob/main/Prompt_Builder_User_Guide.md>

## 2. Job Posting Finder

**STEP 2 · VERIFY**

Takes a shortlist of companies — ideally your top few by Suggested
Priority Rank — and has Claude search live for real, current job
postings: real titles, real URLs, real posted dates. Built around an
explicit anti-hallucination guarantee: report fewer results honestly
rather than pad the list to look complete.

### The First Decision: Standard or Senior/Executive Search

A toggle at the top of the tool, **off by default**, and it changes
almost everything else about how the tool runs:

- **Standard mode (toggle off):** single-stage, title-driven search.
  Best for mid-level and IC roles, which are usually posted with
  recognizable, close-to-literal titles. Company ceiling: **15 or
  fewer** — the tested working limit for real per-company depth.

- **Senior/Executive Search (toggle on):** Director/VP/Managing
  Director/Partner-level roles are frequently filled through internal
  promotion, executive search firms, or warm referral — never posted
  publicly at all — so a single search style doesn’t serve this
  population well. This mode splits into two stages instead:

  - **Stage 1, Triage:** one fast, broad check per company (works up to
    ~30 companies) — does this company have *any* visible senior-level
    posting right now? Any titles you pasted are ignored at this stage.
    Output is a status per company (green = active senior posting /
    yellow = only below-senior postings / white = no visible postings /
    lock = not searchable), plus a ready-to-use LinkedIn saved-search
    URL for every green/yellow company.
  - **Stage 2, Deep Dive:** full-depth search on **5 companies or
    fewer** — a tested number, not a guess. Runs a real 4-query
    treatment per company (LinkedIn Jobs, the company’s own careers
    site, Indeed/Glassdoor/ZipRecruiter, plus a direct verification
    fetch on the best lead). Pasted titles are used here as
    category-matching hints (Seniority + Domain + Function), not literal
    phrases.

### Key Sections & Options

- **Bulk paste from your tracker:** select Company and Suggested Job
  Title Keywords from your Prompt Builder output, paste, and Parse rows
  — reads the real tab-separated columns directly, keeping each
  company’s own specific title variants (semicolon-separated cells are
  kept as OR alternatives to search, not garbled into one string). In
  Executive mode, these titles are ignored during Triage and used as
  matching hints during Deep Dive — nothing pasted is wasted, it’s just
  used differently by stage.

- **What to search for:** typed companies and/or titles as an
  alternative or supplement to bulk paste, combined via Any (OR), All
  (AND), or a custom boolean expression.

- **Scope:** recency window (7/14/30 days or any time), location, and
  max postings per combination. There’s no “which sources to check”
  toggle anymore — every doable source (LinkedIn Jobs, Indeed, each
  company’s own careers page, Google Jobs, Glassdoor, ZipRecruiter) is
  checked by default, and the results say plainly, per company, which
  were actually checked versus which couldn’t be (login-gated, no public
  listings page, etc.).

- **Output:** table in chat (default) or a downloadable Excel file with
  color-coded recency and date-confidence. Triage runs output a single
  status sheet/table instead of a postings list.

### Claude Settings Required

- Web search — required; without it there is no way to find anything
  real

- Code execution and file creation — only if the Excel output format is
  chosen

### What You Get Back

A results table (or .xlsx) grouped by company, with every posting’s real
URL shown directly — required on every row, never summarized away.
Followed by a separate Near-Misses section listing postings that relate
to your search but don’t fully qualify, each with an explicit Reason, so
nothing just silently disappears. In Executive mode, near-misses are the
*expected majority* of what comes back, not a sign of a weak search.

### Worth Knowing

- A batch-size warning appears above the generated prompt once your
  company count goes over the working ceiling for your current
  mode/stage — 15 for Standard, ~30 for Triage, 5 for Deep Dive. It’s
  informational only, nothing is truncated, but expect a larger batch to
  run long or come back thinner per company.

- **Every mode now verifies before trusting a lead.** Any posting
  specific enough to drive a real result gets a direct link check before
  being reported — search snippets and aggregators frequently show
  closed or stale postings as if they were current.

- **KPMG, Accenture, and EY get an automatic extra caution note**
  whenever they’re in your list. Specific leads for these three have
  repeatedly turned out to be dead on direct verification across
  multiple real runs, at every seniority level tested — not a judgment
  on them as employers, just an operational heads-up about how their
  career-site links get indexed and cached.

- Date Confidence (High/Medium/Low) is separate from Posted Date itself
  — it tells you how certain the date actually is, since many aggregator
  listings carry stale or ambiguous dates.

- Genuinely fresh, senior-level postings at large firms are often rarer
  than expected — an honest “nothing qualified” result across several
  companies is a real, useful outcome, not a sign the tool failed.

**Open the tool:**
[<u>https://tjackson8817.github.io/Job-Posting-Finder/job_posting_finder.html</u>](https://tjackson8817.github.io/Job-Posting-Finder/job_posting_finder.html)

**Full user guide:**
[<u>https://github.com/tjackson8817/Job-Posting-Finder/blob/main/Job_Posting_Finder_User_Guide.md</u>](https://github.com/tjackson8817/Job-Posting-Finder/blob/main/Job_Posting_Finder_User_Guide.md)

## 3. Resume & Cover Letter Tailoring

**STEP 3A · APPLY OR CONNECT**

Takes a real job posting and your actual resume, and generates a
keyword/gap analysis, tailored bullet suggestions, a cover letter draft,
and/or a Qualifications Match Letter (T-Letter) — all grounded strictly
in what’s actually true about you. Nothing is invented: a real, honestly
named gap is a correct answer; a fabricated qualification is not
acceptable under any framing.

### Key Sections & Options

- **The job posting:** paste the full text, not a summary — company name
  is optional but scopes the recruiter search precisely.

- **Your resume:** paste your complete resume text, plus any optional
  additional context not yet reflected in it.

- **What to generate:** five independent checkboxes — ATS/Keyword Gap
  Analysis, Resume Bullet Rewrite Suggestions, Cover Letter Draft,
  Qualifications Match Letter (T-Letter, always kept to 1 page), and
  Pivot Positioning Notes. Cover letter tone (Warm/Formal/Direct) and
  length (1 page standard, or 2–3 pages for executive/federal roles) are
  both selectable.

- **Pivot Positioning Notes (default: off):** for when this posting is a
  genuine change of direction from your resume's titles, not a same-lane
  application. Names what to emphasize, what to minimize or reframe
  (never hide), any real skill/certification gaps worth naming, and a
  short honest answer for *why this move* — grounded in a real
  connective thread, not a generic passion statement. Bound by the same
  no-invention rule as everything else this tool produces.

- **Apply the suggestions directly:** two additional checkboxes, nested
  under Gap Analysis and Bullet Rewrites respectively, produce a
  ready-to-use updated resume with those specific suggestions actually
  applied — check one, the other, or both. Each is disabled until its
  parent checkbox is on, since the update is built strictly from what
  that table already justified.

- **Recruiter identification:** on by default, runs a two-tier search
  before drafting either letter. Tier 1 matches by department/function.
  If that finds nothing confident, Tier 2 broadens by location and
  role-appropriate seniority — but never auto-picks a Tier 2 candidate;
  it lists them for you to choose from while still drafting the letter
  in full with a generic salutation.

### Claude Settings Required

- Web search — only if recruiter identification is left on (the default)

- Code execution and file creation — only if the Word document output
  format is chosen

### What You Get Back

Real markdown or Word tables (never plain dashes standing in for one)
for the Gap Analysis and Bullet Rewrites, genuine letter formatting
(date, salutation, paragraph breaks, closing) for any letter, and — if
selected — an updated resume with vetted changes already applied.

### Worth Knowing

- Always read every bullet rewrite side by side with your original
  before using it — confirm you can genuinely stand behind each change
  in an interview.

- A named, honest gap in the analysis is useful information, not a
  failure — don’t look for the tool to paper over something your resume
  genuinely doesn’t support.

- Tier 2 recruiter candidates are intentionally never auto-selected — a
  fabricated or wrongly-guessed name in a real cover letter is a worse
  outcome than an honest "Dear Hiring Team."

**Open the tool:**
[<u>https://tjackson8817.github.io/Resume-Cover-Letter-Builder/resume_cover_letter_tailoring.html</u>](https://tjackson8817.github.io/Resume-Cover-Letter-Builder/resume_cover_letter_tailoring.html)

**Full user guide:**
[<u>https://github.com/tjackson8817/Resume-Cover-Letter-Builder/blob/main/Resume_Cover_Letter_Tailoring_User_Guide.md</u>](https://github.com/tjackson8817/Resume-Cover-Letter-Builder/blob/main/Resume_Cover_Letter_Tailoring_User_Guide.md)

## 4. Outreach Message Builder

**STEP 3B · APPLY OR CONNECT**

Takes your researched tracker rows — Company, Key Contacts, Warm
Introduction Path, and Category — and drafts the actual outreach
messages, tailored per company and per stage of the relationship, rather
than one generic template with the name swapped in.

### Key Sections & Options

- **Paste from your tracker:** Ctrl+click (Cmd+click on Mac) to select
  Company, Key Contacts/Priority Titles, Warm Introduction Path, and
  Category together in Excel — these columns aren’t adjacent in the
  tracker, so this non-contiguous-selection trick is what makes bulk
  paste practical. Each parsed row also gets an optional Target Audience
  field (Recruiter, Hiring Manager, Cold Outreach, or Warm Outreach)
  that further shapes the message.

- **Message goal:** First outreach, Follow-up (no response yet),
  Thank-you (after a call/interview), or Staying in touch — a global
  setting that changes the actual instructions given, not just the
  wording. Anything other than "First outreach" adds a per-row Context
  Notes field (what you discussed, when you first reached out, or your
  reason for reconnecting, depending on the goal) that grounds the
  message instead of leaving it generic or risking fabrication.

- **Message settings:** Channel — LinkedIn connection request (strict
  ~300-character limit, enforced automatically), LinkedIn
  InMail/message, or Email (adds a required, specific Subject line per
  variant). Tone — Warm/casual, Formal/executive, or Direct/concise.
  Your background (optional) grounds messages in real experience rather
  than filler.

- **Output:** table in chat (default) or a downloadable Word document.

### Claude Settings Required

- Code execution and file creation — only if the Word document output
  format is chosen

### What You Get Back

2–3 message variants per company, each shaped by that specific company’s
Warm Introduction Path, Target Audience, and selected Message Goal —
always followed by one line of visible reasoning explaining the approach
taken, so you can catch it if a path, audience, or context note got
misread before sending anything.

### Worth Knowing

- The grounding guardrail is explicit and non-optional, and now covers
  Context Notes too: no invented shared history, mutual connections,
  prior conversation details, or personal specifics beyond what your
  Warm Introduction Path, background, or Context Notes actually state.
  An honestly generic message is fine; a fabricated relationship or
  invented discussion detail is not.

- A vague Warm Introduction Path (e.g. just "recruiter"), or blank
  Context Notes on a follow-up/thank-you/staying-in-touch message, is a
  legitimate input — the message stays appropriately general rather than
  inventing false specifics to sound more personal or more informed than
  you actually are.

- The reasoning line is always included, by design — it’s your check
  that the tool read your research correctly before anything goes out.

**Open the tool:**
[<u>https://tjackson8817.github.io/Outreach-Message-Builder/outreach_message_builder.html</u>](https://tjackson8817.github.io/Outreach-Message-Builder/outreach_message_builder.html)

**Full user guide:**
[<u>https://github.com/tjackson8817/Outreach-Message-Builder/blob/main/Outreach_Message_Builder_User_Guide.md</u>](https://github.com/tjackson8817/Outreach-Message-Builder/blob/main/Outreach_Message_Builder_User_Guide.md)

## 5. Interview Prep Guide Builder

**STEP 4 · INTERVIEW**

Turns your resume, the job description, and (optionally) who you’re
meeting with into a real, grounded prep guide once an interview has
actually landed — the stage none of the funnel tools before it cover.
Afterward, the specific things you actually discuss become the Context
Notes for a genuinely grounded thank-you message back in Outreach
Message Builder (Step 3b), closing the loop.

### Key Sections & Options

- **Three modes, not one generic form:** a toggle at the top of the page
  switches the entire field set and the entire generated guide, not just
  a couple of options — **Recruiter Screen** (a qualifications T-chart,
  a tight “tell me about yourself” script, coached answers for the
  gap/leaving question and the salary question, objection reframing for
  any concerns you named, standard logistics questions, recruiter-
  appropriate questions to ask), **Hiring Manager Interview** (built for
  a real, time-boxed video call — company/role research, a resume-to-JD
  gap map, objection reframing, interviewer research, a Candidate SWOT
  Analysis with honest weakness-mitigation talking points, a video-call
  logistics checklist tied to your actual platform, pacing scaled to
  your actual call length, your top 3-4 STAR-structured stories rather
  than an exhaustive list, and HM-appropriate questions to ask), and
  **General/Other** (the fuller original structure — including its own
  objection reframing and the same Candidate SWOT Analysis — as a
  fallback for technical rounds, panels, and final rounds).

- **Shared inputs across all three modes:** company, role, job
  description, and your resume — paste text, or attach the files
  directly when you paste the generated prompt into Claude instead. An
  optional field for naming what you're worried a hiring manager will
  hold against you (a gap, a pivot, short tenures, overqualification)
  drives a dedicated Objection Reframing section in every mode — left
  blank, that section falls back to general guidance instead of
  inventing your situation.

- **Optional STAR Stories field (Hiring Manager and General/Other
  modes):** write your own Situation/Task/Action/Result for up to 3
  stories if you already know which ones you want to use. The guide
  uses them exactly as written instead of just pointing you to a resume
  bullet, filling any remaining slot up to 3-4 the usual way. Leave all
  three blank and nothing changes — same fallback as before. Not shown
  in Recruiter Screen mode, which doesn't use behavioral-style
  questions.

- **Mode-specific fields:** Recruiter Screen adds location (for salary
  research grounding), an optional reason for a gap or departure, and an
  optional target salary range. Hiring Manager adds call length,
  platform, and an interviewer list (bulk-paste or manual).
  General/Other adds an interview-stage selector and its own separate
  interviewer list.

### Claude Settings Required

- Web search — for company, interviewer, and (in Recruiter Screen mode)
  real salary market-data research

- Code execution and file creation — only if the Word document output
  format is chosen

### What You Get Back

A structured prep guide matching whichever mode you picked, with a
one-page Quick Reference summary at the top for skimming right before
you walk in or join the call, and full detail below it.

### Worth Knowing

- **Never a scripted answer.** If you filled in the optional STAR
  Stories field, the guide uses those stories exactly as you wrote them
  and never embellishes them. Where a slot is unfilled, it points you to
  the specific resume bullet that’s your strongest match and prompts
  STAR structure — it does not write the story for you. Claude doesn’t
  know what actually happened in your work beyond what your resume
  states (or what you wrote yourself), and inventing specifics risks
  putting words in your mouth you’d have to walk back live.

- **Interviewer research stays evidence-based.** If a named interviewer
  has little or no public footprint, the guide says so plainly and falls
  back to role-based prep instead of inventing a personality or
  interests to seem more personalized.

- **SWOT weaknesses stay honest.** In Hiring Manager and General/Other
  modes, a real weakness in the Candidate SWOT Analysis is never
  softened into a non-weakness, and its mitigation talking point is
  never a fabricated accomplishment used to explain the gap away — same
  standard as Objection Reframing.

- **The salary question is grounded in real search, not a guess.**
  Recruiter Screen mode requires actual market-data research (sources
  noted) rather than a number pulled from nowhere.

- **Sensitive personal facts stay yours to supply.** The reason for a
  gap or departure, your notice period, work authorization status — the
  guide never invents these. Left blank, it gives general guidance on
  structure instead.

- **Objection reframing stays honest, not spin.** Every reframe for a
  named concern is grounded in something real from your resume — if a
  concern genuinely doesn't have a strong answer, the guide says so
  rather than manufacturing one.

- Interviewer lists are tracked separately per mode — switching from
  Hiring Manager to General/Other (or back) won’t carry interviewers
  over between them, since they’re genuinely separate lists.

**Open the tool:**
[<u>https://tjackson8817.github.io/Interview-Prep-Guide-Builder/interview_prep_guide_builder.html</u>](https://tjackson8817.github.io/Interview-Prep-Guide-Builder/interview_prep_guide_builder.html)

**Full user guide:**
[<u>https://github.com/tjackson8817/Interview-Prep-Guide-Builder/blob/main/Interview_Prep_Guide_Builder_User_Guide.md</u>](https://github.com/tjackson8817/Interview-Prep-Guide-Builder/blob/main/Interview_Prep_Guide_Builder_User_Guide.md)

## 6. Salary Negotiator

**STEP 5 · NEGOTIATE**

Turns a real offer, sourced market and company-specific compensation
data, and your real qualifications into an actual negotiation plan and
counter-offer draft — not generic “just ask for more” advice. The direct
sequel to Interview Prep Guide Builder’s Recruiter Screen mode, which
explicitly coaches you to state a range *before* an offer exists; this
tool picks up once a real number is actually on the table.

### The One Guardrail That Matters Most

Every tool in this family has a “don’t fabricate” rule. This one is
built around the sharpest version of it: the tool never invents or
exaggerates a competing offer. A fabricated story in a draft message is
bad output you’d catch and fix. A fabricated competing offer used in an
actual negotiation is a lie told to a real employer — one that can
unravel and cost you the offer entirely. Leaving the competing-offer
field blank is the honest, expected default, not a weaker use of the
tool, and the guide will not imply one exists anywhere in its output.

### Key Sections & Options

- **The role, company, and location:** location specifically grounds
  both the general market research and the company-specific research
  that follows.

- **Your resume:** the only source the tool is allowed to draw from when
  identifying differentiators to justify going above the initial number.

- **The offer so far:** paste or describe whatever you actually have —
  partial is fine, and the tool still produces useful research and
  differentiator sections even with nothing here yet.

- **Target number and priorities (optional):** your walk-away number,
  plus what matters most to you beyond salary, which directly weights
  which levers the guide prioritizes if base salary itself turns out to
  be capped.

- **Competing offer (optional):** only fill this in if you actually have
  one, with real figures — see the guardrail above.

### Claude Settings Required

- Web search — for market compensation research and company-specific
  compensation research, both required for real, sourced data

- Code execution and file creation — only if the Word document output
  format is chosen

### What You Get Back

An 8-section negotiation guide: a sourced market data snapshot,
company-specific compensation research (honest when thin), a total
compensation translation covering every offer component, your real
differentiators, negotiation levers beyond base salary, 2-3 real framing
options for the counter, a written counter-offer draft, and practical
negotiation etiquette notes — with a one-page Quick Reference summary at
the top.

### Worth Knowing

- Every dollar figure and source the guide cites is expected to come
  from real search results, both for general market data and for the
  company-specific research — never a guessed number presented as if it
  were sourced.

- The total-compensation comparison against a competing offer only
  happens if you actually provided one — it never appears otherwise.

- Differentiators are pulled only from what’s actually documented in
  your resume, the same grounding standard the rest of this family holds
  to.

**Open the tool:**
[<u>https://tjackson8817.github.io/Salary-Negotiator/salary_negotiator.html</u>](https://tjackson8817.github.io/Salary-Negotiator/salary_negotiator.html)

**Full user guide:**
[<u>https://github.com/tjackson8817/Salary-Negotiator/blob/main/Salary_Negotiator_User_Guide.md</u>](https://github.com/tjackson8817/Salary-Negotiator/blob/main/Salary_Negotiator_User_Guide.md)

## 7. LinkedIn Profile Builder

**ONGOING · PROFILE**

Optimizes your headline, About section, experience descriptions, and
skills specifically for the job search — recruiter-searchable,
ATS-ready, and built around LinkedIn's real current character limits.
Built for mid-level and upper-level management, regardless of industry
or function. A standalone tool, not part of the Step 0–5 funnel, since
it's something you'd reach for independent of where you are in an
active application process.

### Key Sections & Options

- **Your background:** paste your resume/professional background
  (required, unless you attach a file instead — see below), your current
  LinkedIn profile text (optional, preserves existing voice), target
  role and industry, management level, and an optional preferred custom
  URL.

- **Attach a file instead of pasting:** a checkbox lets you skip the
  text fields and attach your resume and/or a downloaded LinkedIn
  profile PDF directly to the Claude message instead — same pattern as
  attaching a job description or resume file in Resume & Cover Letter
  Tailoring or Interview Prep Guide Builder.

- **What to generate:** seven independent checkboxes — Headline, About
  section, Experience rewrites, Skills, Custom URL suggestion,
  Recommendation Request Guidance, and profile banner images.

- **Experience rewrite scope:** a three-way choice — 3 most recent
  (default), All positions, or a Custom number (1–20) — rather than a
  fixed count.

- **Banner options:** how many banners (1–5, default 3) and a visual
  style — Let Claude decide, Abstract/geometric, Industry motif, or
  Minimalist. Generated programmatically (Python's Pillow library), not
  photorealistic images.

- **Output format:** Text in chat (default) or Downloadable Word
  document — same toggle pattern as Resume & Cover Letter Tailoring and
  Interview Prep Guide Builder. Banner images always come through as
  separate `.png` files either way.

### Claude Settings Required

- Web search — recommended, not required, for researching current
  in-demand skills for your target role/industry

- Code execution and file creation — needed if the profile banner
  images are on, or if Downloadable Word document output is chosen

### What You Get Back

A response organized by whichever sections you toggled on, each with
its character count stated so you can confirm it fits LinkedIn's real
limit before pasting it in — delivered as either a chat response or a
downloadable Word document per your Output Format choice, plus separate
banner `.png` files if requested, regardless of that choice.

### Worth Knowing

- **Nothing is invented.** A real number, dollar figure, or percentage
  leads a bullet only where one genuinely exists in your background — a
  strong qualitative bullet is always the correct substitute for a
  fabricated metric, never the other way around.

- **Skills are researched, not recited.** The prompt instructs Claude to
  ground the skills list in real current hiring signal for your specific
  target role and industry, and to only include a skill if something in
  your actual background supports it — not a static "top skills" list
  memorized from training.

- **Recommendation guidance is never ghostwritten.** It tells you who to
  ask and what real talking points to hand them — putting fabricated
  words in a real colleague's mouth isn't acceptable under any framing.

- Banner image generation and the skills-research step both depend on
  capabilities specific to Claude — running the prompt in a different AI
  tool will still produce the text sections, but likely not those two.

**Open the tool:**
<https://tjackson8817.github.io/LinkedIn-Profile-Builder/prompt_builder.html>

**Full user guide:**
<https://github.com/tjackson8817/LinkedIn-Profile-Builder/blob/main/Prompt_Builder_User_Guide.md>

## 8. LinkedIn Article Share Builder

**ONGOING · PERSONAL BRAND**

Finds the 5 most on-brand, recent, real articles worth sharing — ranked
automatically against your actual brand keywords — then drafts the post
for whichever one you pick, and optionally builds matching artwork.
Useful whether or not you’re actively job hunting.

### Key Sections & Options

- **What counts as "on-brand":** your brand keywords/topics (the field
  that makes "impactful" mean something specific to you, not generic
  trending news), a recency window (24 hours to a week), optional
  audience, source guidance, and what you’ve already covered recently so
  the run doesn’t repeat itself.

- **Your brand identity:** set once and reused every time — your name,
  tagline, and an optional eyebrow line (defaults to "WORTH YOUR
  ATTENTION").

- **Options:** generate artwork (a 1200×630 .png built with Python’s
  Pillow library, matching a consistent visual template — Claude-only,
  since most other AI tools have no equivalent way to execute this from
  a pasted prompt), generate hashtags, and whether to end the post with
  a genuine question (off by default, since overusing it starts to read
  as engagement-bait).

### Claude Settings Required

- Web search — required to find real, current articles

- Code execution and file creation — only if artwork generation is on

### What You Get Back

Step 1: the top 5 ranked candidates, each with context (headline,
source, free-to-read status, why it ranked here) plus a ready-to-copy
block (URL, summary, hashtags). Step 2, once you pick one: the actual
LinkedIn post, plain text, no markdown. Step 3 (optional): a real
downloadable .png, not just a description of one.

### Worth Knowing

- Built-in honesty guardrails are non-optional: only real, verifiable
  articles with real URLs, every summary written fresh in Claude’s own
  words (never copied from source), and an honest "fewer than 5 today"
  if genuinely on-brand, free-to-read articles are thin.

- No markdown formatting anywhere in the output — LinkedIn doesn’t
  render it, so asterisks or pound signs would show up as literal stray
  characters.

- Artwork generation only works in Claude itself — pasting the prompt
  into ChatGPT or another tool will not produce an image, regardless of
  wording, since the instruction depends on Claude’s code execution
  environment specifically.

**Open the tool:**
[<u>https://tjackson8817.github.io/LinkedIN-Article-Share/linkedin_article_share.html</u>](https://tjackson8817.github.io/LinkedIN-Article-Share/linkedin_article_share.html)

**Full user guide:**
[<u>https://github.com/tjackson8817/LinkedIN-Article-Share/blob/main/LinkedIn_Article_Share_User_Guide.md</u>](https://github.com/tjackson8817/LinkedIN-Article-Share/blob/main/LinkedIn_Article_Share_User_Guide.md)

## 9. Recruiter Message & Job Posting Sanity Check

**ONGOING · SAFETY CHECK**

Screens either a suspicious recruiter message OR a job posting — pick
the mode at the top of the page — against known scam patterns entirely
in your browser — no prompt, no Claude conversation, finished result
immediately. Flags both what’s present (scammy phrasing, off-platform
pushes, upfront fee requests) and what’s missing (no company named, no
job title mentioned, no responsibilities described), since the latter
catches vague pitches and templated listings that avoid obviously scammy
language altogether.

*This is the one tool in the suite that doesn’t use the paste-a-prompt
pattern described in Getting Started — it’s a self-contained scanner,
not a prompt generator.*

### Key Sections & Options

- **Mode toggle:** "Recruiter Message" or "Job Posting" — switches the
  entire input panel, checklist, and pattern library. These check
  genuinely different things (a message’s sender vs. a posting’s own
  legitimacy), so each mode has its own full field set rather than a
  handful of shared fields with the rest bolted on.

- **Recruiter Message mode:** paste the message text, plus optionally
  the company they claim to represent and the sender’s email, which
  together let the tool flag a domain/employer mismatch. Checklist
  covers profile signals the tool can’t read from text alone — new
  profile, few connections, no verification badge, unrelated profession,
  AI-generated/generic photo, not listed as an employee, few mutuals,
  little activity. Photo-related checks link out to free tools (Google
  Images/TinEye/Bing; Is It AI?/Quillbot) so you can check without
  leaving the page — clearly marked optional, never auto-run.

- **Job Posting mode:** paste the posting text, plus optionally the
  company it’s for, an application email/link, and where you found it.
  Checklist covers listing-legitimacy signals — evergreen/repeatedly
  reposted listings, exact text duplicated for other companies, no
  hiring manager or team named, thin-to-no independent company presence,
  no application deadline ever, chat-only interview process, not found
  on the company’s own careers page. Patterns cover posting-specific
  scam categories: equipment/activation fees, reshipping and
  payment-processing scams, unrealistic pay for no experience, financial
  info requested at the application stage, and more.

- **Custom red flags:** add your own phrases to check for, per mode,
  session-only.

### Claude Settings Required

- None — runs entirely client-side, nothing you enter is sent anywhere

### What You Get Back

A stamped verdict (Low signal / Proceed with caution / High risk) with a
risk-signal-strength score, every flag found with severity and
reasoning, the text with flagged phrases highlighted in place, direct
links to LinkedIn/IC3/FTC reporting when warranted, and — for results
that land in the caution range specifically — a mode-appropriate next
step: a ready-to-send follow-up message for a message-mode result, or a
pre-application verification checklist for a posting-mode result.
History entries are tagged by mode so a mixed session of both checks
stays legible.

### Worth Knowing

- An unnamed intermediary in a message (routed through "a friend" or "a
  colleague" with no one you can actually verify) is treated as a
  high-severity flag on its own — a common pattern that avoids scammy
  keywords entirely. The posting-mode equivalent is a listing with no
  named hiring manager or team at all.

- The follow-up/checklist only appears for caution-range results,
  deliberately — a high-risk result calls for disengaging, not a more
  carefully worded reply or a longer verification process.

- A clean result doesn’t confirm legitimacy, and a flagged result isn’t
  proof of a scam — always verify independently through the company’s
  own careers page or domain.

**Open the tool:**
[<u>https://tjackson8817.github.io/Recruiter-Message-Sanity-Check/</u>](https://tjackson8817.github.io/Recruiter-Message-Sanity-Check/)

**Full user guide:**
[<u>https://github.com/tjackson8817/Recruiter-Message-Sanity-Check/blob/main/Recruiter_Message_Sanity_Check_User_Guide.md</u>](https://github.com/tjackson8817/Recruiter-Message-Sanity-Check/blob/main/Recruiter_Message_Sanity_Check_User_Guide.md)

## Make It Your Own

None of this is locked down. Every tool is just a starting point — if a
field, a wording, a default, or an entire feature doesn’t fit how you
actually want to work, take that tool’s URL back to a Claude
conversation and ask for it to be edited, added to, adjusted, or
refined. That’s exactly how this whole suite came together in the first
place: one tool at a time, one conversation at a time, shaped to fit
real use rather than guessed at in advance. Treat every tool here as a
draft you’re free to keep improving, not a finished product to work
around.
