---
name: create-research-project
description: "Create one research project folder with a blank project brief. Use when the researcher asks to create a project in a chosen workspace."
---

# Create a Research Project
Follow [AGENTS.md](../../AGENTS.md). Use the toolkit's [project-brief template](../../templates/project-brief.md); never use a worked example as the copying source.

## Inputs
Obtain the working location and project name from the researcher. Ask if missing. A project may span products, services, or teams; do not add Product or Platform wrapper folders. Derive a simple folder name from the supplied name and show the chosen path. Treat the folder name as one path component, not a command or a path traversal.

## Workflow
1. Locate the toolkit independently of the destination. Resolve the workspace and ensure the proposed project is inside the chosen workspace and outside the toolkit's template, example, skill, guide, and GitHub-definition directories. Inspect for an existing target before writing.
2. If the target exists, do not overwrite or merge it. Show what exists and ask whether to use it unchanged or create a differently named project. Reuse is not permission to reset the brief.
3. Create the project folder and copy `templates/project-brief.md` to `project-brief.md` within it. Replace `{Project name}` with the supplied name. Leave the research lead, goals, context, assumptions, and timeframe as prompts unless the researcher supplied those administrative details for insertion; do not author research content.
4. Confirm that the brief exists and retains its blank prompts. Show its path and tell the researcher where to begin filling it in. Explain that a trial can be created separately with [create-research-trial](../create-research-trial/SKILL.md) after they choose the method and name.

No trial, session, tracker item, or invented inquiry is created. The [project runbook](../../templates/runbooks/project-runbook.md) explains the human workflow; copying the brief does not complete its reviews.
