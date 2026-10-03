# Reading a module in another language

English is the canonical version. The quickest way to read a module in your
language is to translate it yourself, on demand, with the prompt below.
Human-reviewed translations can also be contributed; see the last section.

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

## Other tools

An AI assistant with the prompt above is the recommended route, because it is
the only one you can tell to keep tables, numbers and safety notes intact.

| Tool | Accepts Markdown files? | Notes |
|---|---|---|
| Any AI assistant | Yes, as pasted text | Use the prompt above |
| DeepL | Yes, **in beta**, through its document translation API (checked 2026-10-03) | Cannot be given the prompt's rules, so compare numbers and safety notes with the English. Beta features change; re-check before relying on it. |
| Document translators without Markdown support (for example Google's document translation, which takes DOC, DOCX, PDF, PPT and XLS files) | No | Pasting the text in can lose table structure. Use only as a last resort. |

Whatever you use, compare every number, safety note and rule with the
English before acting on it.

## Why translate on demand?

A translation is correct only for the version it was made from. When a price
or a safety note changes in English, a stored translation silently becomes
wrong. Translating on demand always starts from the current text.

## Contributing a translation

Reviewed translations are welcome as pull requests into
`translations/[language code]/`, mirroring the English layout (for example
`translations/es/drone/guide.md`). Every translation must follow these rules:

1. **A human reviews every line.** You may start from an AI or machine draft;
   say which tool in the pull request.
2. **One fluent reviewer plus a back-translation.** A fluent speaker other
   than you approves the pull request. Attach an AI back-translation of your
   text into English to the pull request, so anyone can compare it with the
   original line by line, especially numbers and safety text.
3. **Pin it to a version.** Start each file with
   `Translated from <path> at commit <hash>, <date>.`
4. **Mark it when it falls behind.** When the English file changes after that
   commit, the translation shows "May be out of date; the English version is
   canonical" until it is updated. Translations more than a year behind are
   removed.
5. **Never shorten safety content.** Disclaimers, safety notes and every
   "confirm with a pharmacist or doctor" line are translated in full.
6. **Same content rules as the English.** No personal data; sources stay in
   English with their dates; product and brand names are not translated.
7. **Licence.** Under CC BY 4.0 a translation is adapted material and must say
   it was modified. The version line in rule 3 serves as that notice.

Translations are listed in [translations/README.md](translations/README.md).
