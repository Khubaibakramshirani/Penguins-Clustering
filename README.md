# 🐧 Penguin Clustering with K-Means

This project performs **unsupervised clustering** on the [Palmer Penguins dataset](https://allisonhorst.github.io/palmerpenguins/) using **K-Means** and **Principal Component Analysis (PCA)**. The goal is to discover natural groupings of penguin species based on physical characteristics.


## 📁 Project Structure

```

penguins-clustering/
├── penguin\_clustering.ipynb  # Main Jupyter notebook
├── penguins.csv              # Dataset used for clustering
├── README.md                 # Project documentation
└── .gitignore                # Git ignored files (optional)

````

## 📊 Dataset Description

Each penguin is described by:

- `culmen_length_mm` – Length of the penguin's bill
- `culmen_depth_mm` – Depth of the penguin's bill
- `flipper_length_mm` – Flipper length
- `body_mass_g` – Body mass in grams
- `sex` – Male or Female

The species label is **not included** for clustering, simulating a real-world unsupervised learning scenario.

---

## 🧠 What This Project Covers

- Data preprocessing and encoding (`get_dummies` for categorical)
- Feature scaling with `StandardScaler`
- Finding optimal `k` using the **Elbow method**
- Fitting **KMeans** to cluster the data
- Analyzing clusters based on feature averages
- Dimensionality reduction with **PCA**
- Visualizing clusters in 2D space

---

## 📌 Key Insights

- Cluster centers can be interpreted to infer likely species groupings (Adelie, Chinstrap, Gentoo).
- PCA helps visualize high-dimensional cluster structures.

---

## 🚀 Getting Started

### Requirements

Install necessary Python libraries:

```bash
pip install pandas matplotlib seaborn scikit-learn
````

### Run

1. Clone this repo:

   ```bash
   git clone https://github.com/khubaibakramshirani/Penguins-Clustering.git
   cd penguin-clustering
   ```

2. Launch the notebook:

   ```bash
   jupyter notebook Penguins_clustering.ipynb
   ```

---


## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss.

---

## 📄 License

This project is open source under the MIT License.

---

## 🙌 Acknowledgements

* [Palmer Penguins Dataset](https://github.com/allisonhorst/palmerpenguins)
* Inspired by real-world species classification scenarios.
* This project was part of my Machine Learning Scientist Career Track On DataCamp 

```

---

Let me know if you want to:
- Add a sample output image
- Include badges (e.g., Binder, License)
- Turn it into a web app with Streamlit
```
