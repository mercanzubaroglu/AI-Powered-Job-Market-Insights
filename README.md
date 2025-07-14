# AI-Powered Job Market Insights: Data Analysis & Salary Prediction

---

## 📀 Proje Amacı / Project Purpose  
Bu projenin amacı, Kaggle'dan alınan **AI-Powered Job Market Insights** veri seti kullanılarak yapay zeka odaklı iş ilanlarının analizini yapmak ve maaş tahmini için makine öğrenmesi modeli geliştirmektir.  
The goal of this project is to analyze AI-focused job listings using the Kaggle **AI-Powered Job Market Insights** dataset and build a machine learning model to predict salaries.

---

## 📚 Veri Seti Hakkında / About the Dataset  

| Sütun / Column       | Açıklama / Description          |
|----------------------|--------------------------------|
| Job_Title            | İş unvanı / Job title           |
| Industry             | Sektör / Industry               |
| Company_Size         | Şirket büyüklüğü / Company size |
| Location             | Konum / Location                |
| AI_Adoption_Level    | AI benimseme seviyesi / Adoption level |
| Automation_Risk      | Otomasyon riski / Automation risk |
| Required_Skills      | Gereken beceriler / Required skills |
| Salary_USD           | Maaş / Salary in USD            |
| Remote_Friendly      | Uzaktan uygunluk / Remote-friendly |
| Job_Growth_Projection| Büyüme tahmini / Growth projection |

- **Satır / Rows:** 500  
- **Sütun / Columns:** 10  
- **Kaynak / Source:** [Kaggle](https://www.kaggle.com/datasets/...)

---

## 📊 Veri Analizi / Data Analysis  

### 🔢 Maaş Dağılımı / Salary Distribution  
Ortalama maaş çoğunlukla **80.000 - 120.000 USD** arasında yoğunlaşmaktadır.  
Most salaries fall between **80,000 - 120,000 USD**.

### 🏢 Şirket Büyüklüğüne Göre Maaş / Salary by Company Size  
Büyük şirketler ortalama olarak daha yüksek maaşlar vermektedir.  
Large companies offer higher salaries on average.

### 🌎 Lokasyona Göre İlanlar / Jobs by Location  
İlan sayısının en yüksek olduğu şehirler: **San Francisco, Singapore, Sydney**.  
Top cities by job listings: **San Francisco, Singapore, Sydney**.

### 🚀 AI Benimseme Seviyesi ve Maaş / AI Adoption Level vs Salary  
Yüksek AI benimseme seviyesine sahip firmalar daha yüksek maaşlar ödüyor.  
Companies with high AI adoption pay higher salaries.

### ⚠️ Otomasyon Riski / Automation Risk  
- High: %33.8  
- Medium: %34.6  
- Low: %31.6  
Yüksek otomasyon riski olan işler yaygındır.  
High automation risk jobs are common.

### 🏠 Uzaktan Çalışma Durumu / Remote Work  
Uzaktan çalışmaya uygun ilanlar %50.2 oranındadır.  
About 50.2% of jobs are remote-friendly.

### 📈 Büyüme Tahmini ve Maaş / Growth Projection vs Salary  
Büyüme tahmininde azalma olan işlerde bile yüksek maaşlar gözlemlenebilir.  
Even jobs with projected decline can offer high salaries.

---

## 🧐 Makine Öğrenmesi / Machine Learning  

- **Model:** Random Forest Regressor  
- **Öznitelikler / Features:** Industry, Company Size, Location, AI Adoption Level, Automation Risk, Remote Friendly  
- **Hedef Değişken / Target:** Salary_USD  

### Model Performansı / Model Performance  

| Metric       | Değer / Value   | Yorum / Comment                |
|--------------|-----------------|-------------------------------|
| MAE          | $19,040         | Ortalama hata                  |
| RMSE         | $24,351         | Karekök ortalama hata          |
| R² Score     | -0.15           | Zayıf performans, sabit tahminden kötü |


---

## ⚙️ İlerleyen Adımlar / Next Steps  

- Öznitelik mühendisliği (feature engineering) yapılmalı  
- Model hiperparametre ayarları (hyperparameter tuning) gerçekleştirilmeli  
- Farklı modeller denenebilir (XGBoost, Gradient Boosting vb.)  
- Daha fazla veri ve özellik eklenerek performans artırılabilir  

---

