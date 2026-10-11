# ml-course

A structured, step-by-step learning path through the core topics of the [mlcourse.ai](https://mlcourse.ai) curriculum — an open Machine Learning course by OpenDataScience led by Yury Kashnitsky.

## Scope

This repo covers the 10-topic self-paced course from exploratory data analysis with Pandas through gradient boosting. Neural networks and GenAI are out of scope per the original course design. Bonus assignments are included inline with their related topics.

## Structure

```
ml-course/
├── README.md                    # This file
├── pyproject.toml               # Python project config (uv)
├── uv.lock                      # Locked dependency graph
├── .venv/                       # Virtual environment (gitignored)
├── prerequisites/               # Setup and prerequisites
│   ├── steps.md                 # Python, Jupyter, toolchain setup
│   └── materials/
├── topic01-pandas/              # Exploratory Data Analysis with Pandas
│   ├── steps.md
│   └── materials/
├── topic02-visual-analysis/     # Visual Data Analysis in Python
│   ├── steps.md
│   └── materials/
├── topic03-classification/      # Classification, Decision Trees, kNN
│   ├── steps.md
│   └── materials/
├── topic04-models-for-classification/  # Models for Classification
│   ├── steps.md
│   ├── materials/
│   └── bonus-assignment04-alice/  # Alice Kaggle competition
│       └── steps.md
├── topic05-ensemble-tree-boosting/ # Ensemble Models and Tree Boosting
│   ├── steps.md
│   └── materials/
├── topic06-feature-engineering/    # Feature Engineering and Feature Selection
│   ├── steps.md
│   ├── materials/
│   └── bonus-assignment06-feature/  # Feature engineering challenge
│       └── steps.md
├── topic07-pca-clustering/      # Unsupervised Learning: PCA and Clustering
│   ├── steps.md
│   └── materials/
├── topic08-neural-networks/     # Vowpal Wabbit / Online Learning
│   ├── steps.md
│   ├── materials/
│   └── bonus-assignment08-sgd/  # SGD classifier from scratch
│       └── steps.md
├── topic09-time-series/         # Time Series Analysis in Python
│   ├── steps.md
│   └── materials/
├── topic10-gradient-boosting/   # Gradient Boosting
│   ├── steps.md
│   ├── materials/
│   └── bonus-assignment10-boosting/  # Gradient boosting from scratch
│       └── steps.md
```

## Each topic folder contains

- **`steps.md`** — ordered learning steps: articles to read, lectures to watch, assignments to complete
- **`materials/`** — datasets downloaded from the course repo
- **Bonus assignments** (where applicable) — nested subfolder with steps

## Setup

```bash
# Activate the virtual environment
uv sync
uv run jupyter lab

# Or run a script with deps available
uv run python my_script.py

# Or run Python interactively
uv run python
```

1. Work through topics in order (01 → 10)
2. Each `steps.md` lists what to read, watch, and build

## AI Disclosure

This repo was scaffolded using local agentic AI. Any use of generative AI in content creation will be disclosed per topic.

## Source

Based on [mlcourse.ai](https://mlcourse.ai) — Open Machine Learning Course by OpenDataScience. Original course materials remain under their respective licenses.
