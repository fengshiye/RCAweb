---
title: "Resp Cell Atlas - Helps"
layout: piclay
excerpt: "Resp Cell Atlas -- Helps"
permalink: /Helps/
---

# Help

<a class="btn btn-default" href="#Data Viewer" >Data Viewer</a>
<a class="btn btn-default" href="#Portrait">Portrait</a>
<a class="btn btn-default" href="#Genes">Genes</a>
<a class="btn btn-default" href="#Exploration">Exploration</a>
<a class="btn btn-default" href="#Dataset">Dataset</a>
<br><br>

Respiratory Cell Atlas is a comprehensive and unified atlas of the respiratory system that is built across research, organ, disease and sequencing platforms. We integrate the majority of single-cell transcriptome datasets published in all regions of the respiratory system from human respiratory samples from diverse sources to provide a uniform framework of cell types and artificially curated metadata annotation for healthy, disease, and developing respiratory cell studies.

<h1>Data Viewer</h1>
<p><b>*The Data Viewer may take dozens of seconds to load due to the substantial volume of data present in the Respiratory Cell Atlas.*</p>
<p>The function of the Data Viewer page is to display a UMAP of sample characteristics and gene expression in the Respiratory Cell Atlas. In the "EXPLORE" tab, you can view a specific UMAP by selecting any meta information of interest in the "Cell Metadata" tab. In addition, you can view the expression of specific Genes through the "Genes/Features" tab. The "Sets" tab allows you to view differential genes for specific cell types. On the right is the module that displays the specific category of UMAP in the selected meta information.</p>
<img src = "{{ site.url }}{{ site.baseurl }}/images/helpPage/RCA_dataviewer.png" style='height: 800px; width: auto; margin: 0;'>
<!-- <p>On the right is a module that displays a specific category of UMAP in the selected meta information.</p> -->
<!-- <img src = "{{ site.url }}{{ site.baseurl }}/images/helpPage/help_figure_Dataviewer_left.png" style='height: 800px; width: auto; margin: 0;'> -->
<!-- <p>(1) By scrolling down the selection from "Colour By", you can view coloured cells from a certain attribute for the cells. Several other dimiensions to view the UMAP are described as below:
A list of selectable attributes to display the UMAPs are shown in the left column.</p> -->
<table class="table table-hover table-bordered">
  <thead>
    <tr>
      <th>Name</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>sample_ID</td>
      <td>Sample ID of the cells or nuclei.</td>
    </tr>
    <tr>
      <td>donor_ID</td>
      <td>Author specified donor IDs, which are indicated in the original publications.</td>
    </tr>
    <tr>
      <td>donor_gender</td>
      <td>F = Female; M = Male; Unclassified = Unknown.</td>
    </tr>
    <tr>
      <td>donor_age</td>
      <td>For postnatal individuals, 6 months old is denoted by 6mo; 21 years old is denoted by "21yr".
For prenatal individuals, 9w stands for 9 gestational weeks (GW).
For organoids, use d (days in culture)
Eg. 10d.</td>
    </tr>
    <tr>
      <td>donor_status</td>
      <td>Each donor's disease status corresponds to common names appearing in MONDO Diseased Ontology.</td>
    </tr>
    <tr>
      <td>organ</td>
      <td>Anatomical structure level 1 (Please find details in the first table of the Help Page).</td>
    </tr>
    <!-- <tr>
      <td>subregion</td>
      <td>Anatomical structure level 2 (Please find details in the first table of the Help Page).</td>
    </tr> -->
    <tr>
      <td>sample_status</td>
      <td>Each disease status corresponds to common names appearing in MONDO Diseased Ontology.</td>
    </tr>
    <!-- <tr>
      <td>project_code</td>
      <td>Project codes are the data accession codes or strings of abbreviation of the study provided by the authors.
