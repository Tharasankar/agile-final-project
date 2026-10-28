# Agile Final Project — Kanban Setup

This repository is being prepared to track user stories and sprint delivery.

## Kanban board

Create a GitHub Project (Board view) named **Agile Final Project Kanban** with these Status values, in this order:

1. Product Backlog
2. Sprint Backlog
3. In Progress
4. Review/QA
5. Done

Add a custom **Estimate** number field for story points. Show the Estimate field on cards or in the table view.

## User-story format

Use the repository issue template at `.github/ISSUE_TEMPLATE/user-story.md`.

Every story should include:
- **User story:** `As a [role], I need [function], so that [benefit].`
- **Acceptance criteria:** Gherkin scenarios using `Given [context], When [action], Then [outcome].`
- **Estimate:** story points such as 1, 2, 3, 5, or 8.
- **Requirement number:** the corresponding requirement from the project brief.

## Labels

Apply at least one type label to every issue. Recommended labels:
- `enhancement` — product capability or user-facing improvement
- `bug` — incorrect behavior
- `technical debt` — refactoring, maintainability, testability, or infrastructure work

Requirements **9** and **10** must be labeled `technical debt` (use the exact label name requested by the project rubric if capitalization differs).

## Sprint and ownership

Create a milestone named **Sprint 1** (add start/end dates if your course requires them). Link every story in a non-empty board column to this milestone. Assign stories in **In Progress**, **Review/QA**, and **Done** to `Tharasankar`.

## Burndown / progress chart

GitHub milestone pages show open/closed issue progress, but a story-point burndown chart generally needs a Project chart or an external chart. In the GitHub Project:
1. Ensure all sprint stories have numeric Estimate values.
2. Add a chart/insights view that tracks remaining estimate by date if the available chart settings support it.
3. If a true daily burndown is unavailable, maintain a daily remaining-points log and chart it separately.

## Completion checklist

- [ ] Create the Project board and five Status values in the order above.
- [ ] Create all user-story issues from the official project requirements.
- [ ] Apply a label to every story; label requirements 9 and 10 as `technical debt`.
- [ ] Estimate every story in **In Progress** and **Done**.
- [ ] Create the **Sprint 1** milestone and link every story in a non-empty column.
- [ ] Assign all stories in **In Progress**, **Review/QA**, and **Done** to `Tharasankar`.
- [ ] Configure a sprint burndown/progress chart.

> Note: This repository was empty when setup began. Populate the issue list from the actual project brief before assigning story numbers, estimates, and workflow statuses; do not invent requirements.
