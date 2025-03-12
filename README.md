# DNA Enhancers Under Shear Stress
This project uses publicly available data to assess the effect of shear-stress on DNA transcription, comparing multiply-enhanced and singly-enhanced genes.

## Abstract
RNA transcription regulation is influenced by shear stress from fluid flow, leading to the upregulation or downregulation of certain genes. This study examines RNA transcription and gene expression in human umbilical vein endothelial cells (HUVECs) to characterize how enhancer counts affect shear-regulated transcription. Our analysis demonstrates that in HUVEC cells, genes with multiple enhancers are upregulated more significantly than single-enhancer genes, suggesting that multi-enhancer genes exhibit a stronger transcriptional response to shear stress.

## How to use this project
Using the code provided and the data cited below, results from this project can be reproduced. Code in this repository may be downloaded and modified in accordance with the MIT license.

## Data Availability
Research based on [Shear stress switches the association of endothelial enhancers from ETV/ETS to KLF transcription factor binding sites (Tsarsky et al.)](https://www.nature.com/articles/s41598-022-08645-8#data-availability) who's data are available under GEO Accession number [GSE198221](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE198221). Necessary data includes
- 'GSE198221_HUVEC_RNA-Seq.csv'
- '/GSE198221_Flow_Gained_ChIP_peaks.txt'
In addition, it is necessary to have a .bed file of annotated gene data. This raw data is available from [GENCODE](https://www.gencodegenes.org/human/) and can by generated using the code provided (after which it must be sorted), however, the .bed files are included here for ease of use.


*This project was intially created as a part of a graduate biophysics course with instructor Prof. Matthias Keuhne at Brown University.*
