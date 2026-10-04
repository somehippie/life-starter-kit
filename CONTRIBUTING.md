# Contributing

Thank you for helping. These kits are for strangers, so every page has to be
safe, accurate and free of anyone's personal details.

## Starting a new module

Copy `_template/` to a new folder named after the module (lowercase, one
word or hyphenated) and fill in each file. The comments in each file explain
what goes there; delete them when you are done. Add the module to the table
in the root `README.md` and to `llms.txt`.

Related modules can sit inside an umbrella folder with its own README, such
as `hobbies/` or `growing/`. Inside one, links to root files need one more
`../`.

| File | Purpose |
|---|---|
| README.md | Human entry point: who it is for, where to start, status, link to the guide |
| guide.md | The starter kit: opens with a "Who are you?" table of two or three reader types, each with its own path; then ordered steps, buying order and timing, budget / mid / upgrade tiers |
| lessons.md | Field notes: what worked, what did not, and why, written so a stranger can apply them |
| ai-context.md | Paste-into-any-AI version of guide + lessons. About 1,500 words at most. Sections: Purpose, Key facts, Decision rules, Common mistakes, Prompts. First line: `Derived from guide.md as of <date>. Regenerate when guide changes.` |
| SKILL.md | Lets people load the module into Claude as a skill. Derived from guide.md like ai-context.md, and regenerated whenever the guide changes. Points to the guide, lessons, Booster Packs and sources and carries the safety notes; never contains anything ai-context.md does not. Frontmatter limits are in `_template/sources.md`. |
| booster-packs/ | Booster Packs, one file each, added once the starter is solid |
| sources.md | The source and "last verified" date for every factual claim |

## Starter kits and Booster Packs

- A **starter kit** is for first-time users. Its guide opens with a "Who
  are you?" table for two or three reader types (for example, curious but
  unsure, or ready to buy), each with its own path through the guide.
- A **Booster Pack** is for all users: content that takes a skill beyond
  the starter kit. Each module keeps them in `booster-packs/`.

## Content rules

1. **No personal data, ever.** No names of private people, addresses,
   cities or zip codes tied to an author, device names, hostnames or serial
   numbers, absolute file paths, email addresses, API keys, health
   conditions, or financial details.
2. **Generalize lessons.** "I learned X" becomes "X tends to work because Y."
3. **Health and safety modules** carry a visible safety note at the top of
   their README linking [DISCLAIMER.md](DISCLAIMER.md). No personal dosages.
4. **Date anything that changes.** Prices, laws, product models and
   regulations each get a dated source in `sources.md`.
5. **English is canonical.** Unreviewed machine translations are not
   accepted. Human-reviewed translations are, under the rules in
   [TRANSLATE.md](TRANSLATE.md#contributing-a-translation): one fluent
   reviewer plus an attached AI back-translation, pinned to an English commit.
6. **Plain language.** Short sentences, tables for comparisons. Readers may
   be beginners or reading in a second language.
7. **Strip photo metadata.** Remove all metadata, especially GPS location,
   from every photo before it is committed. Check with a tool such as
   `exiftool` that nothing is left.

## Marking how sure we are

Some claims come from a manufacturer page you read yourself; others come from
a summary of someone else's reading. `sources.md` says which, so readers can
weigh them:

| Label | Meaning |
|---|---|
| read at source | The value was read on the original page or document on the date given |
| read at source by a separate review session, [date] | A separate review session read the original on that date; the session that wrote the text could not open it. The row says how it was read (in full, or as first-party excerpts). |
| secondary | Taken from a page quoting or summarizing the original, which could not be opened |
| inferred from [source] wording | Not stated in so many words, but follows directly from text that was read at source. Name the source. |
| unverified | Not yet checked. Say so in the guide text too. |

## Before you open a pull request

- Search your changes for names, places, emails and file paths.
- Make sure every new price or rule has a dated line in `sources.md`.
- If you changed `guide.md` or `lessons.md`, update `ai-context.md`, `SKILL.md` and their dates.
- If you added a photo, confirm its metadata is stripped.
