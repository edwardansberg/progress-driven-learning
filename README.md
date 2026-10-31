# Progress-Driven Learning v0.1

A lean framework for learning with ChatGPT, Codex and ordinary files. Define a human capability, study useful sources, practice, preserve selected attempts and revisit the remaining gaps. Activity supports learning; observable performance supports a capability claim.

## Derivation provenance

Source: [Progress-Driven SDLC](https://github.com/edwardansberg/progress-driven-sdlc)
Verified source revision: [04765e32d8832a9b80fddd0b3875234386891d14](https://github.com/edwardansberg/progress-driven-sdlc/tree/04765e32d8832a9b80fddd0b3875234386891d14)
Basis: All 19 inherited tracked paths and Git blob SHAs matched this pinned snapshot before adaptation.
Adaptation: Learning lifecycle, evidence records and session modes replace software delivery scaffolding; continuity, human ownership and proportionate work are retained.

This is derivation of the framework. A learner workspace records the later learning-framework version it actually adopts in [learner context](docs/context.md#workspace-adoption); neither this repository's first commit nor this source revision is that future release.

## Start learning

1. Create your own repository with GitHub's **Use this template** when available, using the default branch only; leave **Include all branches** unchecked. Alternatively, copy the neutral starter files into an authorized workspace. Read [agent entry](AGENTS.md) and [learning policy](docs/README.md#start-here) explicitly. Keep one writer at a time.
2. State one capability you want to develop and a mode: explanation, guided practice, assessment or artifact production. Background may stay unknown until it matters.
3. Use the [unit template](docs/learning/UNIT_TEMPLATE.md) when retaining a unit; agree on observable criteria and select useful sources. A chat-only explanation need not create records.
4. Save selected attempts, separate feedback and one next action using [bundle conventions](docs/learning/README.md). Resume from [detailed learning state](docs/progress-agent.md); [the overview](docs/progress.md) is a derived view.

For a ready exercise, open the [prepared requirements pilot](docs/learning/pilots/requirements/README.md). It has not been run. The separate [fictional example](docs/learning/examples/fictional-intake/README.md) demonstrates records and is excluded from learner progress.

Example request: “Use the prepared requirements pilot in guided practice. Let me attempt it before hints. Save my original response and separate feedback if this session has write access.” Requesting a direct explanation or solution is also welcome.

## Choose the route

Learning use: [Canonical policy](docs/README.md), [unit/material conventions](docs/learning/README.md), [context](docs/context.md) and [roadmap](docs/roadmap.md). Routine study has no branch-per-session rule or development approval cycle.

Framework changes: [Maintainer procedure](docs/ops/maintain-template.md). An optional local docs/maintenance/progress.md owns development evidence when needed; it is omitted from the reusable starter after durable preservation. Framework work never counts as learner progress. This starter grants no publication rights to another workspace.

Existing workspace: [Adopt or update](docs/ops/adopt-framework.md) selectively, preserving your records and local instructions. Template generation copies the starter files rather than the source Git history; cloning or forking is a different operation. Keep each learner's context, priorities and evidence in their own workspace.

## First-version limits

v0.1 is a file-based framework with neutral learner records. Its initial development baseline was accepted; that acceptance does not establish learner competence or practical learning validation. No application, database, scheduler, installed reminders, automatic shared memory, synchronization or ChatGPT–Codex transport is supplied. Verify file/connector access and instruction loading in each client; links alone load nothing. A local path does not give another session access. Cross-client transport has not been validated.

AI feedback is formative, with stated limits; it is not professional certification or employer recognition. Files do not provide secure examinations or verify undisclosed assistance. Real learner validation, the pilot and delayed review remain pending.

## License

The framework's documentation and templates are available under the [MIT License](LICENSE). Linked third-party sources retain their own terms; this grant does not relicense them.

## Later interactive workspace

A future interface may expose Today (focus, next action, review queue), Materials (sources, notes, visuals), Practice (tasks, original responses, feedback, revisions) and Progress (capabilities, evidence, gaps, workplace application). These views must use the [same authoritative records](docs/README.md#record-ownership).

Editable controls require a real save mechanism, conflict handling and honest draft/saved states. No browser application or editable static snapshot is implemented in v0.1.
