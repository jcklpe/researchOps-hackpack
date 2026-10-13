---
name: create-research-trial
description: "Create a blank interview, survey, or user-testing trial inside a selected research project. Use after the researcher supplies a method and trial name."
---

# Create a Research Trial
Follow [AGENTS.md](../../AGENTS.md). This operation copies blank documents for one round of research; it does not design that round.

## Inputs and Sources
Obtain the existing project location, trial name, and method chosen by the researcher. Ask for missing choices; do not select a method from a project title or invent goals. If another method is requested, explain the available plans and discuss an adaptation before creating it.

| Researcher's method | Source plan in toolkit root | Destination filename |
| --- | --- | --- |
| Interview | `templates/trial-plan-interview.md` | `trial-plan-interview.md` |
| Survey / questionnaire | `templates/trial-plan-survey.md` | `trial-plan-survey.md` |
| User testing / usability testing | `templates/trial-plan-user-testing.md` | `trial-plan-user-testing.md` |

Also copy `templates/trial-brief.md` and `templates/trial-report.md` with their existing filenames. Sources resolve from the toolkit root, two levels above this skill folder.

## Workflow
1. Verify the chosen project exists and locate its project brief. If the brief is missing or has another name, clarify the correct context rather than inventing a project. Resolve the target path and keep the new trial inside that project, outside the toolkit's template/example/instruction directories. Use a single folder-name component derived from the supplied trial name.
2. Inspect for a collision. If the trial target exists, show it and ask whether to use it unchanged or choose a new name; do not overwrite or merge.
3. Create the trial folder, copy the three documents identified above, and create an empty `artifacts/` directory. Do not copy example answers or create a session, questionnaire responses, or a recruitment tracker.
4. Substitute the supplied trial name and method in the brief/report. Replace the brief's `{project brief location}` with a relative Markdown link to the verified project brief. Add a relative link to the selected plan under Methodology. The plan and report already link to `trial-brief.md` alongside them. Keep substantive prompts blank, including questionnaire items, interview questions, user-test tasks, and recommendations.
5. Verify the copied filenames, links, and empty artifacts directory. Report the paths and the researcher's next work: fill in the brief and plan. For an interview or user test, a later explicit request can use [create-research-session](../create-research-session/SKILL.md). A survey uses trial-level datasets instead of one session per response.

The [trial runbook](../../templates/runbooks/trial-runbook.md) describes planning, recruitment, collection, and reporting. File creation does not carry out or approve any of those stages.
