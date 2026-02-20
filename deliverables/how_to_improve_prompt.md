# How to Improve Future Prompts

1. **State Success Criteria Up Front.** Open with a bullet list of required documents, desired formats, and where they must live (e.g., "Create `/deliverables` with NDA.md, GDPR.md...") so nothing is inferred.
2. **Provide Clause Priorities.** Rank which clauses or constraints are critical versus optional. Example: "Mandatory: 5-hour bundle, non-rollover, RACI table. Optional: suggestions for additional clauses."
3. **Clarify Placeholder Handling.** Specify whether placeholders should be capitalized, bracketed (e.g., `[AMOUNT]`), or accompanied by guidance text to simplify later edits.
4. **Define Tone & Jurisdiction.** Indicate governing law, industry vertical, and tone (formal, plain language, etc.) to align drafting style without guesswork.
5. **Reference Source Material.** If templates exist, point to them ("Base the NDA on `/templates/nda_v2.md`") or link to policy requirements to ensure consistency.
6. **Request Validation Steps.** If you need verification (tests, linting, or review), ask explicitly ("Run `markdownlint` on deliverables").
7. **Suggest Example Inputs.** Provide sample numbers when asking for placeholders ("Assume 5-hour bundle at $250/hour"), making it easier to validate clause math while still keeping fields editable.
8. **List Meta-Deliverables Separately.** Separate document drafting from meta files (prompts, logic, improvements) so it's obvious what's content vs. documentation.