Eg. GSE/SCP/E-MTAB-/PRJNA/EGAS/phs/PRJEB/SDY/SRP.</td>
    </tr>
    <tr>
      <td>scAnnot_Level1</td>
      <td>The putative cell type level 1 prediction generated from scAnnot.</td>
    </tr>
    <tr>
      <td>scAnnot_Level2</td>
      <td>The putative cell type level 2 (more specific) prediction generated from scAnnot.</td>
    </tr> -->
  </tbody>
</table>

<ul>
  <li>The scAnnot cell type names are models that predicted cell names based on the transcriptomic expressions and known respiratory system cell names. The model was built using a well-annotated adult human respiratory system snRNA dataset <a href="https://www.science.org/doi/10.1126/science.add7046">(Siletti et al, 2023)</a> and the fetal human respiratory system scRNA resource <a href="https://www.biorxiv.org/content/10.1101/2022.10.24.513487v1">(Braun et al, 2022)</a>.</li>
  <li>You can read more about scAnnot from <a href="https://github.com/rnacentre/scAnnot">scAnnot's GitHub Page</a>.</li>
</ul>

<!-- <p><b>(2)</b> On the right panel you can view the expression of a certain gene on the UMAP from search.</p>
<img src = "{{ site.url }}{{ site.baseurl }}/images/helpPage/help_figure_Dataviewer_right.png" style='height: 800px; width: auto; margin: 0;'> -->
<p><b>(3)</b> You may download the UMAP, using selection tools to crop an area and zoom-in/out by clicking on the tool bars on the top-right of the panel (Some tools may take several seconds to load).</p>


<p id="Portrait"> </p>
<br><br>
<h1 ref="">Portrait</h1>
<p class="header_box" >Portrait</p>
The interactive viewer shows the adult human respiratory system and includes all the major regions from the data used in Respiratory Cell Atlas.
<img src = "{{ site.url }}{{ site.baseurl }}/images/helpPage/help_portrait1.png" style='height: 800px; width: auto; margin: 0;'>
<table class="table table-hover table-bordered">
  <thead>
    <tr>
      <th>Level1</th>
      <th>Level2</th>
      <!-- <th>Level3</th> -->
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Pharynx</td>
      <td>Nasal pharynx</td>
    </tr>
    <tr>
      <td>Pharynx</td>
      <td>Oropharynx</td>
    </tr>
    <tr>
      <td>Pharynx</td>
      <td>Hypopharynx</td>
      <td></td>
    </tr>
    <tr>
      <td>Airway</td>
      <td>Trachea<br>
          Primary bronchus<br>
          Bronchi</td>
      <td></td>
    </tr>
    <tr>
      <td>Lung</td>
      <td>Bronchioles<br>
          Alveoli</td>
      <td></td>
    </tr>
    <tr>
      <td>Nose</td>
      <td>Nasal cavity<br>
          Nostrils</td>
      <td></td>
    </tr>
    <tr>
      <td>Larynx</td>
      <td></td>
      <td></td>
    </tr>
    <!-- <tr>
      <td>Spinal cord</td>
      <td></td>
      <td></td>
    </tr> -->
  </tbody>
</table>


<p id="Genes"> </p>
<br><br>
<h1 ref="">Gene</h1>
<p class="header_box" >Gene</p>
<p>Users can obtain a list of differentially expressed genes of the cell types from a selected brain region and the list is available for download in csv or pdf formats.<br>
The cell type name is defined by the most scored prediced cell type computed from the 8 machine-learning-based annotation methods:</p>
<ul>
  <li><a href="https://academic.oup.com/bioinformatics/article/36/2/533/5540320?login=false">ACTINN</a></li>
  <li><a href="https://www.rnacentre.org/RCA_Web/10.1093/nar/gkz543">CHETAH</a></li>
  <li><a href="https://www.nature.com/articles/s41587-021-01001-7">scArches</a></li>
  <li><a href="https://doi.org/10.1038/nmeth.4644">ScMap</a></li>
  <li><a href="https://doi.org/10.1186/s13059-019-1862-5">ScPred</a></li>
  <li><a href="https://doi.org/10.1016/j.cels.2019.06.004">SingleCellNet</a></li>
  <li><a href="https://doi.org/10.1038/s41590-018-0276-y">SingleR</a></li>
  <li>scAnnot - a hierarchical classification model trained based on scANVI.</li>
