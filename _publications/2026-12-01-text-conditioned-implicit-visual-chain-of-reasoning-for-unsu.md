---
title: 'Text conditioned implicit visual chain-of-reasoning for unsupervised 3D medical image registration'
collection: publications
category: conference
permalink: /publication/text-conditioned-implicit-visual-chain-of-reasoning-for-unsu
date: 2026-12-01
venue: 'Pattern Recognition (ICPR), Lecture Notes in Computer Science'
doi: 'https://doi.org/10.1007/978-3-032-31673-8_42'
cite: 'Iqbal, M. Z., Ulhaq, A., Grandhi, S., & Saeed, Z. (2026). Text conditioned implicit visual chain-of-reasoning for unsupervised 3D medical image registration. In M. De Marsico, T. K. Ho, F. Jurie, C.-L. Liu, D. Lopresti, I. Nyström, J.-M. Ogier, A. Ross, & L. Wang (Eds.), <i>Pattern Recognition</i> (Lecture Notes in Computer Science, pp. 631–644). Springer Nature Switzerland.'
---

**Citation:** Iqbal, M. Z., Ulhaq, A., Grandhi, S., & Saeed, Z. (2026). Text conditioned implicit visual chain-of-reasoning for unsupervised 3D medical image registration. In M. De Marsico, T. K. Ho, F. Jurie, C.-L. Liu, D. Lopresti, I. Nyström, J.-M. Ogier, A. Ross, & L. Wang (Eds.), <i>Pattern Recognition</i> (Lecture Notes in Computer Science, pp. 631–644). Springer Nature Switzerland.

<a href="https://doi.org/10.1007/978-3-032-31673-8_42" class="btn btn--primary">Access paper here</a>

## Abstract

This paper proposes a text-conditioned progressive reasoning framework for anatomically consistent 3D deformable medical image registration. Unlike conventional registration models that rely on image intensities or features, our approach targets progressive enhancement of deformation vector fields. It is conditioned on expert textual guidance to achieve the desired coverage of salient anatomical structures. Textual prompts are embedded into semantic representations that drive a purpose-built modulation pathway. This pathway supports joint reasoning over fixed and moving volumetric features. These text-enhanced features guide a coarse-to-fine stack of deformation vector fields, including DVF1, DVF2, and DVF3. Each level performs an attention mechanism between reference and source features. The network is trained in an unsupervised manner using image similarity and regularisation losses. It does not require ground truth deformations. Experiments on 3D brain MRI from the IXI dataset show improved global alignment and better region-focused accuracy in prompt relevant anatomical structures. Results are compared with a text-free baseline. We also augmented a dataset of 1,064 text descriptions derived from the standard 133 FreeSurfer brain regions. In addition, the model produces interpretable intermediate deformation fields that illustrate how deformation evolves across scales. This highlights the potential of a multimodal chain of reasoning as a strong driver of anatomically consistent 3D image registration.
