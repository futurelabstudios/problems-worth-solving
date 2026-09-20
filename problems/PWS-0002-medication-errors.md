---
id: PWS-0002
title: Catch dangerous medication errors before harm occurs
status: seed
domain: Health
geography: Global
steward: unassigned
last_reviewed: 2026-09-20
tags: [patient-safety, medicines, clinical-decision-support]
---

# PWS-0002: Catch dangerous medication errors before harm occurs

## In one sentence

Patients are harmed because prescriptions, diagnoses, allergies, laboratory results and concurrent medicines are not checked together at the moment a decision is made.

## The human reality

A medicine can be correct in isolation and dangerous in context. The risk grows when patients see several doctors, records are incomplete, brand names vary and clinicians work under time pressure.

## Evidence

WHO identifies medication-related harm as a major avoidable burden and launched **Medication Without Harm** to reduce severe avoidable harm: [WHO patient-safety challenge](https://www.who.int/initiatives/medication-without-harm).

## Desired outcome

Reduce preventable severe medication harm while avoiding alert fatigue and preserving timely access to treatment.

## What has been tried

Electronic prescribing, pharmacy review, interaction databases, barcode administration and clinical decision-support alerts. These help, but fragmented data and excessive low-value alerts limit performance.

## What blocks progress

Incomplete medication histories; variable drug nomenclature; missing allergy and kidney/liver data; weak interoperability; poorly calibrated alerts; and unclear responsibility when software disagrees with a clinician.

## Role for intelligence

Reconcile medicine lists, recognise context-sensitive interactions, rank alerts by severity, explain the evidence and detect unusual dosage or duplication patterns. Intelligence should support—not impersonate—the accountable prescriber or pharmacist.

## Data and access

Prescriptions, dispensing records, clinical diagnoses, allergies, laboratory data and adverse-event reports. These are deeply sensitive; use minimum necessary access, strong security and purpose limitation.

## Commissioning map

Hospitals, pharmacy chains, health systems, insurers, regulators and national digital-health programmes.

## Risks and safeguards

Incorrect alerts could delay necessary treatment; uncalibrated systems can worsen alert fatigue. Require silent prospective evaluation, pharmacist review, subgroup testing and complete audit trails before clinical use.

## Evaluation

Severe preventable adverse drug events per 1,000 prescriptions; accepted high-severity alerts; false-alert burden; time added to workflow; and unequal performance across age, sex and comorbidity groups.

## Scores

| Dimension | Score | Rationale |
|---|---:|---|
| Human value | 5 | Directly prevents avoidable injury and death |
| Scale | 5 | Medication use is ubiquitous |
| Neglectedness | 3 | Tools exist but remain fragmented and noisy |
| Tractability | 4 | Structured rules and review workflows are available |
| Measurability | 4 | Prospective safety evaluation is feasible |
| Leverage | 4 | Improves clinical information infrastructure |
| Safety readiness | 3 | False positives and false negatives both matter |
| Commissionability | 5 | Clear institutional buyers and regulators |

## Smallest meaningful next step

Run a silent 90-day audit in one hospital: compare prescriptions against complete context, have pharmacists adjudicate the highest-risk cases and quantify preventable harm plus alert burden before any live intervention.
