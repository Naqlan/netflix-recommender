# 🎬 Netflix Movie & TV Show Recommendation System

[![Python](https://img.shields.io/badge/Python-3.14%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![uv](https://img.shields.io/badge/Environment-uv-purple?logo=python&logoColor=white)](https://github.com/astral-sh/uv)
[![scikit-learn](https://img.shields.io/badge/Machine%20Learning-scikit--learn-orange?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)

An intelligent, hybrid machine learning recommendation engine designed to cluster Netflix titles by their multi-genre properties and perform context-aware textual similarity searches using show descriptions.

---

## 📌 Project Objective
The primary goal of this system is to overcome the limitations of broad category filtering by building a working, Netflix-style content-driven recommender. It successfully matches and ranks relevant shows based on both granular **genre profiles** and detailed **story content**.

---

## 🛠️ Tech Stack & Dependencies
This project utilizes a modern Python workspace managed with the fast **`uv`** package manager. 

* **Core Language:** Python 3.14+
* **Data Engineering:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn` (`KMeans`, `TfidfVectorizer`, `NearestNeighbors`, `MultiLabelBinarizer`)
* **Visualizations:** `seaborn`, `matplotlib`
* **System Utilities:** `difflib` (for fuzzy title matching), `IPython`

To set up your environment and install all dependencies instantly, ensure you have `uv` installed and execute:
```bash
uv pip install numpy pandas seaborn matplotlib scikit-learn ipython