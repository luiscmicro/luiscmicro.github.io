---
title: Estimating Colony Forming Units (CFU) on a large plate.
author: Luis Cantu
date: '2025-04-17'
slug: calculating-colony-forming-units-cfu-on-large-plates
categories: []
tags: []
subtitle: ''
lastmod: '2025-04-17T13:12:42-07:00'
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
  enable: yes
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

## 📘 Overview

**Colony-forming unit (CFU)** is a measurement of viable bacterial cells capable of forming a colony. Unlike total cell counts, CFU excludes dead cells and only reflects the number of living, reproductive units in a sample.

This protocol is a modified version of the [Miles and Misra method](https://en.wikipedia.org/wiki/Miles_and_Misra_method), adapted for quick estimation from small glycerol stock volumes.

---

## 📘 Notes

- Units:  
  - **CFU/mL** for liquids  
  - **CFU/g** for solids  
- This is a **semi-quantitative** method using ~2 cm streaks with a multichannel pipette.

---

## 🦠 Part I — Growing cells and layout

1. **Re-suspend glycerol stock**  
   - Glycerol stocks are stored in **10 μL aliquots**.  
   - Re-suspend one aliquot in **1000 μL of 2×YT media**.

2. **Heatshock cells**  
   - Incubate at **50 °C for 10 minutes**.

3. **Prepare serial dilutions**  
   - In **10 PCR tubes**, perform **10-fold serial dilutions**:  
     - Transfer **10 μL** of the original suspension into **90 μL** of fresh 2×YT.  
     - Label the tubes as **1, 10⁻¹, 10⁻², ..., 10⁻⁹**.

4. **Plate dilutions**  
   - Using a **multichannel pipette**, draw a **~2 cm streak** of **10 μL** from each dilution onto an ISP2 agar plate supplemented with appropriate antibiotics if needed. See the example below in Step 5.
   
5. **Incubate**  
   - Grow the plates **overnight at 30 °C**.
   > *Note*: In the example below we've plated in triplicate the same strain. Each column has dilutions from top to bottom:  1, 10⁻¹, 10⁻², ..., 10⁻⁹. Be careful not to plate too close to the edges of the plate to avoid edge distortion.
   >
   > ![Dilution plating example](/images/microbes/CFU_example.png)

## Part II — Cell counting and CFU determination

6. **Identify the readable dilution**  
   - Look for the dilution that gives **individual colonies** (typically 3–5).

7. **Count colonies & calculate CFU/mL**  
   Use the formula:

  
  $$
  \text{CFU/mL} = \frac{\text{Number of colonies} \times \text{Dilution Factor}}{\text{Volume plated (mL)}}
  $$

---

## 🧮 Example Calculation

If **5 colonies** grew on the **10⁻⁸ dilution line**, then:

$$
\begin{aligned}
\text{CFU/mL} &= \frac{5 \times 10^8}{0.01} \\
              &= 5 \times 10^{10} \, \text{CFU/mL}
\end{aligned}
$$


> ⚠️ *Note: Since only a small streak was plated, this value provides an **order of magnitude** estimate, not a precise count.*

---

## ✅ Tips

- Make sure your streaks are consistent in length and volume.
- Always include a negative control plate (just 2×YT).
- Plates with <30 or >300 colonies are generally not used for accurate quantification in full CFU counting methods—but this method is for quick estimation.

<!--more-->
