# ReciprocalBLUP
**Reciprocal BLUP for multi-omics data:** integrating genome, metabolome, and microbiome in soybean

<div style="display: flex; align-items: center; gap: 10px;">
  <img src="blup_abstract.png" width="600">
</div>

This repository contains all **data** and **analysis scripts** used in the study.  
Both the datasets and R Markdown scripts are openly available for reproducibility.

---

## 📂 Data Availability
Folder: [`data_reciprocal/`](data_reciprocal/)

| File | Description |
|------|--------------|
| `blup_control.rds` | Multi-omics data under control conditions |
| `blup_drought.rds` | Multi-Omics data drought-stress conditions |

---

## 📜 Code Description
Folder: [`script/`](script/)

| Script | Description |
|---------|--------------|
| `a1_model_1_3.Rmd` | Feature selection and model fitting using Model 1 and Model 3 |
| `a2_model_2_4.Rmd` | Feature selection using Model 2 and Model 4 |
| `b1_histgram.Rmd` | Plot histograms for selected feature distributions |
| `b2_cor.Rmd` | Evaluate omics features prediction |
| `b3_features.Rmd` | Summary and visualization of selected features |
| `b4_phenotype_prediction.Rmd` | Phenotype prediction by selected metabolome features |
| `b5_phenotype_result.Rmd` | Visualization and interpretation of phenotype prediction results |
| `b6_pheno_micro.Rmd` | Phenotype prediction by selected microbiome features |
| `b7_pca.Rmd` | Principal component analysis (PCA) for omics datasets |
| `b8_percent.Rmd` | Phenotype prediction with reduced metabolome features |
| `b9_percent_micro.Rmd` | Phenotype prediction with reduced microbiome features  |
| `b10_micro_pie.Rmd` | Generate pie charts summarizing microbial composition |

> Each `.Rmd` file can be executed sequentially using `rmarkdown::render()`.  
> Please ensure all required R packages are installed before running the scripts.

---

## 🔍 Overview
This repository provides the full set of scripts and data used in the **Reciprocal BLUP** study.  
The materials here are shared for **transparency, reproducibility, and reuse**.  
Researchers are encouraged to adapt and extend the code for related analyses.

If you use this repository, please cite the associated paper or this GitHub project.

---
