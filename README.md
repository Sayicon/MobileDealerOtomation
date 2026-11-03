<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,100:0f3460&height=180&section=header&text=Mobil%20Bayii&fontSize=60&fontColor=fff&animation=fadeIn&fontAlignY=36&desc=Bayi%20Stok%20Otomasyonu%20%7C%20VTYS%20D%C3%B6nem%20Projesi&descSize=16&descColor=ccc&descAlignY=58" width="100%"/>

<p>
  <a href="https://kotlinlang.org/"><img src="https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white" alt="Kotlin"></a>
  <a href="https://developer.android.com/"><img src="https://img.shields.io/badge/Android-min%20SDK%2028-3DDC84?logo=android&logoColor=white" alt="Android"></a>
  <a href="https://www.sqlite.org/"><img src="https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white" alt="SQLite"></a>
  <img src="https://img.shields.io/badge/Android%20Studio-Hedgehog-3DDC84?logo=androidstudio&logoColor=white" alt="Android Studio">
</p>

<img src="https://skillicons.dev/icons?i=kotlin,androidstudio,sqlite,git,github" height="32" alt="teknoloji yığını" />

<p><em>Kocaeli Üniversitesi · Bilişim Sistemleri Mühendisliği · VTYS Dönem Projesi</em></p>

</div>

---

## 📌 Proje Özeti

Mobil Bayii, Android Studio kullanılarak geliştirilen ve SQLite veritabanı ile desteklenen bir bayi yönetim uygulamasıdır. Proje, bir ürün satış ağı içerisinde bayi, müşteri, ürün ve sipariş süreçlerini dijital ortamda takip edebilmeyi amaçlar. Uygulama içerisinde yöneticiler ürünleri sisteme ekleyebilir, müşteriler sipariş oluşturabilir ve bu siparişler yönetim paneli üzerinden onaylanabilir.

## ⚙️ Geliştirme Ortamı

* **IDE:** Android Studio Hedgehog | Arctic Fox
* **Dil:** Kotlin
* **Veritabanı:** SQLite
* **Min SDK:** 28 (Android 9.0)
* **Emülatör/Test Cihazı:** Android API 28 veya üzeri
* **Versiyon Kontrol:** Git & GitHub

## 🗃️ Veritabanı Yapısı

Proje kapsamında kullanılan başlıca tablolar:

* `admin` - Sistem yöneticileri
* `customers` - Kayıtlı müşteriler
* `products` - Ürün bilgileri
* `orders` - Sipariş kayıtları
* `requests` - Müşteri tarafından oluşturulan sipariş istekleri
* `product_images` - Ürün görselleri
* `stocks` - Bayiye özel stok bilgileri
* `request_items` - Sipariş isteklerinde yer alan ürünler
* `deleted_log` - Silinen kayıtların açıklamalarının ve zamanlarının tutulduğu log tablosu

İlişkiler, yabancı anahtarlar (foreign key) aracılığıyla kurulmuş ve veritabanı 3NF-5NF arasında normalleştirilmiştir. Gereksiz veri tekrarları ve transitif bağımlılıklar ortadan kaldırılmıştır. Index, view ve trigger kullanımı sağlanmıştır.

## 🔧 Kurulum ve Çalıştırma

1. Bu repoyu klonlayın:

   ```bash
   git clone https://github.com/mezoxy-dev/mobil-bayii.git
   ```

2. Android Studio ile projeyi açın:

   * `File > Open > mobil-bayii` dizinini seçin.

3. Emulator veya fiziksel bir cihazda uygulamayı çalıştırın:

   * `Run > Run 'app'` veya Shift+F10

4. SQLite veritabanı uygulama içinde gömülüdür ve ilk çalıştırmada oluşturulur.

## 🗈️ Arayüzden Görüntüler

| Ana Ekran                              | Stok Listesi                             | Talepler Sayfası                       |
| -------------------------------------- | ---------------------------------------- | -------------------------------------- |
| ![giris](screenshots/main_page.png)    | ![urunler](screenshots/stok_list.png)    | ![detay](screenshots/requests_page.png)|

## 📁 Proje Dosyaları

* `app/` – Android uygulama kaynak kodları
* `grupno_rapor.pdf` – IEEE formatlı proje raporu


## 📍 Notlar

* Kodlar açıklama satırları ile belgelenmiştir.
* Trigger, view ve index içeren örnek SQL betikleri `sql/` klasöründe yer almaktadır.
* Proje raporu ve tüm istenen çıktı formatları repo içerisinde paylaşılmıştır.

## 📚 Kaynaklar

* [SQLite Documentation](https://www.sqlite.org/docs.html)
* [Android Developer Guide](https://developer.android.com/)
* [Kotlin Language Reference](https://kotlinlang.org/docs/home.html)

## 🧑‍🏫 Proje Ekibi

| İsim                                                        | Görev                    |
|-------------------------------------------------------------|--------------------------|
| [Mustafa Kerem Çekici](https://github.com/Sayicon)          | Uygulama Geliştirici     |
| [Mustafa Mehmet Aslandağ](https://github.com/mezoxy-dev)    | Uygulama Geliştirici     |
| [Efe Süzel](https://github.com/efesu)                       | Veritabanı Tasarımcısı   |


---

© 2025 – Kocaeli Üniversitesi Bilişim Sistemleri Mühendisliği – VTYS Dönem Projesi

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,100:16213e&height=100&section=footer" width="100%"/>

</div>
