# futbol

Bu repo Android APK üretmek için WebView tabanlı bir mobil uygulama içerir.

## Uygulama (MVP)

Güncel sürüm, **FMS (Functional Movement Screen) değerlendirme** odaklıdır:

- 7 temel FMS hareketi için 0-3 puanlama
- Toplam skor hesaplama (21 üzerinden)
- Basit seviye yorumu ve zayıf hareket önerileri
- LocalStorage ile değerlendirme geçmişi kayıtları
- Android WebView içinde çevrimdışı çalışabilir yapı

## APK oluşturma

1. Android Studio ile `android-app` klasörünü açın.
2. SDK/Build Tools kurulumunu tamamlayın.
3. **Build > Build Bundle(s) / APK(s) > Build APK(s)** seçin.
4. Çıktı: `android-app/app/build/outputs/apk/debug/app-debug.apk`

## Uygulama yapısı

- `android-app/app/src/main/assets/index.html`: FMS arayüzü, puanlama ve local kayıt mantığı.
- `android-app/app/src/main/java/com/futbolokulum/MainActivity.kt`: WebView başlatır ve `index.html` dosyasını açar.
