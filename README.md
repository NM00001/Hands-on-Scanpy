# Hands-on-Scanpy

**Practice single-cell RNA-seq analysis with Scanpy — step-by-step, notebook by notebook.**

This repository is a hands-on playground to learn [Scanpy](https://scanpy.readthedocs.io/) and build reproducible single-cell analysis pipelines. Each notebook is a focused exercise covering the complete workflow: download datasets, preprocess, find highly variable genes, reduce dimensionality, cluster, identify marker genes, annotate cell types, and train ML/AI models.

## 🎯 Learning Objectives

- Master the Scanpy ecosystem for single-cell RNA-seq analysis
- Understand quality control and preprocessing best practices
- Learn feature selection and dimensionality reduction techniques
- Perform clustering and cell type annotation
- Apply machine learning models to single-cell data
- Build reproducible analysis pipelines

## 📚 Notebooks

Each notebook is self-contained and focuses on a specific analysis step:

| Notebook | Topic | Key Concepts |
|----------|-------|--------------|
| **01** | [Data Loading & QC](notebooks/01_data_loading_and_qc.ipynb) | Loading data, quality metrics, filtering cells/genes |
| **02** | [Preprocessing & Normalization](notebooks/02_preprocessing_normalization.ipynb) | Normalization, log transformation, scaling |
| **03** | [Highly Variable Genes](notebooks/03_highly_variable_genes.ipynb) | Feature selection, variance analysis |
| **04** | [Dimensionality Reduction](notebooks/04_dimensionality_reduction.ipynb) | PCA, t-SNE, UMAP |
| **05** | [Clustering](notebooks/05_clustering.ipynb) | Leiden/Louvain clustering, resolution tuning |
| **06** | [Marker Gene Identification](notebooks/06_marker_genes.ipynb) | Differential expression, statistical testing |
| **07** | [Cell Type Annotation](notebooks/07_cell_type_annotation.ipynb) | Manual & automated annotation, reference mapping |
| **08** | [ML/AI Model Training](notebooks/08_ml_model_training.ipynb) | Classification, prediction, deep learning |

# Data Directory

This directory will contain downloaded single-cell RNA-seq datasets.

Datasets are automatically downloaded when you run the notebooks for the first time.

## Datasets used:
- PBMC 3k from 10X Genomics
- PBMC 68k from 10X Genomics
- Other public datasets as needed

# Results Directory

This directory will contain:
- Generated plots and figures
- Analysis outputs
- Saved models
- Intermediate results

Files are automatically saved here when running the notebooks.

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab
- 8GB+ RAM recommended

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/Hands-on-Scanpy.git](https://github.com/yourusername/Hands-on-Scanpy.git)
   cd Hands-on-Scanpy