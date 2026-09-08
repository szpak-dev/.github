# Contribution and delivery policy

## One repository, one delivery board

Each maintained repository owns a separate GitHub Project created from the **Repository Delivery** organization template. Repository issues are the source of truth. Do not duplicate or move issues between repository boards; represent cross-repository sequencing with links or native issue dependencies.

After creating a project from the template:

1. Rename it for the repository.
2. Link only that repository.
3. Configure an auto-add workflow scoped to that repository.
4. Ensure the standard labels exist.
5. Verify item-added, reopened, closed, and merged lifecycle workflows.
6. Create the repository release-gate issue and attach native blockers.

GitHub does not copy auto-add workflows, repository links, collaborators, or existing issues from a Project template, so these steps are intentionally repository-specific.

## Issue content

- File defects with the Bug form and planned changes with the Task or proposal form.
- Search for duplicates and verify any reproduction before filing.
- Include only the project problem, actual and expected behavior, runnable verification, and acceptance criteria.
- Exclude conversation history, caller context, agent instructions, credentials, private data, internal audit output, and absolute, local, or temporary paths.

## Classification

- Repository labels encode work type and release gates.
- Project Status represents flow.
- Priority represents scheduling urgency.
- Area represents the affected subsystem.
- Size represents relative effort.
- Milestones group release work.
- Native blocked-by relationships represent sequencing and release gates.
- Parent issues and sub-issues represent decomposition.
