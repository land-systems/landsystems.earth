---
title: 'Taking It Further: Leveraging Pseudo-Labels for Field Delineation across Label-Scarce Smallholder Regions'
authors:
- philippe-rufin
- Sherrie Wang
- sa-lisboa
- Jan Hemmerling
- Mirela G. Tulbure
- patrick-meyfroidt
date: '2024-11-01'
publication: International Journal of Applied Earth Observation and Geoinformation
publication_types:
- '2'
abstract: 'Satellite-based field delineation has entered a quasi-operationalstage due to recent advancesin machine learning for computer vision. Transfer learning allows for the resource-efficient transfer of pre-trained field delineation models across heterogeneous geographies. However, the scarcity of labeled data for complex and dynamic smallholder landscapes remains a major bottleneck. The key innovation of this study is to overcome this challenge by using pre-trained models to generate sparse (i.e., not fully annotated) field delineation pseudo-labels for fine-tuning models across geographies and sensor characteristics. We build on a FracTAL ResUNet trained for crop field delineation in India (median field size of 0.24 ha) based on multi-spectral imagery at 1.5 m spatial resolution. We use this model to generatepseudo-labels for the use in Northern Mozambique (median field size of 0.06 ha) based on sub-meter resolution true-color satellite imagery. We designed multiple pseudo-label selection strategies based on field-level probability scores and compared the quantities, area properties, seasonal distribution, and spatial agreement of the pseudo-labels against human-annotated training labels (n = 1,512). We then used the human-annotated labels and the pseudo-labels for model fine-tuning and compared predictions against human field annotations (n = 2,199). We evaluated performance with regards to object-level spatial agreement and site-level field size estimation. Our results indicate i) a good baseline performance of the pre-trained model in both field delineation (mean intersection over union (mIoU) of 0.634) and field size estimation (mean root mean squared error (mRMSE) of 0.071 ha), and ii) the added value of regional fine-tuning with performance improvements in nearly all experiments (mIoU increases of up to 0.060, mRMSE decreases of up to 0.034 ha). Moreover, we found iii) substantial performance increases when using only pseudo-labels (up to 77 % of the mIoU increases and 68 % of the mRMSE decreases obtained by human-annotated labels), and iv) additional performance increases (mIoU +0.008, mRMSE: -0.003 ha) when complementing human annotations with pseudo-labels. Pseudo-labels are architecture-agnostic, can be efficiently generated at scale, and thus facilitate domain adaptation in label-scarce settings. The workflow presented here is a stepping stone for overcoming the persisting challenges in mapping heterogeneous smallholder agriculture.'
tags:
links:
- name: URL
  url: https://doi.org/10.1016/j.jag.2024.104149
doi: 10.1016/j.jag.2024.104149
---