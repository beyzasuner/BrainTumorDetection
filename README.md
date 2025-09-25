# 🧠 Brain Tumor MRI Classification with CNN

## 📌 Giriş  
Bu projede [Brain Tumor MRI Detection](https://www.kaggle.com/datasets/arwabasal/brain-tumor-mri-detection) veri seti kullanılmıştır.  
Hedef, verilen MRI görüntülerini **“Tümör Var”** ve **“Tümör Yok”** olarak ayırabilen bir **Convolutional Neural Network (CNN)** modeli geliştirmektir.  

Projenin ana adımları:  
- Veri önişleme ve data augmentation (ör. yatay çevirme, döndürme)  
- PyTorch ile custom CNN modeli geliştirme  
- Eğitim sürecinin takip edilmesi (accuracy & loss grafikleri)  
- Confusion Matrix ve Classification Report ile performans değerlendirmesi  
- Grad-CAM yöntemiyle modelin dikkat ettiği bölgelerin görselleştirilmesi  
- Hiperparametre optimizasyonu  

---

## 📊 Sonuçlar & Metrikler  
Model 15 epoch boyunca eğitilmiştir.  

- **Validation Accuracy:** %78  
- **Classification Report:**  
  - **No Tumor:** Precision=0.63, Recall=0.75, F1=0.69  
  - **Tumor:** Precision=0.87, Recall=0.79, F1=0.83  
- **Genel Accuracy:** 0.78  

### 🔹 Confusion Matrix  
Model, özellikle **“Tumor”** sınıfında daha yüksek başarı göstermiştir.  


### 🔹 Accuracy & Loss Grafikleri  
Eğitim sürecinde küçük dalgalanmalar gözlemlense de ciddi bir overfitting tespit edilmemiştir.  


### 🔹 Grad-CAM Görselleştirmeleri  
Modelin karar verme sırasında odaklandığı bölgeler, MRI görüntülerindeki tümör alanlarıyla büyük ölçüde örtüşmektedir.  


---

## 🔧 Ek Çalışmalar  
Deneme yapılan hiperparametreler:  
- **Learning Rate:** 0.001, 0.0005  
- **Batch Size:** 32, 64  
- **Dropout:** 0.3 – 0.5  

En iyi performans `lr=0.001, batch_size=32, dropout=0.5` parametreleri ile elde edilmiştir.  
Proje hem GPU hem de CPU üzerinde çalıştırılabilmektedir.  

---

## 🚀 Sonuç ve Gelecek Planlar  
- Model, %78 doğruluk ile beyin tümörü tespitinde umut verici sonuçlar üretmiştir.  

Gelecekte yapılabilecek geliştirmeler:  
- Daha güçlü CNN mimarileri veya **transfer learning** (ResNet, EfficientNet, VGG)  
- Daha geniş ve çeşitli MRI veri setlerinin eklenmesi  
- Kullanıcı arayüzü için **Streamlit/Gradio** ile deploy edilmesi  
- Klinik sistemlere entegre edilerek gerçek zamanlı kullanım  

---

## 🔗 Linkler  
- 📓 Kaggle Notebook: https://www.kaggle.com/code/beyzasuner/braintumordetection 
- 📂 Dataset: https://www.kaggle.com/datasets/arwabasal/brain-tumor-mri-detection

---

## 👥 Katkıda Bulunanlar  
Bu proje **Beyza Süner** ve **Senanur Öztürk** tarafından geliştirilmiştir.  

- 🧑‍💻 [Beyza Süner] 
- 🧑‍💻 [Senanur Öztürk] 
