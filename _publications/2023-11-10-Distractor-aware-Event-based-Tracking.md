---
title: " Distractor-aware Event-based Tracking"
collection: publications
permalink: /publication/2023-11-10-Distractor-aware-Event-based-Tracking
excerpt: 'Keywords: Event camera, visual object tracking, vision transformer, deep neural network'
date: 2023-11-10
venue: 'IEEE Transactions on Image Processing'
paperurl: 'http://WangYuanchen-wyc.github.io/files/IEEE TIP 2023.pdf'
citation: 'Fu Y, Li M, Liu W, et al. Distractor-aware event-based tracking[J]. IEEE Transactions on Image Processing, 2023.'
---
## Input-Output
With the event camera, given the video and the starting target position of the first frame, our network produces the subsequent position of target in the video.
## Abstract
Event cameras, or dynamic vision sensors, have recently achieved success from fundamental vision tasks to high-level vision researches. Due to its ability to asynchronously capture light intensity changes, event camera has an inherent advantage to capture moving objects in challenging scenarios including objects under low light, high dynamic range, or fast moving objects. Thus event camera are natural for visual object tracking. However, the current event-based trackers derived from RGB trackers simply treat events as another form of visual cues, which may not be robust dealing with moving cameras or cluttered foreground. In this paper, we propose a distractor-aware event-based tracker that introduces transformer modules into Siamese network architecture. Specifically, our model is composed of a motion-aware network and a target-aware network, which simultaneously exploits both motion cues and object contours from event data, so as to discover motion objects and identify the target object by removing dynamic distractors. Our proposed tracker can be trained in an end-to-end manner without any post-processing and can run at over 80 FPS on a single V100. We conduct comprehensive experiments on two large event tracking datasets to validate the proposed model. We demonstrate that the proposed method has superior performance against the state-of-the-art trackers in terms of both accuracy and efficiency.
