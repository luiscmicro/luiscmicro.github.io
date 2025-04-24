---
title: Protocol for IC50 using Kinase-Glo assay
author: Luis Cantu
date: '2025-04-23'
slug: protocol-for-ic50-using-kinase-glo-assay
categories: ["Biochemistry"]
tags: []
subtitle: ''
lastmod: '2025-04-23T20:26:02-07:00'
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
  enable: yes
library:
  css: ~
  js: ~
seo:
  images: []
---

# Protocol: IC₅₀ Measurement Using Kinase-Glo Assay

This protocol outlines how to measure IC₅₀ for kinase reactions using the Kinase-Glo assay system.

---

## Stage 1: Prepare Buffer Mix

Prepare an excess of buffer (Tris + 100 mM MgCl₂) for all dilutions and ATP mixes. One 10 mL preparation is sufficient for a single plate.

**Buffer Mix (5 mL total):**

- 400 µL of 1.25 M MgCl₂
- 4600 µL of Tris Buffer (pH 8)

---

## Stage 2: Prepare ATP Mix

### A. 1500 µM ATP (1000 µL total)

- 985 µL Buffer Mix (from Stage 1)
- 15 µL of 100 mM ATP

### B. 800 µM ATP Ladder (400 µL total)

- 396.8 µL Buffer Mix (from Stage 1)
- 3.2 µL of 100 mM ATP

---

## Stage 3: Prepare Protein + Buffer Mix

Use the Protein Calculation Spreadsheet to calculate required volumes. Final concentration of protein in reaction should be 0.5 µM (use 2× protein stock in Tris + MgCl₂ buffer).

**Example Preparation (Fourth Try - 01/23/24):**

| Vial | Protein | Final Conc. (µM) | Final Vol (µL) | Protein Vol (µL) | Stock Conc. (µM) | H₂O (µL) |
|------|---------|------------------|----------------|------------------|------------------|-----------|
| 1    | A8-A    | 1.5              | 80             | 38.5             | 3.12             | 41.5      |
| 2    | A8-A    | 1.5              | 80             | 38.5             | 3.12             | 41.5      |
| 3    | H183A   | 1.0              | 80             | 2.8              | 28.2             | 77.2      |

---

## Stage 4: Prepare Inhibitory Molecule

| Vial | Molecule | Final Conc. (µM) | Final Vol (µL) | Stock Vol (µL) | Stock Conc. (µM) | H₂O (µL) |
|------|----------|------------------|----------------|----------------|------------------|-----------|
| 4    | F8       | 3.0              | 80             | 4.0            | 60               | 76.0      |

---

## Stage 5: Serial Dilution of Inhibitory Molecule

1. Dispense **10 µL Buffer Mix (no ATP)** into PCR tubes labeled 2–8.
2. Dispense **20 µL of inhibitory molecule** (from Stage 4) into tube 1.
3. Perform **serial 1:2 dilutions** by transferring 10 µL sequentially from tubes 1 → 2 → 3 → ... → 8.

---

## Stage 6: Set Up Kinase Reactions in PCR Tubes

1. Dispense **9 µL** from each serial dilution (Stage 5) into new PCR tubes labeled `v1-1` to `v1-8`.
2. Add **9 µL protein mix** (from Stage 3) into each tube.
3. For controls (no inhibitor), use **9 µL Buffer Mix** instead of serial dilution.
4. Add **9 µL of ATP Mix** (from Stage 2) to all tubes.
5. Incubate for **30 minutes at 30°C**.

---

## Stage 7: Kinase-Glo Measurement

1. Dispense **5 µL** of each reaction into a white assay plate.
2. Add **5 µL Kinase-Glo reagent** to each well.
3. Incubate at **room temperature for 10 minutes**.
4. Read luminescence.

---

> 💡 *Ensure all volumes and conditions are adjusted based on your protein stock concentration and assay plate layout.*

<!--more-->
