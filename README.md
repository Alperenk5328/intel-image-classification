# Intel Image Classification Project

Bu proje, Intel Image Classification veri setini kullanarak 6 farklı doğal manzara sınıfını (buildings, forest, glacier, mountain, sea, street) sınıflandıran bir CNN modeli geliştirmektedir.

## Giriş

Bu projede Intel Image Classification veri seti kullanılarak:
- Veri ön işleme ve görselleştirme
- CNN modeli tasarımı ve eğitimi
- Model performans değerlendirmesi
- Hiperparametre optimizasyonu
gerçekleştirilmiştir.

## Metrikler

Model performansı:
- **Test Accuracy**: %81
- **Precision**: 0.81 (macro avg)
- **Recall**: 0.81 (macro avg)
- **F1-Score**: 0.80 (macro avg)

En iyi performans gösteren sınıflar:
- Forest: %93 F1-score
- Sea: %83 F1-score

## Teknik Detaylar

- **Framework**: TensorFlow/Keras
- **Model**: Sequential CNN
- **Veri Artırma**: Rotation, zoom, flip, brightness
- **Optimizasyon**: Adam optimizer
- **Regularization**: Dropout (0.5)

## Sonuç ve Gelecek Çalışmalar

Proje başarıyla tamamlanmış ve %81 doğruluk oranı elde edilmiştir. Gelecek çalışmalarda:
- Transfer learning (ResNet, VGG) denenmesi
- Web arayüzü eklenmesi
- Real-time prediction özelliği
planlanmaktadır.

## Linkler

[Kaggle Notebook Linki - https://www.kaggle.com/code/alperenkara5328/notebook504cd7fbcf ]
