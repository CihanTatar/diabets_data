Diabetes Prediction / Diyabet Tahmini

Bu proje, bir kişinin diyabet hastası olup olmadığını makine öğrenmesi yöntemleriyle tahmin etmeyi amaçlıyor. Veri analizi, görselleştirme ve farklı modellerin karşılaştırılması yer alıyor.

Veri setinde glukoz seviyesi, kan basıncı, BMI, yaş, insülin, cilt kalınlığı gibi değişkenler bulunuyor. Hedef sütunu “Outcome” olup 1 diyabet, 0 diyabet değil anlamına geliyor.

Projede üç model denendi:
• Random Forest Classifier  
• Gaussian Naive Bayes  
• Support Vector Machine (SVM)

Üç model arasında en yüksek doğruluk oranı SVM modelinde elde edildi. Henüz hiçbir model için hiperparametre optimizasyonu yapılmadı.

Kullanılan kütüphaneler: pandas, numpy, matplotlib, seaborn, scikit-learn

Model sonuçları:  
Random Forest: 0.7395  
Gaussian NB: 0.7447  
SVM: 0.7552 (en yüksek)

SVM modeli diğer modellere göre biraz daha iyi sonuç verdi. Hyperparameter tuning yapıldığında doğruluk oranı artırılabilir.

Eksik verilerin kontrolü, korelasyon analizi, görselleştirmeler ve modelleme adımları uygulandı. Her model için ayrı ayrı eğitim ve test sonuçları incelendi.

Geliştirilebilecek noktalar:  
• GridSearchCV veya RandomizedSearchCV ile parametre optimizasyonu  
• Cross-validation eklenmesi  
• XGBoost veya Logistic Regression gibi farklı modellerle denenmesi

Yazar: Cihan Tatar  
E-posta: tatarcihan25@hotmail.com


English Version

This project predicts whether a person has diabetes using machine learning. It includes data analysis, visualization, and model comparison.

The dataset includes features like glucose level, blood pressure, BMI, age, insulin, and skin thickness. The target column “Outcome” is 1 for diabetic, 0 for non-diabetic.

Three models were tested:  
• Random Forest Classifier  
• Gaussian Naive Bayes  
• Support Vector Machine (SVM)

SVM achieved the highest accuracy. No hyperparameter tuning has been applied yet.

Libraries used: pandas, numpy, matplotlib, seaborn, scikit-learn

Model results:  
Random Forest: 0.7395  
Gaussian NB: 0.7447  
SVM: 0.7552 (highest)

SVM performed slightly better than the others. Accuracy could improve with parameter optimization.

Data cleaning, correlation analysis, visualization, and model training/testing were done. Each model was evaluated separately.

Possible improvements:  
• Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)  
• Adding cross-validation  
• Trying other models like XGBoost or Logistic Regression

Author: Cihan Tatar  
Email: tatarcihan25@hotmail.com
