# Career Path Discovery Prompt Builder — User Guide

## What this tool is for

Most tools in the JobRadar suite assume you already know what role you're chasing — a target company list, a specific posting, an actual interview. This tool covers the step before that, in one of two ways:

- **Discover mode:** you're not sure what to go after next. Claude reviews your real history and surfaces realistic career paths you might not have considered, ranked and grounded in evidence.
- **Target Pivot mode:** you already have a direction in mind, such as Marketing → Sales or Engineering → Sales. Claude tests that pivot honestly, shows how your existing skills translate into the target function, outlines the real gaps, rewords your resume for it, and still surfaces adjacent careers worth considering alongside it.

If you already know your target role *and* have a specific posting in hand, you can skip straight to Resume & Cover Letter Tailoring. If you know the target and need companies, go to Target Company Prompt Builder.

## Before you start

You'll get the most out of this with real substance, not a polished summary. Specific accomplishments — numbers, technologies, team sizes, deal sizes, what you actually did — work better than an objective statement or a vague list of responsibilities.

Have ready:

- Your resume (text to paste, or the file to attach in Claude), LinkedIn About + Experience sections, or a written summary of your career
- (Optional) Any hard constraints — things genuinely off the table, like relocation limits or role types you won't consider
- (Optional) A minimum acceptable compensation figure
- (Target Pivot mode) The function you want to move into, and in your own words, what's drawing you to it

## Field-by-field

### Your background

**Career background** — paste your resume, LinkedIn sections, or a written summary. No length limit. Required unless you check the attach option below.

**I'll attach my resume file (PDF/Word) directly in Claude** — check this to upload your resume file to the Claude chat along with the prompt instead of pasting it. The Career background box becomes optional; use it for anything extra that isn't on your resume (LinkedIn highlights, side projects, context). Nothing is uploaded from this page itself.

**Current or most recent title** *(optional)* — a quick anchor point, separate from the fuller background text.

**Anything off the table** *(optional)* — hard constraints, not soft preferences. The prompt tells Claude to filter every recommendation through these. Examples: "no relocation outside Texas," "no people-management roles," "must stay remote-eligible."

**Minimum acceptable compensation** *(optional)* — a floor, not a target.

**Stay within my current industry?** — "No" (default) shows everything, including a full break into an unrelated industry. "Yes" restricts recommendations to adjacent roles within your current industry.

**Rule out paths that need years of additional schooling or an entry-level restart?** — "Yes" (default) keeps the focus on paths you could realistically move into now, though Claude can still flag an unusually compelling exception. "No" opens the door to paths that would require significant retraining, with that cost stated plainly.

### What are you looking for?

**Discover paths** (default) or **I have a target pivot in mind.** Choosing the second reveals:

**Pivoting from** *(optional)* — your current function. Leave it blank and Claude infers it from your background.

**Pivoting to** *(required in this mode)* — the function you want to move into. Pick a suggestion (Sales, Sales Engineering / Solutions Consulting, Business Development, Account Management, Customer Success, Marketing, Product Management, Engineering, and more) or type your own.

**What's drawing you to this pivot** *(optional)* — your own reasons, used as context only. Claude won't invent motivations you don't state.

**Also surface adjacent careers I should consider alongside this pivot** — on by default. Keeps the tool's discovery output: adjacent paths, each compared against your named pivot, including any that may be a stronger or lower-risk fit.

**Include resume repositioning for this pivot** — on by default. Adds the Resume Repositioning section described below, including the hand-off to Resume & Cover Letter Tailoring.

### Output scope

**How many alternative paths to surface** — defaults to 1–4. In Target Pivot mode this is the number of *adjacent* paths, surfaced alongside your pivot. Ask for more (8–12, or any number) for a deeper pass.

**Include a ranked fit table?** — scores each path on transferability, employer credibility, compensation potential, availability, retraining required, durability, network leverage, and advancement potential. In Target Pivot mode your pivot is listed first. On by default.

**Include a "Hidden Opportunities" section?** — roles at the intersection of two or more of your capabilities rather than title-to-title matching. In Target Pivot mode it also looks at intersections between your background and the target function. On by default.

