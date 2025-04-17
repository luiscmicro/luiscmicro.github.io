---
title: Protocol for Small Molecule Solvent Extractions
author: Luis Cantu
date: '2025-04-17'
slug: protocol-for-small-molecule-solvent-extractions
categories: ["LCMS"]
tags: []
subtitle: ''
lastmod: '2025-04-17T13:55:33-07:00'
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

## Introduction

This protocol outlines the steps for extracting small molecules produced by *Actinomycetota* colonies grown on solid media. Colonies are allowed to grow and produce secondary metabolites, after which a small **agar "plug"** containing the colony is removed using a sterile plug corer or biopsy punch. The plug is then subjected to **solvent extraction** to recover diffusible metabolites for downstream analysis, such as LC-MS.

### Definitions

- **Plug**: A small cylindrical section of agar (typically 6–8 mm in diameter) containing microbial growth, excised using a plug tool or biopsy punch.
- **Solvent extraction**: A chemical method used to isolate small molecules by mixing biological samples with solvents (e.g., methanol, ethyl acetate) that dissolve specific classes of compounds.
- **Secondary metabolites**: Bioactive small molecules produced by microbes, often during stationary phase, which can include antibiotics, pigments, or signaling compounds.


# Protocol for Solvent Extractions

1. Add the plugs to **750 µL** of solvent *(methanol and ethyl acetate are most commonly used)* in an Eppendorf tube.

2. Vortex, sonicate for **10 minutes**, and let sit at **room temperature** for at least **1 hour** (or up to 24 hours).

3. Vortex again and transfer the solvent to a new **1.5 mL Eppendorf tube**.

4. **SpeedVac** to evaporate all solvent:  
   - ~15 min for EtOAc  
   - ~45 min for MeOH  
   - ~1 hour for water  
   > ⚠️ Use the **lowest vacuum level** for ethyl acetate (EtOAc), as it's very volatile. Check the chart next to the SpeedVac.

5. Re-suspend the pellet in **500 µL methanol + reserpine** (10 or 100 ng/mL).  
   - *10 ng/mL is usually enough*  
   - *100 ng/mL gives a more robust peak, but may interfere with co-eluting compounds*  
   - For water extractions, use **50:50 methanol:water**.

6. Vortex, **sonicate for 5 min**, then vortex again.

7. Centrifuge for **5 min at 14,000 rpm**.

8. Using solvent-safe pipette tips, **transfer supernatant to LCMS vial**, leaving **~50 µL** behind to avoid disturbing the pellet.

9. **Inspect visually** for any floating particles.  
   - If particles are present, transfer to a new Eppendorf tube and **repeat steps 7–8**.  
   - Ensure it's particle-free before submitting to LCMS.

---

## 💡 Tips

- **Always use solvent-safe tips**. Contaminants from regular tips (e.g., Genesee/Olympus) have caused serious issues.
- **Always include media and solvent controls** in your run.
- Some labs wash Eppendorf tubes before extractions to remove contaminants. We don’t, as long as extraction controls are included:
  - Solvent-only control
  - Sterile media control
- For **small extractions (3–4 plugs)**, use **500 µL solvent**, and re-suspend in **100 µL**. Use **vial inserts** for LCMS.
- **Reserpine** is not required, but helpful to confirm LCMS injection success.
- Avoid extracting in **pure water** – it solubilizes media components and introduces noise into the data.

<!--more-->
