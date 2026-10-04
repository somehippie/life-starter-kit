<!--
One row per factual claim in guide.md and lessons.md.
Checked: read at source | secondary | unverified (see CONTRIBUTING.md).
Delete comments when done.
-->

# <Module name>: sources

| Claim | Value | Source | Last verified | Checked |
|---|---|---|---|---|
| <claim> | <value used> | [<publisher>](<url>) | <YYYY-MM-DD> | read at source |

## Skill format

Keep this section: it is the source for the format of SKILL.md.

| Claim | Value | Source | Last verified | Checked |
|---|---|---|---|---|
| SKILL.md needs YAML frontmatter with `name` and `description` | Both required | [Anthropic: Agent Skills overview, "Skill structure"](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview#skill-structure) | 2026-10-04 | read at source |
| Limits on `name` | At most 64 characters; lowercase letters, numbers and hyphens only; no XML tags; must not contain "anthropic" or "claude" | same page | 2026-10-04 | read at source |
| Limits on `description` | Non-empty; at most 1,024 characters; no XML tags; must say what the skill does and when to use it | same page | 2026-10-04 | read at source |
| Where to install a skill | Claude Code: `~/.claude/skills/` (personal) or `.claude/skills/` (project). claude.ai: upload a zip under Settings > Features, on Pro, Max, Team and Enterprise plans with code execution enabled | same page, "Where Skills work" | 2026-10-04 | read at source |
