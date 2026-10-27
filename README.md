# Food Delivery Service Data Analysis

## Project objective
Analyze food-delivery order data to understand order volume, revenue, customer ratings, delivery time, cancellation rate, and payment preferences.

## Folder structure
- `dataset/food_delivery_orders.csv` — sample dataset (synthetic practice data)
- `analysis.py` — Python analysis and chart-generation script
- `notebook/Food_Delivery_Analysis.ipynb` — notebook version / Colab starter
- `visualizations/` — sample charts generated from the dataset
- `report/Project_Report.md` — short project report

## Tools
Python, Pandas, Matplotlib, Jupyter Notebook / Google Colab, GitHub.

## Run on your computer
1. Install Python 3.
2. Install libraries: `pip install pandas matplotlib`
3. Keep the folder structure unchanged.
4. From the project folder, run: `python analysis.py`

## Run in Google Colab
1. Upload `food_delivery_orders.csv` to Colab.
2. Change the CSV path in the notebook to `/content/food_delivery_orders.csv`.
3. Run all cells.

## Important note
The included dataset is synthetic and made for academic demonstration. Do not present it as real company data. If your teacher provided an official dataset, replace this CSV and rerun the analysis.

## Optional interactive dashboard
From the project root, install dependencies with `pip install -r requirements.txt`, then run:
`streamlit run dashboard/app.py`

The dashboard uses the CSV in `dataset/food_delivery_orders.csv`. The included dataset is synthetic sample data for academic demonstration.
