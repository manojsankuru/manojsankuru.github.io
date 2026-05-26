---
title: "DGM-CAM: A Lifelong Editing Framework using Dynamic Gradient Masking and Conflict-Aware Merging"
date: 2025-04-16
description: "Poster presented at the UMass Dartmouth Sigma Xi 29th Annual Research Exhibition. Introduces Dynamic Gradient Masking and Conflict-Aware Merging to prevent catastrophic forgetting during continuous model editing streams."
summary: "Introduced Dynamic Gradient Masking and Conflict-Aware Merging to mitigate optimization interference and preserve baseline knowledge base integrity during continuous model editing sequence streams."
tags: ["Model Editing", "Lifelong Learning", "LLMs", "Gradient Masking", "Deep Learning"]
showToc: false

params:
  pubtype: "poster"
  venue: "UMass Dartmouth Sigma Xi 29th Annual Research Exhibition"
  authors: "Manoj Sankuru, Md Shohel Rana"
  doi: "10.13140/RG.2.2.24383.16801"
  event_date: "April 16–17, 2025"
---

## 🔗 Resource Links

* **ResearchGate:** [View Poster & Full Record](https://www.researchgate.net/publication/396921950_DGM-CAM_A_Lifelong_Editing_Framework_using_Dynamic_Gradient_Masking_and_Conflict-Aware_Merging)
* **DOI:** [10.13140/RG.2.2.24383.16801](https://doi.org/10.13140/RG.2.2.24383.16801)

---

## Venue

**University of Massachusetts Dartmouth — Sigma Xi Scientific Research Honor Society**
29th Annual Research Exhibition · April 16–17, 2025

*Posters on display: Wednesday 1:00–3:00 PM and Thursday 10:00 AM–12:00 PM.
Organized by the UMass Dartmouth Chapter of Sigma Xi with financial assistance from the Office of the Chancellor and the Office of Research and Innovation.*

---


## Key Contributions

* **Dynamic Gradient Masking (DGM):** Isolates specific parameter clusters responsible for localised knowledge properties, protecting baseline tasks during model modification and preventing unintended parameter drift across unrelated editing operations.

* **Conflict-Aware Merging (CAM):** Resolves gradient direction contradictions when combining parallel edits across shared network segments, enabling safe concurrent knowledge injection without mutual interference.

* **Lifelong Editing Stability:** Demonstrates sustained editing accuracy across sequential update streams without catastrophic forgetting of previously encoded knowledge — a key open challenge in continual model editing literature.
