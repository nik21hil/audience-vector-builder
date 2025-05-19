# 🧠 Customer Vector Lab

> Create unified vector embeddings for customer profiling and segmentation

[![Streamlit App](https://img.shields.io/badge/Live_App-Click_to_Launch-00bfff?logo=streamlit)](https://customer-vector-lab-7c2fxjhe296qqwonpkhg6k.streamlit.app/)

---

## ✨ Overview

**Customer Vector Lab** is a no-code tool to:

- Upload raw customer CSV data
- Automatically clean and standardize numeric features
- Generate vector embeddings using PCA
- Cluster customers using KMeans
- Visualize personas using:
  - 📊 PCA scatter plot
  - 📈 UMAP + t-SNE projections
  - 🕸 Radar charts of cluster traits
- Explore customer distribution across clusters

It's perfect for **data scientists**, **marketers**, and **business analysts** to quickly identify segments and personas for personalization, targeting, or storytelling.

---

## 🧑‍💻 How to Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/nik21hil/customer-vector-lab.git
cd customer-vector-lab

# 2. (Optional) Create virtual environment
python -m venv env
source env/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Streamlit app
streamlit run app.py
```

---

## 📂 Folder Structure

```
customer-vector-lab/
├── data/              # Sample customer CSVs
├── notebooks/         # Jupyter demo notebooks
├── src/               # Modular Python code
│   ├── preprocess.py
│   ├── embeddings.py
│   ├── clustering.py
│   ├── visualize.py
├── app.py             # Main Streamlit app
├── requirements.txt
└── README.md
```

---

## 📊 Built With

- [Streamlit](https://streamlit.io/)
- [scikit-learn](https://scikit-learn.org/)
- [UMAP](https://umap-learn.readthedocs.io/en/latest/)
- [matplotlib](https://matplotlib.org/)
- [pandas](https://pandas.pydata.org/)

---

## 💡 Future Improvements

- Export clusters and segments as downloadable CSVs
- Allow users to choose number of clusters dynamically
- Add support for categorical variable encoding
- Filter and zoom into radar chart personas
- Add authentication for saving runs

---

## 🧾 License

MIT License — feel free to fork, remix, and use.

---

## 🙌 Acknowledgements

Built by [@nik21hil](https://github.com/nik21hil)  

