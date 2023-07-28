---
title: "Localized adaptive waveform inversion: regularizations for Gabor deconvolution and 3-D field data application"
collection: publications
permalink: /publication/2023-YONG-LAWI
excerpt: 'This paper develops an effective method to address the cycle-skipping issue.'
date: 2023-5-29
venue: 'Geophysical Journal International'
# paperurl: 'http://academicpages.github.io/files/paper2.pdf'

---
Recently, we have developed a localized adaptive waveform inversion (LAWI) method to tackle the cycle-skipping issue in velocity reconstruction through seismic waveform inversion. The LAWI method employs a local matching filter, computed using Gabor deconvolution, to measure the instantaneous time-shift between observed and calculated data. Unlike the adaptive waveform inversion (AWI) approach, the LAWI method can take the non-stationarity between observed and calculated data into account. In this work, we investigate two types of regularization based on prior information about the expected filter, which could be a minimum-norm filter or a delta-shape filter, with regard to their effects on the robustness and resolution of inversion. We demonstrate on synthetic data the advantages and disadvantages of these two types of prior information, where the delta-type LAWI may handle multiple observed phases not initially predicted by the starting velocity model. Therefore, we apply the delta-type LAWI to a high-quality 3-D field data set in the North Sea, eliminating the need for data-windowing tuning, which can be tedious and time-consuming for 3-D data. Under different workflows with varying reliable initial models and frequency bands of the pressure data considered, we show that the LAWI approach is robust, effective and efficient for reconstructing the P-wave velocity, while other approaches such as AWI and graph-space optimal-transport method may require meticulous data-tuning strategies to converge to the correct model. Well logs and data fits, primarily from early arrivals, give us confidence that this LAWI approach could be applied to various acquisitions and subsurface targets, thanks to its phase-driven principle.

[Download paper here](https://doi.org/10.1093/gji/ggad225)

citation: **Yong, P.**, Brossier, R., Métivier, L., & Virieux, J. (2023). Localized adaptive waveform inversion: regularizations for Gabor deconvolution and 3D field data application. **<i>Geophysical Journal International</i>**, 235(1), 448-467.
