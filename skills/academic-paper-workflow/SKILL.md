---
name: academic-paper-workflow
description: Support semester papers and coursework through literature search, evidence tables, source-grounded outlining and drafting, and citation verification in chat. Use for finding papers, literature reviews, research angles, academic drafts, or checking references and claim support; not for unrelated tasks merely located in that folder.
---

# Academic paper workflow

## User context and project selection

Use the user-selected project directory, or the current workspace when none is specified. Discover its current organization instead of assuming course names or paths. Match the user's conversation language; infer manuscript language from the assignment and existing draft.

Identify the active course/project from the request and current working directory. Read applicable AGENTS.md, the assignment brief, rubric, citation requirements, and relevant existing draft before proposing structure or changing prose. Use targeted file discovery; do not read every course, backups, personal records, or unrelated files. If several projects fit, ask which while doing independent useful work. A shared parent directory never licenses mixing sources or requirements between courses.

Use the existing project organization. Treat files named final or verified as starting material, not proof of currency or accuracy. Preserve originals when creating revisions unless an in-place edit is requested. The default directory does not grant filesystem permissions; use the environment's approval mechanism for writes outside permitted roots.

## Select the requested stage

Do only the stages needed for the current request. A citation check need not trigger a full rewrite; a writing task need not trigger a systematic review. This is a chat-native workflow using available browsing, file, and document tools, without the upstream application's server, database, or model API keys. Discover current tools rather than assuming API credentials or services exist.

- **Find literature or build an evidence table:** read [references/research-and-verification.md](references/research-and-verification.md). Search real records, screen against the assignment, and record what evidence was actually accessible.
- **Develop a research angle or outline:** compare candidate arguments against the collected evidence and rubric. Distinguish a plausible gap within the searched pool from demonstrated field-wide novelty. Map section claims to source IDs and allocate words using the assignment limit.
- **Draft or revise:** ground sourced claims in the evidence ledger. Preserve the user's argument, numbers, and authorial voice. Use relevant available writing-style skills for substantive prose and document/PDF skills when those formats require inspection or editing. Separate source findings from the user's analysis. Never invent experiments, participants, results, quotations, or search methods. Missing evidence should become a clearly identified gap or a narrower supported claim.
- **Verify references or review a draft:** read the verification reference. Distinguish source existence from support for the particular claim. Report actionable findings with location, source, and proposed correction; modify only the authorized scope. Simulated review is optional when requested and should be identified as simulated.

## Keep semester work resumable

For substantial multi-step work, keep a compact project-local research record alongside the relevant draft, using existing records when available. A `research-notes` directory is a fallback, not a required reorganization. Record project objective, assignment constraints, current draft path, decisions, unresolved questions, source/evidence ledger, and next step. Log actual search dates, queries, sources, and screening decisions when searching. Create only the records useful for this task; short chat answers do not need bookkeeping files.

At continuation, read relevant records and the current draft before relying on old chat context. Keep stable source IDs across revisions. Explain what changed, what was verified, what remains unresolved, and link any delivered files. Do not imply that installing this skill indexes the folder, monitors files, or retains all prior conversations.

## Provenance

This is an independently written chat workflow informed by the publicly documented retrieval, evidence-table, drafting, and citation-checking stages of [Open Academic Paper Gen](https://github.com/mmlong818/open-academic-paper-gen). It does not bundle or execute upstream code and is not an official integration or a deployment of that application.
