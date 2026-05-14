# Running Seurat inside Conda Environment
This repo explains how to create a **conda** environment where [Seurat](https://satijalab.org/seurat/) can be executed.

## How to create the environment
After installing miniconda, you can execute the following:
1. Install Rstudio $\Rightarrow$ this depends on your linux distro   
3. Create a conda environment      
```conda create -n seurat_di_conda```      
4. Activate the environment    
```conda activate seurat_di_conda```         
5. Install seurat      
```conda install -c conda-forge r-seurat```     
6. Install bpcells        
```conda install -c conda-forge bioconda::r-bpcells```
7. Install presto     
```conda install -c conda-forge bioconda::r-presto```
8. Install glmgampoi     
```conda install -c conda-forge bioconda::bioconductor-glmgampoi```
9. Install signac     
```conda install -c conda-forge bioconda::r-signac```     
10. Install seuratdata    
```conda install -c conda-forge pwwang::r-seuratdata```
11. Install azimuth     
```conda install -c conda-forge bioconda::r-azimuth```
12. Install seuratwrappers     
```conda install -c conda-forge pwwang::r-seuratwrappers```
13. Run Rstudio inside this environment.

              
Now you can start learning [Seurat](https://satijalab.org/seurat/articles/get_started_v5_new). Enjoy!
