---
name: create-research-session
description: "Prepare blank field notes for one interview or user-test session in an existing trial. Use for session file setup, not survey response collection."
---

# Create a Research Session
Follow [AGENTS.md](../../AGENTS.md). Use the [field-note template](../../templates/field-notes.md) for a requested interview or user-test session. Survey datasets belong at trial level; explain that distinction instead of creating a survey session automatically.

## Inputs
Obtain the trial location and session identifier, such as `session-01`. Read the trial brief to verify the method and locate the actual plan. If they are missing or ambiguous, ask rather than inferring from nearby examples. Observer and participant identifiers are optional; leave placeholders when unknown. Do not request contact details just to create notes.

## Workflow
1. Verify that the chosen trial is actual research work outside the toolkit's templates/examples/instruction directories. Resolve the target under its `artifacts/` directory, using the session identifier as one folder-name component. Inspect any existing target; on collision, ask whether to use it unchanged or choose a different identifier. Never overwrite existing notes.
2. Create only `artifacts/<session-identifier>/` and the requested blank notes. With no observer list, copy `templates/field-notes.md` to `field-notes.md`. For multiple named observers, make one copy per observer with distinct filenames such as `field-notes-observer-a.md`; resolve name collisions before writing.
3. Insert only supplied identifiers and date. Replace `{plan location}` with a relative link from the notes to the verified trial plan. Leave observations, participant responses, and interpretations unwritten. Do not fabricate transcripts, recordings, or findings.
4. Check that the notes link to the correct plan and that each observer's file is distinct. Show the created paths. File setup does not schedule, recruit, conduct, or record a session.

See [research-artifacts.md](../../guides/research-artifacts.md) for grouping later material from the same encounter. Do not create every illustrated artifact in advance.
