---
title: Colony PCR
author: Luis Cantu
date: '2025-04-15'
slug: colony-pcr
categories: []
tags: []
subtitle: ''
lastmod: '2025-04-15T16:24:09-07:00'
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
## Colony PCR Protocol

1. Add **50 µL** of filtered dH₂O to a PCR tube.  
2. Scrape **2 µL loop** of cells from plates and resuspend in the 50 µL dH₂O.  
3. Grind up the colony using the electric grinder for **30 seconds**.  
4. Boil at **98°C for 10 minutes** using the thermocycler.  
5. This will be your **2 µL template** for the PCR reaction.  
6. Prepare a **Master Mix** PCR solution using the NEB table of ingredients.  
7. Split your master mix into **19 µL aliquots**.  
8. Add **2 µL of template** to each aliquot.  
9. Edit the `BB_Q5` program in the thermocycler to adjust the **annealing temperature**.  
10. Edit the `BB_Q5` program in the thermocycler to adjust the **annealing time**.  
11. Run the PCR products on a **1% agarose gel**.

---

### Notes

- Always calculate annealing temperature using the NEB Tm Calculator:  
  [http://tmcalculator.neb.com/#!/main](http://tmcalculator.neb.com/#!/main)

- Select annealing time according to the formula:  
  **20–30 seconds per 1000 bp**
<!--more-->
