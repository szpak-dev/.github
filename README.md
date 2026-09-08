# szpak-dev organization defaults

This repository contains the shared issue forms, pull request template, and contribution policy for repositories in the **szpak-dev** organization.

The organization Project template is [Repository Delivery](https://github.com/orgs/szpak-dev/projects/10).

## What is shared

- Bug and task issue forms
- Pull request structure and verification checklist
- Issue-content and board-ownership policy
- The Repository Delivery Project template with its Kanban view, fields, and lifecycle workflows

A repository-local `.github/ISSUE_TEMPLATE` directory overrides the organization issue forms.

## Project-template boundary

GitHub Project templates are provisioning snapshots, not live inheritance. Projects created from Repository Delivery receive its views, fields, configured workflows, and insights at creation time. They do not receive existing issues, repository or team links, collaborators, or repository-specific auto-add workflows.

## Repository bootstrap

For every maintained repository:

1. Create a Project from Repository Delivery and rename it for the repository.
2. Link only that repository.
3. Configure auto-add for issues from that repository.
4. Ensure the standard labels exist: `type:bug`, `type:maintenance`, `contract`, and `release-gate`.
5. Verify the item-added, reopened, closed, linked-pull-request, and merged-pull-request workflows.
6. Create a release-gate issue and use native blocked-by relationships.
7. Keep repository issues as the source of truth; do not duplicate issues across boards.

Mermaiden's operational board was the source for version 1 of this template. It remains independent and will not be altered by later template changes.
