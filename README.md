# 🧠 Dimensionality Reduction Techniques for Quant & HFT ML

This repository is a structured deep-dive into **Dimensionality Reduction techniques** — starting from core mathematical intuition to high-dimensional financial applications.

📍 **Goal**: 
To master techniques that reduce noise, extract latent structure, and compress alpha signals in high-frequency and statistical trading contexts. This directly feeds into my long-term goal of becoming a **Machine Learning-Powered HFT Engineer** .

---

## 📂 Repository Structure

```
dimensionality-reduction-aion/
├── 0_basics/                            # Linear algebra & statistical foundations
├── 1_core_techniques/                   # PCA, LDA, Kernel PCA, MDS etc.
├── 2_nonlinear_methods/                 # t-SNE, UMAP, Autoencoders, VAEs
├── 3_feature_selection_vs_extraction/   # Comparison & ML pipelines
├── 4_finance_usecases/                  # Alpha signals, vol surfaces, order book compression
├── 5_towards_aion/                      # Feature engineering for Alpha Engines
├── 6_benchmarks_experiments/            # Visualizations, tests, performance metrics
├── 7_interview_ready/                   # Case studies, challenges, top questions
├── assets/                              # Diagrams, datasets, visuals
└── README.md
```

---

## 🔍 What's Covered?

### `0_basics/`
- Linear algebra (vectors, matrices, dot products, eigendecomposition)
- Covariance matrices and SVD
- Built for intuitions that drive PCA and factor models

### `1_core_techniques/`
- **Principal Component Analysis (PCA)**
- **Linear Discriminant Analysis (LDA)**
- **Kernel PCA, Factor Analysis, MDS, ISOMAP**
- Full implementation from scratch + sklearn + visual intuition

### `2_nonlinear_methods/`
- **t-SNE** & **UMAP** for manifold learning
- **Autoencoders & Variational Autoencoders (VAE)** for deep feature compression
- Builds nonlinear feature pipelines for HFT data

### `3_feature_selection_vs_extraction/`
- Filters vs Wrappers vs Embedding methods
- PCA vs Lasso vs Mutual Info vs Random Forest Importance
- Sklearn pipelines for model-friendly reduction

### `4_finance_usecases/`
- Dimensionality reduction applied to:
  - Equity time series embeddings
  - Sector-based PCA clusters
  - Alpha signal compression
  - Options volatility surface factor modeling
  - Order book data snapshots

### `5_towards_aion/`
- Autoencoder feature banks for alpha models
- Joint latent factor generation from multimodal market data
- RL-based conditional compression pipelines
- Prototypes for evolving HFT data feature sets

### `6_benchmarks_experiments/`
- Visualization of compression quality
- Metric-driven evaluations (reconstruction loss, retained variance, generalization)
- Tradeoff studies on data size vs algorithm scalability

### `7_interview_ready/`
- Top 30 dimensionality reduction questions asked in interviews
- Real-world hedge fund reduction case studies
- Mini project prompts to build intuition under constraints

---

## 🚧 How This Helps Me as an HFT ML Engineer

Dimensionality reduction plays a crucial role in:
- **Reducing latency and computation** during inference in real-time systems
- **Extracting latent factors** that drive alpha (pricing anomalies, vol clusters, microstructure)
- **Preventing overfitting** in low-data or noisy high-frequency environments
- Building scalable, interpretable pipelines for **multi-strategy alpha engines**

All techniques here are steps toward architecting intelligent alpha systems and compression-aware ML pipelines for HFT.

---

## 📌 Built With

- Python, NumPy, Pandas, Scikit-learn
- Matplotlib, Seaborn, Plotly
- PyTorch (Autoencoders, VAEs)
- Financial datasets (simulated & real)
- Notebook-first design for experimentation and visualization

---

## 🧭 Next Milestone

Merge this repository’s best feature extraction strategies into my **AION Nexus Engine**, where it will power:
- Latent market representations
- Real-time adaptive alpha generation
- Smart signal compaction for production-ready ML models

---

> 🔒 This repo is part of my private learning infrastructure — optimized for speed, real-world relevance, and alpha deployment readiness.