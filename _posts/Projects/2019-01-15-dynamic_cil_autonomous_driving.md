---
layout: page
title: Dynamic Conditional Imitation Learning Autonomous Driving
tags: [Autonomous Driving, Dynamic Conditional Imitation Learning, End-to-end Learning]
category: Dataset
image: /data/DCIL/Results Video Thumbnail.png
---

<h2 style="text-align: center;"><strong>Dynamic Conditional Imitation Learning Autonomous Driving</strong></h2>
<h4 style="text-align: center;"><strong>Hesham M. Eraqi<sup>1</sup>, Mohamed N. Moustafa<sup>2</sup>, Jens Honer<sup>3</sup></strong></h4>
<p style="text-align: center;"><sup>1 </sup>Computer Science and Engineering Department, <b>The American University in Cairo</b>, Egypt<br /> <sup>2 </sup>Last Mile Geospatial team, <b>Amazon</b>, Seattle, Washington, United States<br /> <sup>3 </sup> Driving Assistance department, <b>Valeo</b> Schalter und Sensoren GmbH, Germany Egypt<br />
<div class="row" style="width:400; margin:0 auto;" align="center"> 
  <div class="column">
    <img src="/data/DCIL/AUC.jpg" width="120" />
	<img src="/data/DCIL/Amazon.png" width="120" />
	<img src="/data/DCIL/Valeo.png" width="120" />
  </div>
</div>
</p>
<h4 style="text-align: center;"><a href="https://heshameraqi.github.io/docs/Dynamic_Conditional_Imitation_Learning for_Autonomous_Driving.pdf"><strong>Download Paper PDF (Peer-reviewed accepted preprint)</strong></a></h4>

{: .box-warning} 
**Please cite our work:** Hesham M. Eraqi, Mohamed N. Moustafa, Jens Honer. Dynamic Conditional Imitation Learning for Autonomous Driving. IEEE Transactions on Intelligent Transportation Systems (ISSN: 1524-9050, Online ISSN: 1558-0016). Issue 12, Vol 23, Pages 22988-23001. DOI: 10.1109/TITS.2022.3214079, December 2022. [Impact Factor: 9.551]

![D-CIL](https://heshameraqi.github.io/data/DCIL/Work Zones.png)

**Paper:** [https://ieeexplore.ieee.org/document/9928072](https://ieeexplore.ieee.org/document/9928072)

**Code:** [https://github.com/heshameraqi/Dynamic-CIL-Driving](https://github.com/heshameraqi/Dynamic-CIL-Driving)

**arXiv:** [https://arxiv.org/abs/2211.11579](https://arxiv.org/abs/2211.11579)

**Video showing D-CIL method in action in test town (better watched in Full-HD):**

[![Video showing D-CIL method in action in test town](/data/DCIL/Results Video Thumbnail.png)](https://www.youtube.com/watch?v=v3DaKJL-HCQ)

The ego-car successfully detects two road blockages and dynamically estimate and follows new routes to eventually reach the designation successfully.

### Summary:

An extension to the Conditional Imitation Learning approach for Autonomous Driving is presented to tackle the challenges of lack of generalization, inconsistency against varying weather conditions, and inability to avoid unexpected static road blockages. The laser scanner input is fused with the regular camera streams, at the features level of the proposed Deep Learning model, to overcome the generalization and consistency challenges. A new efficient Occupancy Grid Mapping method is introduced, with improved runtime performance, memory utilization, and map accuracy, along with new algorithms for road blockages avoidance and global route planning to allow for dynamically detecting partial and full road blockages and guiding the vehicle to another route to reach the destination. Experimental results on CARLA simulator urban driving benchmark demonstrated the effectiveness of the proposed methods.

![Work Zones Algorithm](https://heshameraqi.github.io/data/DCIL/Work Zones Algorithm.png)

![Work Zones Algorithm](https://heshameraqi.github.io/data/DCIL/DCIL-Network.png)
