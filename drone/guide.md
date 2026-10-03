# Drone: guide

Prices and rules checked 2026-10-02. Prices moved a lot in 2026 and stock is
thin; re-check before buying. Sources for every figure are in
[sources.md](sources.md).

## What you are aiming for

Flying a tiny FPV drone (a "whoop") through goggles, after learning on a
simulator first, without spending more than you need to. The order matters:
the radio comes first because it doubles as your simulator controller, and
crashes in a simulator are free.

## Steps

| Step | Do this | Why now |
|---|---|---|
| 1 | Buy the radio (transmitter) | You need it for simulator practice, and it is the part you keep longest |
| 2 | Set it up as a USB joystick and install a simulator | Builds stick skill and crash recovery at no risk |
| 3 | Practise on a general FPV simulator, then a whoop-specific one | General skills first; then match the sim to the drone you will fly |
| 4 | While practising, order goggles, drone, batteries and charger | Stock runs out and prices are rising; ordering early avoids waiting at the end |
| 5 | Take the FAA's free TRUST test and save the certificate | Required before any recreational flight in the US |
| 6 | Check where you can fly with the FAA's B4UFLY app | Controlled airspace needs authorization, and local parks may have their own rules |
| 7 | Find a visual observer for goggle flights | The FAA says an observer is necessary for goggle flying: someone next to you who can see the drone |
| 8 | Set the drone's throttle curve, then fly | Whoops hover low on the stick; the default curve wastes control there |

## What to buy

| Item | Budget | Mid | Upgrade (digital) |
|---|---|---|---|
| Complete kit (drone + goggles + radio) | BetaFPV Meteor75 Pro II FPV Kit, $208.99 (sold out when checked) | Buy parts separately (rows below) | — |
| Radio | — | RadioMaster Pocket, $59.99-71.50 | — |
| Goggles | Box goggles such as BetaFPV VR04, $74.99 (sold out when checked) | Skyzone SKY04X Pro (analog), $661.99 | HDZero Goggle 2, ~$649 (price unverified as of 2026-10-02) |
| Drone | BetaFPV Meteor75 Pro II (analog), $99.99 | Same | A digital whoop matched to your goggles' system |
| Batteries | BetaFPV LAVA 1S 550mAh, $25.99 for 4 (sold out when checked) | Same; plan on 6-8 packs | Same |
| Charger | BetaFPV 6-port 1S charger, ~$26 | Same | Same |
| Simulators | Uncrashed, $14.99; Liftoff: Micro Drones, $15.99 (both on Steam, often discounted) | Same | Same |

Where to start: the radio and both simulators cost under $100 together and
tell you whether you enjoy flying before you buy anything else. For the
drone, analog is the cheapest way in.

**Make the parts match.** The radio's link protocol (for example ExpressLRS,
"ELRS") must match the receiver in the drone, and the drone's video
transmitter must match the goggles: analog with analog, or the same digital
system on both.

### Analog or digital?

| | Analog | Digital (HDZero, DJI, Walksnail) |
|---|---|---|
| Picture | Lower resolution, can show static | Sharp |
| Latency | Lowest | Low, but usually higher than analog |
| Cost to start | Lowest | Higher goggles and drone cost |
| Mixing brands | Any analog goggle works with any analog drone | Goggles and drone must use the same system |

Analog is the usual first choice on price; digital is an upgrade path, not a
requirement. This comparison reflects common community experience rather
than measurements.

### Buying in the US after December 2025

On 22 December 2025 the FCC added drones and drone components made outside
the US to its Covered List. In practice:

- **New** foreign-made models (drones, radios, video transmitters, flight
  controllers, batteries, motors) cannot get the FCC authorization needed to
  be sold here.
- Models authorized **before** that date can still be sold, and can keep
  receiving firmware updates until at least 1 January 2029.
- Nearly all hobby FPV gear is made abroad, so expect the current models to
  be what is available, and expect sell-outs. If a part you need is in stock,
  buying it now is usually safer than waiting for a newer version.

## Rules for recreational flyers (US)

Outside the US, look up your national aviation authority's rules instead.

| Rule | What it means for a whoop |
|---|---|
| Take TRUST and carry proof | Free online test from an FAA-approved provider. Keep the certificate; providers do not keep a copy. |
| Register drones of 250 g or more | Whoops weigh about 30-40 g (figure from retailer listings, secondary source), so they do not need registration when flown for fun. Registration, if needed, is $5 for 3 years and covers all your recreational drones. **Do not register a sub-250 g whoop unless you have to**: see Remote ID. |
| Remote ID | Applies to drones that are registered **or** required to be registered. A sub-250 g whoop flown for fun is not required to be registered, so it does not need Remote ID. If you register one anyway, the rule's wording ("registered or required to be registered") brings it under Remote ID. |
| Visual line of sight | Keep the drone in sight, **or** use a visual observer. The FAA says an observer is necessary for goggle (FPV) flying. The observer must stand next to you, close enough to talk directly without radios or phones, and must be able to see the drone with the naked eye for the whole flight. The FAA also expects club safety guidelines to cover the goggle pilot's own ability to see the drone, so keep it close enough that you could see it if you lifted your goggles. |
| Altitude and airspace | At or below 400 ft in uncontrolled (Class G) airspace. Controlled airspace needs prior authorization (LAANC or DroneZone). |
| Give way | Do not interfere with other aircraft. |
| Fly for fun only | Anything for work, a business or even a nonprofit falls under Part 107 instead. |
| Follow a community safety code | Follow the guidelines of an FAA-recognized community-based organization. |

## Setup notes

- **Throttle curve.** A whoop hovers at roughly 20-35% throttle, much lower
  than a 5-inch drone. A starting point many beginners use in Betaflight:
  Mid 0.25, Expo 0.35. This is a community suggestion, not a manufacturer
  setting; adjust to taste.
- **Simulator throttle.** If the simulator feels too sensitive, soften it in
  the simulator or with a sim-only radio model, and keep the real flight
  setup untouched.
- **Spare parts.** Check screw size and prop fit for your exact frame before
  ordering spares; small whoops often use M1.4 screws, not M2.

## When to stop and get help

Swollen or damaged LiPo batteries: stop using them and dispose of them
following local rules. If the drone does not respond to the radio, or the
video drops in flight, land and fix it before flying again.
