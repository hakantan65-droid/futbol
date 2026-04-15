# futbol

Bu repo artık Android APK üretmek için temel bir WebView projesi içerir.

## APK oluşturma

1. Android Studio ile `android-app` klasörünü açın.
2. SDK/Build Tools kurulumunu tamamlayın.
3. **Build > Build Bundle(s) / APK(s) > Build APK(s)** seçin.
4. Çıktı: `android-app/app/build/outputs/apk/debug/app-debug.apk`

## Uygulama yapısı

- `android-app/app/src/main/assets/index.html`: Uygulamada gösterilen HTML arayüzü.
- `android-app/app/src/main/java/com/futbolokulum/MainActivity.kt`: WebView başlatır ve `index.html` dosyasını açar.
