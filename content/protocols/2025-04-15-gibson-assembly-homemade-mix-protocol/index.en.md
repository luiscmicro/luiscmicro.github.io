---
title: Gibson Assembly Homemade mix Protocol
author: Luis Cantu
date: '2025-04-15'
slug: gibson-assembly-homemade-mix-protocol
categories: []
tags: []
subtitle: ''
lastmod: '2025-04-15T16:34:03-07:00'
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
## Overview

This protocol outlines how to prepare a homemade Gibson Assembly mix and carry out the reaction for cloning. It includes buffer preparation, enzyme mix, reaction setup, and transformation tips.

---

## Reagents

- **Taq DNA Ligase** (NEB; M0208L)  
- **T5 Exonuclease** (NEB; M0363S)  
- **Phusion HF DNA Polymerase** (NEB; M0530S)  
- **β-Nicotinamide adenine dinucleotide (NAD⁺)** (NEB; B9007S)  
- **JM109 Chemical Competent Cells** (Promega; L2005)  
- **10-beta Electrocompetent *E. coli*** (NEB; C3020K)  
- **ElectroMAX™ Stbl4™ Competent Cells** (Invitrogen; 11635-018)  

---

## 🧪 5× ISO Reaction Buffer (6 mL)

| Reagent                           | Amount     |
|----------------------------------|------------|
| 1 M Tris-HCl pH 7.5              | 3.0 mL     |
| 2 M MgCl₂                        | 150 μL     |
| 100 mM dGTP                      | 60 μL      |
| 100 mM dATP                      | 60 μL      |
| 100 mM dTTP                      | 60 μL      |
| 100 mM dCTP                      | 60 μL      |
| 1 M DTT                          | 300 μL     |
| PEG-8000                         | 1.5 g      |
| 100 mM NAD⁺                      | 300 μL     |
| Nuclease-free H₂O               | to 6 mL    |

> 📌 **Aliquot 350 μL** and store at **−20 °C**. Stable for 1 year.

---

##  2× Gibson Assembly Master Mix (1.2 mL)

| Reagent                        | Amount     |
|--------------------------------|------------|
| 5× ISO Buffer                 | 320 μL     |
| T5 Exonuclease (10 U/μL)      | 0.64 μL    |
| Phusion Polymerase (2 U/μL)   | 20 μL      |
| Taq DNA Ligase (40 U/μL)      | 160 μL     |
| Nuclease-free H₂O             | up to 1.2 mL |

> 📌 **Aliquot 100 μL** and store at **−20 °C**. Stable for 1 year.

---

## Assembly Reaction Setup

| Component                       | 20 μL Reaction | 10 μL Reaction |
|--------------------------------|----------------|----------------|
| 2× Gibson Master Mix           | 10 μL          | 5 μL           |
| Digested Plasmid               | x μL           | x μL           |
| Insert DNA (1:2–10 molar ratio) | y μL           | y μL           |
| Nuclease-free H₂O             | z μL           | z μL           |
| **Total Volume**               | 20 μL          | 10 μL          |

> ⚠️ Use a molar ratio of **1:2 to 1:10** (plasmid : insert).

### 🔥 Incubation
Incubate at **50 °C for 15 min to 2 hours** (usually 2 hours).

---

## Transformation

- Use **JM109 Chemical Competent Cells** for inserts <10 kb.  
- Use **Electrocompetent Cells** (e.g., 10-beta or ElectroMAX™ Stbl4™) for inserts >10 kb.  


---

> ✅ Homemade Gibson is cost-effective and reliable for many cloning workflows, especially in high-throughput settings.
<!--more-->
