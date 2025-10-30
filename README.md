# 🧩 Kraljic Matrix Analysis using Python

## 📌 Project Overview
This project implements the **Kraljic Portfolio Matrix**, a strategic tool used in supply chain and procurement management to classify products and suppliers based on two key dimensions:
- **Profit Impact** – The financial importance of an item.
- **Supply Risk** – The difficulty in obtaining the item.

By analyzing the dataset and visualizing supplier/product categories, this project helps businesses:
- Optimize procurement strategies.
- Identify critical, leverage, bottleneck, and non-critical items.
- Improve risk management and supplier relationship strategies.

---

## 📂 Dataset Information
**Dataset name:** `realistic_kraljic_dataset.csv`  
This dataset represents various items or suppliers with attributes related to **supply risk**, **profit impact**, and other procurement-related factors.

### 🧾 Sample Columns (Features)
| Column | Description |
|:--------|:-------------|
| `Item_ID` | Unique identifier for each product or supplier |
| `Item_Name` | Name or category of the item |
| `Supply_Risk` | Measure of supplier dependency or delivery uncertainty |
| `Profit_Impact` | Measure of the financial importance of the item |
| `Annual_Spend` | Annual expenditure on this item |
| `Supplier_Reliability` | Rating or score representing supplier performance |
| `Lead_Time` | Average time to receive the item (in days) |
| `Strategic_Importance` | Qualitative indicator for business-critical materials |

> 💡 *The dataset is designed to simulate real-world procurement decisions and supplier evaluations.*

---

## ⚙️ Technologies and Libraries Used
This project is implemented in **Python (Jupyter Notebook)** and uses the following libraries:

```python
import pandas as pd
import numpy as np
from sklearn.neighbors import KNeighborsClassifier
from sklearn.naive_bayes import GaussianNB
from sklearn.linear_model import LogisticRegression
from sklearn.svm import SVC
from sklearn.model_selection import train_test_split
from sklearn.metrics import classification_report


🚀 Project Workflow

Data Loading – Import and explore the dataset.

Data Cleaning – Handle missing or inconsistent values.

Feature Scaling – Normalize supply risk and profit impact values.

Visualization – Create a Kraljic Matrix plot (2D scatter).

Segmentation – Classify items into four quadrants:

  ⚙️ Non-Critical Items (Low Risk, Low Impact)

  💰 Leverage Items (Low Risk, High Impact)

  🚧 Bottleneck Items (High Risk, Low Impact)

  🧠 Strategic Items (High Risk, High Impact)

Result Interpretation – Provide insights and recommendations for each category.

📈 Results & Insights

The Kraljic Matrix visualization clearly distinguishes supplier categories.

Strategic items require partnership-based management and risk mitigation.

Leverage items are candidates for competitive bidding.

Bottleneck items need contingency planning due to high supply risk.

Non-critical items should be optimized for efficiency and cost control.
