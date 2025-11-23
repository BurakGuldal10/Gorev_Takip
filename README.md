Görev Yöneticisi

Bu proje, Motivex Intelligence teknik değerlendirme süreci kapsamında geliştirilmiştir. Proje, Client-Server mimarisi kullanılarak Mobil (Flutter) ve Web (HTML/JS) arayüzlerinin ortak bir Python (Flask) Backend ile haberleşmesini sağlar.

Özellikler

- Çapraz Platform: Aynı veri tabanına hem Web hem de Mobil üzerinden erişim.
- RESTful API: Python Flask ile yazılmış, JSON tabanlı veri alışverişi.
- Git Flow: Profesyonel versiyon kontrol disiplini ile geliştirilmiştir.

Teknolojiler

- Backend: Python, Flask, Flask-CORS
- Mobile: Flutter (Dart), HTTP Package
- Web Frontend: HTML5, JavaScript (Fetch API), 
- Veri Kaynağı:Local JSON Dosyası

---

Kurulum ve Çalıştırma

Projeyi çalıştırmak için aşağıdaki adımları sırasıyla uygulayınız.

1. Backend (Sunucu) Kurulumu
Önce sunucuyu ayağa kaldırmalısınız.
```bash

cd backend
pip install flask flask-cors
python server.py


2. Mobil Uygulama (Flutter)
Yeni bir terminal açın ve mobil uygulamayı başlatın.

cd mobile_app
flutter pub get
flutter run

3. Web Arayüzü
web_frontend klasöründeki index.html dosyasını tarayıcınızda açmanız yeterlidir.



## Ekran Görüntüleri

| Mobil Uygulama | Web Arayüzü |
| :---: | :---: |
| ![Mobil Arayüz](screenshots/mobil-arayuz.png) | ![Web Arayüzü](screenshots/web-arayuz.png) |