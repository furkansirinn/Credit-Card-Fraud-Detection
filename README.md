# Credit-Card-Fraud-Detection
A Python machine learning project that detects credit card fraud
# 💳 Credit Card Fraud Detection with Machine Learning

Bu proje, kredi kartı işlemleri üzerinde dolandırıcılığı tespit etmek için çeşitli sınıflandırma algoritmalarını karşılaştırır. Veri seti dengesiz olduğu için SMOTE kullanılmış ve Logistic Regression, Decision Tree, Random Forest ve SVM algoritmaları değerlendirilmiştir.

## 🔍 Kullanılan Yöntemler

- **Veri Temizleme & Hazırlama**
  - Veri analizi, eksik veri kontrolü
  - Hedef değişkenin dengesizliği (Class: 0 & 1)
  - SMOTE ile dengeleme
  
- **Uygulanan Modeller**
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)

- **Değerlendirme Metrikleri**
  - Accuracy, Precision, Recall, F1 Score, ROC AUC
  - Confusion Matrix
  - Decision Tree Görselleştirmesi

## 🧪 Sonuçlar

| Model              | Accuracy | Precision | Recall | F1 Score | ROC AUC |
|-------------------|----------|-----------|--------|----------|----------|
| Logistic Regression | 0.46     | 0.45      | 0.54   | 0.49     | 0.51     |
| Decision Tree      | 0.59     | 0.58      | 0.59   | 0.59     | 0.59     |
| Random Forest      | 0.53     | 0.51      | 0.54   | 0.53     | 0.50     |
| SVM                | 0.50     | 0.48      | 0.38   | 0.42     | 0.45     |

## 📊 Görselleştirme

- Confusion Matrix
- Karar Ağacı Grafiği
- ROC Curve (isteğe bağlı)

## 🔧 Gereksinimler

```bash
pip install pandas scikit-learn imbalanced-learn matplotlib seaborn
