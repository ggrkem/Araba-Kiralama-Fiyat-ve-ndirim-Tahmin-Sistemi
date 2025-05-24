🚗 Bulanık Mantık ile Araba Kiralama Fiyat ve İndirim Tahmin Sistemi

Bu proje, Python ve bulanık mantık (fuzzy logic) kullanılarak geliştirilmiş bir karar destek sistemidir. Kullanıcıdan alınan bilgiler doğrultusunda, bir araba kiralama işlemi için tahmini fiyat ve indirim oranı hesaplanır.

🌟 Proje Amacı

Gerçek dünyada kiralama ücretleri birçok faktöre bağlıdır ve bu faktörler arasında keskin sınırlar koymak zordur. Bu sistem, kiralama süreci, araba tipi, sezon, müşteri sadakati ve ek hizmetler gibi değişkenlere göre fiyat ve indirim hesaplamalarını bulanık mantık ile daha esnek ve gerçekçi bir şekilde yapmayı amaçlamaktadır.

🛠️ Kullanılan Teknolojiler

Python 3.x

scikit-fuzzy

Tkinter (GUI için)

Matplotlib (grafiksel gösterimler için)

📅 Girdi Değişkenleri

Değişken

Açıklama

Aralık

Kiralanma Süreci

Kaç günlüğüne araç kiralanacak

1 - 30
![image alt](https://github.com/ggrkem/Araba-Kiralama-Fiyat-ve-ndirim-Tahmin-Sistemi/blob/2e69db487ec8ea7d5f4a31afd1ff45b0eb88d992/screenshots/1.png)
Araba Tipi

1: Küçük, 2: Orta, 3: Büyük

1 - 3

Sezon

1: Düşük, 2: Orta, 3: Yüksek

1 - 3

Müşteri Sadakati

0 (yeni) - 10 (sadık müşteri) !en az 4 girilmelidir.

0 - 10

Ek Hizmetler

Alınan ek hizmet sayısı

0 - 5

📄 Çıktı Değişkenleri

Fiyat: 0 - 100 TL arası tahmini ücret

İndirim: 0 - 50% arası uygulanabilecek indirim

📋 Kurulum

# Gerekli kütüphaneleri yükleyin
pip install -r requirements.txt

# Uygulamayı çalıştırın
python app.py

📊 Örnek Kullanım

# Örnek bir kural:
ctrl.Rule(kiralanma_suresi['kisa'] & araba_tipi['kucuk'] & sezon['dusuk'], (fiyat['dusuk'], indirim['fazla']))

📖 Öğrenilenler

Bulanık mantığın karar verme süreçlerine uygulanması

Tkinter ile GUI geliştirme

Matplotlib ile grafik üretme

Python'da kural tabanlı sistemler oluşturma

📍 Proje Dosya Yapısı

.
├── app.py
├── README.md
├── requirements.txt
└── screenshot.png

🤝 Katkı

Lütfen önce bir issue açın ve neyi geliştirmek istediğinizi belirtin. Ardından fork edin ve pull request gönderin. Katkılarınızı bekliyoruz!

📄 Lisans

Bu proje MIT lisansı ile lisanslanmıştır. Daha fazla bilgi için LICENSE dosyasını inceleyin.

👨‍💻 Geliştirici

Görkem Akyol – ggrkem

