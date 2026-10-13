# ResearchOps HackPack Agent Instructions
This is the consumer toolkit. Start with [README.md](README.md). The researcher authors the inquiry and chooses methods; the initial agent skills prepare blank files and folders.

## Choose the Requested Operation
Read the relevant file explicitly; these skills do not require a globally installed skill library.
- Workspace orientation and preparation: [setup-research-repo](skills/setup-research-repo/SKILL.md).
- One project and its blank brief: [create-research-project](skills/create-research-project/SKILL.md).
- One trial and its blank method-specific documents: [create-research-trial](skills/create-research-trial/SKILL.md).
- One interview or user-test session's blank notes: [create-research-session](skills/create-research-session/SKILL.md).

Keep these operations separate. Setup is not permission to create a project, and creating a project is not permission to create trials. A runbook describes human work and handoffs; reading it does not authorize performing them.

## File Setup Boundaries
Copy from `templates/`, never from `examples/`. Substitute only supplied administrative information such as names, paths, method, and observer identifiers. Leave research questions, hypotheses, recruitment choices, scripts, analysis, findings, and recommendations for the researcher. Do not infer these from an example or project name.

Resolve the toolkit root from this file and the template paths below it, independently of the current working directory. Ask for missing destinations or choices that affect the requested operation. Inspect existing paths and resolve symbolic links before writing; never overwrite, delete, or merge existing research as an automatic setup step. If the requested target exists, report what is there and ask whether to use it unchanged or choose another name. A repeated request must not silently create duplicates.

No dependencies beyond file access are needed for the skills; obtaining a checkout uses Git or the user's download method. A missing tool is a limitation to explain, not permission to install software. Tracker integrations are optional future work. Do not publish, change remotes, commit, push, schedule participants, or write to external systems without a separate instruction.

## Maintaining the Toolkit
When explicitly asked to develop the kit, trace changed template and runbook links into skills, examples, and GitHub issue forms. Update affected dependencies together. The portable Markdown runbooks own the workflow; GitHub forms adapt it. Worked examples may adapt a template's prompts, but must stay coherent and link to their source templates. Label invented material clearly, including in individually opened documents.

Keep research content blank in templates and personal context out of public toolkit files. Use portable relative references and plain Markdown; do not embed a maintainer's filesystem paths or global skill dependencies. Do not add unnecessary folder READMEs. Preserve unrelated work and honor any requested review-before-commit period.
