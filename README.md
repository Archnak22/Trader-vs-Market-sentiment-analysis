"# Trader-vs-Market-sentiment-analysis" 
This project analyzes how Bitcoin market sentiment (Fear/Greed index) relates to trader behaviour and performance on the Hyperliquid exchange. It combines a sentiment dataset with detailed trade history to uncover patterns in PnL, win rate, trade frequency, position size, and long/short bias across different sentiment regimes.

Main files
data/fear_greed_index.csv
data/historical_data.csv
notebooks/main.ipynb
output/ – generated tables and charts (pnl, win rate, num_trades, avg_size, long_ratio, segment plots).

Setup
Prerequisites
Python 3.9+
Git

Clone the repository
bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>

Create and activate a virtual environment (recommended)
bash
# using venv
python -m venv .venv
source .venv/bin/activate   # on Windows: .venv\Scripts\activate

Install dependencies
Make sure requirements.txt contains at least:
text
pandas
numpy
matplotlib
seaborn
jupyter

Then install:
bash
pip install -r requirements.txt

Place data files
Put the CSVs in the data/ folder with these names (or update paths in the notebook):
data/fear_greed_index.csv
data/historical_data.csv

How to Run the Analysis
Run the Jupyter notebook
bash
jupyter notebook

In the browser:
Open notebooks/main.ipynb.
Run all cells from top to bottom (Kernel → Restart & Run All).
Generated tables and charts will be saved in the output/ folder.