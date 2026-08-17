# Career Path Discovery Prompt Builder

A free, browser-based tool that turns a form into a ready-to-paste prompt for Claude — the prompt asks Claude to analyze your career background like a career strategist and executive recruiter would, and surface realistic alternative career paths grounded in your actual experience, before you've settled on a specific role to target.

**No installation needed.** Open `prompt_builder.html` in any modern browser. Paste your background, fill in what applies, copy or download the generated prompt, and paste it into a Claude conversation (web search recommended, for checking current role/salary norms) to get the actual analysis. Nothing you enter is sent anywhere — this page only builds text locally in your browser.

## Where this fits

This is **Step 0** in the JobRadar tool suite — it runs *before* Target Company Prompt Builder, not after. The rest of the suite assumes you already know what role you're going after:

- **Not sure what to target next** → start here (Career Path Discovery)
- **Know your target, need companies** → Target Company Prompt Builder
- **Have a posting, need materials** → Resume & Cover Letter Tailoring / Outreach Message Builder
- **Have an interview, need prep** → Interview Prep Guide Builder
- **Have an offer** → Salary Negotiator

This tool stops at "here's what to go after and why." It doesn't rewrite your resume or LinkedIn, and it doesn't prep you for objections — those stay with the tools built specifically for that job, so nothing here duplicates work another tool in the suite already does well.

## How it works

The page is a single form with two fieldsets:

1. **Your background** — paste your resume, LinkedIn About/Experience sections, or a written summary of your career history. This is the only required field; everything else is optional. You can also add hard constraints (things genuinely off the table, not just preferences), a minimum compensation floor, whether to restrict the analysis to your current industry, and whether to rule out paths that would require years of additional schooling or an entry-level restart.
2. **Output scope** — toggle which sections the generated prompt asks for: a ranked fit table, a "Hidden Opportunities" section (roles at the intersection of two or more of your capabilities, not just title-matching), a Final Recommendation summary, and next-step routing to the other JobRadar tools.

The live output panel updates as you type. Copy the prompt or download it as a `.txt`, then paste it into a Claude conversation.

## What the generated prompt asks for

1. **Career Profile Assessment** — your strongest areas of expertise, most valuable transferable skills, leadership/strategic capabilities, and career patterns that may not be immediately obvious, separating what you're demonstrably good at from what your job titles alone suggest.
2. **Career Capital** — the professional assets you've accumulated (executive communication, complex sales, technical expertise, partner development, and so on), each tied to specific evidence in your background.
3. **Alternative Career Paths** — 8–12 realistic paths by default (adjustable), mixing natural adjacent moves, less obvious but highly transferable roles, leadership and individual-contributor options, consulting/advisory work, and roles outside your current industry — evaluated the way a hiring manager actually would, not just what you could theoretically do.
4. **Career Path Ranking** *(optional)* — a table scoring each path on transferability, employer credibility, compensation potential, availability, retraining required, durability, network leverage, and advancement potential.
5. **Hidden Opportunities** *(optional)* — roles at the intersection of two or more of your capabilities (e.g. technical expertise + communication, sales + strategy) rather than a title-to-title match.
6. **Final Recommendation** *(optional)* — best immediate pivot, best higher-compensation path, best long-term path, best lower-risk path, most overlooked opportunity, and one path to probably avoid, each with a reason.
7. **What's Next** *(optional)* — for your top 3 paths, which JobRadar tool to run next and why.

## Important notes

- This tool **generates a prompt** — it does not itself call any AI model. You paste the output into a separate Claude conversation to get the actual analysis.
- Not a file upload — paste your background as text directly. More real detail (specific accomplishments, numbers, technologies, team sizes) produces a sharper analysis; generic resume-objective boilerplate doesn't give Claude much to work with.
- This tool deliberately does **not** cover resume rewriting, LinkedIn repositioning, or interview objection-handling — see "Where this fits" above for which tool owns each of those.
- Constraints and the compensation floor are instructions to Claude, not a guaranteed filter — spot-check that recommendations actually respect them.

## Files in this repo

| File | Purpose |
| --- | --- |
| `prompt_builder.html` | The tool itself — open it in a browser |
| `Prompt_Builder_User_Guide.md` / `.docx` | Full user guide, same content in both formats |
| `sample_prompt.txt` | Real example of the generated prompt, filled in with a sample background |

## About

Career path discovery prompt builder — Step 0 of the JobRadar tool suite, for figuring out which role to go after before researching companies, tailoring materials, or prepping for interviews.
