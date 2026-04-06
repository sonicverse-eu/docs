# Contributing to Sonicverse docs

Thank you for your interest in contributing to the Sonicverse documentation! This guide covers everything you need to get started, submit changes, and communicate with the team.

All participants are expected to follow the [Code of Conduct](/audiostreaming-stack/code-of-conduct).

## How to contribute

### Option 1: Edit directly on GitHub

1. Navigate to the page you want to edit on [docs.sonicverse.eu](https://docs.sonicverse.eu)
2. Click the **Edit this page** link at the bottom of the page
3. Make your changes in the GitHub editor
4. Submit a pull request with a clear description of your change

### Option 2: Local development

1. Fork and clone this repository
2. Install the Mintlify CLI: `npm i -g mint`
3. Create a branch for your changes: `git checkout -b docs/my-change`
4. Make your changes to the relevant `.mdx` files
5. Run `mint dev` from the repository root to preview locally at `http://localhost:3000`
6. Commit your changes and open a pull request

## Pull request process

1. **Branch from `main`** — use a short, descriptive branch name (`docs/fix-quickstart`, `docs/add-firewall-section`)
2. **Keep PRs focused** — one logical change per pull request
3. **Write a clear description** — explain what changed and why; link to any related issue with `Closes #123`
4. **Check links** — run `mint broken-links` before opening the PR to catch any broken references
5. **Review cycle** — a maintainer will review your PR; expect feedback within a few business days
6. **Address review comments** — push additional commits to your branch; do not force-push after review starts

## Writing guidelines

- **Use active voice**: "Run the command" not "The command should be run"
- **Address the reader directly**: Use "you" instead of "the user"
- **Keep sentences concise**: Aim for one idea per sentence
- **Lead with the goal**: Start instructions with what the user wants to accomplish
- **Use consistent terminology**: Don't alternate between synonyms for the same concept
- **Use sentence case for headings**: "Getting started" not "Getting Started"
- **Bold UI elements**: Click **Settings**, not Click "Settings"
- **Include examples**: Show, don't just tell

## Code style

MDX pages in this repository use [Mintlify components](https://mintlify.com/docs/components). Keep the following conventions consistent:

- Use fenced code blocks with a language identifier (`bash`, `typescript`, `python`, etc.)
- Use `<Steps>` / `<Step>` for multi-step procedures
- Use `<Warning>` for security or data-loss notices, `<Note>` for general callouts
- Keep frontmatter fields to `title` and `description` unless a specific page needs more

## Project-specific contribution guides

For contributing to the source code of Sonicverse projects, see the contributing guide in each repository:

- **Audio Streaming Stack** — [audiostreaming-stack/contributing](/audiostreaming-stack/contributing)
- **Website** — [website/contributing](/website/contributing)

## Communication

- **GitHub Issues** — use for bug reports, doc gaps, or feature requests
- **GitHub Discussions** — use for questions, ideas, and general feedback
- **Slack** — join the [Sonicverse OSS Slack](https://join.slack.com/t/sonicverse-oss/shared_invite/zt-3u969i5rr-cmfgEycFAi8V7Baj0uBx0A) for real-time conversation
- **Security issues** — do not open public issues; see [security policy](/audiostreaming-stack/security) instead

## Reporting issues

Use the **Documentation issue** template on GitHub. Include:

- The URL of the page with the problem
- A description of what is incorrect or missing
- A suggested correction, if you have one
