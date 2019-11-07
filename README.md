# Single Cell Differential Gene Expression Analysis

### Obtain the data
(GSE100428)[https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE100426]

There are two processed files:
- GSE100426_SC_TPM.txt.gz
- GSE100426_SC_counts.txt.gz

For differential gene expression analysis, the second count matrix should be used `GSE100426_SC_counts.txt.gz`.

The first one is a further processed data matrix with normalization.
TPM stands for Transcripts Per Million. If you want to know more about RNA-seq data normalization, please watch [this](https://www.youtube.com/watch?v=TTUrtCY2k-w) YouTube video.


### Set up the environment

#### Install miniconda

Instruction can be found [here](https://docs.conda.io/en/latest/miniconda.html)

#### Prepare the working environment

You will need several packages including:

- scanpy
- tensorflow
- diffxpy
- numpy
- scipy
- pandas

Here are the R packages you need
- tidyverse
- data.table
- Seurat


### Process the data
- Please check out the Jupyter notebook `mann_cellreport_2018_sc.ipyhb`
- And the Rmarkdown file `single_cell_analysis.Rmd`

## Some tutorials that might be helpful

[Clustering 3K PBMCs](https://scanpy-tutorials.readthedocs.io/en/latest/pbmc3k.html)
[CZ Biohub tutorial](https://github.com/theislab/scanpy-demo-czbiohub/blob/master/10X_PBMC.ipynb)
