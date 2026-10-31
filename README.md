# Banka Müşteri Kaybı Tahmini | Bank Customer Churn

[Notebook](notebook.ipynb) · [Kaggle](https://www.kaggle.com/code/enesfurkanmacit/bank-customer-churn-prediction-classification)

## Türkçe

Banka müşteri verileri üzerinde müşteri kaybını sınıflandırmaya yönelik keşifsel analiz ve model karşılaştırması. Pandas ve scikit-learn ile lojistik regresyon, Random Forest ve SVC modelleri; sınıf ağırlıkları ve GridSearchCV kullanılarak değerlendirilmiştir. Ayrılan test kümesinde Random Forest, müşteri kaybı sınıfı için **0,85 F1**, 0,91 precision ve 0,80 recall üretmiştir.

Bu sonuç eğitim amaçlı bir veri kümesi ve tek bir test ayrımına aittir; gerçek banka performansı olarak yorumlanmamalıdır. Ön işleme ve özellik seçiminin çapraz doğrulama içinde yapılması, gelecekteki iyileştirmeler arasındadır.

## English

An exploratory analysis and classification comparison on bank customer churn data. Logistic regression, Random Forest and SVC were evaluated with class weighting and GridSearchCV. On the held-out test set, Random Forest achieved **0.85 F1**, 0.91 precision and 0.80 recall for the churn class. Results reflect one experimental split, not production performance.

## Çalıştırma / Reproduction

Open the notebook in Kaggle or Jupyter with Python, pandas, NumPy, matplotlib, seaborn and scikit-learn. Update the dataset path for your environment. The original Kaggle notebook currently indicates that its dataset is no longer available; the rendered outputs are retained in the notebook.
