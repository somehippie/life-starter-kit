---
name: <module-name>-starter
description: <What this skill does and when to use it, in one or two sentences. Name the reader's situation, e.g. "Use when someone wants to start X, choose what to buy first, or check a plan against common mistakes.">
---

<!--
SKILL.md lets people load this module into Claude as a skill.
Derived from guide.md, like ai-context.md, and regenerated when the guide
changes. It must never contain anything ai-context.md does not: no new
facts, prices or rules. It points to the module's files instead of copying
them. Keep the safety notes word for word from README.md.

Frontmatter limits (see sources.md, "Skill format"):
- name: at most 64 characters, lowercase letters, numbers and hyphens only,
  no XML tags, and must not contain "claude" or "anthropic".
- description: at most 1,024 characters, no XML tags, and must say both
  what the skill does and when to use it.
Delete comments when done.
-->

Derived from guide.md as of <YYYY-MM-DD>. Regenerate when guide changes.

# <Module name>

## Safety

<The module's safety note, word for word from README.md. Delete this section
for modules without one.> Not professional advice; see the repository's
DISCLAIMER.md.

## How to use this skill

1. Start with the "Who are you?" table at the top of [guide.md](guide.md).
   Ask the user which reader type fits them, then follow that path.
2. Use [ai-context.md](ai-context.md) for the key facts, decision rules,
   common mistakes and prompts.
3. Check [lessons.md](lessons.md) before recommending anything to buy.
4. Look in [booster-packs/](booster-packs/) when the user is past the starter.
5. Cite [sources.md](sources.md) for any price, rule or fact, with its "last
   verified" date. If a date is old, tell the user to re-check.

## Rules

- Use only what is in this module's files. If something is not there, say so
  instead of guessing.
- Give links for every source you use.
- <Module-specific rules from ai-context.md's decision rules, e.g. what the
  skill must never recommend.>
