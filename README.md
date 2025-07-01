# AdminPortal
🎯 Proje Amacı:
Yönetim portalı kapsamı itibariyle bir data setini yönetmek üzerine geliştirilecektir. Bu bir hata yönetimi olabilir vs. 
İçerikte liste, ekle, düzenle, sil işlevlerini kapsayan bir projedir.

⚙️ Teknolojiler:
* Backend: ASP.NET MVC (.NET Framework veya .NET Core)

* Frontend: Razor Pages + Bootstrap

* Veritabanı: SQL Server (Entity Framework ile ORM)

* Diğer: LINQ, ViewModel yapısı, TempData/ViewBag kullanımı, CRUD işlemleri

![ExampleUI](https://github.com/cmlcrn17/AdminPortal/blob/main/adminportal.png)

---

## 🧩 Kapsanacak Özellikler
✅ Giriş Ekranı
* Admin panel girişi (sabit kullanıcı: admin, şifre: admin123)

🗂️ Hata Listesi Sayfası
* Tüm hataların listelendiği ana sayfa
* Filtreleme (açık/tamamlandı)
* Hata detayına gitme bağlantısı

➕ Hata Ekle
* Başlık, açıklama alanı
* Varsayılan durum: "Açık"

📝 Hata Güncelle
* Hata başlığı ve açıklamasını düzenleme

❌ Hata Sil
* Kayıtlı hatanın silinmesi

✅ Tamamlandı Olarak İşaretle
* Durum alanını "Tamamlandı" yapar, CompletedAt alanını günceller

💬 Hataya Çözüm Ekle
* Hata detay sayfasında, çözüm metni girip eklenmesi
* Birden fazla çözüm desteklenebilir

---

🔄 Stajyerin Öğrenmesi Beklenenler
* MVC mimarisi
* CRUD işlemleri
* Veritabanı ilişkileri
* Razor syntax
* Proje yapısı kurma ve katmanlı mimari
* Basit validasyonlar ve hata yönetimi
* Git kullanımı
