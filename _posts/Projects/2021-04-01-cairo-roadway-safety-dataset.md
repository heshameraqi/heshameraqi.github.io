---
layout: page
title: Cairo Roadway Safety Oriented Bounding Boxes Dataset
tags: [Cairo, Roadway, Safety, Oriented Bounding Boxes, Dataset]
category: Dataset
---

<h2 style="text-align: center;"><strong>Cairo Roadway Safety Oriented Bounding Boxes Dataset</strong></h2>
<h4 style="text-align: center;"><strong>Hesham M. Eraqi et al.</strong></h4>

### Dataset

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;border-color:#aabcfe;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:#aabcfe;color:#669;background-color:#e8edff;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:#aabcfe;color:#039;background-color:#b9c9fe;}
.tg .tg-c3ow{text-align:center}
.tg .tg-0pky{text-align:left}
</style>
<table class="tg" style="undefined;table-layout: fixed; width: 874px" align="center">
<colgroup>
<col style="width: 160px">
<col style="width: 714px">
</colgroup>
  <tr>
    <th class="tg-c3ow"><strong>Field</strong></th>
    <th class="tg-c3ow"><strong>Details</strong></th>
  </tr>
  <tr>
    <td class="tg-c3ow">Key Contributions</td>
    <td class="tg-0pky">
      <ul class="dashed">
        <li>First publicly available dataset for roadway safety assessment in the Greater Cairo Region (GCR)</li>
        <li>Annotated with oriented object bounding boxes (OBB) for roadway features</li>
        <li>Covers 473 km of diverse road classes: local, collector, arterial, and highways</li>
        <li>4,732 samples at 2560 × 1440 px resolution, captured every 100 m</li>
        <li>Data collected over two years (January 2017 – August 2019)</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td class="tg-c3ow">Dataset Statistics</td>
    <td class="tg-c3ow">4,732 samples — 3,714 training/validation + 1,018 testing</td>
  </tr>
  <tr>
    <td class="tg-c3ow">License Agreement</td>
    <td class="tg-c3ow"><a href="https://heshameraqi.github.io/data/cairo.roadway.safety.dataset/Cairo_Roadway_Safety_Dataset_License_Agreement.pdf">License Agreement (PDF)</a></td>
  </tr>
  <tr>
    <td class="tg-c3ow">Download Link</td>
    <td class="tg-c3ow">If you agree with the terms and conditions, please fill out the license agreement and send it to: <a href="mailto:hesham.eraqi@gmail.com">Hesham M. Eraqi: hesham.eraqi@gmail.com</a>. Upon receiving a filled and signed license agreement, we will send you the dataset download link: <a href="https://drive.google.com/drive/u/0/folders/1W3Pz_UdLPrunUs-VVhEIXQR9hiO4Ep7a" target="_blank">Google Drive</a>.</td>
  </tr>
  <tr>
    <td class="tg-c3ow">Annotation Tool</td>
    <td class="tg-c3ow"><a href="https://github.com/heshameraqi/labelImg_OBB" target="_blank">labelImg_OBB — Oriented BBox Annotation Tool</a></td>
  </tr>
  <tr>
    <td class="tg-c3ow">Publication</td>
    <td class="tg-0pky">
      <ul class="dashed">
        <li>Hesham M. Eraqi et al. <a href="https://www.mdpi.com/2076-3417/11/8/3531" target="_blank">Automatic Roadway Features Detection with Oriented Object Detection</a>. <em>Applied Sciences</em> (ISSN: 2076-3417), 11(8), 2021.</li>
      </ul>
    </td>
  </tr>
</table>


### Terms & Conditions

<ul class="dashed">
  <li>The dataset is the sole property of the Machine Intelligence group at the American University in Cairo (MI-AUC) and is protected by copyright. The dataset shall remain the exclusive property of the MI-AUC.</li>
  <li>The End User acquires no ownership, rights or title of any kind in all or any parts with regard to the dataset.</li>
  <li>Any commercial use of the dataset is strictly prohibited. Commercial use includes, but is not limited to: Testing commercial systems; Using screenshots of subjects from the dataset in advertisements, Selling data or making any commercial use of the dataset, Broadcasting data from the dataset.</li>
  <li>The End User shall not, without prior authorization of the MI-AUC group, transfer in any way, permanently or temporarily, distribute or broadcast all or part of the dataset to third parties.</li>
  <li>The End User shall send all requests for the distribution of the dataset to the MI-AUC group.</li>
  <li>All publications that report on research that use the dataset should cite our publication.</li>
  <li>This database was captured to develop the state-of-the-art in detection of roadway safety assessment and so it may be used freely to this purpose. Other research uses of this database are encouraged. However, the End User must first obtain prior consent from the MI-AUC group.</li>
</ul>


### Description

The dataset was collected in the Greater Cairo Region (GCR) and is composed of 473 km travelled between local roads, collector roads, regional and primary arterial roads, and regional and primary highways. The dataset was fully annotated with oriented object bounding boxes. The table below details the distances covered for each roadway class; such variety of road classes in the dataset allowed validating the proposed methods on roadway classes that are unseen during training and development time.

A front-facing camera was designed to capture an image every 100 m, with each image including the longitude, latitude, altitude, time and average vehicle speed. The data collection plan was designed to cover a period of over two years from January 2017 to August 2019 and covered times from 6:00 a.m. to 12:00 p.m. and from 2:00 p.m. to 7:00 p.m. The complete dataset is composed of 4,732 samples (divided to 3,714 for training and validation and 1,018 samples for testing) with a resolution of 2560 × 1440 pixels captured every 100 m. In order to label the collected images, a multi-platform oriented bounding boxes (OBB) annotation tool was developed: [labelImg_OBB](https://github.com/heshameraqi/labelImg_OBB).

**Data collection design in the Greater Cairo Region (GCR):**

<div style="text-align: center; margin: 20px 0;">
  <img src="/data/cairo.roadway.safety.dataset/cairo-dataset-map.png" style="max-width: 100%;" alt="Data collection design in the Greater Cairo Region (GCR)" />
</div>

**Distances covered and number of snapshots for each road functional classification:**

<div style="text-align: center; margin: 20px 0;">
  <img src="/data/cairo.roadway.safety.dataset/cairo-dataset-roads-classification.png" style="max-width: 100%;" alt="Distances covered and number of snapshots for each road functional classification" />
</div>


### Citation

All publications that report on research that use the dataset should cite our work:

{: .box-warning}
Hesham M. Eraqi et al. Automatic Roadway Features Detection with Oriented Object Detection. Journal of Intelligent Transportation Systems. Applied Sciences (ISSN: 2076-3417), 11(8), 2021. [https://www.mdpi.com/2076-3417/11/8/3531](https://www.mdpi.com/2076-3417/11/8/3531)
