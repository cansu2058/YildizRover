# STOP Sign Detection with OpenCV

Bu proje, görüntülerdeki STOP trafik işaretlerini renk tabanlı görüntü işleme yöntemiyle tespit etmek için hazırlanmıştır.

Kod, görüntü içerisindeki kırmızı bölgeleri belirler, bu bölgeler arasından en büyük alanı seçer, STOP tabelasının etrafına dikdörtgen çizer ve tabelanın merkez koordinatını hesaplar.

## Proje Amacı

Bu çalışmanın amacı, OpenCV kullanarak bir görüntüdeki STOP tabelasını basit görüntü işleme teknikleriyle tespit etmektir.

Bu kapsamda:

- Görüntü okunur.
- Kırmızı rengin baskın olduğu pikseller belirlenir.
- Maske görüntüsü oluşturulur.
- Contour analizi ile en büyük kırmızı bölge bulunur.
- STOP tabelasının etrafına dikdörtgen çizilir.
- Tabelanın merkez noktası hesaplanır ve işaretlenir.

## Kullanılan Teknolojiler

- Python
- OpenCV
- NumPy
- Google Colab

## Klasör Yapısı

```text
ödev2/
│
├── README.md
├── code
│
├── stop_sign_data_set/
│   ├── photo-1518749031467-bb37f48aee10.jpg
│   ├── photo-1558626219-fa0c107b5613.jpg
│   ├── photo-1635481585588-2440d43b6747.jpg
│   ├── photo-1727156275339-aad186798856.jpg
│   └── premium_photo-1731192705955-f10a8e7174d2.jpg
│
└── stop_sign_outputs/
    ├── photo-1518749031467-bb37f48aee10_result.jpg
    ├── photo-1558626219-fa0c107b5613_result.jpg
    ├── photo-1635481585588-2440d43b6747_result.jpg
    ├── photo-1727156275339-aad186798856_result.jpg
    └── premium_photo-1731192705955-f10a8e7174d2_result.jpg
