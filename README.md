# Plasma membrane order maps functional diversity in immune cells
Luca A. Andronico<sup>1,2,3*</sup>, Cenk O. Gurdap<sup>1,2</sup>, Abishek Arora<sup>1,2,4</sup>, Franziska Ragaller<sup>1,2</sup>, Patrick A. Sandoz<sup>1,3,5</sup>, Yidan Jiang<sup>1,2,6</sup>, Sarantis Giatrellis<sup>7</sup>, Leonard L. de Boer<sup>1,2</sup>, Valentina Carannante<sup>1,4</sup>, Sofiia Iskrak<sup>1,2</sup>, Jaromir Mikes<sup>2</sup>, Marcus Buggert<sup>8</sup>, Anders Österborg<sup>9,10</sup>, Björn Önfelt<sup>1,4,8</sup>, Andrey Klymchenko<sup>11</sup>, Petter Brodin<sup>2,12,13</sup> & Erdinc Sezgin<sup>1,2*</sup>

<sup>1</sup>Science for Life Laboratory, 171 65 Solna, Sweden.</br>
<sup>2</sup>Department of Women's and Children's Health, Karolinska Institutet, 17165 Solna, Sweden.</br>
<sup>3</sup>Department of Applied Physics, KTH Royal Institute of Technology, 114 28 Stockholm, Sweden.</br>
<sup>4</sup>Astrid Lindgren Children’s Hospital, Karolinska University Hospital, Region Stockholm, Stockholm, Sweden.</br>
<sup>5</sup>Department of Materials Science and Engineering, Uppsala University, 751 03, Uppsala, Sweden.</br>
<sup>6</sup>European Molecular Biology Laboratory (EMBL), 69117, Heidelberg, Germany.</br>
<sup>7</sup>Department of Cell and Molecular Biology, Karolinska Institute; 171 77 Stockholm, Sweden.</br>
<sup>8</sup>Department of Medicine Huddinge, Centre for Infectious Medicine, Karolinska Institutet, 171 77, Stockholm, Sweden.</br>
<sup>9</sup>Department of Hematology, Karolinska University Hospital, Stockholm, Sweden.</br>
<sup>10</sup>Department of Oncology-Pathology, Karolinska Institutet, 171 77, Stockholm, Sweden.</br>
<sup>11</sup>Laboratoire de Bioimagerie et Pathologies, UMR 7021 CNRS, Université de Strasbourg 74 Route du Rhin 67401 Illkirch France.</br>
<sup>12</sup>Medical Research Council Laboratory of Medical Sciences (MRC LMS), Imperial College Hammersmith Campus, London, UK.</br>
<sup>13</sup>Department of Immunology and Inflammation, Imperial College London, W12 0NN, London, UK.</br>
<sup>*</sup>Corresponding authors: [erdinc.sezgin@ki.se](mailto:erdinc.sezgin@ki.se@ki.se), [luca.andronico@ki.se](mailto:luca.andronico@ki.se)

**Published in *Nature Chemical Biology* (2026), DOI:** [10.1016/abc](https://doi.org/10.1016/abc) | **PubMed:** [00000000](https://pubmed.ncbi.nlm.nih.gov/00000000/) | **GEO:** [GSE341300](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE341300)

## Analysis Pipeline

Thank you for showing interest in our manuscript. In this GitHub repository you will find the source code and data sets required to replicate our figures and findings using R.

### Differential Gene Expression Analysis - RNAseq

The [R Markdown file](RNAseq_Analysis.Rmd) along with the relevant [dataframes](Dataframes) required for differential gene expression analysis is included in this repository. Please refer to the methods section of the manuscript for details regarding the steps followed. In brief, differential gene expression analysis of RNA-seq data was performed for human NK cells enriched from healthy donor PBMC samples that were sorted as per low or high plasma membrane order. Here, the linear model used was *design = ~ Batch + GP_Status*. The significance thresholds used were adjusted p value<0.05 (Benjamini-Hochberg adjustment), base mean>20 and absolute log2 fold change>0.3.
