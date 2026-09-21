# Explore farther: calculations, habitats and unresolved physics

**Supporting research proposal; reviewed 2026-09-21.** Exploration and settlement are proposed extensions of this project's scope, not existing commitments or validated catalogue problems. Their human purposes could include discovery, participation in science and more choices about where to live. They also require discussion of costs, opportunity costs and who gets to participate.

The [human-outcome method](../METHODOLOGY.md) still applies: a faster instrument or spacecraft is useful when it enables something people value. Open scientific knowledge may be a benefit, but a calculation cannot establish affordable access to space or justify a settlement program on its own.

## One inspectable journey

Consider an idealized **1 kg probe** traveling to Proxima Centauri, the nearest star beyond the Sun. Use **4.25 light-years**, the rounded distance in [NASA's description of the neighboring system](https://science.nasa.gov/exoplanets/other-stars-other-worlds/our-nearest-celestial-neighbor-an-exotic-3-star-system/), and **c = 299,792,458 m/s**, the exact [NIST value](https://physics.nist.gov/cuu/Constants/Value/c.html). Probe mass and cruise speeds are illustrative assumptions, not mission designs.

Model origin and destination as stationary in one inertial frame. Ignore gravity, stellar motion, acceleration distance and changing mass. Assume instantaneous acceleration to cruise speed and, for a rendezvous, instantaneous deceleration at arrival. Those assumptions make travel times optimistic lower bounds for the selected maximum speed; they are not achievable maneuvers.

Let `beta = v/c`, `gamma = 1/sqrt(1-beta²)`, and `m = 1 kg`:

- Cruise time in the origin frame: `t = distance/v = 4.25/beta years`.
- Payload kinetic energy in that frame: `K = (gamma-1)mc²` joules.
- One kilowatt-hour equals `3.6 × 10^6 J`.
- A reply from a stationary probe at the destination takes about **4.25 years one way**, or **8.5 years round trip**, ignoring processing time. During transit the separation varies.

| Assumed cruise speed | Ideal transit time | Kinetic energy added to 1 kg | Equivalent energy in kWh | Energy magnitude added, then removed for rendezvous |
|---|---:|---:|---:|---:|
| 0.01c | 425 years | 4.494 × 10^12 J | 1.248 × 10^6 | 8.988 × 10^12 J |
| 0.10c | 42.5 years | 4.528 × 10^14 J | 1.258 × 10^8 | 9.056 × 10^14 J |
| 0.20c | 21.25 years | 1.853 × 10^15 J | 5.148 × 10^8 | 3.707 × 10^15 J |

The last column is `2K`, an accounting of the magnitudes of acceleration and braking energy changes. **It is not a universal purchased-energy requirement:** braking might dissipate energy, recover some, or require additional propellant and input energy. A flyby does not perform destination braking. A propulsion design must specify the mechanism before translating these numbers into a supply budget.

These figures include only payload kinetic energy. They omit propulsion equipment, propellant/exhaust energy, inefficiency, beam losses, shielding, interstellar dust impacts, power generation, communications, thermal rejection and reliability over decades. Adding mass scales the listed energy linearly at fixed speed; increasing speed does not. This is a lower-bound calculation, not a costed mission.

### Reproduce and challenge the result

Use the definitions above in a spreadsheet or calculator. At 0.10c, `gamma = 1.0050378153`, so `K = 0.0050378153 × 299792458² ≈ 4.528 × 10^14 J`. Recompute the other rows and verify that the low-speed value approaches `mv²/2`. Keep light-years as distance and years as time; do not treat a light-year as a duration.

For a useful next comparison, specify one propulsion concept and separately identify whether it is a flyby or rendezvous. Replace instantaneous acceleration with a trajectory, add hardware and propulsion mass, and show how the concept supplies or removes momentum and energy. Record every input's source, units, date and uncertainty. An independently checked bound that rules out an appealing configuration is a useful result.

## Living away from Earth is another problem

Travel does not establish habitable conditions on arrival. A proposed habitat must balance water, oxygen, food, waste, spare parts, radiation exposure and power over a stated duration, including faults. NASA reported a [98% water-recovery milestone in the ISS system](https://www.nasa.gov/missions/station/iss-research/nasa-achieves-water-recovery-milestone-on-international-space-station/). That specific achievement does not demonstrate a self-sufficient ecology or eliminate the need for resupply.

A first investigation could audit an existing published life-support mass balance: which flows enter and leave, which losses recur, and which repairs need Earth? Then evaluate fault detection against conventional alarms on declared scenarios. Count false alarms and operator effort. Simulation success is not authorization to control occupied life-support equipment.

Human freedom belongs in the design too. Ask who controls access to air, housing and transport; what happens in a dispute; and whether a resident can leave. A technically functioning habitat can still be an unacceptable place to live.

## Four structures, different purposes

| Concept | Purpose and evidence boundary | Next constraint to resolve |
|---|---|---|
| Smaller rotating habitat | Create an inhabited environment with rotation-induced apparent gravity. [NASA SP-413](https://nss.org/settlement/nasa/75SummerStudy/Design.html) is a historical conceptual design study, not evidence of a built settlement. | Structure, radiation shielding, human response to rotation, maintenance and full life-support accounting. |
| Banks-style Orbital | A fictional enormous rotating ring used as living space; [Banks describes the construction assumptions](https://teagmhail.github.io/the-culture/essays/a-few-notes/). | Materials and structural loads at that scale, before any claim of buildability. Smaller habitats do not establish its feasibility. |
| Dyson swarm | Here, a proposed collection of separately orbiting energy collectors; not necessarily inhabited. | Mass supply, manufacturing, orbital coordination, maintenance and disposal of waste heat. Specify intercepted power and collector area. |
| Rigid Dyson shell | Here, a continuous shell surrounding a star, distinct from an orbital swarm. | A mechanically consistent support and stability model, materials and thermal balance. Do not reuse swarm assumptions for a shell. |

“Dyson” draws on [Dyson's 1960 proposal to search for artificial stellar infrared sources](https://pubmed.ncbi.nlm.nih.gov/17780673/); the name supplies no engineering validation. For any proposed structure, report the intended service, material budget and governing loads before using artistic scale as evidence.

## Warp travel: a question, not an engineering schedule

[Alcubierre (1994)](https://arxiv.org/abs/gr-qc/0009013) describes a spacetime geometry allowing effective superluminal travel and explicitly requires exotic matter. A mathematical metric is not a method to create or control that geometry. It does not demonstrate a craft locally accelerating through the speed of light.

[Santiago, Schuster and Visser (2022)](https://arxiv.org/html/2105.03079v2) analyze energy-condition violations in broad classes of warp geometries and challenge positive-energy claims. Their conclusions depend on stated frameworks and conditions; they are substantial constraints, not an experimental demonstration of every conceivable future theory's impossibility.

Useful progress would specify a physically realizable source of the required stress-energy, a stable and controllable formation process, and predictions distinguishing the proposal from existing physics. New physics must account for existing observations as well as produce independent testable predictions. Reproducing a metric or optimizing its parameters cannot substitute for these steps. No feasible warp-drive construction or readiness date is established by the cited papers.

## Where AI could earn its place

Compare AI-assisted calculation checking with a unit-aware spreadsheet and expert review. For literature reproduction, preserve equations, assumptions, versions and failed attempts. For constrained design search, evaluate held-out configurations against conventional optimization with the same budget. For mission-data analysis, measure validated scientific findings and false positives, not generated hypotheses alone.

The first contribution wanted is an independent audit of the probe table and identification of one published propulsion or habitat model with sufficient inputs to reproduce. A physics or engineering reviewer must assess the selected model before stronger feasibility claims. No mission, partner, experiment or funding is secured. Retain negative results, and stop expanding a design when its required assumptions cannot be stated or checked.
