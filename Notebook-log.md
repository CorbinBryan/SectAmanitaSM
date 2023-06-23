# Installing MycoTools
1. Configure conda channels using the following: 
```
conda config --add channels defaults
conda config --add channels bioconda
conda config --add channels conda-forge
conda config --set channel_priority strict
```
2. Run the following: 
```
conda create -n mycotools mycotools -c xonq -y
conda activate mycotools
mtdb -d
```