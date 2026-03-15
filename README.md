# Zhu et al.  *"Defective human somitogenesis in the absence of HOX genes"* scRNA-Seq analysis
#### Code used for the 10x scRNA-Seq analysis in the manuscript *"Defective human somitogenesis in the absence of HOX genes"* by Zhu et al. 

# All fastq and count matrices have been deposited in GEO under the accession number GSE288370

This repository contains the following jupyter notebooks organized by theme: 
##### *Analysis of the WT sample*: 
- 20240924_HOXWT-individualanalysis-Upload 
##### *Analysis of the HOXKO sample*: 
- 20241108_HOXKO-individualanalysis-Upload 
##### *Merging of all the samples followed by regression and scaling :* 
- 20241109_HOX_singlecell_project-regscalling-Upload 
##### *Merging of all the samples followed by regression and scaling and Harmony Integration :* 
- 20241013_HOX_singlecell_project-Upload 
- 20241017_HOX_singlecell_project-Downstream_Upload 
- 20241017_HOX_singlecell_project-Subsampling-Upload
##### *Additional plots requested during the revision process:* 
- 20251220_HOX_singlecell_revision-Upload 
- 20251220_HOX_singlecell_revision-part2_Upload 
##### *Miscellaneous code:* 
- 20250108_HOXproject_UMAP_coloring-Upload

## Software / key packages
Analyses were run in Python 3.9.18 (packaged by conda-forge) using the following key packages:

- scanpy 1.10.0
- anndata 0.10.7
- numpy 1.23.0
- pandas 2.2.2
- scipy 1.13.0
- matplotlib 3.8.0
- jupyterlab 4.1.1
- notebook 7.1.0

The list of dependencies can be found in each notebook uploaded. 

AnnData .h5ad files to reproduce the figures are available in Zenodo. 
