# STOP Sign Detection with OpenCV

Bu proje, görüntülerdeki STOP trafik işaretlerini renk tabanlı görüntü işleme yöntemi ile tespit etmek için hazırlanmıştır.

Algoritma, görüntüdeki BGR renk kanallarını karşılaştırarak kırmızı rengin baskın olduğu bölgeleri tespit eder. Daha sonra contour analizi ile en büyük kırmızı alan seçilir, bu alanın etrafına dikdörtgen çizilir ve merkez piksel koordinatı hesaplanır.

## Kullanılan Teknolojiler

- Python
- OpenCV
- NumPy
- Google Colab

## Gereksinimler

Projeyi çalıştırmak için aşağıdaki Python kütüphaneleri gereklidir:

```bash
pip install opencv-python numpy
