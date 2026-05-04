# CycleTrack - Free-to-Premium Conversion Analysis

## Overview

CycleTrack is a freemium women's health app with 15,000 users across six markets.
The product team reported an overall free-to-premium conversion rate of 11%, a
number that on the surface looked acceptable.

This project investigates whether the 11% average is telling the full story,
identifies the root cause of underperformance in a specific user segment,
sizes the revenue opportunity, and designs an experiment to test a targeted
intervention.

---

## Business Questions

1. Is the 11% conversion rate uniform across users, or is it masking meaningfully
   different behaviour across segments?
2. If underperforming segments exist, what is causing it?
3. What should the team do about it, and how would we know it is working?

---

## Key Findings

- **The 11% average masks a 4x conversion gap.** Segmenting users by their first
  30 days of behaviour reveals trackers convert at 22%, while insights readers,
  26% of the user base, convert at just 5.1%.

- **The root cause is a paywall mismatch, not lack of demand.** Insights readers
  convert at 19% when shown an insights-specific paywall but only 5.1% when shown
  a generic prompt. They see the generic prompt 75% of the time.

- **The opportunity is worth approximately £16,000 in incremental annual revenue**
  from this segment alone, based on a conservative lift from 5.1% to 14%
  conversion.

---

## Proposed Intervention

Show insights readers an insights-specific paywall by default, one that surfaces
premium health content directly relevant to what they already engage with, rather
than the generic upgrade prompt, they currently see 75% of the time.

---

## Experiment Design Summary

| | |
|---|---|
| **Hypothesis** | Personalising the paywall for insights readers will increase free-to-premium conversion |
| **Exposed population** | Insights readers only |
| **Primary metric** | Free-to-premium conversion rate |
| **Proxy metric** | Premium preview engagement rate (fires 10 days before conversion event) |
| **Guardrails** | Overall conversion rate, month 1 churn |
| **Experiment duration** | 10 weeks |
| **Read proxy metric at** | Week 2 |

---
