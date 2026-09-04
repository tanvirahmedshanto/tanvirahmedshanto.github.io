---
layout: page
permalink: /projects/conference/
title: conference papers
description: Peer-reviewed conference proceedings spanning SAMPE, the Solid Freeform Fabrication Symposium, IISE, and MARTEC.
nav: false
toc:
  sidebar: left
---

[← Back to research overview]({{ '/projects/' | relative_url }})

---

## Evaluation of deep learning architectures for defect detection in fused filament fabrication

Dola, I. S., Ahmed, R., Zulqernine, M. J., **Shanto, T. A.**, & Taylor, R. M.
_SAMPE Conference and Exhibition_, Seattle, WA, April 27–30, 2026.

{% comment %} Add a figure: e.g. annotated defect detection output
{% include figure.liquid path="assets/img/research/defect-detection.jpg" alt="Detected FFF print defects" caption="Automated detection of warping, stringing and layer shifting." zoomable=true %}
{% endcomment %}

**Methodology.** Three deep-learning computer-vision architectures — YOLO, Mask R-CNN, and DeepLab — were
evaluated for detecting and segmenting typical FFF defects: cracking, warping, stringing, off-platform
errors, and layer shifting. Object detection and semantic segmentation were compared on image data from
controlled in-house experiments and external sources, focusing on variation in defect size and severity
under consistent geometric conditions. Performance was assessed with mean Average Precision (mAP), AP50,
Intersection over Union (IoU), and Dice coefficient.

**Findings.** YOLO gave superior object-level localization across most defect categories; Mask R-CNN
offered better spatial interpretability through instance-level segmentation; DeepLab performed well
mainly for compact defects. The comparison provides practical guidance for matching an architecture to
defect characteristics in in-situ quality monitoring.

