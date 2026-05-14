# Running Seurat inside Conda Environment
This repo explains how to create a **conda** environment where [Seurat](https://satijalab.org/seurat/) can be executed.

## How to create the environment
After installing miniconda, you can execute the following:
1. Create a conda environment
```conda create -n seurat_di_conda```    
2. Install seurat      
```conda install -c conda-forge r-seurat```     
3. Install bpcells        
```conda install -c conda-forge bioconda::r-bpcells```
4. Install presto     
```conda install -c conda-forge bioconda::r-presto```
5. Install glmgampoi     
```conda install -c conda-forge bioconda::bioconductor-glmgampoi```
6. Install signac     
```conda install -c conda-forge bioconda::r-signac```     
7. Install seuratdata    
```conda install -c conda-forge pwwang::r-seuratdata```
8. Install azimuth     
```conda install -c conda-forge bioconda::r-azimuth```
9. Install seuratwrappers     
```conda install -c conda-forge pwwang::r-seuratwrappers```
10. Install rstudio and run rstudio inside this environment.
        
Now you can start learning [Seurat](https://satijalab.org/seurat/articles/get_started_v5_new). Enjoy!
