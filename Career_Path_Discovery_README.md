# Career Path Discovery Prompt Builder

A free, browser-based tool that turns a form into a ready-to-paste prompt for Claude. The prompt asks Claude to analyze your career background like a career strategist and executive recruiter would, and either surface realistic alternative career paths grounded in your actual experience, or test a specific pivot you already have in mind (for example, Marketing → Sales or Engineering → Sales) and show you how to reposition your resume for it.

**No installation needed.** Open `prompt_builder.html` in any modern browser. Paste your background (or plan to attach your resume file in Claude), fill in what applies, copy or download the generated prompt, and paste it into a Claude conversation (web search recommended, for checking current role/salary norms) to get the actual analysis. Nothing you enter is sent anywhere — this page only builds text locally in your browser.

## Where this fits

This is **Step 0** in the JobRadar tool suite — it runs *before* Target Company Prompt Builder, not after:

- **Not sure what to target next** → start here, in Discover mode
- **Know the pivot you want, need to reposition for it** → start here, in Target Pivot mode, then carry the hand-off into Resume & Cover Letter Tailoring
- **Know your target, need companies** → Target Company Prompt Builder
- **Have a posting, need materials** → Resume & Cover Letter Tailoring / Outreach Message Builder
- **Have an interview, need prep** → Interview Prep Guide Builder
- **Have an offer** → Salary Negotiator

In Discover mode this tool stops at "here's what to go after and why." In Target Pivot mode it goes one step further, repositioning your resume for the target *function* in general, and hands that off to Resume & Cover Letter Tailoring, which tailors it to a specific posting. It still doesn't prep you for interview objections; that stays with Interview Prep Guide Builder.

## How it works

The page is a single form:

1. **Your background** — paste your resume, LinkedIn About/Experience sections, or a written summary. Or check **"I'll attach my resume file (PDF/Word) directly in Claude"** and upload the file to the Claude chat along with the prompt; the text box then becomes optional, for anything extra that isn't on your resume. You can also add hard constraints, a minimum compensation floor, whether to restrict the analysis to your current industry, and whether to rule out paths that would require years of additional schooling or an entry-level restart.
2. **What are you looking for?** — choose **Discover paths** (the default) or **I have a target pivot in mind**. Target Pivot mode adds:
   - **Pivoting from** (optional; Claude infers it if blank) and **Pivoting to** (required), each with suggestions like Sales, Sales Engineering, Marketing, Engineering, Customer Success, and Product Management, or type your own
   - **What's drawing you to this pivot** (optional, in your own words; used as context, never embellished)
   - **Also surface adjacent careers I should consider** (on by default)
   - **Include resume repositioning for this pivot** (on by default)
3. **Output scope** — how many paths to surface (1–4 by default, adjustable), plus on/off toggles for a ranked fit table, Hidden Opportunities, a Final Recommendation summary, and next-step routing to the other JobRadar tools.

The live output panel updates as you type. Copy the prompt or download it as a `.txt`, then paste it into a Claude conversation. A downloaded prompt can be loaded back into the form later to tweak a field.

## What the generated prompt asks for

**In both modes:**

1. **Career Profile Assessment** — your strongest expertise, transferable skills, leadership capabilities, and non-obvious career patterns, separating what you're demonstrably good at from what your job titles alone suggest.
2. **Career Capital** — your accumulated professional assets, each tied to specific evidence in your background.

**Target Pivot mode only:**

3. **Target Pivot Assessment** — the evidence a hiring manager in the target function would find credible, real gaps stated plainly, the realistic entry title and level, bridge roles (for example Sales Engineering for an engineer moving into Sales), compensation impact against your floor, the fastest ways to close gaps, and a verdict: pursue directly, pursue via a bridge role, or reconsider.
4. **Resume Repositioning for the Pivot** *(optional, on by default)*:
   - **Skill Translation** table — each skill, the evidence for it, how you use it now, how the target function uses it, and suggested resume wording. Covers shared skills you apply differently (same skill, different purpose or audience) and "hidden" skills your experience shows but your resume never names.
   - **Bullet Rewrites** table — your original bullets verbatim beside versions rewritten for the target function, with what changed. Numbers and facts stay exactly as stated.
   - **Positioning Summary** — a 2–3 sentence summary aimed at the target, plus honest keywords.
   - **Gap Outline** table — every real gap, why hiring managers care, must-have vs. nice-to-have, how to close it, and how to handle it on your resume now without implying you have it.
   - **Hand-off to Resume & Cover Letter Tailoring** — two copy-ready plain-text blocks: a one-line pivot description for that tool's Pivot Positioning Notes field, and a first-person Additional context block summarizing what to emphasize and which gaps to flag.

**In both modes (optional sections):**

- **Alternative Career Paths** (Discover) or **Adjacent Career Paths to Consider** (Target Pivot, each compared against your named pivot)
- **Career Path Ranking** — a table; in Target Pivot mode your pivot is the first row, then bridge roles, then adjacent paths
- **Hidden Opportunities** — roles at the intersection of two or more of your capabilities
- **Final Recommendation** — in Target Pivot mode it opens with a direct verdict on your pivot
- **What's Next** — which JobRadar tool to run next for your top 3 paths

The output is always a downloadable Word document with real headings and real Word tables.

## Using the hand-off in Resume & Cover Letter Tailoring

Once you have a specific posting in your target function:

1. Open Resume & Cover Letter Tailoring and paste the posting and your resume as usual.
2. Paste **Block 2** from the hand-off into its **Additional context** field.
3. Check **Pivot Positioning Notes** and paste **Block 1** into the field that appears under it.
4. Generate as normal. The tailoring tool then works from your pivot-level repositioning and flags the same gaps, rather than starting from scratch.

## Important notes

- This tool **generates a prompt** — it does not itself call any AI model.
- If you paste text, more real detail (specific accomplishments, numbers, technologies, team sizes) produces a sharper analysis. If you attach a file, remember to actually attach it in Claude when you paste the prompt.
- Every resume rewording is bound by the same rule as the rest of the suite: rewording and re-emphasis only, never a new metric, title, employer, tool, or credential. Read every suggested line against your original before using it.
- Constraints and the compensation floor are instructions to Claude, not a guaranteed filter — spot-check that recommendations respect them.
- The Word document output requires the Code execution and file creation setting in Claude (Settings → Capabilities).

## Files in this repo

| File | Purpose |
| --- | --- |
| `prompt_builder.html` | The tool itself — open it in a browser |
| `index.html` | Redirects the repo's GitHub Pages root to `prompt_builder.html` |
| `Prompt_Builder_User_Guide.md` / `.docx` | Full user guide, same content in both formats |
| `sample_prompt.txt` | Real example of a Discover-mode prompt, filled in with a sample background |
| `sample_prompt_pivot.txt` | Real example of a Target Pivot–mode prompt (Engineering → Sales) with resume repositioning and adjacent paths on |

## About

Career path discovery prompt builder — Step 0 of the JobRadar tool suite, for figuring out which role to go after, or testing and repositioning for a pivot you already have in mind, before researching companies, tailoring materials, or prepping for interviews.
