---
layout: post
title: Investigating the interaction between genetic breast cancer risk and epigenome
date: 2023-09-28 10:00
inline: false
---

Research into genetic risk factors for breast cancer has yielded polygenic risk scores (PRSs). However, genetic risk factors such as polygenic risk scores are static. To follow a person's changing environment and health, dynamic markers are required. In a new manuscript published in [npj Precision Oncology](https://doi.org/10.1038/s41698-023-00452-2), we investigated the interaction between the epigenome and genetic background at methylation quantitative trait loci (mQTLs) associated with breast cancer.

Our results indicate that although methylation levels at methylation QTLs are genetically determined, they show variability across cell types. This variability may carry information about non-heritable changes in risk. For breast cancer, cervical samples with a high epithelial cell content carried the largest amount of variability.

<p float="left">

<img src="../../assets/img/qtbc_variability.png" alt="Variability across mQTL sites or all CpGs in cervical, buccal, or blood samples of varying immune cell proportion." width="750" />

</p>

A linear combination of methylation values at 104 mQTL sites, termed the '<b>W</b>omen's cancer risk <b>id</b>entification - <b>q</b>uantitative <b>t</b>rait index for <b>b</b>reast <b>c</b>ancer', or simply WID™-qtBC, detects current cancer cases with an AUC of 0.71 in cervical samples.

The methylation-based WID™-qtBC was modified by age and other nonheritable factors associated with breast cancer risk, including body mass index or age at menopause. Interestingly, the correlation between the polygenic risk score (PRS) and mQTL index was weak. However, women with both a high PRS and high WID-qtBC score exhibited a 9.6-fold increased risk for being diagnosed with breast cancer, indicating an interaction of genetic and non-genetic risk factors at the level of the epigenome.

<p float="center">

<img src="../../assets/img/qtbc_auc.png" alt="The WID™-qtBC detects current breast cancer cases with an area under the curve of 0.71 in an external validation set." width="290" />

<img src="../../assets/img/qtbc_age.png" alt="The WID™-qtBC is increased with chronological age, a key risk factor for breast cancer." width="290" />

</p>

Our data suggest that the WID™-qtBC alone or in combination with the PRS may improve breast cancer risk stratification compared to current methods, but further research is required to validate our findings.

Read the article:

<div class="publications">

	{% bibliography --query @*[keywords=qtbc] %}

</div>