**Include a Final Recommendation summary?** — best immediate pivot, best higher-comp, best long-term, best lower-risk, most overlooked, and one path to probably avoid. In Target Pivot mode it opens with a direct verdict on your pivot. On by default.

**Include next-step routing to the other JobRadar tools?** — for your top 3 paths, which tool to run next and why. On by default.

## What you'll get back

A downloadable Word document with real headings and real Word tables, organized into the sections you turned on. Section numbers adjust automatically to match.

**Both modes:**

1. **Career Profile Assessment** — your strongest expertise, transferable skills, leadership capabilities, and non-obvious career patterns.
2. **Career Capital** — accumulated professional assets, each tied to specific evidence.

**Target Pivot mode:**

3. **Target Pivot Assessment** — credible evidence for the target function, real gaps stated plainly, the realistic entry title and level, bridge roles, compensation impact against your floor, the fastest ways to close gaps, and a verdict (pursue directly, via a bridge role, or reconsider) with a fit score.
4. **Resume Repositioning for the Pivot** *(if enabled)*:
   - **Skill Translation** — a table of Skill / Capability, Evidence in My Background, How I Use It Now, How the Target Uses It, and Suggested Resume Wording. This is where a common skill gets reframed for how it's used in the target job. For example, "presented design trade-offs to plant managers" is an engineering skill in your current role, and in Sales the same skill is consultative discovery and executive communication. It also surfaces "hidden" skills your experience shows but your resume never names, with the evidence pointed to so you can verify it.
   - **Bullet Rewrites** — your original bullets verbatim beside versions rewritten for the target function, plus what changed. Emphasis, order, and terminology only; every number and fact stays as stated.
   - **Positioning Summary** — a 2–3 sentence professional summary aimed at the target, plus honest keywords your background supports.
   - **Gap Outline** — every real gap, why target hiring managers care, must-have vs. nice-to-have, how to close it, and how to handle it on your resume now without implying you already have it.
   - **Hand-off to Resume & Cover Letter Tailoring** — two plain-text blocks in a shaded box, ready to copy (see below).

**Both modes (optional sections):** Alternative Career Paths (Discover) or Adjacent Career Paths to Consider (Target Pivot), Career Path Ranking, Hidden Opportunities, Final Recommendation, and What's Next.

## Feeding the hand-off into Resume & Cover Letter Tailoring

The repositioning in this tool is for the target *function* in general. Resume & Cover Letter Tailoring then tailors it to one real posting. When you have a posting:

1. Open Resume & Cover Letter Tailoring and paste the posting and your full resume as usual.
2. Paste **Block 2 — Additional context** into its **Additional context** field.
3. Check **Pivot Positioning Notes**, then paste **Block 1 — Pivot description** into the field that appears under it.
4. Choose your other outputs and generate as normal.

Because Block 2 includes the real gaps, the tailoring tool's gap analysis flags them honestly instead of treating them as solved. Read Block 2 before pasting it: that tool treats Additional context as true about you, so remove anything you can't stand behind.

## What this tool intentionally doesn't do

- **Tailor to a specific posting.** Target Pivot mode repositions your resume for a function, not a job ad. Resume & Cover Letter Tailoring does the posting-level work, including ATS keyword matching, and can produce a finished updated resume.
- **Prep you for objections.** Interview Prep Guide Builder's Objection Reframing handles turning a pivot, a gap, or perceived overqualification into a credible interview answer.
- **Research companies.** Target Company Prompt Builder does that, once you've picked a path.

## A note on honesty

The generated prompt tells Claude not to give generic career advice and to tie every recommendation to specific evidence in your background. In Target Pivot mode it adds three more rules: don't soften a real gap into a non-gap, don't overstate how ready you are, and don't suggest any resume wording you couldn't defend line by line in an interview. Rewording is allowed; inventing a metric, title, employer, tool, credential, or scope is not. If any suggestion doesn't trace back to something you actually provided, push back on it in the conversation.
