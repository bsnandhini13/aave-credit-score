# 🔐 Aave V2 Wallet Credit Scoring (DeFi ML Project)

This project builds a simple credit scoring system for wallets interacting with the **Aave V2 protocol**, using raw transaction-level data.

We analyze DeFi behaviors like **deposits, borrows, repayments, and liquidations** to estimate a **credit score from 0 to 1000** for each wallet.

---

## 📄 File in Repository

- `main.ipynb` – Jupyter/Colab notebook containing:
  - Data preprocessing
  - Feature extraction
  - Heuristic credit scoring
  - (Optional) score visualization

> 📌 You can open this notebook in Google Colab to run it interactively.

---

## 🧠 What the Notebook Does

- Loads and parses raw Aave V2 transactions
- Extracts user-level features (e.g., deposit count, total borrow amount)
- Applies simple logic to compute a credit score for each wallet

---

## 🔧 How to Use

1. Clone this repo or open `main.ipynb` in Google Colab.
2. Upload your `user-wallet-transactions.json` file when prompted.
3. Run all cells to compute credit scores.

---

## 📌 Requirements

- Google Colab or Jupyter Notebook
- Libraries used:
  - `pandas`
  - `numpy`
  - `tqdm`
  - `matplotlib`, `seaborn` (for optional visualization)

---

## ⚠️ Note

This is a **heuristic model**, not a financial credit system. It is built for educational and prototyping purposes.

---

## 🛠️ Future Enhancements (optional)

- Add visualizations and save plots
- Export results as `credit_scores.csv`
- Train ML models on labeled data for improved scoring

---

## 📄 License

MIT License © 2025
