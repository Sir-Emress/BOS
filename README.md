# BOS

BOS (Bugema Operating System) is a community-driven, self-hostable "internet
OS" focused on simplifying web services for campus and community use.

## Project Overview

BOS is intended to become a practical foundation for shared digital services
that schools, student communities, and local organisations can host for
themselves. The project emphasizes simple deployment, open collaboration, and a
workflow that helps new contributors learn by building in public.

This repository is currently documentation-first. It captures the product
direction, contribution workflow, and starter conventions for future modules.
There is not yet a packaged installer or a runnable BOS application in this
repository.

## Goals

- Provide a lightweight, open platform for hosting shared services.
- Encourage contributions from students and community developers.
- Keep deployments simple and self-hostable.
- Establish a clear open-source workflow before the codebase expands.

## Planned Scope

The long-term BOS platform is expected to support:

- campus and community web services,
- reusable admin and collaboration tools,
- self-hosted deployment patterns, and
- documentation that helps new contributors onboard quickly.

## Repository Contents

| Path | Purpose |
| --- | --- |
| `README.md` | High-level project overview and onboarding notes |
| `CONTRIBUTING.md` | Contribution workflow, branch naming, and PR guidance |
| `LICENSE` | Repository license |
| `.github/ISSUE_TEMPLATE/` | Starter issue templates for bugs and feature requests |

## Quick Start

Because BOS is still in a documentation-first phase, the quickest way to get
started is to contribute to the project structure and planning materials.

1. Clone the repository:

   ```bash
   git clone https://github.com/bos-com/BOS.git
   cd BOS
   ```

2. Review the current project direction in this README and the contribution
   expectations in `CONTRIBUTING.md`.
3. Choose an existing issue or open a new one describing the gap you want to
   address.
4. Create a focused branch, make your change, and open a pull request.

## Local Requirements

At the current project stage, contributors only need a lightweight toolchain:

- Git for version control
- A GitHub account for issues and pull requests
- A text editor or IDE for Markdown and future code changes
- Optional: Markdown preview support to validate documentation updates

## Contributor Workflow

- Start from a clear issue or documented improvement.
- Keep changes scoped to one concern where possible.
- Document assumptions when the repository does not yet contain runnable code.
- Use pull requests to explain what problem was solved and how it was verified.

Detailed conventions are documented in `CONTRIBUTING.md`.

## Roadmap

Near-term repository improvements include:

- expanding architecture notes,
- documenting expected service modules,
- defining local development standards, and
- introducing starter implementation scaffolding for BOS components.

## License

This project is available under the terms described in [`LICENSE`](LICENSE).
