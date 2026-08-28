# Archgate

**Enterprise-grade linting and guardrails for AI work.**

AI agents write code fast, but they don't know your rules. Archgate turns your team's decisions into executable checks: a lint step for architecture, conventions, and AI output. Agents read the rules before writing code, and `archgate check` blocks what slips through. In CI, in pre-commit hooks, and inside every major AI coding tool.

```bash
curl -fsSL https://cli.archgate.dev/install-unix | sh
archgate init
archgate check
```

## Start here

| Repo | What it is |
|------|------------|
| [cli](https://github.com/archgate/cli) | The Archgate CLI. Free and open source. |
| [awesome-adrs](https://github.com/archgate/awesome-adrs) | Ready-to-use ADRs for your project. |
| [check-action](https://github.com/archgate/check-action) | GitHub Action that runs `archgate check` in CI. |
| [setup-action](https://github.com/archgate/setup-action) | GitHub Action that installs the CLI. |
| [studies](https://github.com/archgate/studies) | Reproducible governance studies and methodology. |

## Links

Website: [archgate.dev](https://archgate.dev) · Docs: [cli.archgate.dev](https://cli.archgate.dev) · Community: [r/archgatedev](https://www.reddit.com/r/archgatedev)
