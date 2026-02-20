# Prompting Guidance for Future Requests

## 1. Structure the Request
- Start with a short checklist of deliverables, e.g. "Need NDA, MSA, GDPR addendum, POPIA addendum, Contracting Agreement, plus prompt-tracking files." This keeps scope tight.
- Specify tone, governing law, and industry context up front ("Use South African law and a practical, plain-English style for managed infrastructure services").
- Call out must-have clauses ("Include bundle rollover ban, RACI table, coordinator requirement") separately from optional ideas.

## 2. Define Placeholder Rules
- Explain how placeholders should look (e.g., `[AMOUNT_ZAR]`, `{{PAYMENT_METHOD}}`) so you can find and replace them easily later.
- Provide sample numbers purely for context if that helps verify math, but note they are examples.

## 3. Describe Meta Deliverables
- When you need prompt histories, logic write-ups, or improvement notes, list each required filename and what should go inside.
- Mention formatting preferences ("Use plain English", "Add Mermaid diagrams") near each meta deliverable.

## 4. Request Validation Steps
- If you expect sanity checks (e.g., "confirm all files reference South African law"), ask for them explicitly so they show up in the logic log.

## 5. Suggested Starter Files
Consider beginning every legal-doc project with:
- `README.md` — quick summary of goals and required outputs.
- `requirements.md` — detailed list of clauses, placeholders, and formatting constraints.
- `timeline.md` — target dates, review owners, and sign-off steps.
- `glossary.md` — definitions for recurring legal or technical terms.
- `project_init/project_init.md` — a pre-filled template (see the included example) describing the initial file tree and checklists for new contributors.

Using these files keeps future prompts shorter because you can reference them directly ("follow requirements in `requirements.md` and update the glossary").