</ul>
<p>For example, choosing an atlas to start with (Adult is shown here), and compute for candidate markers within a specific region by selecting the tab <b>By Region</b> or find candidate markers of a cell type by selecting the tab <b>By CellType</b>. After selection and click on the tab <b>Markers</b>, a volcano plot will be shown and list of candidate markers are listed in the table available for downlod in pdf or csv format.</p>

<div style="display: flex; justify-content: center;">
<img src = "{{ site.url }}{{ site.baseurl }}/images/helpPage/RCA_genes_marker1.png" style='height: 600px; width: auto; margin: 0;'>
</div>
<div style="display: flex; justify-content: center;">
<img src = "{{ site.url }}{{ site.baseurl }}/images/helpPage/help_figure_marker2.png" style='height: 600px; width: auto; margin: 0;'>
</div>
<div style="display: flex; justify-content: center;">
<img src = "{{ site.url }}{{ site.baseurl }}/images/helpPage/help_figure_marker3.png" style='height: 600px; width: auto; margin: 0;'>
</div>

<h1>Region DEG</h1>
<p>Region DEG (Differential expression Genes) compares different cell types from the same region. A violin plot of the top 3 DEGs for each different cell types of the region will be shown after selection of the input.</p>
<div style="display: flex; justify-content: center;">
<img src = "{{ site.url }}{{ site.baseurl }}/images/helpPage/help_figure_DEG.png" style='height: 400px; width: 100%; margin: 0;'>
</div>
<div style="display: flex; justify-content: center;">
<img src = "{{ site.url }}{{ site.baseurl }}/images/helpPage/help_figure_DEG2.png" style='height: 600px; width: auto; margin: 0;'>
</div>

<h1>CellType DEG</h1>
<p>CellType DEG compares the same cell type from different regions. Likewise, a violin plot of the top 3 DEGs for this cell type across different region will be shown after selection of the input.</p>

<!-- <p id="Exploration"> </p>
<br><br> -->
<!-- <h1>Exploration</h1>
<p>This page present the statistics of Brain Cell Atlas with various of plots.<br>
You can locate the relevant atlas and brain region to get summary information about the relevant resources in the Brain Cell Atlas. From the "Atlas" tab, you can choose a particular Atlas from Adult Brain, Fetal Brain, Tumour and Organoids. Then, select a brain region from the "Region" tab and click on the "Submit" button to view the statistics information.</p>
<ul>
  <li><b>Cell Proportion</b><br>The pie chart on the leftside shows the proportion of different cell types in the selected atlas and the barplot on the right shows the cell/nucleus counts of each cell types. The cell types are annotated with <a href="https://github.com/rnacentre/scAnnot">scAnnot</a> and using <a href="https://www.science.org/doi/10.1126/science.add7046">(Siletti et al, 2023)</a> and <a href="https://www.biorxiv.org/content/10.1101/2022.10.24.513487v1">(Braun et al, 2022)</a> as a reference.</li>
  <li><b>Features</b><br>The violin plot shows a selected gene's expression across different cell types across the atlas. You may select a gene by scrolling down or type in the gene's name to search.</li>
</ul>
<div style="display: flex; justify-content: center;">
<img src = "{{ site.url }}{{ site.baseurl }}/images/helpPage/help_figure_Exploration.png" style='height: 100%; width: 100%; margin: 0;'>
</div> -->

<p id="Dataset"></p>
<br><br>
<h1>Dataset</h1>
<p>The Dataset page includes all the datasets used in the Brain Cell Atlas, a full list of the studies and authors from this page can be found here. Processed data with re-annotated cell type metadata will be avaiable for download upon publication.</p>
<div style="display: flex; justify-content: center;">
<img src = "{{ site.url }}{{ site.baseurl }}/images/helpPage/help_figure_dataset.png" style='height: 100%; width: 100%; margin: 0;'>
</div>