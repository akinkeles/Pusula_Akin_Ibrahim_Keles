# Pusula_Akin_Ibrahim_Keles
Akın İbrahim Keleş - akin.ibrahim190@gmail.com

## 📌 Proje Hakkında
Bu repository, Pusula Data Science Staj Case Study 2025 için hazırladığım kodları içermektedir.  
Amaç, hedef değişken (`TedaviSuresiNumeric`) etrafında veri setini temiz, tutarlı ve analiz edilebilir `(modellemeye hazır)` hâle getirmektir.  
Model eğitimi beklenmediğinden sadece `'Modele Hazır'` hale getirildi.,

Ana Görevler
- İlgili veri setinde EDA
- Data preprocessing ve missing value handling
- Model-ready data hazırlığı

### 🔍 Key Findings
- **2,235 kayıt** başarıyla işlendi ve model-ready hale getirildi.
- **Tedavi patterns:** %57 hasta 15-20 seans aralığında tedavi alıyor.
- **Data quality:** %27 missing value problemi çözüldü.
- **Feature engineering:** Text verilerden 8 adet numerik özellik türetildi.
- **Final output:** Model için hazır dataset.


## 📂 Dosya Yapısı
- `Pusula_CaseStudy_EDA_Preprocessing.ipynb` - Çalıştırılacak kod dosyası.
- `missing_uygulama.xlsx` - Çalışmada kullanılar veri seti.
- `Summary.pdf` - Çalışmanın özetini içeren doküman.  
- `README.md` - Proje açıklaması ve kullanım talimatları.
- `requirements.txt` - Kodu çalıştırmak için gerekli olan kütüphaneler.

  
## ⚙️ Kullanım
1. Repository’yi klonlayın:
   ```bash
   git clone https://github.com/akinkeles/Pusula_Akin_Ibrahim_Keles.git
   cd Pusula_Akin_Ibrahim_Keles
2. Gerekli Python kütüphanelerini yükleyin:
   ```bash
   pip install -r requirements.txt
4. Jupyter Notebook’u açın:
   ```bash
   jupyter notebook Pusula_CaseStudy_EDA_Preprocessing.ipynb

## 📈 Veri Seti Bilgileri
- **Kayıt Sayısı:** 2,235 kayıt gözlemlendi
- **Özellik Sayısı:** 13 sütun
- **Target:** TedaviSuresi (Seans)

## 🎯 Gerçekleştirilen Analizler
### 1. Exploratory Data Analysis (EDA)
  - Veri yapısı ve kalite analizi
  - Missing value tespiti
  - Target değişkenin veri üzerindeki dağılımı
  - Korelasyona bakıldı
  - Görselleştirmeler (heatmaps, histogram.. gib)

### 2. Data Pre-Processing
  - Missing value imputasyonu
  - Kategorik bir değişken için (Yas) encoding
  - Verilerin normalizasyonu. (Dummy data temizliği)
  - Feature engineering. (Eklenen yeni özellikler var.)
  - Model-ready data preparation. (Eski kategorik dataların temizlenmesi)
 
