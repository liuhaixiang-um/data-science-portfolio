---
layout: page
title: Data Science Portfolio
---

MSc student at the University of Macau, building practical skills in data
analysis, reproducible research, and clear communication.

## About me

I am a graduate student at the University of Macau. My current focus is on
turning raw data into reproducible analyses and understandable stories: asking
a precise question, documenting the data and methods, and presenting findings
with visualizations that a non-specialist can read. I am currently completing
CISC7204, where this portfolio is part of my practice work.

## Technical skills

- **Programming:** Python (pandas, NumPy, scikit-learn, matplotlib)
- **Data work:** exploratory data analysis, data cleaning, descriptive
  statistics, feature comparison, cross-validation
- **Tools:** Git and GitHub, GitHub Pages, Jupyter/VS Code, Markdown, HTML
- **Practices:** reproducible environments (`requirements.txt`), documented
  workflows, version control, responsible data use

## Project showcase

### Iris Morphology: How Well Do Petal Measurements Separate Species?

**Research question:** How well do petal length and petal width separate
*Iris setosa*, *Iris versicolor*, and *Iris virginica*, and which measurements
are most discriminative?

**Visualization**

![Petal length vs. petal width by species](https://raw.githubusercontent.com/liuhaixiang-um/data-science-project/main/figures/petal_scatter.svg)

*Figure: Petal length vs. petal width, coloured by species.*

**What the visualization shows:** *Iris setosa* forms a completely isolated
cluster with short, narrow petals. *Iris versicolor* and *Iris virginica* lie
along a nearly linear band and are mostly separated, with a small overlap
around petal lengths of 4.5–5.0 cm. Petal length and petal width are strongly
correlated (r ≈ 0.96), and a depth-3 decision tree trained on these two
features reaches about 96% stratified 5-fold cross-validation accuracy. The
practical takeaway is that petal measurements carry most of the species signal
in this dataset, while sepal measurements are much less discriminative.

A second view of the same data shows the distribution of petal length by
species:

![Distribution of petal length by species](https://raw.githubusercontent.com/liuhaixiang-um/data-science-project/main/figures/petal_box.svg)

**Limitation:** the Iris dataset is small, balanced, and historical (150
flowers from one original collection), so this near-perfect separation is
evidence about this sample, not a general claim about all Iris populations.

- **Project repository:** https://github.com/liuhaixiang-um/data-science-project
- **Status:** Completed

## What is next

I plan to add a larger and messier dataset with documented cleaning decisions
and uncertainty estimates, and to include a reproducible execution check so
that readers can verify the results, not only read about them.
