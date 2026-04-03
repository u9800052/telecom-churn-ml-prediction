# 機器學習：電信業客戶流失率預測與商業洞察<br>Machine Learning: Telecom Customer Churn Prediction and Business Insights

詳細的分析過程與代碼說明可參考[我的 Medium 文章](https://medium.com/@jasper_huang/telecom-churn-dataset-analysis-python-code-included-8dca3ff08982?postPublishedType=repub)

## 🎯 專案核心目標 (Project Core Objective)

本專案利用**機器學習演算法**預測電信客戶的流失行為，並透過數據洞察提供具體的商業決策建議。

---

## 🏗️ 分析與技術架構 (Analysis and Technical Architecture)

* **資料探索與前處理 (EDA & Preprocessing):**
  運用 `Pandas` 、 `NumPy` 與 `SMOTE` 進行缺失值填補、異常值檢測以及特徵分箱，確保數據品質。
* **特徵工程 (Feature Engineering):**
  處理類別變數並標準化連續變數，以提升演算法的收斂速度與預測穩定性。
* **模型建立與評估 (Modeling & Evaluation):**
  訓練以下10種分類模型，並採用**交叉驗證 (Cross-Validation)** 來防止過度擬合。
1. Gaussian Naive Bayes
2. Logistic Regression
3. KNN
4. Decision Tree
5. Decision Tree
6. Random Forest
7. AdaBoost
8. Gradient Boost
9. XGBoost
10. Stacking

---

## 🛠️ 技術棧與使用工具 (Tech Stack & Tools)

* **數據分析 (Data Analysis):** `Pandas`, `NumPy`
* **資料視覺化 (Visualization):** `Seaborn`, `Matplotlib`
* **機器學習框架 (ML Framework):** `Scikit-learn`
* **環境與語言 (Environment):** `Jupyter Notebook` / `Python 3.x`

---

## 📊 模型評估指標 (Model Evaluation Metrics)

為確保預測模型的商業實用性，主要採用以下指標進行綜合評估：
* **準確率 (Accuracy)**
* **召回率 (Recall)**
* **F1-score**

---

## 📂 專案結構 (Project Structure)

```text
.
├── data/               # 包含原始與處理後的數據集
├── notebooks/          # 包含 EDA 與模型訓練的 Jupyter Notebooks
├── src/                # 包含用於特徵工程與模型處理的 Python 腳本
└── requirements.txt    # 專案所需的相依套件清單
