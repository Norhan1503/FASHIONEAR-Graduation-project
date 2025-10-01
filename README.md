# :womans_hat: FASHIONEAR : AI powered Fashion Website
<p align="center">
  <img src="images/logo.jpg" alt="Logo" width="600"/>
</p>

<p align="center">
  AI Powered Visual Search & Price Prediction Website For Fashion
</p>

This project is a **graduation project** that improves online fashion shopping using **Artificial Intelligence**. It combines **visual search** and **price prediction** for fashion items.

---

## 📌  Features

### 1. Visual Search
- Upload an image of a fashion item.
- The system finds **visually similar products** from multiple e-commerce websites.
- Helps users discover products faster and smarter.

### 2. Price Prediction
- Predicts the **selling price** of a fashion item based only on its image.
- Useful for sellers who are unsure about pricing **unbranded or second-hand items**.
- Detects pricing anomalies (overpriced or underpriced items).
- Supports small business owners and online sellers entering the market.

---

## 💻 Technologies Used
- Python, TensorFlow, Keras
- Pre-trained deep learning models: **InceptionV3** (for classification) & **MobileNetV2** (for price prediction)
- Web scraping: **BeautifulSoup, Selenium**
- Data preprocessing, image augmentation, regression models

---

## 🌐 Dataset
- Collected from multiple fashion e-commerce websites: **Defacto, Mitcha, Amazon**
- Includes images, price, category, gender, and product link
- Over **9,000 products** across multiple categories

  ---

## 🎯 Accuracy
- **Classification Model**  
  - Overall Accuracy: **97%** (on 1794 test samples)  
  - Macro Avg (Unweighted Mean): Precision: **0.96**, Recall: **0.96**, F1-Score: **0.96**  
  - Weighted Avg (Accounts for Support): Precision: **0.97**, Recall: **0.97**, F1-Score: **0.97**  

- **Price Prediction Model**  
  - **MAE**: 196  
  - **MAPE**: 28%


