# Kurulum (bir kez, yaklaşık 15 dakika)

1. console.firebase.google.com > **Proje ekle** (Analytics'i kapatabilirsiniz). Ücretli plana geçmeyin, Spark planı kalsın.
2. **Build > Authentication > Başla > Google** sağlayıcısını etkinleştirin.
3. **Build > Firestore Database > Veritabanı oluştur** (üretim modu, konum olarak Avrupa seçin).
4. Firestore > **Kurallar** sekmesine `firestore.rules` içeriğini yapıştırın, e-posta adresinizi yazıp **Yayınla** deyin.
5. **Proje ayarları > Uygulamalarınız > Web (</>)** ile uygulama ekleyin, çıkan değerleri `config.js` içine yazın.
6. **Build > Hosting > Başla** deyin. Bilgisayarınızda program kuramıyorsanız bu adımda Firebase'in web arayüzünden dosyaları sürükleyip yükleme seçeneğini kullanın. Bu seçenek yoksa bana yazın, GitHub Pages ile alternatif kurarım.
7. Yayın adresinden (`PROJE_ID.web.app`) Google ile girin. **Authentication > Ayarlar > Yetkili alanlar** listesinde bu alan adı yoksa ekleyin.
8. Telefonda adresi açıp tarayıcı menüsünden **Ana ekrana ekle** deyin.

## İlk kullanım
Personel sekmesi > **İK listesi yükle** > önizlemeyi onaylayın > **Yerleşke tablosu yükle** (TC, Ad Soyad, Görevi, Bağlı Olduğu Yerleşke) > onaylayın.
Yerleşkeler sekmesinde her yerleşkeye daire, saha sorumlusu telefonu ve raporda geçen sorumluyu ekleyin.
