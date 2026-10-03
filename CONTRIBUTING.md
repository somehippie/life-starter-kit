# Contributing

Thank you for helping. These kits are for strangers, so every page has to be
safe, accurate and free of anyone's personal details.

## Starting a new module

Copy `_template/` to a new folder named after the module (lowercase, one
word or hyphenated) and fill in each file. The comments in each file explain
what goes there; delete them when you are done. Add the module to the table
in the root `README.md` and to `llms.txt`.

| File | Purpose |
|---|---|
| README.md | Human entry point: who it is for, where to start, status, link to the guide |
| guide.md | The starter kit: ordered steps, buying order and timing, budget / mid / upgrade tiers |
| lessons.md | Field notes: what worked, what did not, and why, written so a stranger can apply them |
| ai-context.md | Paste-into-any-AI version of guide + lessons. About 1,500 words at most. Sections: Purpose, Key facts, Decision rules, Common mistakes, Prompts. First line: `Derived from guide.md as of <date>. Regenerate when guide changes.` |
| boosters/ | Deeper add-on packs, one file each, added once the starter is solid |
| sources.md | The source and "last verified" date for every factual claim |

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
5. **English is canonical.** Do not commit machine translations; point
   readers to [TRANSLATE.md](TRANSLATE.md) instead.
6. **Plain language.** Short sentences, tables for comparisons. Readers may
   be beginners or reading in a second language.

## Marking how sure we are

Some claims come from a manufacturer page you read yourself; others come from
a summary of someone else's reading. `sources.md` says which, so readers can
weigh them:

| Label | Meaning |
|---|---|
| read at source | The value was read on the original page or document on the date given |
| secondary | Taken from a page quoting or summarizing the original, which could not be opened |
| inferred from [source] wording | Not stated in so many words, but follows directly from text that was read at source. Name the source. |
| unverified | Not yet checked. Say so in the guide text too. |

## Before you open a pull request

- Search your changes for names, places, emails and file paths.
- Make sure every new price or rule has a dated line in `sources.md`.
- If you changed `guide.md` or `lessons.md`, update `ai-context.md` and its date.
