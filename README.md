# Turkey Geolocation Dataset (Türkiye İl-İlçe-Mahalle Koordinat Veri Seti)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Türkiye geneli İl, İlçe ve Mahallelerin tam listesini ve bu bölgelerin **enlem (latitude)** ve **boylam (longitude)** koordinatlarını içeren açık kaynaklı ve geliştirici dostu CSV veri setidir.

Özellikle e-ticaret, lojistik, kargo entegrasyonları, harita (GIS) ve lokasyon bazlı CRM uygulamaları geliştiren yazılımcıların adres seçimi (drop-down) veya uzaklık hesaplama gibi ihtiyaçlarını kolaylaştırmak için derlenmiştir.

## 📂 Dosya İçerikleri

Depo (Repository) içerisinde iki farklı CSV dosyası bulunmaktadır:

### 1. `tr_il_ilce_mahalle_koordinat.csv`
Tüm mahallelerin koordinat (enlem ve boylam) bilgilerini içeren ana veri setidir.

**Sütunlar:**
- `il_id`: İlin kodu
- `il_adi`: İl adı (Örn: ADANA)
- `ilce_id`: İlçenin sistem kodu
- `ilce_adi`: İlçe adı (Örn: ALADAĞ)
- `mahalle_id`: Mahallenin sistem kodu
- `mahalle_adi`: Mahalle adı (Örn: AKÖREN MAH.)
- `enlem`: Koordinat / Enlem (Latitude)
- `boylam`: Koordinat / Boylam (Longitude)

### 2. `tr_mahalle_listesi.csv`
Koordinat verisi olmadan, sadece Türkiye'deki il, ilçe ve mahalle hiyerarşisini (il_id, ilce_id vb.) liste halinde çekmek isteyenler için daha hafif boyutlu alternatif veri setidir.

## 🚀 Kullanım Alanları

- Dinamik İl/İlçe/Mahalle seçimi formları oluşturmak.
- İki mahalle arasındaki kuş uçuşu uzaklığı veya rota planlamasını hesaplamak.
- Harita üzerinde mahalleleri (marker ile) pinlemek/göstermek.
- Veri analizi ve coğrafi bilgi sistemleri (CBS/GIS) projeleri yürütmek.

## ⚠️ Sorumluluk Reddi (Disclaimer)

Bu veri seti çeşitli açık kaynaklı harita ve altyapı servislerinden, geliştiricilerin eğitim ve uygulama geliştirme süreçlerine katkı sağlamak amacıyla bağımsız olarak derlenmiştir. Uygulamalarınızda ve ticari projelerinizde kullanım durumunda verilerin %100 doğruluğu veya resmi kurumlardaki güncel durumu yansıtması konusunda herhangi bir resmi garanti verilmemektedir. Kullanım sorumluluğu tamamen geliştiriciye aittir.

## 🤝 Katkıda Bulunma

Eğer eksik veya hatalı bir koordinat/mahalle tespit ederseniz, veri setini güncelleyip bir `Pull Request` (PR) göndererek katkıda bulunabilirsiniz. Açık kaynak projelere katkınız için şimdiden teşekkürler!

Projeyi faydalı bulduysanız deponun sağ üstünden yıldız (⭐) vererek daha fazla geliştiriciye ulaşmasına destek olabilirsiniz!
