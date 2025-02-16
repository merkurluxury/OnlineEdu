# OnlineEdu

Bu proje, ASP.NET Core 8.0 tabanlı bir API + API Consume mimarisine sahip olup, üç farklı yönetim paneli (Admin, Teacher, Student) içeren bir Eğitim Yönetim Sistemidir.

## 🚀 Kullanılan Teknolojiler

- **ASP.NET Core 8.0**
- **Web API**
- **.NET Core MVC + API Consume**
- **N-Tier Architecture**
- **Entity Framework Core**
- **Code First, Migrations**
- **Lazy Loading Proxies**
- **Repository Design Pattern**
- **JWT Token-Based, Role-Based Authentication**
- **Identity**
- **AutoMapper (Entity - DTO Mappings)**
- **FluentValidation**
- **Named HttpClient**

## 📌 Proje Hakkında

Bu proje, bir eğitim yönetim sistemi olarak geliştirilmiş olup Admin, Öğretmen ve Öğrenci rolleri için ayrı yönetim panelleri içermektedir. API tarafında verilerin yönetimi sağlanırken, Consume (MVC) tarafında kullanıcı dostu bir arayüz tasarlanmıştır.

### 📌 API Katmanı

- Tüm verilerin yönetildiği ve iş kurallarının işlendiği katmandır.
- JWT Token ile kimlik doğrulama ve rol tabanlı yetkilendirme bulunmaktadır.
- Repository Design Pattern kullanılarak veri erişimi soyutlanmıştır.
- FluentValidation ile verilerin doğrulaması yapılmaktadır.
- AutoMapper ile DTO'lar ve Entity'ler arasında dönüşümler sağlanmıştır.

### 📌 API Consume (MVC) Katmanı

- Named HttpClient kullanılarak API ile etkileşim sağlanmıştır.
- MVC (Model-View-Controller) mimarisi kullanılmıştır.
- Lazy Loading Proxies ile ilişkili verilerin yönetimi optimize edilmiştir.
- JWT Token kullanılarak API'ye yetkili erişim sağlanmaktadır.

