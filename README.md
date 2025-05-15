# Greed-Controlled-Portfolio-Experiments

Experiments for **HKUST MSDM5058 Project II (Sections 7–9)**  
— trading AAPL & GOOGL with MACD, dynamic greed, efficient-frontier projection and a 1-day Bayes detector.

---

## 1. Repository layout

| File / folder                | Purpose                                                            |
| ---------------------------- | ------------------------------------------------------------------ |
| `5058_project2_ass7_9.ipynb` | Jupyter notebook containing **all Python code** for Sections 7–9.  |
| `past_prices.csv` / `future_prices.csv`   | Daily close prices of AAPL & GOOGL.<br>Past = 2015-01-02 → 2022-09-26, Future = 2022-09-27 → 2025-05-10 |
| `past_returns.csv` / `future_returns.csv` | Corresponding log-returns (to avoid recomputation in the notebook). |
| `README.md`                  | You are here.                                                      |

All data are public Yahoo Finance downloads; files are provided for deterministic re-runs.

---

## 2. Quick start

```bash
# clone
git clone https://github.com/ToSniperSam/Greed-Controlled-Portfolio-Experiments.git
cd Greed-Controlled-Portfolio-Experiments

# create env (optional)
python -m venv venv && source venv/bin/activate

# install minimal dependencies
pip install numpy pandas matplotlib scipy jupyter
