---
name: setup-research-repo
description: "Orient a ResearchOps HackPack checkout and prepare a working location. Use for initial workspace setup, without creating a project or trial."
---

# Set Up a Research Workspace
Read the toolkit's [agent instructions](../../AGENTS.md) and [README](../../README.md). This skill begins with an available checkout; the README's getting-started prompt handles cloning first. File access is sufficient after that. No global skills, packages, or integrations are required.

## Workflow
1. Locate the toolkit root from this skill folder (`../..`) and verify that `templates/`, `examples/`, and the four skill files exist. If the kit is incomplete, report what is missing rather than reconstructing it from memory.
2. Ask where the researcher wants actual work to live if they have not supplied a location. Offer `research/` inside the checkout or a chosen external directory. Explain that the kit's `research/` is Git-ignored by default; an external location has its own storage and version-control arrangements.
3. Inspect and resolve the selected path. Never choose `templates/`, `examples/`, `skills/`, `.github/`, or `guides/` (or a location within them) as the working area. Do not use the toolkit root itself as the working area. If a selected directory already exists, report its contents and use it unchanged only when the user has chosen it for this purpose. Stop on a file/directory conflict or uncertain target instead of overwriting or merging.
4. Create only the selected working directory if needed. Do not copy examples or create a project, trial, session, hidden settings, or synthetic research content. Do not initialize another repository or change Git configuration.
5. Show the absolute workspace location in the conversation, link the blank templates and fictional examples, and explain the next optional request: use [create-research-project](../create-research-project/SKILL.md) when the researcher is ready to name a project. Stop here unless a separate operation was also requested.

## Completion Check
The selected working directory exists; existing contents are unchanged; no research instance was created. Report any limitation honestly. A second setup run should inspect and reuse the chosen directory, not duplicate or reset it. The prompt or skill does not authorize commits, publishing, tracker setup, or substantive research work.
