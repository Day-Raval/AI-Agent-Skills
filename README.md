# AI Agent Skills

Reusable AI agent skills for real workflows in careers, finance, healthcare and the enterprise.

Each skill follows one rule: **outputs must be verifiable.** Facts come from the user's own data, figures are computed by code, and claims are checked against exact source quotes before an answer is returned.

| Skill | Domain | What it does |
| --- | --- | --- |
| [jd-resume-tailor](https://github.com/Day-Raval/jd-resume-tailor) | Careers | Tailors a resume to one job description using only facts from your own portfolio bank, and reports unsupported requirements as gaps instead of inventing them. Listed in Anthropic's Claude plugin directory. |
| [txn-statement-analyzer](https://github.com/Day-Raval/txn-statement-analyzer) | Finance | Turns a bank or card statement CSV into a spending summary where every figure is computed by a script and tied to its source rows. |
| [discharge-summary-structurer](https://github.com/Day-Raval/discharge-summary-structurer) | Healthcare | Converts hospital discharge summaries into schema-validated JSON (diagnoses, medication changes, allergies, follow-ups), with each fact checked against a verbatim quote. |
| [policy-qa](https://github.com/Day-Raval/policy-qa) | Enterprise | Answers questions about company policy documents, citing a policy section with an exact quote for every sentence and rejecting answers whose quotes or numbers don't match. |

## Works with

Claude Code, Claude.ai, OpenAI Codex, Gemini CLI, Cursor and GitHub Copilot. See each skill's README for install steps (installer script, Claude Code plugin, or a zip upload for Claude.ai).

## Why I built these

I'm learning agent design by shipping real tools, one skill at a time. Each one explores a different pattern: grounding in user data, code-computed figures, quote-verified extraction and cited retrieval.

---

Built by [Dayesh Raval](https://github.com/Day-Raval) · More skills coming.