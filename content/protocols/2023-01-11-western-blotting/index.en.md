---
title: Western Blotting
author: Luis Cantu
date: '2023-01-11'
slug: []
categories: ["Biochemistry"]
tags: []
subtitle: ''
lastmod: '2023-01-11T14:40:46-08:00'
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
This protocol is adapted from the BioRad User Protocol TB446 Rev. A 0905 for their SDS-PAGE Strep-Tag II Fusion products. The protocol is for the transfer and detection of proteins on PVDF and nitrocellulose membranes. However, different membranes might have different blocking conditions.

## Buffer preparation
The following buffer preparations are required for one small blot. You might need to prepare larger volumes.

1. Prepare 300 mL 1x PBS (137 mM NaCl, 10 mM Na2HPO4, 2.7 mM KCl, 1.8 mM KH2PO4, pH 7).
2. Prepare 50 mL blocking solution by mixing 2.5g of BSA and 250 uL TWEEN-20 in 50 mL PBS (5% BSA, 0.5% TWEEN-20 in 1x PBS).
3. Prepare 150 mL PBST by mixing 30 mL of blocking solution with 120 mL of PBS (final concentrations are 1% BSA, 0.1% v/v TWEEN-20 in 1x PBS).
4. Prepare 1 L of Running Buffer by diluting the 10x Tris/Glycine/SDS solution to 1x (Final 1x concentration of Running Buffer is).
5. Prepare Western Transfer Buffer (192 mM glycine, 25 mM Trisbase, 20% methanol, pH 8.0)
6- Have methanol available for activating membrane if needed.

## Protocol
1. Run 10 uL samples on SDS-Page gel (we use miniProtean TGX). Voltage is best at constant 195 V for about 1hr. You need to have New Running Buffer for better results.

2. Electrophoretically transfer proteins to nitrocellulose or other membrane. Our device supports TURBO transfer for 3 minutes per gel, but best results are achieved on our custom protocol of 25V limit, 2.5A constant and 7 minute transfer for 1 gel or 14 minutes for two gels.
{{< admonition type=note title="Monitor the current/voltage on the transferring device. " open=true >}}
You need to have at least 10 minutes of 0.5 A with a limit of 25V. If the current is too low, you should increase the time to ensure complete transfer of the proteins. Similarly, if the current is higher than 0.5 you should decrease the time of transfer to 7 minutes or as little as 3 minutes depending on the current.
{{< /admonition >}}
3. Wash emmbrane 2 times, each for 10 minutes with 15 mL 1x PBS.
{{< admonition type=note title="Tip about membrane size" open=true >}}
Before you transfer the membrane to the washing tray, cut the membrane to the size of the PAGE gel using a blade. This is to ensure you fit the membrane in the small tray and save some antibody since the volumes are smaller.
{{< /admonition >}}

4. Incubate membrane in the remaining 20 mL blocking solution for 2.5 hr at room temperature, or overnight at 4 C with gentle agitation.
Blocking overnight may give a better signal-to-noise ratio.
5. Wash membrane 3 times, each for 5 minutes, with 15 mL PBST.
6. Prepare Primary Antibody solution adding **3.75 uL of His Antibody** in **15 mL** PBST (1:4000 dilution).
7. Add 15 mL diluted Primary antibody solution and **incubate for 60 minutes** at room temperature with gentle agitation.
8. Wash membrane in PBST 3 times for 5 minutes each with 20 mL PBST.
9. Prepare HRP Conjugate Antibody solution adding **3.75 uL of His-HRP conjugate Antibody** in **15 mL** PBST (1:4000 dilution).
10. Add 15 mL diluted HRP Conjugate antibody solution and **incubate for 60 minutes** at room temperature with gentle agitation.
11. Wash membrane 2 times, each for 10 minutes with 20 mL PBST.
11. Wash membrane 2 times, each for 10 minutes with 20 mL PBS.

## Visualizing Blot membrane
1. Drain the membrane by touching the corner of a dry paper towel in a 45 degree angle.
2. Place the membrane on the clean tray cover.
3. Prepare SuperSignal HRP Substrate by mixing 1 mL of 2x Luminol/Enhancer and 1 mL of 2x Stable Peroxide Solution.
4. Wet the entire surface with SuperSignal HRP Substrate quickly . Incubate the blot in the substrate for 2 minutes.
5. Remove membrane from substrate and drain excess membrane by touching paper towel.
6. Place membrane in plastic development folder to remove any bubbles.
7. Use the Chemi high sensitivity setting on the Visualizer camera.


<!--more-->
