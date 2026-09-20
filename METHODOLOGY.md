# What counts as progress?

A problem list becomes useful when another person can tell whether anything improved.

## Three layers

1. **Grand challenge:** the human outcome we ultimately want, in [PROBLEMS.md](PROBLEMS.md).
2. **Bounded brief:** a specific population, workflow and test, in [CATALOGUE.md](CATALOGUE.md).
3. **Evidence record:** observed baseline, experiment and results, added when actual work happens.

The repository currently contains the first two. It does not yet contain completed experiments.

## Separate five kinds of numbers

| Type | Meaning | Current treatment |
|---|---|---|
| Observed baseline | Measured performance of a defined system | Unknown until a host supplies it |
| Source-backed estimate | Published estimate with population, date and method | Cite the exact supporting source |
| Planning assumption | Hypothetical input for sizing | Label explicitly and vary it |
| Proposed target | A threshold for deciding whether a pilot is useful | All numerical targets in the new briefs |
| Achieved result | An observed effect under a documented evaluation | None claimed |

The broad map's 80%, 90%, 100× and similar numbers are aspiration prompts. They are not estimates of AI capability or guaranteed savings. The narrower briefs provide more testable starting hypotheses.

## Pick a measurable slice

Name the population, geography, workflow, unit, exclusions and time horizon. A global problem can begin with one language or one facility. Global relevance does not imply global validity.

Break the workflow into detection, decision and completed outcome. Where only a proxy can be measured in 90 days, state the later outcome study required.

## Beat the strongest practical alternative

Compare with the existing workflow after obvious repairs, a rules-based process, a tuned classical method or qualified human work. Hold access, budget and support constant where possible. A bad baseline can make any intervention look impressive.

Use chronological or held-out-site evaluation for predictive tasks. Do not leak future outcomes into training. Prefer randomised or crossover comparisons when feasible; otherwise document confounders and avoid causal claims.

## Write an outcome contract before running the pilot

For each metric define:

- Numerator and denominator, including failed and abandoned cases.
- Measurement window and source of truth.
- Absolute baseline, proposed change and whether change is relative or percentage points.
- Full cost, including data work, compute, review, integration and ongoing maintenance.
- Counter-metrics, subgroup checks and stop conditions.
- A named independent reviewer and a plan for disputed cases.

If a baseline rate is 20%, a 25% relative reduction means 15%, not minus five percent of all possible cases without a denominator. If there are no failures in 100 independent trials, that does not establish zero real-world failure probability.

## Estimate value without inventing a global market

**Hypothetical time-saving example:** 1,000 cases/month × 12 minutes baseline × 30% reduction = 60 gross hours/month. If review and integration support consume 25 hours/month, net saving is 35 hours. These inputs are illustrative, not evidence for any brief.

**Hypothetical waste example:** 500 kg/week baseline waste × 20% reduction = 100 kg/week avoided. Count extra transport, reduced sales, supplier losses and downstream disposal before claiming a net benefit.

Use a range of volumes, effects and costs. Do not extrapolate one successful store, language, clinic or simulator to the world. Avoid monetising lives or relationships casually; retain natural outcome units.

## Evidence maturity

- **Draft:** a falsifiable specification; evidence and host not yet secured.
- **Seed:** prior work and local relevance reviewed; baseline acquisition planned.
- **Active:** named steward, verified access, baseline, comparator and outcome contract.
- **In progress:** an experiment is actually running.
- **Solved locally:** independently supported outcome within the stated scope.
- **Archived:** superseded, rejected or inactive, with reasons retained.

A score is optional at draft stage. At later stages, assess human value, global relevance, AI contribution, decomposability, measurability, economic sustainability, safety readiness and deployment path. Explain each judgment and uncertainty; do not manufacture a universal leaderboard.

## Source and result integrity

The new briefs are authored research and product hypotheses, not a systematic literature review. Named existing approaches are starting comparators. Any linked source supports only the associated context, not our proposed targets.

For medical, legal, financial, engineering and public-safety uses, a pilot target is never a substitute for applicable professional validation. High-stakes decisions remain with qualified, accountable people. Data access, approvals and partners must be real before a trial starts.

## Publish what would change your mind

Every brief includes a stop condition. Report negative results and simpler solutions that win. The value of this project includes discovering where AI is unnecessary.
