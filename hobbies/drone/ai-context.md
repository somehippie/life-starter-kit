Derived from guide.md as of 2026-10-04. Regenerate when guide changes.

# Drone: AI context

## Purpose

Helps a beginner get into FPV (first-person-view) drone flying cheaply and
legally: what to buy, in what order, how to practise first, and the US rules
for recreational flyers. Built around a tiny whoop, the usual affordable first
drone. Not legal advice; rules differ by country and change. LiPo batteries
can catch fire if damaged: stop using any that are swollen or damaged.

## Reader types

Ask which fits before advising; each has its own path in the guide.

- Curious, not sure they will enjoy flying: radio and a simulator only, then
  decide. Rules and safety before buying a drone.
- Ready to buy and fly: the full buying order, parts that match, the FCC
  buying notes, the rules (visual observer included), setup, and when to
  stop.
- Already practising or flying, weighing digital: analog or digital, the
  upgrade tier, parts that match, the FCC notes and the rules.

## Key facts

Prices checked 2026-10-02; they change, and many items were sold out.

- Order: radio first (it is also the simulator controller), simulators next,
  then goggles, drone, batteries and charger while practising.
- Radio: RadioMaster Pocket, $59.99-71.50. Simulators: Uncrashed $14.99 and
  Liftoff: Micro Drones $15.99 on Steam, often discounted.
- Drone: BetaFPV Meteor75 Pro II (analog), $99.99. Complete kit with goggles
  and radio: $208.99 (sold out when checked).
- Goggles: box goggles ~$75 (budget), Skyzone SKY04X Pro $661.99 (analog),
  HDZero Goggle 2 ~$649 (digital, price unverified as of 2026-10-02).
- Batteries: 1S 550mAh packs, $25.99 per 4; plan on 6-8. Charger: 6-port 1S,
  ~$26.
- Parts must match: radio protocol (e.g. ELRS) to the drone's receiver;
  drone video to the goggles (analog with analog, or the same digital system).
- Analog: cheapest, lowest latency, lower picture quality. Digital: sharper,
  costlier, goggles and drone must share a system.
- FCC, 22 Dec 2025: new foreign-made drones and drone components cannot get
  US authorization. Models authorized before then can still be sold and
  updated (firmware until at least 1 Jan 2029). Expect current models only.
- US recreational rules: pass the free TRUST test and carry proof; register
  drones of 250 g or more ($5, 3 years); Remote ID only for drones that must
  be registered; keep line of sight or use a co-located visual observer;
  400 ft max in Class G; authorization (LAANC) in controlled airspace; give
  way to other aircraft; recreational purpose only.
- Goggle (FPV) flying needs a visual observer next to the pilot, able to
  talk without radios or phones and to see the drone unaided all flight
  (FAA Advisory Circular 91-57D).
- Whoops weigh about 30-40 g, so no registration or Remote ID when flown for
  fun. Registering one voluntarily brings it under Remote ID (14 CFR 89.101),
  so do not register a sub-250 g whoop unless required.
- Whoops hover at roughly 20-35% throttle. Community starting curve in
  Betaflight: Mid 0.25, Expo 0.35.

## Decision rules

- If unsure you will enjoy it, buy only the radio and a simulator first.
- If buying parts separately, pick the radio protocol first and match the
  drone's receiver to it.
- If a needed part is in stock and authorized, buy it rather than wait for a
  newer model, given the FCC restrictions.
- If flying with goggles, bring a visual observer every time.
- If flying near an airport or in controlled airspace, get authorization
  through LAANC first, or fly elsewhere.
- If a firmware update is available for a budget radio, check what it removes
  for your exact model before installing.

## Common mistakes

- Buying goggles and a drone on different video systems.
- Buying a radio whose protocol does not match the drone's receiver.
- Flying with goggles alone, with no visual observer.
- Copying a 5-inch drone's throttle curve onto a whoop.
- Treating forum comments as confirmation of what hardware supports.
- Ordering generic spare screws or props instead of ones for the exact frame.
- Picking a "developer kit" listing that needs soldering when a ready-built
  version was wanted.

## Prompts

Copy one of these into your AI assistant after pasting this file.

```
Using the drone kit above, ask me which reader type fits me, my budget, where I live, and whether
I have flown before. Then give me a shopping list in buying order, with what
to check for compatibility between each part.
```

```
I live in <country/state>. Using the US rules above only as a comparison,
tell me what I need to check in my own country's drone rules before flying a
30 g FPV whoop, and where to find the official source.
```

```
Here is the gear I am considering: <list>. Using the kit above, check that
the radio protocol, receiver, video transmitter and goggles all match, and
flag anything that will not work together.
```