**Status.** Published — [DOI: 10.33599/nasampe/s.26.91](https://doi.org/10.33599/nasampe/s.26.91)

---

## Machine learning-based prediction of toughness in fused filament fabrication: leveraging in-process annealing with enhanced printheads

Ahmed, R., **Shanto, T. A.**, Rahman, M. M., Taylor, R. M., & Jain, A.
_Solid Freeform Fabrication 2025: Proceedings of the 36th Annual International Solid Freeform Fabrication Symposium_, 1182–1200.

**Methodology.** An enhanced printhead enabling in-situ annealing was used to improve interlayer bonding
in ABS. Forty-four thermal features captured by infrared thermography were analysed using correlation
and Principal Component Analysis, retaining 99.8% of variance. Classifiers including k-Nearest
Neighbours, Decision Trees, Naive Bayes, Support Vector Machines, Artificial Neural Networks, XGBoost,
and CatBoost were evaluated for predicting mechanical toughness.

**Findings.** Artificial Neural Networks achieved the highest balanced accuracy at **86.7%** with an area
under the curve of **90.7%** for toughness classification, while regression models offered only limited
continuous prediction. Pairing thermal monitoring with machine learning shows real potential for
non-destructive, real-time quality assurance.

**Status.** Published.

---

## Leveraging large language models for process parameter optimization in 3D-printed ABS polymer specimens

**Shanto, T. A.**, Pavel, H. R., Ahmed, R., Abdullah, M., & Taylor, R. M.
_IISE Annual Conference and Expo 2025_, 1351–1356.

**Methodology.** Four large language models — Microsoft Phi-2, Qwen2.5-Math-1.5B,
DeepSeek-R1-Distill-Qwen-1.5B, and StableLM-3B-4e1t — were applied to predictive modelling of tensile
strength using few-shot inference. Experimental tensile data from specimens printed with varied nozzle
type, extrusion width, and print speed provided the basis, with performance assessed by Mean Absolute
Error, Root Mean Square Error, and R².

**Findings.** Phi-2 showed the strongest predictive capability among the models tested, indicating that
LLM-based few-shot methods can adapt rapidly in additive manufacturing settings where data is scarce —
a regime where conventional design-of-experiments approaches struggle with non-linear parameter
interactions.

**Status.** Published — [DOI: 10.21872/2025IISE_6901](https://doi.org/10.21872/2025IISE_6901)

---

## Predicting mechanical strength in FDM printed ABS parts with in-process annealing: a machine learning approach

**Shanto, T. A.**, Shahriar, M. A., Ahmed, T., Zulqernine, M. J., & Taylor, R. M.
_IISE Annual Conference and Expo 2025_, 1224–1229.

**Methodology.** A patent-pending modified heater block assembly and a conventional brass nozzle were
used to print ASTM D638 Type IV tensile specimens. Nozzle type, print speed, and part spacing were
studied against ultimate tensile strength, and Decision Tree, Random Forest, Gradient Boosting, and
Support Vector Regression models were fitted to predict tensile stress.

**Findings.** Nozzle type dominated ultimate tensile strength, with in-situ annealing clearly
outperforming the conventional nozzle, while part spacing and print speed had smaller effects. Random
Forest attained the highest prediction accuracy, demonstrating its suitability for modelling mechanical
properties tied to FDM process parameters.

**Status.** Published — [DOI: 10.21872/2025IISE_6734](https://doi.org/10.21872/2025IISE_6734)

---

## A statistical approach for evaluating printing temperature and material flowrate effects on lightweight polylactic acid in fused filament fabrication

Ahmed, S., Rahman, M. M., **Shanto, T. A.**, Ahmed, R., & Taylor, R. M.
_IISE Annual Conference Proceedings 2026_ (Abstract ID 17263).

**Methodology.** A full-factorial design of experiments examined printing temperature and flowrate
variation for lightweight PLA. Tensile coupons were printed under controlled conditions and modulus of
toughness assessed, with analysis of variance and pairwise comparisons of factor levels used to separate
main effects from interactions.

**Findings.** Both main effects and their interaction were statistically significant for mechanical
toughness, confirmed by pairwise comparison. The study addresses a gap in the literature around the
coupled effects of temperature-dependent foaming and material flowrate in lightweight PLA, giving
practical guidance for balancing performance against efficiency.

**Status.** Published (in press).

---

## A statistical study on the influence of build-volume temperature and bead overlapping of PEI in fused filament fabrication

Rahman, M. M., Ahmed, S., **Shanto, T. A.**, Ahmed, R., & Taylor, R. M.
_IISE Annual Conference Proceedings 2026_ (Abstract ID 16940).

**Methodology.** A full-factorial design of experiments on ULTEM™ 9085 (PEI) examined build-volume
temperature at three levels (80 °C, 100 °C, 120 °C) against infill overlap at three levels (0%, 10%,
16.67%). A heated build volume promotes interlayer bonding by improving polymer chain mobility, while
bead overlap creates a "squish effect" that presses beads together to reduce voids and raise contact
area.

**Findings.** Build-volume temperature and infill overlap each exert a strong individual influence on the
quality and mechanical strength of printed PEI parts, giving concrete guidance for optimizing
high-performance polymer printing.

**Status.** Published (in press).

---

## Genetic algorithms in order-picking route optimization: a review of advances and implications for logistics

Abdullah, M., Ozay, D., Ahmed, S. M. T., **Shanto, T. A.**, & Sridhar, E. P.
_IISE Annual Conference and Expo 2025_, 1375–1380.

**Methodology.** A systematic literature review following the PRISMA approach, searching ProQuest, Web of
Science, and ScienceDirect. Keywords were refined through preliminary searches, and the process moved
through initial search, title and abstract screening, and full-text review — 30 papers reached full-text
analysis, with the 10 most-cited examined in depth.

**Findings.** Genetic algorithms proved effective and flexible across diverse routing conditions and
outperformed traditional methods, informing decision-making in logistics and supply-chain management
where order picking accounts for a large share of warehouse cost.

**Status.** Published — [DOI: 10.21872/2025IISE_6932](https://doi.org/10.21872/2025IISE_6932)

---

## Application of fused filament fabrication in the marine sector: from rapid prototyping to final product

Ahmed, R., Niloy, R. S., Mozumder, M. R., & **Shanto, T. A.**
_Proceedings of MARTEC 2024_, Johor Bahru, Malaysia, 24–26 September 2024.

**Methodology.** A review of recent advances in applying FFF within the marine sector, together with the
limitations constraining its use and recent attempts to overcome them.

**Findings.** Identifies where FFF is already viable for marine production and sets out future research
directions for moving from rapid prototyping toward final marine products.

**Status.** Published.

---

## An investigation on the applications of additive manufacturing in the marine industry

Zulqernine, M. J., Alam, M. A., Uddin, M. R., Dola, I. S., & **Shanto, T. A.**
_Proceedings of MARTEC 2024_, Johor Bahru, Malaysia, 24–26 September 2024.

**Methodology.** A survey of metal and polymer AM processes as applied to marine use: fabrication of ship
structural components, machinery, and auxiliary equipment including stiffeners, panels, and propeller
blades; on-board 3D printing for component repair and spare-part production; and polymer AM in boat
manufacturing.

**Findings.** Sustainability, production capacity, and part reliability emerge as the principal barriers
to adoption. The paper proposes routes for integrating AM into ship construction and repair.

**Status.** Published.
