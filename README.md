# Who eats like a Groninger? 🍳
## Finding the eierbal's hidden cousins in Dutch snack culture

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Data License](https://img.shields.io/badge/data-Google%20Trends-lightgrey)
![License](https://img.shields.io/badge/license-MIT-green)

---

## Why this project

I live in Groningen and the eierbal is everywhere here, a deep-fried egg wrapped in minced
meat that locals treat as a point of civic pride. The rest of the Netherlands has mostly
never heard of it.

That got me thinking: are there any national Dutch snacks that actually behave like the
eierbal? Not in terms of what they are, but in terms of when people search for them,
how seasonal they are, how quietly consistent their pattern is over the years.

I used Google Trends data for 11 Dutch snacks and applied PCA to find out.
The answer surprised me a little.

---

## What I found

| | |
|---|---|
| **Closest neighbour** | Kaassouffle, nearly identical search trajectory in PCA space |
| **Second closest** | Mexicano, same low key and consistent pattern over the years |
| **Surprise entry** | Stroopwafel, unexpected but the data says so |
| **Most different** | Gehaktbal, completely different search behaviour |
| **PC1 explains** | 86% of all variance, meaning national popularity is the dominant dimension |

> The eierbal is not alone. Somewhere out there, kaassouffle lovers and eierbal lovers
> are searching Google at the same time of year, probably from the same kind of cold Tuesday evening.
> They just don't know it yet.

---

## Data source

**Dataset:** Google Trends, search interest for 11 Dutch snacks  
**Country:** Netherlands  
**Period:** 2004 to 2026  
**License:** Google Trends data is freely available for public use  
**Note:** Google Trends reports relative search interest on a scale of 0 to 100, not absolute consumption volumes.

---

## Tech stack

- **pandas** — data loading and merging
- **scikit-learn** — PCA and standardisation
- **matplotlib** — all charts
- **seaborn** — styling

---

*Debora Brigido, 2026*
