---
layout: page
<!---
title: Distracted Driver Dataset
subtitle: Machine Intelligence Research Group, the American University in Cairo
-->
---
<h4 style="text-align: center;"><strong>Distracted Driver Dataset</strong></h4>
<h4 style="text-align: center;"><strong>Hesham M. Eraqi <sup>1,3,*</sup>, Yehya Abouelnaga <sup>2,*</sup>, Mohamed H. Saad <sup>3</sup>, Mohamed N. Moustafa <sup>1</sup></strong></h4>
<p style="text-align: center;"><sup>1</sup>The American University in Cairo<br /> <sup>2</sup>Technical University of Municho<br /> <sup>3</sup>Valeo Egypto<br /> <sup>*</sup>Both authors equally contributed to this work.</p>

![Data](https://heshameraqi.github.io/data/auc.distracted.driver.dataset/Data.png)

### Datasets

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-34fe{background-color:#c0c0c0;border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
</style>
<table class="tg">
  <tr>
    <th class="tg-c3ow"></th>
    <th class="tg-c3ow">Distracted Driver V1</th>
    <th class="tg-c3ow">Distracted Driver V2</th>
  </tr>
  <tr>
    <td class="tg-c3ow">Key Contributions</td>
    <td class="tg-0pky">
		<ul class="dashed">
			<li>First publicly available dataset for distracted driving</li>
			<li>Training and testing datasets are split randomly</li>
		</ul>
	</td>
    <td class="tg-0pky">
		<ul class="dashed">
			<li>Collected more data with more drivers</li>
			<li>More precise labeling and better sampling per class</li>
			<li>Training and testing datasets are split based on drivers</li>
		</ul>
	</td>
  </tr>
  <tr>
    <td class="tg-c3ow">Dataset Information</td>
    <td class="tg-c3ow">31 drivers</td>
    <td class="tg-c3ow">44 drivers</td>
  </tr>
  <tr>
    <td class="tg-c3ow">License Agreement</td>
    <td class="tg-c3ow"><a href="https://heshameraqi.github.io/data/auc.distracted.driver.dataset/Distracted_Driver_Dataset_V1_License_Agreement.pdf">License Agreement V1</a></td>
    <td class="tg-c3ow"><a href="https://heshameraqi.github.io/data/auc.distracted.driver.dataset/Distracted_Driver_Dataset_V2_License_Agreement.pdf">License Agreement V2</a></td>
  </tr>
  <tr>
    <td class="tg-c3ow">Download Link</td>
    <td class="tg-c3ow" colspan="2">If you agree with terms and conditions, please fill out the license agreement and send it to: <a href="mailto:yehya.abouelnaga@tum.de">Yehya Abouelnaga: yehya.abouelnaga@tum.de</a> or <a href="mailto:heraqi@aucegypt.edu">Hesham M. Eraqi: heraqi@aucegypt.edu</a>.Upon receiving a filled and signed license agreement, we will send you the dataset and our training/testing splits.</td>
  </tr>
  <tr>
    <td class="tg-c3ow">Publication</td>
    <td class="tg-0pky" colspan="2">
		<ul class="dashed">
			<li>H. Eraqi, Y. Abouelnaga, M. Saad, M. Moustafa, "Driver Distraction Identification with an Ensemble of Convolutional Neural Networks", Journal of Advanced Transportation, Machine Learning in Transportation (MLT) Issue, 2019.</li>
			<li>Y. Abouelnaga, H. Eraqi, and M. Moustafa. "Real-time Distracted Driver Posture Classification". Neural Information Processing Systems (NIPS 2018), Workshop on Machine Learning for Intelligent Transportation Systems, Dec. 2018.</li>
		</ul>
	</td>
  </tr>
</table>


### Terms & Conditions

<td class="tg-0pky" colspan="2">
	<ul class="dashed">
		<li>The dataset is the sole property of the Machine Intelligence group at the American University in Cairo (MI-AUC) and is protected by copyright. The dataset shall remain the exclusive property of the MI-AUC.</li>
		<li>The End User acquires no ownership, rights or title of any kind in all or any parts with regard to the dataset.</li>
		<li>Any commercial use of the dataset is strictly prohibited. Commercial use includes, but is not limited to: Testing commercial systems; Using screenshots of subjects from the dataset in advertisements, Selling data or making any commercial use of the dataset, broadcasting data from the dataset.</li>
		<li>The End User shall not, without prior authorization of the MI-AUC group, transfer in any way, permanently or temporarily, distribute or broadcast all or part of the dataset to third parties.</li>
		<li>The End User shall send all requests for the distribution of the dataset to the MI-AUC group.</li>
		<li>All publications that report on research that uses the dataset should cite our publications.</li>
	</ul>
</td>

### Description

This is the first publicly available dataset for distracted driver detection. We had 44 participants from 7 different countries: Egypt (37), Germany (2), USA (1), Canada (1), Uganda (1), Palestine (1), and Morocco (1). Out of all participants, 29 were males and 15 were females. Some drivers participated in more than one recording session with different time of day, driving conditions, and wearing different clothes.
Videos were shot in 5 different cars: Proton Gen2, Mitsubishi Lancer, Nissan Sunny, KIA Carens, and a prototyping car. We extracted 14,478 frames distributed over the following classes: Safe Driving (2,986), Phone Right (1,256), Phone Left (1,320), Text Right (1,718), Text Left (1,124), Adjusting Radio (1,123), Drinking (1,076), Hair or Makeup (1,044), Reaching Behind (1,034), and Talking to Passenger (1,797). The sampling is done manually by inspecting the video files with eye and giving a distraction label for each frame. The transitional actions between each consecutive distraction types are manually removed. The figure below shows samples for the ten classes in our dataset.

### Citation

All publications that report on research that use the dataset should cite our work(s):

{: .box-warning}
Hesham M. Eraqi, Yehya Abouelnaga, Mohamed H. Saad, Mohamed N. Moustafa, "Driver Distraction Identification with an Ensemble of Convolutional Neural Networks", Journal of Advanced Transportation, Machine Learning in Transportation (MLT) Issue, 2019.

{: .box-warning}
Yehya Abouelnaga, Hesham M. Eraqi, and Mohamed N. Moustafa, "Real-time Distracted Driver Posture Classification", Machine Learning for Intelligent Transportation Systems Workshop in the 32nd Conference on Neural Information Processing Systems (NeuroIPS), Montréal, Canada, 2018.

![Data](https://heshameraqi.github.io/data/auc.distracted.driver.dataset/System.png)

### Institutions

Our work is being used by researches across academia and research labs:
<div>
<div><img src="/images/logos/auc.jpg" /></div>
<div><img src="/images/logos/tum.gif" /></div>
<div><img src="/images/logos/valeo.png" /></div>
<div><img src="/images/logos/intel.png" /></div>
<div><img src="/images/logos/university-of-warwick.png" /></div>
<div><img src="/images/logos/washington.edu.png" /></div>
<div><img src="/images/logos/University-of-Waterloo.png" /></div>
<div><img src="/images/logos/university_of_illinois.gif" /></div>
<div><img src="/images/logos/University_of_Sussex_Logo.png" /></div>
<div><img src="/images/logos/DCU_Three_Castles.png" /></div>
<div><img src="/images/logos/uestc.png" /></div>
<div><img src="/images/logos/ustc.png" /></div>
<div><img src="/images/logos/beijing-institute-of-technology.png" /></div>
<div><img src="/images/logos/chinese-academy-of-sciences.png" /></div>
<div><img src="/images/logos/beijing_info_tech_uni_logo.png" /></div>
<div><img src="/images/logos/chalmers.png" /></div>
<div><img src="/images/logos/kyungpook.png" /></div>
<div><img src="/images/logos/alzahra_university.jpg" /></div>
<div><img src="/images/logos/national_usct_pakistan.png" /></div>
<div><img src="/images/logos/UNIMIB-LOGO.png" /></div>
<div><img src="/images/logos/raphta.png" /></div>
<div><img src="/images/logos/Lanzhou_Univ_logo.png" /></div>
<div><img src="/images/logos/technical-university-cluj-napoca-romania.png" /></div>
<div><img src="/images/logos/kyunghee-university.jpg" /></div>
</div>
