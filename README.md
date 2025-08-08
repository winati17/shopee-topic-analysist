# Shopee Topic Analysis

**Description**  
This project performs **topic analysis** on Shopee data using clustering techniques. The main workflow is explored in a Jupyter Notebook.

---

## Project Structure
- `agglomerativeclustering.ipynb`  
  → Main notebook containing data preprocessing, clustering, and analysis.

- `fix-data.csv`  
  → Cleaned and prepared dataset for analysis.

---

## Main Features
The notebook includes:
1. **Data loading** – reading in `fix-data.csv`.
2. **Data preprocessing** – cleaning text, feature extraction (e.g., TF-IDF or similar).
3. **Clustering** – using Agglomerative Clustering to identify topics or groups.
4. **Evaluation & Visualization** – interpreting clustering results via visualizations or cluster labels.

---

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/winati17/shopee-topic-analysist.git
   cd shopee-topic-analysist
   ```
2. (Optional, but recommended) Create a virtual environment:
   ```bash
    python -m venv venv
    source venv/bin/activate  # Linux/Mac
    venv\Scripts\activate     # Windows
   ```
3. Open `agglomerativeclustering.ipynb` in Jupyter Notebook. Follow the cell order:
- Load and explore the dataset.
- Apply text preprocessing and feature engineering.
- Run Agglomerative Clustering and analyze the results.
- Experiment with parameters to refine topic grouping.