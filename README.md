CaloricX — Adaptive Calorie Coach
Description

CaloricX is a small full-stack app that adjusts your weekly calorie target based on your real progress—combining your recent weight trend with logged intake—rather than a one-time questionnaire.
For learning & portfolio use only — not medical advice.

Table of Contents

Problem

Solution

MVP Features

Limitations & Disclaimer

Problem

Most calorie apps assign a fixed daily/weekly target and rarely update it as your weight and activity change. This static approach often leads to stalls when progress slows, or overshooting when the target is too aggressive, because the plan doesn’t adapt to your actual outcomes.

Solution

CaloricX recomputes next week’s calorie budget using your recent weight trend and logged intake, then applies a bounded adjustment (e.g., ±250 kcal/day). Each update includes a human-readable rationale so you understand what changed and why. This creates a feedback loop that adapts targets to your observed progress while avoiding extreme swings.

MVP Features

Email/password auth (session via http-only cookies)

Daily food logging (manual entry; simple search stub)

Morning weigh-ins (one per day)

Weekly budget recompute with an explanation card

Dashboard summarizing adherence and trend charts

Limitations & Disclaimer

The energy-balance model is simplified and intended for educational demonstration, not clinical accuracy.

Results can be influenced by hydration, measurement variance, illness, medication, and other factors not modeled here.

Not medical advice. Always consult a qualified professional for nutrition, health, or medical decisions.

This project is for learning & portfolio purposes and may change frequently; features and calculations are subject to revision.
