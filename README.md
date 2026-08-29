# Spillwave Skills Marketplace

Catalog for **domain skills plugins** (Docker, LocalStack, Zola, macOS apps, Python, AWS CDK, Codebase Wizard, Google Docs style, UI Guard, STE100, Architect Agent, Image Gen).

This is **not** the second-brain suite. Knowledge/OKF packs live in [`second-brain-marketplace`](https://github.com/SpillwaveSolutions/second-brain-marketplace).

MIT. Multi-host: **Claude Code**, **Grok Build**, **Codex**, **Cursor**, **Agent Plugins 1.0**. Tracking: **WikiTicket SDD**.

## Install

```bash
# Claude Code / Grok Build
/plugin marketplace add SpillwaveSolutions/skills-marketplace
/plugin install developing-with-docker@spillwave-skills
/plugin install using-localstack@spillwave-skills
/plugin install creating-zola-static-sites@spillwave-skills
/plugin install automating-mac-apps@spillwave-skills
/plugin install mastering-python-skill@spillwave-skills
/plugin install mastering-aws-cdk@spillwave-skills
/plugin install codebase-wizard@spillwave-skills
/plugin install google-docs-style@spillwave-skills
/plugin install spillwave-ui-guard@spillwave-skills
/plugin install ste100@spillwave-skills
/plugin install architect-agent@spillwave-skills
/plugin install image-gen@spillwave-skills
```

Codex: install from each plugin repo's `.codex-plugin` (or `codex plugin marketplace add SpillwaveSolutions/skills-marketplace` if the host reads this catalog).

Cursor: each plugin ships `.cursor-plugin/plugin.json` and `.cursor/rules/`.

Skilz:

```bash
skilz install SpillwaveSolutions/developing-with-docker-agentic-skill
skilz install SpillwaveSolutions/image_gen
```

## Plugins

| Plugin | Repo | Version | What it is |
|--------|------|---------|------------|
| `developing-with-docker` | [developing-with-docker-agentic-skill](https://github.com/SpillwaveSolutions/developing-with-docker-agentic-skill) | 1.1.0 | Docker CLI/Compose/Desktop debug-first skill |
| `using-localstack` | [using-localstack-plugin](https://github.com/SpillwaveSolutions/using-localstack-plugin) | 1.1.0 | Local AWS with LocalStack |
| `creating-zola-static-sites` | [creating-zola-static-sites-plugin](https://github.com/SpillwaveSolutions/creating-zola-static-sites-plugin) | 1.1.0 | Zola static sites |
| `automating-mac-apps` | [automating-mac-apps-plugin](https://github.com/SpillwaveSolutions/automating-mac-apps-plugin) | 1.1.0 | AppleScript/JXA macOS automation |
| `mastering-python-skill` | [mastering-python-skill-plugin](https://github.com/SpillwaveSolutions/mastering-python-skill-plugin) | 1.1.0 | Modern Python coaching |
| `mastering-aws-cdk` | [mastering-aws-cdk-plugin](https://github.com/SpillwaveSolutions/mastering-aws-cdk-plugin) | 1.1.0 | AWS CDK v2 TypeScript |
| `codebase-wizard` | [codebase-mentor](https://github.com/SpillwaveSolutions/codebase-mentor) | 1.4.0 | Conversational codebase tour/docs |
| `google-docs-style` | [google-docs-style](https://github.com/SpillwaveSolutions/google-docs-style) | 1.1.2 | Google developer docs style + formatter/hooks |
| `spillwave-ui-guard` | [spillwave-ui-guard](https://github.com/SpillwaveSolutions/spillwave-ui-guard) | 0.2.2 | Wireframe-first adversarial UI review |
| `ste100` | [ste100-agent-plugins](https://github.com/SpillwaveSolutions/ste100-agent-plugins) | 0.1.3 | ASD-STE100 Simplified Technical English gate |
| `architect-agent` | [architect-agent](https://github.com/SpillwaveSolutions/architect-agent) | 3.2.0 | Plan → delegate to code agents → grade → iterate |
| `image-gen` | [image_gen](https://github.com/SpillwaveSolutions/image_gen) | 2.0.0 | Article covers and illustrations (imagen CLI, Nano Banana 2/Pro, grok/codex fallback) |

Each listed plugin already has five-host packaging and WikiTicket SDD (`.work/`). Nested Claude marketplace layouts were preserved.

## Related catalogs

- [second-brain-marketplace](https://github.com/SpillwaveSolutions/second-brain-marketplace) — OKF ContentPacks, foundation, AGER translators, worklog
- [wiki_ticket_sdd](https://github.com/SpillwaveSolutions/wiki_ticket_sdd) — work tracking
