# Hands-on-Scanpy

**Practice single-cell RNA-seq analysis with Scanpy — step-by-step, notebook by notebook.**

This repository is a hands-on playground to learn [Scanpy](https://scanpy.readthedocs.io/) and build reproducible single-cell analysis pipelines. Each notebook is a focused exercise covering the complete workflow: download datasets, preprocess, find highly variable genes, reduce dimensionality, cluster, identify marker genes, annotate cell types, and train ML/AI models.

## 👋 About This Project

Hi! I'm **NM0001**, a pharmacist by training with a deep passion for research and science. My current focus is on **AI/ML applications in life sciences**, and this repository is part of my **#BuildInPublic** journey.

### Why This Repository?

I've always dreamed of becoming a professor one day, and what better way to start than by teaching now? This repository is designed as if I'm my own Professor — breaking down complex concepts, explaining the "why" behind each step, and making single-cell analysis accessible.

**My philosophy**: 
- **Pedagogy first** - *"Ce que l'on conçoit bien s'énonce clairement, et les mots pour le dire arrivent aisément."* — Nicolas Boileau
- **Science meets code** - *"L'intelligence artificielle et la biologie computationnelle ouvrent une nouvelle ère : celle où l'on peut enfin modéliser la complexité du vivant, non plus comme une métaphore, mais comme une réalité calculable."* — Jean-Pierre Changeux
- **Student one day, professor another** - *"La vie est un apprentissage permanent ; plus on croit savoir, moins on sait, tant les choses changent, et avec elles les mentalités."* — Yasmina Khadra

Whether you're a student, researcher, or fellow learner, I hope these notebooks help you master single-cell RNA-seq analysis!

---

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

## Acknowledgments & Inspiration

This repository was inspired by and built upon excellent resources from the single-cell genomics community:

### Primary Sources

- **[Scanpy Official Tutorials](https://scanpy-tutorials.readthedocs.io/)** - The foundational tutorials from the Scanpy team
- **[Single-cell Best Practices](https://www.sc-best-practices.org/)** - Comprehensive guide with theory and best practices
- **[Scanpy Documentation](https://scanpy.readthedocs.io/)** - Official documentation and API reference

### Additional Resources

- **[Theis Lab](https://github.com/theislab)** - Creators of Scanpy and related tools
- **[10X Genomics Datasets](https://www.10xgenomics.com/resources/datasets)** - Public datasets used in tutorials
- The broader single-cell genomics community for tools and methodologies

**Standing on the shoulders of giants** - This work wouldn't be possible without the incredible open-source contributions of the Scanpy team and the single-cell community. 🙏

## 🚀 Getting Started

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/NM00001/Hands-on-Scanpy.git](https://github.com/NM0001/Hands-on-Scanpy.git)
   cd Hands-on-Scanpy
