# Handoff

Read this and [ROADMAP.md](ROADMAP.md) at the start of every session.

**Review files:** before publishing a phase or module, write the review
(file tree, claims with sources and dates, PII scan results) into the
private notes repo's `reviews/` folder, one file per phase, for example
`reviews/phase2-drone.md`. Never put review files in this public repo.

## Last session: 2026-10-04 (phases 8 and 9)

### Decisions made by the owner (2026-10-04)

| Decision | Detail |
|---|---|
| Starter Kit definition | For first-time users. Each starter guide opens with a "Who are you?" fork for two or three reader types (for example curious but unsure, or ready to buy), each with its own path through the guide. |
| Booster Pack definition | For all users: content that takes a skill beyond the starter. One definition across all of the owner's projects. The AI Starter Kit's Part 8 courses are that kit's Booster Packs, so its README wording stays accurate. |
| Phase 4 rename reversed | `add-ons/` folders are now `booster-packs/`. |
| Modules as skills | Each module ships a SKILL.md alongside ai-context.md, so people can load it into Claude as a skill. |
| Hobbies umbrella | `hobbies/`, framed as paths into flow state. Art and music join later. |
| Growing umbrella | Top-level `growing/`, separate from hobbies (homesteading direction). Its starter kit is houseplants; cannabis is a Booster Pack inside it. |
| Cure device | The owner's own invention: a separate repository later, linked from the cannabis Booster Pack and a Projects table in the root README (phase 13). |
| Successor | Designating a GitHub repository successor is the last roadmap item (phase 14). |
| Photos | Strip all metadata, especially GPS, from any photo before it is committed to either repository (CONTRIBUTING rule 7). |

### Done

- **Phase 8.** `add-ons/` renamed `booster-packs/` everywhere. `drone/` moved
  to `hobbies/drone/` with every link fixed; the owner's profile README link
  was updated to match. `_template/guide.md` opens with a "Who are you?"
  table; `_template/SKILL.md` added, its frontmatter limits taken from
  Anthropic's Agent Skills overview (read at source 2026-10-04, cited in
  `_template/sources.md`). Home, Supplements and Drone each ship a SKILL.md;
  Supplements keeps every no-dose rule and the pharmacist report.
- **Phase 9.** `hobbies/` README and stubs (motorsports, snowboarding,
  skateboarding, photography, fishing-boating); `growing/` README with the
  houseplant starter (varieties unidentified until the owner's photos) and
  the cannabis Booster Pack stub. Its legal notice was checked against
  California Health and Safety Code 11362.1, 11362.2 and 11359, 21 CFR
  1308.11 and 1308.13, and 21 USC 802 and 841 on 2026-10-04. It states
  plainly that home growing remains federally illegal: only FDA-approved
  and state-medical-licensed marijuana moved to Schedule III in April 2026,
  and growing counts as manufacturing in any schedule. Corrections: the limit is **six** plants (an
  earlier note had a different number; it was wrong); cities and counties can ban outdoor growing but **cannot** fully
  ban indoor growing in a private residence; the locked-space rule is state
  law.
- Raw growing notes are in the private notes repo; nothing from them is
  public until phase 10.
- Review: `reviews/phase8-9-restructure.md`.

### Next

- Done later the same day: Home, Supplements and Drone guides now open with
  a "Who are you?" fork (three reader types each); ai-context.md and
  SKILL.md regenerated; Home's soap section gained a "when to stop" line
  (MedlinePlus); the template ai-context.md has a Reader types section.
  Review: `reviews/phase8b-reader-forks.md`.
- Phase 10 (Growing build) waits on the owner's plant photos.
- Phase 6 (Booster Packs) is still gated on a module reaching Usable.

### Open questions

- Which module reaches Usable first.

## Earlier session: 2026-10-03 (Supplements field test)

### Done

- **Supplements field test.** The owner ran the five checks on one real
  product using only the guide (product not recorded). Gaps found and fixed:
  NIH fact sheets were hard to find; seals were not visible on the label; the
  guide assumed every step was done by hand and was a lot for a new user.
- The guide now opens with **the quick way**: paste `ai-context.md` into an AI
  assistant, run its **guided session** prompt, and finish with a short report
  for a pharmacist. Every check has an AI handoff; new guidance on finding
  fact sheets and checking seals on the maker's and tester's sites; a closing
  section "Take a report to your pharmacist" with a template, noting that many
  pharmacies don't accept email (print it, show it at the counter, or read it
  on a call). AI steps must give links and never recommend whether, how much
  or when to take anything.
