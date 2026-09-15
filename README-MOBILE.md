# Freebuff Android APK

Bu proje, Freebuff web oyununu Android WebView uygulaması olarak paketler.

## Telefonda kurulum

1. Bu klasörün içindeki dosyaları GitHub'daki kendi repository'ne yükle.
2. Repository'de **Actions** sekmesine gir.
3. Soldan **Freebuff APK** workflow'unu seç.
4. **Run workflow** → **Run workflow**.
5. İşlem bitince workflow çalışmasına gir.
6. **Artifacts** bölümündeki **Freebuff-APK** dosyasını indir.
7. ZIP'i açıp `app-debug.apk` dosyasını telefona kur.

## Oyun adresi

Uygulama şu adresi açar:

https://sanalstar.freebuff.app/

Değiştirmek istersen:
`app/src/main/kotlin/app/freebuff/wrapper/MainActivity.kt`

dosyasındaki `gameUrl` değerini değiştir.

## Not

Bu sürüm debug APK üretir. Telefonda test etmek için uygundur.
Play Store'a yüklemeden önce imzalı release/AAB sürümü hazırlamak gerekir.
