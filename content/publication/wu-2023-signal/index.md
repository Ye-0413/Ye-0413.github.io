---
title: 'Signal-to-image: Rolling bearing fault diagnosis using ResNet family deep-learning
  models'
authors:
- Guoguo Wu
- Xuerong Ji
- Guolai Yang
- Ye Jia
- Chuanchuan Cao
date: '2023-01-01'
publishDate: '2024-08-18T18:50:16.455665Z'
publication_types:
- article-journal
publication: '*Processes*'
---
### Abstract

Rolling element bearings (REBs) are the most frequent cause of machine breakdowns. Traditional methods for fault diagnosis in rolling bearings rely on feature extraction and signal processing techniques. However, these methods can be affected by the complexity of the underlying patterns and the need for expert knowledge during signal analysis. This paper proposes a novel signalto-image method in which the raw signal data are transformed into 2D images using continuous wavelet transform (CWT). This transformation enhances the features extracted from the raw data, allowing for further analysis and interpretation. Transformed images of both normal and faulty rolling bearings from the Case Western Reserve University (CWRU) dataset were used with deeplearning models from the ResNet family. They can automatically learn and identify patterns in raw vibration signals after continuous wavelet transform is used, eliminating the need for manual feature extraction. To further improve the training results, squeeze-and-excitation networks (SENets) were added to improve the process. By comparing results obtained from several models, we found that SE-ResNet152 has the best performance for REB fault diagnosis.