# Reading a module in another language

English is the only maintained version. Rather than ship machine translations
that go stale, this repository gives you a prompt to translate any page
yourself, on demand, with whichever AI assistant you use.

## How

1. Open the file you want (for example `home/guide.md`) and copy all of it.
2. Paste the prompt below into your AI assistant, replacing the two placeholders.
3. Read the result alongside the English if anything matters: prices, doses,
   rules and safety notes are where mistakes cost the most.

```
Translate the following Markdown document into <LANGUAGE>.

Rules:
- Keep all Markdown formatting, tables, links and code blocks exactly as they are.
- Do not translate product names, brand names, model numbers, or URLs.
- Keep every number, unit, price and date unchanged. If a unit is unusual where
  <LANGUAGE> is spoken, add the local equivalent in brackets after it.
- Keep safety notes and disclaimers complete. Do not shorten or soften them.
- If a sentence is ambiguous, translate it literally and add [?] after it rather
  than guessing.

Document:
<PASTE THE FILE HERE>
```

## Why not commit translations?

A translation is correct only for the version it was made from. When a price
or a safety note changes in English, a committed translation silently becomes
wrong. Translating on demand always starts from the current text.

Community-reviewed translations may be accepted later; see
[ROADMAP.md](ROADMAP.md).
