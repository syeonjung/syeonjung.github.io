---
layout: post
title: Neighborhood Effects Through Private Supplementary Education
categories: [research]  # research 카테고리로 지정
---

## Neighborhood Effects Through Private Supplementary Education

### Background
Over the past decades, the academic achievement gap between neighborhoods in SOuth Korea has steadily widened. To uncover the causes of these educational disparities across neighborhoods, unequal educational quality within neighborhoods, particularly the disparate quality of private supplementary education across different areas, has been identified as a major concern. However, contrary to these discussions, most studies have only recognized private supplementary education as an inequality resource at the individual level, while  few research has examined whether it actually explains educational inequality between neighborhoods. This study aimed to investigate the influence of private supplementary education beyond individual academic achievement at the community level.

### A Graphical Causal Model
<div style="text-align: center; margin: 20px 0;">
  <img src="{{ site.baseurl }}/assets/img/fig1_causal.png" alt="Causal Diagram" style="display: block; margin: 0 auto; max-width: 100%;">
</div>
<p>
Figure 1 illustrates the relationships between neighborhood context (treatment A), private supplementary education (mediator M), and academic performance (outcome Y). The model includes individual characteristics (baseline confounder C) and school quality (exposure-induced confounder Z). Neighborhood effects operate through two pathways. The direct pathway (A → Y and A → Z → Y) shows neighborhood effects independent of private supplementary education. The indirect pathway (A → M → Y and A → Z → M → Y) demonstrates how neighborhoods influence academic performance through private supplementary education. Total effects can be decomposed into these pathways even with exposure-mediator interaction (VanderWeele, 2015).
</p>
<p>
Two potential confounders require attention. First, individual characteristics (C) like family income and parent's education must be controlled to account for residential sorting. Second, school quality (Z) represents exposure-induced confounding (Wodtke & Zhou 2019), as it affects both private supplementary education and outcomes while being influenced by neighborhood context. 
</p>
<p>
Analyses of time-varying exposures, such as neighborhood socioeconomic status, are complicated by the presence of exposure-induced confounders. These are variables influenced by prior exposures that, in turn, may influence future exposures and outcomes. For instance, in examining how neighborhood socioeconomic status affects academic performance through private supplementary education, private supplementary education can be shaped by neighborhood conditions while simultaneously confounding or moderating the effect of subsequent neighborhood contexts on academic outcomes.
</p>
Exposure-induced confounders pose significant methodological challenges. If left uncontrolled, they introduce bias by conflating the effects of the exposure and the confounder. On the other hand, controlling for them naively using conventional methods can block causal pathways, leading to biased estimates of the direct and indirect effects of the exposure. This dual challenge creates a methodological conundrum for researchers attempting to disentangle the causal mechanisms in longitudinal analyses of neighborhood effects and their mediating processes.Proper adjustment for these confounders, particularly exposure-induced confounding, is crucial for unbiased estimation. This study employs the RWR (regression-with-residuals) method to address these methodological challenges.

### Effects of Private Supplementary Education on Academic Performnace

<div style="text-align: center; margin: 20px 0;">
  <img src="{{ site.baseurl }}/assets/img/fig2_med.png" alt="Causal Diagram" style="display: block; margin: 0 auto; max-width: 100%;">
</div>
<p>
RNDE and RNIE are referred to as ‘natural direct effects’ and ‘natural indirect effects’, which are divided from RATE.
</p>
<p>
While there is an overall neighborhood effect present, these effects are explained solely through the lens of cultural geography across all subjects. When private supplementary education is measured by focusing on physical(number of private supplemenatry education) or economic geography(average tuition fee of private supplementary education), there is little evidence that neighborhood effects on academic performance are mediated by private supplementary education, as the size of RNIE are substantially small and far from statistical thresholds for reading, English, and math scores. Regarding physical and economic geography, the neighborhood effects would not be explained by private supplementary education. Conversely, estimates of the RNIE about cultural geography indicate that the neighborhood effects can be partially explained by private supplementary education across all subjects. Specifically, as the RPIE indicates, the mediated effect predominantly occurs without the interaction effect. Since this model only includes one mediator, it suggests that the cultural characteristics of private supplementary education may explain the direct effects of physical or economic geography.
</p>
<p>
In sum, during middle school, the impact of neighborhoods on academic performance was only meaningful for English scores. Also, the effect is primarily mediated by the cultural characteristics of private supplementary education and partially explained by the economic factors. However, in high school, the neighborhood effects substantially stand out among all subjects, and these disparities across neighborhoods can be explained by cultural geography. In other words, the effects are affected by different educational aspirations against private supplementary education, not the number or tuition fees of private supplementary education.
</p>
