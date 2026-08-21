# Progress Percent Plans

Progress Percent Plans is a skills-only plugin for ChatGPT and Codex. It keeps a visible completion percentage on every meaningful step of a multi-step plan and updates those percentages as implementation, research, review, and testing progress.

The percentages represent evidence-backed completion of each named step. They are not elapsed-time measurements or delivery estimates.

## What it does

- Prefixes each plan step with `[NN%]`.
- Keeps plan status and completion percentages consistent.
- Updates progress at material checkpoints and whenever the user asks for status.
- Preserves evidence-backed progress after interruptions.
- Avoids creating ceremonial plans for trivial one-step requests.

## Contents

- `.codex-plugin/plugin.json` — plugin manifest.
- `skills/progress-percent-plans/SKILL.md` — workflow instructions and activation boundary.
- `assets/` — original plugin logo and composer icon.

## Privacy

This plugin has no MCP server, authentication, analytics, network integration, or external storage. See [PRIVACY.md](PRIVACY.md).

## Support

Open an issue in this repository. See [SUPPORT.md](SUPPORT.md) for the information that helps diagnose a problem.

## License

MIT. See [LICENSE](LICENSE).
