# GitHub Profile Card
GitHub User Finder – Dinamik GitHub Profil ve Repo Görüntüleyici

Bu proje, GitHub kullanıcılarının profil bilgilerini ve repolarını gerçek zamanlı olarak API üzerinden çekerek gösteren modern ve etkileşimli bir web uygulamasıdır. Kullanıcı deneyimi ön planda tutularak, hızlı arama, temiz tasarım ve hata yönetimi ile işlevsellik sağlanmıştır.

🚀 Proje Özellikleri

Gerçek Zamanlı Veri Çekme: GitHub REST API v3 kullanılarak kullanıcı bilgileri ve repolar çekilir.

Kullanıcı Profili Bilgileri: Profil fotoğrafı, isim, kullanıcı adı, biyografi, takipçi (followers), takip edilen (following) sayısı ve toplam repo sayısı dinamik olarak görüntülenir.

Repo Listeleme: Kullanıcının en popüler veya ilk 3 reposu bağlantılarıyla birlikte listelenir.

Hata Yönetimi: API’dan dönen 404 veya diğer hata durumları için kullanıcıya anlamlı hata mesajları gösterilir.

Responsive Tasarım: Her cihazda ve ekran boyutunda uyumlu, modern ve sade kullanıcı arayüzü.

Vanilla JavaScript: Saf JS ile API entegrasyonu, DOM manipülasyonu ve olay yönetimi.

Axios Kullanımı: HTTP isteklerini basitleştiren popüler kütüphane ile asenkron veri çekme.

Font Awesome İkonları: Profil bilgileri ve repo linklerini desteklemek için görsel ikonlar.

📚 Teknoloji ve Araçlar

HTML5 & CSS3: Semantik yapı ve stil

JavaScript (ES6+): Async/Await, Template Literals, Arrow Functions gibi modern özellikler

Axios: API istekleri için

Font Awesome: Kullanıcı arayüzünü zenginleştirmek için ikonlar

Google Fonts: Özel font ile estetik yazı tipi

📌 Nasıl Çalışır?

Kullanıcı arama: Arama formuna bir GitHub kullanıcı adı girilir ve form gönderilir.

API çağrısı: getUser fonksiyonu, Axios ile GitHub API’dan kullanıcının bilgilerini çeker.

Profil kartı oluşturma: createUserCard fonksiyonu, çekilen verilerle profil kartını dinamik olarak oluşturur ve sayfaya yerleştirir.

Repo bilgileri: getRepos fonksiyonu aynı kullanıcı için repo verilerini çeker ve addReposToCard fonksiyonu ile ilk 3 repo linkini profile ekler.

Hata kontrolü: Kullanıcı bulunmazsa veya API hatası olursa, createErrorCard fonksiyonu anlamlı bir uyarı mesajı gösterir.

🛠 Geliştirme Sürecinde Öğrenilenler

API ile asenkron veri yönetimi

Axios kullanımı ve hata yakalama

DOM manipülasyonu ile dinamik içerik oluşturma

Modern JavaScript özellikleri (Destructuring, Async/Await)

Kullanıcı deneyimi odaklı hata ve durum yönetimi

Responsive ve erişilebilir web tasarımı
