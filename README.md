# 機器學習：電信業客戶流失率預測與商業洞察<br>Machine Learning: Telecom Customer Churn Prediction and Business Insights

**分析過程與說明另外可參考[我的 Medium 文章](https://medium.com/@jasper_huang/telecom-churn-dataset-analysis-python-code-included-8dca3ff08982?postPublishedType=repub)**

## 🎯 專案核心目標 (Project Core Objective)

本專案利用**機器學習演算法**預測電信客戶的流失行為，並透過數據洞察提供具體的商業決策建議。

---

## 🏗️ 專案流程與技術架構 (Analysis and Technical Architecture)

* **資料探索與前處理 (EDA & Preprocessing):**
  使用 `pandas` 、 `numPy` 、 `matplotlib` 與 `seaborn` 初步了解資料特性及分布情形 。
  與 對資料進行**ETL**，增進後續模型準確度。
* **特徵工程 (Feature Engineering):**
  使用`SMOTE` 、 `LabelEncoder` 與 `MinMaxScaler` 做資料擴增及標準化，以提升演算法的收斂速度與後續模型穩定性。

* **模型建立與評估 (Modeling & Evaluation):**
  1. 將資料區分 **訓練集與測試集 (Cross-Validation)** 來防止過度擬合(Overfitting)
  
  2. 使用`GridSearchCV` , `RandomizedSearchCV` 、 `RepeatedKFold` 與 `cross_val_score`尋找模型最佳參數。
  
  3. 採用以下指標進行模型評估：
      * **準確率 (Accuracy)**
      * **召回率 (Recall)**
      * **F1-score**
      * **Roc Curve**
  
  4. 使用以下分群及機器學習等模型進行建模、模型評估、優化及預測。
      
      - K-means
      - Principle Component Analysis, PCA
      - t-SNE
      - Gaussian Naive Bayes
      - Logistic Regression
      - KNN
      - Decision Tree
      - Decision Tree
      - Random Forest
      - AdaBoost
      - Gradient Boost
      - XGBoost
      - Stacking

---

## 🛠️ 技術棧與使用工具 (Tech Stack & Tools)

* **數據分析 (Data Analysis):** `Pandas`, `NumPy`
* **資料視覺化 (Visualization):** `Seaborn`, `Matplotlib`
* **機器學習框架 (ML Framework):** `Scikit-learn`
* **環境與語言 (Environment):** `Jupyter Notebook`