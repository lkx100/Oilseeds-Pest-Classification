# 🐛 Pest Classification App
> This is an on-going research work, repo will be updated soon!

## Introduction
Pest detection in economically vital crops like castor (Rici-
nus communis) is critical for food security, yet manual inspection is im-
practical at scale. Deep learning (DL) offers a potent solution, but its
application is hindered by data scarcity and the need for lightweight, de-
ployable models. This study addresses this gap by conducting a rigorous
comparative analysis of transfer-learned Convolutional Neural Networks
(CNNs) against custom-trained Vision Transformers (ViTs) optimized
for efficiency. We introduce a novel, expert-annotated dataset of castor
pests, collected under diverse field conditions, and systematically eval-
uate architectures under three augmentation setup, including CutMix.
Our5-foldcross-validationresultsshowthatCNNs,ledbyResNet50with
a peak accuracy of 98.18%, consistently outperform their transformer
counterparts by approximately 5%. However, our custom lightweight
ViTsdemonstratedhighlycompetitiveperformancewithafractionofthe
parameters, showcasing significant gains from augmentation. This find-
ing highlights their substantial potential as a future-proof solution for
highly resource-constrained environments. Our work ultimately provides
critical insights into the evolving trade-offs between model architecture,
data availability, and on-device deployment in agricultural AI.
