---
title: "Frame-Event Alignment and Fusion Network for High Frame Rate Tracking"
collection: publications
permalink: /publication/2023-Frame-Event-Alignment-and-Fusion-Network-for-High-Frame-Rate-Tracking
excerpt: 'Object Tracking'
date: 2023
venue: 'CVPR 2023'
paperurl: 'http://WangYuanchen.github.io/files/CVPR_2023_pdf.pdf'
citation: 'Zhang J, Wang Y, Liu W, et al. Frame-event alignment and fusion network for high frame rate tracking[C]//Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2023: 9781-9790.'
---
## Input-Output
Given the first event frame image and corresponding bounding box, our network produces the following bounding boxes.
## Abstract
Most existing RGB-based trackers target low frame rate benchmarks of around 30 frames per second. This setting restricts the tracker’s functionality in the real world, especially for fast motion. Event-based cameras as bioinspired sensors provide considerable potential for high frame rate tracking due to their high temporal resolution. However, event-based cameras cannot offer fine-grained texture information like conventional cameras. This unique complementarity motivates us to combine conventional frames and events for high frame rate object tracking under various challenging conditions. In this paper, we propose an end-toend network consisting of multi-modality alignment and fusion modules to effectively combine meaningful information from both modalities at different measurement rates. The alignment module is responsible for cross-style and crossframe-rate alignment between frame and event modalities under the guidance of the moving cues furnished by events. While the fusion module is accountable for emphasizing valuable features and suppressing noise information by the mutual complement between the two modalities. Extensive experiments show that the proposed approach outperforms state-of-the-art trackers by a significant margin in high frame rate tracking. With the FE240hz dataset, our approach achieves high frame rate tracking up to 240Hz.
