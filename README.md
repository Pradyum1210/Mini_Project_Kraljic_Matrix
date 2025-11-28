# 🧩 Kraljic Matrix Analysis using Python

## 1️⃣ Project Overview 📌

This project implements the **Kraljic Portfolio Matrix**, a strategic tool used in **supply chain and procurement management** to classify products and suppliers based on two key dimensions:

- **Profit Impact** – The financial importance of an item.  
- **Supply Risk** – The difficulty in obtaining the item.  

By analyzing the dataset and visualizing supplier/product categories, this project helps businesses:  

- Optimize procurement strategies  
- Identify **Critical, Leverage, Bottleneck, and Non-Critical items**  
- Improve risk management and supplier relationship strategies  

---

## 2️⃣ Dataset Information 📂

**Dataset name:** `realistic_kraljic_dataset.csv`  
This dataset represents various items or suppliers with attributes related to **supply risk**, **profit impact**, and other procurement-related factors.

### 🧾 Sample Columns (Features)

| Column | Description |
|--------|-------------|
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

## 3️⃣ Project Workflow 🛠️

| Step | Description |
|------|-------------|
| **Data Loading** | Import the dataset and explore its structure |
| **Data Cleaning** | Handle missing, inconsistent, or incorrect values |
| **Feature Scaling** | Normalize `Supply_Risk` and `Profit_Impact` for plotting |
| **Visualization** | Create a **Kraljic Matrix plot** (2D scatter) |
| **Segmentation** | Classify items into four quadrants:<br>• ⚙️ Non-Critical Items (Low Risk, Low Impact)<br>• 💰 Leverage Items (Low Risk, High Impact)<br>• 🚧 Bottleneck Items (High Risk, Low Impact)<br>• 🧠 Strategic Items (High Risk, High Impact) |
| **Result Interpretation** | Provide insights and recommendations for each category |

---

## 4️⃣ Results & Insights 📈

- The **Kraljic Matrix visualization** clearly distinguishes supplier categories.  
- **Strategic items** require partnership-based management and risk mitigation.  
- **Leverage items** are candidates for competitive bidding.  
- **Bottleneck items** need contingency planning due to high supply risk.  
- **Non-critical items** should be optimized for efficiency and cost control.  

---

## 5️⃣ Tools & Technologies 🛠️

| Tool / Technology | Purpose |
|------------------|---------|
| Python | Programming language for analysis and visualization |
| Pandas | Data loading, cleaning, and manipulation |
| NumPy | Numerical computations |
| Matplotlib | Kraljic Matrix plotting and visualization |
| Seaborn | Enhanced scatter plot styling |
| Jupyter Notebook / Google Colab | Interactive analysis environment |

---


git clone https://github.com/your-username/kraljic-matrix-analysis.git
cd kraljic-matrix-analysis
