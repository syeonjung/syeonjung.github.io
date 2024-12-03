---
layout: post
title: Neighborhood Effects Through Private Supplementary Education
categories: [research]  # research 카테고리로 지정
---

## Neighborhood Effects Through Private Supplementary Education

### Background
Over the past decades, the academic achievement gap between neighborhoods in SOuth Korea has steadily widened. To uncover the causes of these regional educational disparities, unequal educational quality within neighborhoods, particularly the disparate quality of private supplementary education across different areas, has been identified as a major concern. However, contrary to these discussions, most studies have only recognized private supplementary education as an inequality resource at the individual level, while  few research has examined whether it actually explains educational inequality between neighborhoods. This study aimed to investigate the influence of private supplementary education beyond individual academic achievement at the community level.

### A Graphical Causal Model
<div style="text-align: center; margin: 20px 0;">
  <img src="{{ site.baseurl }}/assets/img/fig1_causal.png" alt="Causal Diagram" style="display: block; margin: 0 auto; max-width: 100%;">
</div>
Figure 1 illustrates the relationships between neighborhood context (treatment A), private supplementary education (mediator M), and academic performance (outcome Y). The model includes individual characteristics (baseline confounder C) and school quality (exposure-induced confounder Z). Neighborhood effects operate through two pathways. The direct pathway (A → Y and A → Z → Y) shows neighborhood effects independent of private supplementary education. The indirect pathway (A → M → Y and A → Z → M → Y) demonstrates how neighborhoods influence academic performance through private supplementary education. Total effects can be decomposed into these pathways even with exposure-mediator interaction (VanderWeele, 2015).
Two potential confounders require attention. First, individual characteristics (C) like family income and parent's education must be controlled to account for residential sorting. Second, school quality (Z) represents exposure-induced confounding (Wodtke & Zhou 2019), as it affects both private supplementary education and outcomes while being influenced by neighborhood context. Analyses of time-varying exposures, such as neighborhood socioeconomic status, are complicated by the presence of exposure-induced confounders. These are variables influenced by prior exposures that, in turn, may influence future exposures and outcomes. For instance, in examining how neighborhood socioeconomic status affects academic performance through private supplementary education, school quality can be shaped by neighborhood conditions while simultaneously confounding or moderating the effect of subsequent neighborhood contexts on academic outcomes.

Exposure-induced confounders pose significant methodological challenges. If left uncontrolled, they introduce bias by conflating the effects of the exposure and the confounder. On the other hand, controlling for them naively using conventional methods can block causal pathways, leading to biased estimates of the direct and indirect effects of the exposure. This dual challenge creates a methodological conundrum for researchers attempting to disentangle the causal mechanisms in longitudinal analyses of neighborhood effects and their mediating processes.Proper adjustment for these confounders, particularly exposure-induced confounding, is crucial for unbiased estimation. This study employs the RWR (regression-with-residuals) method to address these methodological challenges.

### Effects of Private Supplementary Education on Academic Performnace