---
title: "Flix"
summary: "An iOS movie discovery app that pulls from The Movie Database API and presents films in a browsable grid."
status: "Coursework"
role: "iOS developer"
stack: ["Swift", "UIKit", "REST APIs", "iOS"]
repo: "https://github.com/debarshikundu/flix_demoDK"
featured: false
order: 4
---

## What it does

Flix is an iOS app for browsing movies. It fetches data from **The Movie Database (TMDB)** API and displays posters in a grid. Tapping a film opens a detail screen with its artwork and information.

## What I built

- A tab-based interface with a poster grid backed by a `UICollectionView`
- Networking against a third-party REST API, including loading and error states
- A detail view that carries the selected movie's data between screens

## What I learned

- Third-party APIs are a lesson in defensive programming: fields go missing, images arrive late, requests fail.
- The difference between a demo and an app is mostly what happens while the network is slow.
- Small UI decisions — spacing, image aspect ratio, back navigation — carry most of the perceived quality.
