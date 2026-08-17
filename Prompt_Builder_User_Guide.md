# Career Path Discovery Prompt Builder — User Guide

## What this tool is for

Every other tool in the JobRadar suite assumes you already know what role you're chasing — a target company list, a specific posting, an actual interview. This tool is for the step before all of that: **you're not sure what to go after next.**

Feed it your career background, and it builds a prompt that asks Claude to act like a career strategist and executive recruiter — reviewing your actual history and surfacing realistic career paths you might not have considered, ranked and grounded in evidence, not generic advice.

If you already know your target role, skip this tool and go straight to Target Company Prompt Builder.

## Before you start

You'll get the most out of this if you paste real substance, not a polished summary. A tight paragraph of specific accomplishments — numbers, technologies, team sizes, deal sizes, what you actually did — works better than an objective statement or a vague list of responsibilities. The analysis can only work with what you give it: thin input produces thin output.

Have ready:

- Your resume text, LinkedIn About + Experience sections, or a written summary of your career
- (Optional) Any hard constraints — things genuinely off the table, like relocation limits or role types you won't consider
- (Optional) A minimum acceptable compensation figure

## Field-by-field

### Your background

**Career background** *(required)* — paste your resume, LinkedIn sections, or a written summary. No length limit. This is the only field that has to be filled in for the tool to generate anything.

**Current or most recent title** *(optional)* — gives Claude a quick anchor point, separate from the fuller background text.

**Anything off the table** *(optional)* — hard constraints, not soft preferences. The generated prompt tells Claude to filter every recommendation through these rather than just weigh them loosely. Examples: "no relocation outside Texas," "no people-management roles," "must stay remote-eligible."

**Minimum acceptable compensation** *(optional)* — a floor, not a target. Helps Claude flag paths that wouldn't realistically clear it.

**Stay within my current industry?** — "No" (default) shows everything, including a full break into an unrelated industry. "Yes" restricts recommendations to adjacent roles within your current industry.

**Rule out paths that need years of additional schooling or an entry-level restart?** — "Yes" (default) keeps the focus on paths you could realistically move into now, though Claude can still flag an unusually compelling exception if one comes up. "No" opens the door to paths that would require significant retraining, with that cost stated plainly.

### Output scope

**How many alternative paths to surface** — defaults to 8–12. Adjust up or down.

**Include a ranked fit table?** — scores each path on transferability, employer credibility, compensation potential, availability, retraining required, durability, network leverage, and advancement potential. On by default.

**Include a "Hidden Opportunities" section?** — looks specifically for roles at the intersection of two or more of your capabilities (e.g. technical expertise + communication, sales + strategy) rather than matching your past titles to similar titles. On by default — this is often where the most useful, non-obvious recommendations come from.

**Include a Final Recommendation summary?** — closes with a best-immediate-pivot / best-higher-comp / best-long-term / best-lower-risk / most-overlooked / probably-avoid breakdown, each with a reason. On by default.

**Include next-step routing to the other JobRadar tools?** — for your top 3 paths, names which JobRadar tool to run next and why (Target Company Prompt Builder, Resume & Cover Letter Tailoring, or Interview Prep Guide Builder). On by default. This is what keeps this tool from trying to also do positioning or objection-handling — it just points you to the tool that already does that well.

## What you'll get back

When you paste the generated prompt into Claude, the response is organized into the sections you toggled on:

1. **Career Profile Assessment** — your strongest areas of expertise, transferable skills, leadership capabilities, and non-obvious career patterns, with what you're demonstrably good at kept separate from what your job titles alone suggest.
2. **Career Capital** — your accumulated professional assets, each tied to specific evidence from what you pasted.
3. **Alternative Career Paths** — a mix of adjacent moves, less-obvious transferable roles, leadership and IC options, consulting/advisory paths, and (unless restricted) roles outside your current industry — evaluated as an employer actually would, not just what's theoretically possible.
4. **Career Path Ranking** *(if enabled)* — a table, one row per path.
5. **Hidden Opportunities** *(if enabled)* — capability-intersection roles.
6. **Final Recommendation** *(if enabled)* — the six-way breakdown described above.
7. **What's Next** *(if enabled)* — routing for your top 3 paths.

This is a chat response, not a generated file — there's no document or spreadsheet output from this particular tool.

## What this tool intentionally doesn't do

- **Rewrite your resume or LinkedIn.** Once you've picked a direction from this tool's output, Resume & Cover Letter Tailoring is where you tailor your actual materials — including its optional "Pivot Positioning Notes," which handles what to emphasize or reframe for a specific posting.
- **Prep you for objections.** Interview Prep Guide Builder's "Objection Reframing" section handles turning a career pivot, a gap, or perceived overqualification into a credible answer once you're actually in an interview.
- **Research companies.** Target Company Prompt Builder does that, once you've picked a path here.

Keeping this tool scoped to discovery — not positioning, not company research — means each JobRadar tool does one job well instead of three tools giving you overlapping, possibly conflicting advice on the same question.

## A note on honesty

The generated prompt explicitly tells Claude not to give generic career advice and to tie every recommendation back to specific evidence in your background. If a recommended path doesn't have a clear connection to something you actually pasted, that's worth pushing back on in the conversation — ask Claude to point to the specific evidence for any recommendation that feels like a stretch.
