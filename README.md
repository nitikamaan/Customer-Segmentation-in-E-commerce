# Customer-Segmentation-in-E-commerce

This GitHub repository presents a machine learning project for customer segmentation and classification using real-world e-commerce transaction data. Developed as part of the AI MSE assessment.

## 🔍 Project Summary
The notebook processes an e-commerce dataset to:
- Extract **RFM (Recency, Frequency, Monetary)** features
- Segment customers using **KMeans clustering**
- Classify **high-value customers** using **Random Forest**
- Evaluate the model with accuracy, precision, and recall
- Visualize insights with **heatmaps** and **PCA**

## 📁 Files Included
| File Name                       | Description |
|--------------------------------|-------------|
| `Nitika_202401100400132.ipynb` | Main Colab notebook with code and analysis |
| `report.pdf`                   | Report (problem, methods, outputs) |
| `README.md`                    | This README file |

## 🗃️ Dataset Overview
The dataset includes:
- `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `UnitPrice`, `CustomerID`, `Country`

## ⚙️ How to Use
1. Clone the repo:
2. Open the `.ipynb` file in Google Colab or Jupyter Notebook
3. Upload the dataset file `Customer Segmentation in E-commerce.csv`
4. Run the notebook to generate clusters and evaluate model performance

## 📊 Key Outputs
- ✅ **Confusion Matrix** as a heatmap
- 📈 **PCA Scatter Plot** showing KMeans clusters
- 📌 **Classification Report** with Accuracy, Precision, and Recall
- 🔥 **Heatmap of RFM Scores** across clusters

## 📚 Technologies Used
- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
-------------------------------------------------
