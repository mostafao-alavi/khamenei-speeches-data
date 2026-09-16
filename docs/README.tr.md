# 🇹🇷 Ayetullah Hamaney'in Konuşmaları Kronolojik Ağaç Arşivi (1979–2026)
### Hesaplamalı Dilbilim, Tarih Araştırmaları ve Yapay Zeka İçin Resmi Tam Metin Külliyatı

---

## 📌 Proje Özeti
Bu depo, Ayetullah Seyyid Ali Hamaney'in 1979'dan 2026'ya (1357–1404 Şemsi) kadar 47 yıl boyunca yaptığı tüm resmi konuşmaların, hutbelerin ve beyanatların kronolojik ve hiyerarşik tam metin arşivini sunmaktadır.

---

## 🛡️ Veri Bütünlüğü ve Doğruluk Standartları
- **Yalnızca Tam Metinler:** Haber özetleri, kısa alıntılar ve kısaltılmış metinler temizlenmiş, sadece orijinal konuşmanın eksiksiz hali korunmuştur.
- **Yorum ve Analizlerin Hariç Tutulması:** Konuşmaların orijinalliğini korumak amacıyla ikincil makaleler ve analizler depoya dahil edilmemiştir.
- **En Kapsamlı Nüshanın Seçimi:** Aynı tarihe ait birden fazla kayıt mevcut olduğunda, kelime sayısı en yüksek ve resmi PDF belgesi bulunan versiyon temel alınmıştır.

---

## 📁 Dizin Yapısı
```text
data/
└── YYYY/
    └── MM/
        └── YYYYAAGG_id<ID>_<Başlık>/
            ├── content.md        # Temiz Markdown formatında tam metin
            ├── metadata.json     # Standart meta veriler (tarih, kaynak link, kelime sayısı)
            ├── original.html     # Denetlenebilirlik için orijinal HTML çıktısı
            └── document.pdf      # Varsa resmi yayın PDF belgesi
```

---

## 📈 İstatistiki Göstergeler
- **Tam Metin Konuşma Sayısı:** 1.066 adet
- **Toplam Kelime Sayısı:** 3.156.132 kelime
- **Toplam Karakter Sayısı:** 16.533.837 karakter
- **Kapsanan Dönem:** 12 Mayıs 1979 – 17 Ocak 2026 (47 yıl)
