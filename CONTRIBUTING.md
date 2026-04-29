# Contributing to BOS

Thank you for helping shape BOS. This repository is still in an early,
documentation-first stage, so thoughtful planning, issue refinement, and clear
pull requests are just as valuable as code.

## Before You Start

- Check the open issues to avoid duplicating work.
- If no issue exists, open one that explains the problem, the proposed
  improvement, and the expected benefit.
- Keep each pull request focused on one feature, fix, or documentation task.

## Local Setup

There is no application build pipeline in this repository yet. For now, the
main setup steps are:

```bash
git clone https://github.com/bos-com/BOS.git
cd BOS
```

Use a Markdown-friendly editor and preview your documentation changes before
submitting them.

## Branch Naming

Use descriptive branch names that match the type of work being done:

- `docs/<short-topic>` for documentation improvements
- `feat/<short-topic>` for new features or scaffolding
- `fix/<short-topic>` for bug fixes
- `chore/<short-topic>` for maintenance tasks

Examples:

- `docs/readme-quick-start`
- `feat/service-layout`
- `fix/broken-links`

## Pull Request Expectations

Each pull request should:

- reference the related issue number,
- explain the problem being solved,
- summarize the change,
- describe how you verified it, and
- note any follow-up work that remains.

If your change affects documentation or contributor workflow, include before and
after context so reviewers can quickly understand the improvement.

## Documentation Standards

- Prefer clear, direct language over placeholders.
- Keep setup instructions honest to the current repository state.
- Do not describe commands or services that do not yet exist in the repo.
- Use consistent Markdown headings and code fences.

## Reporting Issues

When opening an issue, include:

- a short, specific title,
- the current problem or gap,
- the proposed improvement,
- why it matters, and
- any relevant screenshots, logs, or links.

Starter issue templates are available in `.github/ISSUE_TEMPLATE/`.

## Review Checklist

Before opening a pull request, make sure:

- the change is scoped to the issue,
- file names and headings are consistent,
- links and commands are correct,
- documentation reflects the real repository state, and
- the PR description includes verification notes.
