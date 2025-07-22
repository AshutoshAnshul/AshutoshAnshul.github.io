---
title: "Intra-modal and Cross-modal Synchronization for Audio-visual Deepfake Detection and Temporal Localization"
collection: publications
category: conferences
permalink: /publication/2025-10-Intra-Modal-Cross-Modal-Sync
excerpt: 'This paper is about using temrporal synchrnoization within and across-modalities for the task of Multimodal Deepfake Detection and Temporal Localization'
date: 2025-10-19
venue: 'ICCV'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'TBC'
---

Recent deepfake detection algorithms focus solely on uni-modal or cross-modal inconsistencies. While the former disregards audio-visual correspondence entirely rendering them less effective against multimodal attacks, the latter overlooks inconsistencies in a particular modality. Moreover, many models are single-stage supervised frameworks, effective on specific training data but less generalizable to new manipulations. To address these gaps, we propose a two-stage multimodal framework that first learns intra-modal and cross-modal temporal synchronization on real videos, capturing audio-visual correspondences crucial for deepfake detection and localization. We introduce a Gaussian-targeted loss in our pretraining model to focus on learning relative synchronization patterns across multimodal pairs. Using pretrained features, our approach not only enables classification on fully manipulated videos but also supports a localization module for partial deepfakes with only specific segments spoofed. Moreover, the pretraining stage does not require fine-tuning, thus reducing complexity. Our model, tested on various benchmark datasets, demonstrates strong generalization and precise temporal localization.