- Review: `reviews/phase3c-supplements-field-test.md`.

### Next

Supplements stays **Draft**. It moves to Usable after one rerun using the
guided-session prompt, with the resulting report reaching a pharmacist.

Phase 6 (add-ons) remains the only roadmap phase, still gated on a module
reaching Usable. Other routes: record the Home soap trial outcome; add Drone
first-flight lessons.

### Open questions

- Which module reaches Usable first.

## Earlier session: 2026-10-03 (Supplements sources, phase 7 complete)

### Done

- **Supplements sources upgraded.** USP and NSF are now cited directly,
  labelled "read at source by a separate review session, 2026-10-03" (a new
  label in CONTRIBUTING.md), with each row saying how it was read: NSF in
  full, USP as first-party excerpts. Guide adds that neither mark means a
  supplement works or is right for you. Supplements stays **Draft**: Usable
  needs one person to run the five checks on a real product end to end.
  Review: `reviews/phase3b-supplements-sources.md`.
- **Phase 7 complete.** TRANSLATE.md recommends an AI assistant with its
  prompt, adds an "Other tools" table (DeepL accepts Markdown in beta, checked
  2026-10-03), and sets seven rules for contributed translations: pull
  requests into `translations/[language code]/`, one fluent reviewer plus an
  AI back-translation attached to the pull request, pinned to an English
  commit, marked when out of date, safety text never shortened. CONTRIBUTING
  rule 5 updated to match; `translations/README.md` added as the index.
  Review: `reviews/phase7-translation.md`.

### Next: phase 6 (add-on packs per module)

The only roadmap phase left. Still gated on modules leaving Draft:

- Home: record the soap dispenser trial outcome.
- Drone: add first-flight lessons after real flights.
- Supplements: one person runs the five checks on a real product.

Revisit a translation platform such as Crowdin if three or more languages
arrive.

### Open questions

- Which module to move to Usable first.

## Earlier session: 2026-10-03 (phase 4, complete)

### Done

- **Phase 4 complete.** The AI Starter Kit README now has a "Related"
  section linking here, with a dated entry in its CHANGELOG under
  "Repository history". The curriculum is unchanged: it stays at v0.10 and
  no tag was added. Its paused-document rule was respected, because only the
  README and CHANGELOG changed, at the owner's request.
- The link says life-starter-kit is **not** a Booster Pack. The owner
  defines Booster Packs as the advanced AI courses that follow the AI Starter
  Kit, each to get its own name; the curriculum's Part 8 names the first.
- To keep that term unambiguous, each module's `boosters/` folder was renamed
  `add-ons/`, with the template, CONTRIBUTING, READMEs and roadmap updated.
- Reviewed in the private notes repo before publishing:
  `reviews/phase4-crosslink.md`.

### Next: phase 6 (add-on packs per module)

Phase 5 is already done, so phase 6 is next. It is gated on the starters
maturing: add-ons come after a module's starter is solid, and all three
modules are still Draft. The quickest ways to unblock it:

- Home: record the soap dispenser trial outcome and move Home to Usable.
- Drone: add first-flight lessons after real flights.
- Supplements: read the USP and NSF pages by hand to upgrade the two
  secondary rows.

Phase 7 (translation quality) is independent of the starters and can be
started instead if the owner prefers. Follow the review workflow either way.

### Open questions

- Which comes first: unblocking phase 6, or starting phase 7?

## Earlier session: 2026-10-02 to 2026-10-03 (phase 3, complete)

### Done

- **Supplements** module (Draft): how supplements are regulated, five checks
  (need, evidence, quality, label, interactions), label auditing, interaction
  examples, free tools, levels of checking, generalized lessons.
- Module rules set by the owner: no doses, timings or stacks presented as
  recommendations; every interaction claim ends "confirm with a pharmacist or
  doctor"; nothing that reveals the owner's own stack or health.
- Sources read at source: NIH ODS consumer and nutrient fact sheets, NCCIH,
  FDA Q&A, 21 CFR 101.36, NCCIH Know the Science (types of research), NIH
  ODS Vitamin E, Tucker 2018 (JAMA Netw Open, abstract), Cohen 2023 (JAMA),
  Murad 2016 (abstract), Ejima 2016 (Eur J Clin Invest, abstract). USP and NSF
  sites refused automated access, so their program details are labelled
  secondary.
