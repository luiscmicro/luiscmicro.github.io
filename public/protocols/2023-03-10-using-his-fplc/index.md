# Using His-FPLC


<!--more-->
This protocol is used to purify protein from E. coli with a IPTG induceable plasmid. Adjustments to the growth conditions, lysis buffers, and wash buffers can help achieve higher yields.


We typically make 500 mL of autoinducing media.

## Buffer preparation
The following buffer preparations are required for purification of a large culture. (500 mL autoinducing-media culture). These volumes are sufficiently large for a 60 mL lysate suspension.

1. Prepare 600 mL of Buffer A (500 mM Sodium Phosphate Buffer, 500 mM NaCl, 0.01% tween-20, pH ~8.0).
{{< admonition type=note title="To make Buffer A " open=true >}}
  1. Mix 27.9 mL of 1M Na2HPO4, 2.04 mL of 1M NaH2PO4.
  2. Add 570 mL of ddH2O.
  3. Add 17.53g NaCl
  4. Add 60 uL of tween-20
{{< /admonition >}}

2. Prepare 300 mL of Buffer B (500 mM Sodium Phosphate Buffer, 500 mM NaCl, 300 mM Imidazole, pH ~8.0).
{{< admonition type=note title="To Make Buffer B " open=true >}}
  1. Mix 14 mL of 1M Na2HPO4, 1 mL of 1M NaH2PO4.
  2. Add 267 mL of ddH2O.
  3. Add 8.76 g NaCl
  4. Add 18 mL of 5M Imidazole.
{{< /admonition >}}

## Preparing Cell Lysate

1. Weight 

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




