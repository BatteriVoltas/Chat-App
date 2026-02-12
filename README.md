# 💬 Flutter Real-Time Chat App

Flutter ve Firebase kullanılarak geliştirilmiş, modern arayüze sahip gerçek zamanlı bir mesajlaşma uygulamasıdır. Kullanıcılar kayıt olup giriş yapabilir ve anlık olarak birbirleriyle mesajlaşabilirler.

## Özellikler

- **Kullanıcı Girişi & Kayıt:** Firebase Authentication ile güvenli e-posta/şifre girişi.
- **Anlık Mesajlaşma:** Cloud Firestore ile gerçek zamanlı veri akışı.
- **Güvenli Veritabanı:** Sadece giriş yapmış kullanıcılar mesaj okuyabilir/yazabilir.
- **Modern Arayüz:** Mesaj balonları, kullanıcı dostu tasarım ve akıcı animasyonlar.
- **Kimlik Kontrolü:** Gönderilen mesajın kime ait olduğunu (Ben/Başkası) otomatik algılama.

## Kullanılan Teknolojiler

* **Flutter:** UI Framework
* **Dart:** Programlama Dili
* **Firebase Authentication:** Kimlik Doğrulama
* **Cloud Firestore:** NoSQL Veritabanı


## Kurulum ve Çalıştırma

Bu projeyi bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyin:

1.  **Projeyi Klonlayın:**
    ```bash
    git clone 
    ```

2.  **Gerekli Paketleri Yükleyin:**
    Terminalde proje dizinine gidip şu komutu çalıştırın:
    ```bash
    flutter pub get
    ```

3.  **Uygulamayı Başlatın:**
    ```bash
    flutter run
    ```

## Notlar

Bu proje eğitim ve portfolyo amaçlı geliştirilmiştir. `firebase_options.dart` dosyası projeye dahildir, böylece ek bir ayar yapmadan doğrudan test edebilirsiniz.

---