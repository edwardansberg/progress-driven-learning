# Learning bundles

[Core policy](../README.md) owns behavior and evidence rules. Use [UNIT_TEMPLATE.md](UNIT_TEMPLATE.md) for a retained capability; keep only useful fields. A brief session can end with a next action without creating a bundle.

## Unit identity and placement

Use a stable readable ID, for example U-acceptance-criteria, and a portable folder such as docs/learning/units/acceptance-criteria/. Create it only when it holds a real selected unit. IDs survive renames. A source/course is not the unit ID; several sources can support one capability.

For a small unit, one unit.md may hold capability, materials, labeled notes and current assessment. For important attempts, use distinct attempt-01.md and feedback-01.md (or clearly separate immutable sections). Add revision-01.md or an artifact file only when needed. Do not precreate empty source/notes/visual folders.

## One home per content type

- unit.md: Capability, why, criteria, relevant prerequisite/gap, current assessment linked to evidence, remaining gap and review rationale. Link the current session/next action to detailed state instead of maintaining a second active session.
- Materials section or sources.md: Source IDs, title, URL/accessible reference, page/section, version/date consulted and verification limits.
- Labeled notes section or notes.md: Learner notes and AI explanation in separate labeled sections; cite source IDs. Preserve permitted excerpts as source content.
- attempt-NN.md: Original task/response and agreed/actual conditions. Never replace it with a polished answer.
- feedback-NN.md: Assessor, criterion findings, limitations and suggested next practice. Link the original; identify AI-generated examples/rewrites explicitly.
- revision-NN.md: A later learner correction or revised artifact, linked to the original and feedback; label the assistance used.
- A retained visual: Put a useful named SVG/PNG/other artifact beside its topic or in a populated visuals/ folder; link it from notes/unit, include text description, sources, assumptions and illustrative/approximate limits.

Use relative links inside the workspace, accessible external references outside it, and a versioned copy/reference for mutable evidence. An absolute local path alone is not a cross-session reference. No new application, renderer or synchronization service is implied.

## Minimal important attempt

Record Unit/task ID; actual date; task; agreed criteria; permitted resources; actual help including hints/solution exposure; observed versus learner-reported conditions; original response/artifact; feedback link; limitations; revision/correction link if any; and next-action link. Keep the exact supplied original response. Do not invent an answer, score or assistance report.

Feedback evaluates the agreed criteria with findings and support, names assessor/source/date, states limits and suggests next practice. The unit owns the current synthesis; detailed state owns current next action and the dated cross-unit review queue. See [record ownership](../README.md#record-ownership).

## Practical file/agent use

1. Start/resume using [the explicit bootstrap](../README.md#saving-and-resumption). Ask for explanation, guided practice, assessment or artifact production; mode can change when requested.
2. Add a source by supplying its title/link and useful section/page. Ask the agent to read it if access exists; otherwise mark it unverified and supply a permitted excerpt.
3. Say “Save my following text as my original attempt” or “Save this as my notes”; confirm the intended unit when ambiguous. Check the destination before editing.
4. Ask for criterion-based feedback or a visual explanation. Label generated explanations and keep them distinct from your response and sources.
5. Close with the selected evidence, gap and next action. Update unit assessment, then detailed state, then its overview revision; change context/roadmap only for their owned facts.
6. Revisit the saved original and feedback before choosing new practice. Use a fresh unexposed task for later independent evidence, then a learner-chosen delayed review date/trigger.

[Saving rules](../README.md#saving-and-resumption) govern conflicts, partial writes and unsaved drafts. A successful local reopen verifies that write in that environment only.

## Reusable exercise bundles

The [fictional example](examples/fictional-intake/README.md) contains synthetic data at both bundle and record level. Never copy its assessments, dates or next steps into real progress/review queues.

The [requirements pilot](pilots/requirements/README.md) is prepared and unrun. Selecting it starts a new real unit/session; it does not activate merely by existing. Its [save scaffold](pilots/requirements/SESSION_TEMPLATE.md) is not a learner response.

Solutions and AI rewrites belong in separate labeled feedback/material records, away from the initial task. File separation is a reading convention, not secure examination software; a learner can open files and outside help cannot be ruled out.
