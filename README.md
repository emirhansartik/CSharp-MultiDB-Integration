# 🗄️ C# Multi-Database Entegrasyonu (MongoDB & PostgreSQL)

Bu proje, C# ile hem geleneksel ilişkisel (SQL) hem de ilişkisel olmayan (NoSQL) veritabanı mimarileri üzerine başarıyla tamamlanmış kapsamlı bir veri erişim uygulamasıdır. Proje kapsamında, modern backend sistemlerinde sıklıkla karşılaşılan "farklı veri tipleri için farklı veritabanları" (Polyglot Persistence) yaklaşımı tam anlamıyla simüle edilerek çalışır duruma getirilmiştir.

## 🚀 Proje Amacı ve Çıktıları

Aynı altyapı üzerinde birbirinden tamamen farklı iki veritabanı teknolojisinin kusursuz entegrasyonu sağlanmıştır. Tamamlanan uygulama içerisinde:

* **MongoDB** kullanılarak esnek döküman (JSON/BSON) tabanlı NoSQL mimarisi kuruldu ve veriler dinamik bir şekilde işlendi.
* **PostgreSQL** kullanılarak katı, kurumsal ve ilişkisel tablo (SQL) mimarisi entegre edildi ve veri bütünlüğü sağlandı.
* Her iki veritabanı üzerinde de arayüz (UI) bağlantılı temel CRUD (Ekle, Sil, Güncelle, Listele) operasyonları hatasız bir şekilde gerçekleştirildi.

## 🛠️ Teknoloji Yığını

* **Programlama Dili:** C# (.NET)
* **Veritabanları:**
  * MongoDB (Community Server & Compass)
  * PostgreSQL (EnterpriseDB & pgAdmin 4)
* **Araç / Sürücüler:** MongoDB.Driver, Npgsql
* **Arayüz:** Windows Forms
