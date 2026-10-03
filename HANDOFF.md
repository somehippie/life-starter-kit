# Handoff

Read this and [ROADMAP.md](ROADMAP.md) at the start of every session.

**Review files:** before publishing a phase or module, write the review
(file tree, claims with sources and dates, PII scan results) into the
private notes repo's `reviews/` folder, one file per phase, for example
`reviews/phase2-drone.md`. Never put review files in this public repo.

## Last session: 2026-10-03 (phase 4, complete)

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
