---
title: "Localized adaptive waveform inversion: theory and numerical verification"
collection: publications
permalink: /publication/2022-YONG-LAWI
excerpt: 'This paper develops an effective method to address the cycle-skipping issue.'
date: 2022-12-15
venue: 'Geophysical Journal International'
# paperurl: 'http://academicpages.github.io/files/paper2.pdf'

---
Correctly interpreting phase events thanks to data processing techniques based on correlation or deconvolution has been the focus of numerous studies in the field of high-resolution seismic imaging using full-waveform inversion. To mitigate the non-convexity of the misfit function and the risk to converge towards non-informative local minima, correlation and deconvolution techniques make it possible to focus on phase information instead of amplitude information and to design more convex misfit function, alleviating the dependency of the full-waveform inversion process on the accuracy of initial models. Such techniques however rely on the assumption that phase events can be compared one by one, or that all the phase events are shifted in time in a similar way. This assumption is not satisfied in practice, which limits the effectiveness of these correlation/deconvolution-based methods. To overcome this issue, we propose to account for the non-stationary relation between observed and predicted data through a local in-time deconvolution technique, based on time–frequency analysis of the signal using a Gabor transform. This makes it possible to estimate instantaneous time-shift between locally coherent phase events. This strategy generalizes the conventional normalized deconvolution technique, which has been popularized under the name of adaptive waveform inversion. To support the introduction of our novel method, we compare it with four misfit functions based respectively on classical cross-correlation, penalized cross-correlation, penalized deconvolution, and adaptive waveform inversion. We analyse the behaviour of these methods on specific scenarios, and then propose a comparison on 2-D synthetic benchmarks. We show how our ‘localized’ adaptive waveform inversion applies in these realistic tests and overcomes some of the limitations of the aforementioned techniques.

[Download paper here](https://doi.org/10.1093/gji/ggac496)

citation: **Yong, P.**, Brossier, R., Métivier, L., & Virieux, J. (2023). Localized adaptive waveform inversion: theory and numerical verification. **<i>Geophysical Journal International</i>**, 233(2), 1055-1080.
