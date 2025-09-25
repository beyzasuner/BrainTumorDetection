# 🧠 Brain Tumor Detection with CNN  

## 📌 Giriş  
Bu proje, **MRI görüntülerinden beyin tümörü tespiti** üzerine yapılmıştır.  
Kullanılan veri seti: [Brain Tumor MRI Detection (Kaggle)](https://www.kaggle.com/datasets/arwabasal/brain-tumor-mri-detection)  

Amaç, verilen MRI görüntülerini **“Tumor”** ve **“No Tumor”** olarak sınıflandırmaktır. Bunun için **Convolutional Neural Network (CNN)** tabanlı bir model tasarlanmıştır.  

---

## ⚙️ Yöntem  
- **Veri Ön İşleme:** Görseller yeniden boyutlandırılmış, normalize edilmiştir.  
- **Model Mimarisi:** CNN katmanları kullanılarak ikili sınıflandırma modeli oluşturulmuştur.  
- **Eğitim Süreci:** Model `train/validation` ayrımı ile eğitilmiş, `accuracy` ve `loss` grafikleri takip edilmiştir.  
- **Model Değerlendirmesi:** Confusion Matrix, Classification Report, Accuracy ve Loss metrikleri ile performans ölçülmüştür.  
- **Grad-CAM Görselleştirme:** Modelin hangi bölgelerden etkilendiği incelenmiştir.  

---

## 📊 Metrikler  
- **Eğitim Doğruluğu:** %XX  
- **Doğrulama Doğruluğu:** %YY  
- **Confusion Matrix ve Classification Report** ile detaylı sonuçlar paylaşılmıştır.  

Model, tümör ve tümör olmayan görüntüleri ayırt etmede yüksek başarı sağlamıştır.  

---

## 🚀 Ekler  
- Projede Grad-CAM ile **modelin odaklandığı bölgeler görselleştirilmiştir**.  
- İlerleyen süreçlerde Streamlit ile basit bir **web arayüzü** eklenmesi planlanmaktadır.  

---

## 🔮 Sonuç ve Gelecek Çalışmalar  
Bu proje, temel bir CNN modeliyle beyin tümörü tespitinin mümkün olduğunu göstermektedir.  
Gelecekte:  
- Daha büyük ve çeşitli veri setleri ile test edilebilir.  
- Transfer learning (ör. ResNet, VGG) modelleri denenebilir.  
- Gerçek zamanlı MRI analizi için web veya mobil uygulama geliştirilebilir.  

---

## 🔗 Linkler  
- 📓 Kaggle Notebook: [Brain Tumor Detection Notebook](KENDİ_NOTEBOOK_LINKİNİ_EKLE)  
- 📂 Dataset: [Brain Tumor MRI Detection](https://www.kaggle.com/datasets/arwabasal/brain-tumor-mri-detection)  
