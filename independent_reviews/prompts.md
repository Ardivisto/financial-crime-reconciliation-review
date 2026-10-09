# Separate AI conversation prompts

These are path-redacted records of the two dispatch prompts. They differ only by reviewer label and output filenames. Both conversations began without earlier chat turns. Both received the same source archive and blank official template, identified by the SHA-256 hashes in [README](README.md). No published submission or other review was sent to either reviewer.

## Conversation A

> You are independent AI reviewer A for case DPI-HT-01. Perform a fresh analysis using ONLY the 12 original case files in `03 CASE FILES - Open and Investigate-20261008T152707Z-1-001.zip` and the BLANK official template `01 GIVE TO CODEX - Answer Template.json`. Do not read any existing answers, app.js, submission.json, review_report.md, prior analyses, other agent output, or this chat. Extract/read source files as needed in your own temporary directory. Examine all 25 material decisions D041–D049, D056–D059, D064–D068, D071–D075, D091, D100. For EACH: independent proposed treatment, original source file plus page/row evidence, ambiguity/limitation, effect on profit/cash/noncash assets/liabilities/equity (state overlaps, no double counting), and reasoning. Include overall PBT basis and board recommendation. Preserve genuine uncertainty; do not invent payroll/insurance detail. Write a standalone report and structured JSON. Do not submit, certify, or change the public site.

[Read conversation A response](dialogue_A.md) · [25 structured entries](dialogue_A.json)

## Conversation B

> You are independent AI reviewer B for case DPI-HT-01. Perform a fresh analysis using ONLY the 12 original case files in `03 CASE FILES - Open and Investigate-20261008T152707Z-1-001.zip` and the BLANK official template `01 GIVE TO CODEX - Answer Template.json`. Do not read any existing answers, app.js, submission.json, review_report.md, prior analyses, other agent output, or this chat. Extract/read source files as needed in your own temporary directory. Examine all 25 material decisions D041–D049, D056–D059, D064–D068, D071–D075, D091, D100. For EACH: independent proposed treatment, original source file plus page/row evidence, ambiguity/limitation, effect on profit/cash/noncash assets/liabilities/equity (state overlaps, no double counting), and reasoning. Include overall PBT basis and board recommendation. Preserve genuine uncertainty; do not invent payroll/insurance detail. Write a standalone report and structured JSON. Do not submit, certify, or change the public site.

[Read conversation B response](dialogue_B.md) · [25 structured entries](dialogue_B.json)

The public records include the prompts and final written responses, not the reviewers’ private tool-call traces. The local filesystem paths and output instructions were shortened in this public copy. A second common follow-up requested structured JSON fields for each decision; it supplied no other analysis or answers.
