---
title: "TrackingExperiments"
summary: "A research prototype for psychophysics experiments where a participant tracks a moving object in real time."
status: "Research"
role: "Developer"
stack: ["C#", ".NET", "Experiment software"]
repo: "https://github.com/debarshikundu/TrackingExperiments"
featured: true
order: 1
---

## The problem

Psychophysics research often needs a participant to follow a moving target while the software records what they do and when. Off-the-shelf tools are either too rigid for a custom experiment or too expensive for a student lab.

## What it does

TrackingExperiments is a desktop prototype that presents a moving object and captures the participant's tracking behaviour. It was built to be adapted quickly: the experiment loop, visual presentation, and data capture live in one small application instead of being spread across a stack of scripts.

## How it's built

The application is written in **C#** on .NET. Keeping it as a single desktop program made it possible to run on lab machines without a server, and to reason about timing in one place.

## What I took away

- Real-time interaction is mostly a timing and state problem, not a graphics problem.
- Research software has to be boring in the right places: reproducible runs, predictable output, no surprises.
- The hardest part of a prototype is deciding which knobs to expose and which to hard-code.

## Next steps

Packaging the configuration so a researcher can define a new experiment without touching the source, and adding a cleaner export format for analysis.
