# CNN ile Beyin Tümörü Sınıflandırma 🧠  

Bu proje, **Evrimsel Sinir Ağları (CNN)** kullanarak beyin tümörü görüntülerini sınıflandırmayı amaçlamaktadır. Kullanılan veri kümesi, **tümör yok, hipofiz tümörü, menenjiom tümörü ve gliom tümörü** olmak üzere dört kategoriye ayrılmış **MR görüntülerinden** oluşmaktadır.  

## 📌 Veri Kümesi  
- **Eğitim Seti:** Modelin eğitilmesi için kullanılan etiketli görüntüler.  
- **Test Seti:** Modelin doğruluğunu değerlendirmek için kullanılan görüntüler.  

### Etiketler:  
- **no_tumor (Tümör Yok)**  
- **pituitary_tumor (Hipofiz Tümörü)**  
- **meningioma_tumor (Menenjiom Tümörü)**  
- **glioma_tumor (Gliom Tümörü)**  

📂 **Veri Kümesi Bağlantısı:** [Beyin Tümörü Sınıflandırma (MRI) Veri Kümesi](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri/code?datasetId=672377&sortBy=voteCount)  

## 🔧 Gereksinimler  
Bu proje aşağıdaki kütüphaneleri kullanmaktadır:  
- **TensorFlow/Keras** - Model oluşturma ve eğitme  
- **OpenCV** - Görüntü işleme  
- **Matplotlib/Seaborn** - Görselleştirme  
- **Scikit-learn** - Veri bölme ve değerlendirme metrikleri  

## 🚀 Kullanım  
1. Bağımlılıkları yükleyin:  
   ```bash
   pip install -r requirements.txt
