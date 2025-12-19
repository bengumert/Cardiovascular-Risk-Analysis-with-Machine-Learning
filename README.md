# Cardiovascular Risk Analysis with Machine Learning

Bu proje, kardiyovasküler hastalıkların makine öğrenmesi yöntemleri kullanılarak tahmin edilmesini amaçlamaktadır. Çalışma kapsamında klinik ve yaşam tarzına dayalı veriler üzerinde veri önişleme, görselleştirme, istatistiksel analiz ve farklı sınıflandırma algoritmalarının karşılaştırılması gerçekleştirilmiştir.

## Veri Seti
- **Kaynak:** Kaggle – Cardiovascular Disease Dataset  
- **Hedef Değişken:** `cardio`  
  - 0: Kardiyovasküler hastalık yok  
  - 1: Kardiyovasküler hastalık var  

## Kullanılan Yöntemler
- Veri temizleme ve öznitelik mühendisliği
- Keşifsel veri analizi (EDA) ve görselleştirme
- İstatistiksel analiz ve hipotez testleri
- Sınıflandırma modelleri:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
  - Naive Bayes
  - Gradient Boosting
- Model değerlendirme metrikleri:
  - Accuracy
  - Precision
  - Recall
  - F1-Score

## Sonuçlar
Modeller karşılaştırıldığında, **Gradient Boosting** modeli F1-score ve recall açısından en dengeli performansı göstermiştir. Accuracy metriği açısından ise **SVM** modeli en yüksek sonucu elde etmiştir. Sağlık alanındaki sınıflandırma problemlerinde yanlış negatif sonuçların önemi göz önünde bulundurulduğunda, Gradient Boosting modeli bu veri seti için en uygun model olarak değerlendirilmiştir.

## Proje Yapısı
Cardiovascular-Risk-Analysis-with-Machine-Learning/
├── data/
│ ├── cardio_train.csv
│ └── cardio_cleaned.csv
├── notebooks/
│ └── analysis.ipynb
├── README.md
├── LICENSE
└── .gitignore


## 🛠️ Kullanılan Teknolojiler
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook (VS Code)

## Not
Bu proje, veri bilimi dersi kapsamında **akademik amaçlı** olarak geliştirilmiştir.

