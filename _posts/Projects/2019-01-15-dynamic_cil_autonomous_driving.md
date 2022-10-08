---
layout: page
title: Distracted Driver Dataset
tags: [Distracted Driver, Dataset]
category: Dataset
---

<h2 style="text-align: center;"><strong>Dynamic Conditional Imitation Learning Autonomous Driving</strong></h2>
<h4 style="text-align: center;"><strong>Hesham M. Eraqi <sup>1,*</sup>, Mohamed N. Moustafa <sup>2,*</sup>, Jens Honer <sup>3,*</sup></strong></h4>
<p style="text-align: center;"><sup>1 </sup>Computer Science and Engineering Department, The American University in Cairo, Egypt<br /> <sup>2 </sup>Amazon<br /> <sup>3 </sup> Driving Assistance department, Valeo Schalter und Sensoren GmbH, Germany Egypt</p>

![D-CIL](https://heshameraqi.github.io/data/DCIL/Work Zones.png)

### Institutions
Code: https://github.com/heshameraqi/Dynamic-CIL-Driving
arXiv: (will be posted soon)

### Abstract:

Conditional imitation learning (CIL) trains deep neural networks, in an end-to-end manner, to mimic human driving. This approach has demonstrated suitable vehicle control when following roads, avoiding obstacles, or taking specific turns at intersections to reach a destination. Unfortunately, performance dramatically decreases when deployed to unseen environments and is inconsistent against varying weather conditions. Most importantly, the current CIL fails to avoid static road blockages. In this work, we propose a solution to those deficiencies. First, we fuse the laser scanner with the regular camera streams, at the features level, to overcome the generalization and consistency challenges. Second, we introduce a new efficient Occupancy Grid Mapping (OGM) method along with new algorithms for road blockages avoidance and global route planning. Consequently, our proposed method dynamically detects partial and full road blockages, and guides the controlled vehicle to another route to reach the destination. Following the original CIL work, we demonstrated the effectiveness of our proposal on CARLA simulator urban driving benchmark. Our experiments showed that our model improved consistency against weather conditions by four times and autonomous driving success rate generalization by 52%. Furthermore, our global route planner improved the driving success rate by 37%. Our proposed road blockages avoidance algorithm improved the driving success rate by 27%. Finally, the average kilometers traveled before a collision with a static object increased by 1.5 times. The source code will be made publicly available.

### Citation

Please cite our work:

{: .box-warning}
Hesham M. Eraqi, Mohamed N. Moustafa, Jens Honer. Dynamic Conditional Imitation Learning for Autonomous Driving. IEEE Transactions on Intelligent Transportation Systems, 2022.

![Work Zones Algorithm](https://heshameraqi.github.io/data/DCIL/Work Zones Algorithm.png)
![Work Zones Algorithm](https://heshameraqi.github.io/data/DCIL/DCIL-Network.png)