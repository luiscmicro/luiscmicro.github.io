---
title: Michelis Menten with Kinase-Glo Assay
author: Package Build
date: '2025-04-18'
slug: michelis-menten-with-kinase-glo-assay
categories:
  - biochemistry
tags: []
subtitle: ''
lastmod: '2025-04-18T14:27:44-07:00'
authorLink: ''
description: ''
license: ''
images: []
featuredImage: ''
featuredImagePreview: ''
hiddenFromHomePage: no
hiddenFromSearch: no
twemoji: no
lightgallery: yes
ruby: yes
fraction: yes
fontawesome: yes
linkToMarkdown: yes
rssFullText: no
toc:
  enable: yes
  auto: yes
  keepStatic: no
code:
  copy: yes
  maxShownLines: 50
math:
  enable: no
mapbox: ~
share:
  enable: yes
comment:
  enable: no
library:
  css: ~
  js: ~
seo:
  images: []
---


Protocol for Measuring ATPase with Kinase-Glo Assay.
We will hold the protein concentration constant and increase concentrations of substrate (ATP) and incubate for 30 minutes. We can then calculate Km and Vmax using Michaelis-Menten kinetics. 

## Stage 1. Prepare Buffer Mix

Prepare an excess of Buffer Mix (Tris + 100 mM MgCl₂) to make all dilutions and the ATP Buffer.  
5 mL of Buffer Mix should be enough for one plate. Use a sterile 10 mL tube.

- 400 µL 1.25 mM MgCl₂  
- 4600 µL Tris Buffer (pH 8)

---

## Stage 2. Prepare Protein + Buffer Mix

Use the Protein Calculation Spreadsheet to calculate the volume of protein needed.  
We use **0.5 µM protein concentration** diluted in Tris + MgCl₂ buffer.  
This is the **2x concentration buffer**.

> For example:
>
> | Vial | Protein | Final Concentration (µM) | Final Volume (µL) | Protein (µL) | Concentration (µM) | Water (µL) |
> |------|---------|---------------------------|-------------------|--------------|---------------------|------------|
> | 1    | A8-A    | 1.5                       | 80                | 7.1          | 17                  | 72.9       |
> | 3    | H183A   | 1.5                       | 80                | 4.2          | 28.2                | 75.8       |

---

## Stage 3. Prepare ATP Mix

Prepare **400 µL of 800 µM ATP Vial**:

- 396.8 µL of Buffer Mix (from Stage 1)  
- 3.2 µL of 100 mM ATP

---

## Stage 4. Prepare Plate with ATP Serial Dilutions

Make serial dilutions of the ATP Vial (Stage 3) using Eppendorf tubes labeled 1–8.

1. Dispense 200 µL of Buffer Mix (from Stage 1) into tubes labeled 2–8.
2. Dispense 400 µL of ATP Vial (from Stage 3) into tube 1.
3. Make serial dilutions by pipetting 200 µL from tube 1 to 2, then tube 2 to 3, and so on through tube 8.

---

## Stage 5. Prepare PCR Tubes for Kinase Reaction

1. Dispense **9 µL** of each serial dilution (from Stage 4) into new PCR tubes labeled `v1-1` to `v1-8`.
2. Dispense **9 µL** of the appropriate protein mix (e.g., vial 1) into each tube.
3. Repeat for each protein variant (e.g., vial 3).
4. Incubate reaction strips for **30 minutes at 30°C**.

---

## Stage 6. Prepare ATP Standard Curve (Optional but Recommended)

To convert luminescence to ATP concentration, prepare a standard curve in parallel:

1. Start with **600 µM ATP stock solution**.
2. Prepare 1:2 serial dilutions down to 0 µM using Buffer Mix (e.g., 600, 300, 150, 75, 37.5, 18.75, 9.38, 0 µM).  
3. Dispense **5 µL** of each dilution into a white plate well.
4. Add **5 µL** of Kinase-Glo reagent to each well.
5. Let sit at **room temperature for 10 minutes**.
6. Measure luminescence and use to generate a standard curve.

---

## Stage 7. Measurement

1. Dispense **5 µL** of each kinase reaction (from Stage 5) into a white 384-well plate.
2. Add **5 µL** of Kinase-Glo reagent to each well.
3. Let the plate sit for **10 minutes at room temperature** (preferably with light shaking).
4. Read luminescence. If standard curve is available, convert values to ATP concentration.


<!--more-->