- Reviewed in the private notes repo before publishing:
  `reviews/phase3-supplements.md`. Approved with changes on 2026-10-03: label
  example switched to vitamin E, evidence table re-sourced to NCCIH (the
  testimonials row was cut for lack of a source), abstract citations marked.
- **Phase 3 complete.** Published 2026-10-03; Supplements stays **Draft**.

### Next: phase 4 (cross-link from the AI Starter Kit)

Add a short "Related" section, linking here, to the AI Starter Kit
repo's README only; it stays a separate repo. Follow the review
workflow: write `reviews/phase4-crosslink.md` in the private notes repo and
wait for approval before pushing. Phases 6 (add-ons) and 7 (translation)
follow.

### Open questions

- USP and NSF program pages could be read by hand to upgrade two rows from
  secondary.
- Supplements, Drone and Home are all Draft.

## Earlier session: 2026-10-02 (phase 2, phase 5)

### Done

- **Drone** module (Draft): buying order, budget / mid / upgrade tiers,
  analog vs digital, US recreational rules, FCC import restrictions,
  lessons distilled from the public fpv-starter-kit build.
- FAA rules read at faa.gov (Recreational Flyers page updated 2026-03-18),
  plus FAA Advisory Circular 91-57D (2025-06-24) and 14 CFR 89.101.
  FCC Public Notices DA 25-1086, DA 26-22 and DA 26-454 read at source.
- Owner review before publishing: two rules derived from FAA wording are now
  labelled "inferred from FAA wording" (a new label in CONTRIBUTING.md), with
  their primary sources. Added: do not register a sub-250 g whoop voluntarily
  (it would bring it under Remote ID), and the visual observer details from
  AC 91-57D.
- Phase 5 pulled forward: the older private home starter kit repo was
  archived with a README pointing here.

### Worth knowing

- Since 2025-12-22, new foreign-made drones and drone components cannot get
  FCC authorization. Already-authorized models can still be sold. Nearly all
  hobby FPV gear is foreign-made, so the guide tells readers to buy current
  models while in stock.
- Prices rose sharply in 2026 (Skyzone SKY04X Pro now $661.99) and many
  BetaFPV items were sold out when checked.

### Next: phase 3 (Supplements)

Public content = how to evaluate supplements and evidence, how to read a
label, timing and interactions, keeping a routine simple. No personal stack.
Strong disclaimer. Primary sources: NIH Office of Dietary Supplements fact
sheets.

### Open questions

- HDZero Goggle 2 US price could not be read from the maker's page; marked
  unverified.
- Drone moves to Usable after first real flights.
- Soap trial outcome still pending for Home.
- Three Home soap facts remain "secondary" (CDC, NEA pages blocked automated
  access).

## Previous session: 2026-10-02 (phase 1)

### Done

- Scaffolded the repository: README, llms.txt, ROADMAP, CONTRIBUTING (module
  template and content rules), DISCLAIMER, TRANSLATE, CC BY 4.0 for content,
  MIT for code.
- `_template/` with every module file and guidance comments.
- **Home** module (Draft): fragrance-free soap dispensers (trial in progress)
  and hot tub upkeep. Every figure checked on 2026-10-02 and listed in
  `home/sources.md` with a Checked label.
- **Supplements** and **Drone** stubs (Planned).
- A separate private notes repo holds the raw notes these modules are
  distilled from. Nothing is copied from it verbatim.
- Ran a PII scan (clean), then published the repository as public with
  topics starter-kit, guides, ai-context, home-improvement, fpv.

### Corrections made while checking facts

- The simplehuman pump's official page gives $70-80 and about 4 months per
  charge. Earlier notes said ~$60 and ~3 months, and claimed an IP67 rating
  the page does not state. The guide uses the official figures and omits the
  rating.
- A basic 3-way test kit does not measure alkalinity, and FROG @ease needs its
  own strips. Both went into the guide as lessons.

### Next: phase 2 (Drone)

Fresh research from official sources: FAA recreational rules (TRUST, Remote
ID, registration), current models and prices. Distill the separate public
`fpv-starter-kit` repo into the module format.

### Open questions

- Soap trial outcome: does the dispenser work well with the chosen soap?
  Update `home/` and move it to Usable when known.
- Three soap facts are marked "secondary" (CDC top-off guidance, NEA Seal
  meaning, unscented vs fragrance-free) because the original pages could not
  be opened automatically. Worth reading the originals by hand.
- Hot tub notes cover the FROG @ease system only.
