# 🌤️ Proje 6 – Şehirler ve Hava Durumu API’si

## 📘 Proje Açıklaması
Bu proje, **ASP.NET Core Web API** kullanılarak geliştirilmiş basit bir **şehir ve hava durumu yönetim sistemi** örneğidir.  
Uygulama, şehir bilgileri ile bu şehirlere ait hava durumu verilerini tutan bir API sağlar.  
Ayrıca şehirlerin **ID değerine göre sorgulanması** ve **temel istatistiksel bilgilerin** elde edilmesi mümkündür.

---

## ⚙️ Kullanılan Teknolojiler
- ASP.NET Core 8.0  
- C#  
- Entity Framework Core  
- SQL Server  
- RESTful API yapısı  

---

## 🌍 Özellikler
- Tüm şehirleri listeleme  
- **ID’ye göre şehir getirme**  
- Şehirlere ait **hava durumu bilgilerini** görüntüleme  
- **Temel istatistiksel veriler** (örneğin ortalama sıcaklık, şehir sayısı vb.)  
- JSON formatında veri çıktısı  

---

## 🧩 Örnek Endpoint’ler

| HTTP Metodu | Endpoint | Açıklama |
|--------------|-----------|-----------|
| GET | `/api/sehirler` | Tüm şehirleri listeler |
| GET | `/api/sehirler/{id}` | ID’ye göre şehir getirir |
| GET | `/api/havadurumu` | Hava durumu verilerini listeler |
| GET | `/api/istatistik` | Temel istatistik bilgilerini döndürür |

---

## 💡 Amaç
Bu proje, **ASP.NET Core Web API** yapısını kavramak, veri tabanı bağlantısı kurmak ve RESTful servis geliştirme mantığını öğrenmek için hazırlanmıştır.  
Öğrenciler için temel düzeyde **API geliştirme pratiği** sunar.

---
