#  CNN ile Görüntü Sınıflandırma – Akbank Derin Öğrenme Bootcamp Projesi

##  Projenin Amacı  
Bu proje, **Convolutional Neural Network (CNN)** mimarisi ve **Transfer Learning** yöntemleri kullanılarak çok sınıflı bir görüntü sınıflandırma problemini çözmeyi amaçlamaktadır. Çalışma, **Akbank Derin Öğrenme Bootcamp** kapsamında hazırlanmıştır.  

##  Veri Seti  
- **Veri Seti**: [Intel Image Classification](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)  
- **Sınıflar**: Buildings, Forest, Glacier, Mountain, Sea, Street   
- Eğitim seti: ~25.000 görüntü  
- Test seti: ~14.000 görüntü  
- Veri artırma teknikleri: rotation, flip, zoom, color jitter  

## Kullanılan Yöntemler  
- Veri önişleme ve görselleştirme  
- Data augmentation (`ImageDataGenerator`)  
- CNN modeli (Conv2D, MaxPooling, Dropout, Dense)  
- Aktivasyon fonksiyonları: ReLU, Softmax  
- Değerlendirme: Accuracy & Loss grafikleri, Confusion Matrix, Classification Report  

## Sonuçlar  
- **Validation Accuracy**: ~%88–89  
- **Test Accuracy**: **%83.37**  
- **Test Loss**: 0.47  
- Ortalama **Precision / Recall / F1-score**: ~0.83  
- En iyi sınıf: **Forest** (Recall %98, F1-score %96)  
- Zorlayıcı sınıflar: **Glacier** ve **Mountain**  

## 🔗 Kaggle Notebook  

