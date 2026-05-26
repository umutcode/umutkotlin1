# Merhaba Dünya - Android Kotlin Uygulaması

Bu proje, Kotlin kullanarak yazılmış basit bir Android uygulamasıdır. Ekrana "Merhaba Dünya!" mesajını yazdırır.

## Proje Yapısı

```
umutkotlin1/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── kotlin/com/example/merhabadunya/
│   │   │   │   ├── MainActivity.kt
│   │   │   │   └── ui/theme/
│   │   │   │       ├── Theme.kt
│   │   │   │       ├── Color.kt
│   │   │   │       └── Type.kt
│   │   │   ├── res/
│   │   │   │   ├── values/
│   │   │   │   │   ├── strings.xml
│   │   │   │   │   └── themes.xml
│   │   │   └── AndroidManifest.xml
│   └── build.gradle.kts
├── settings.gradle.kts
└── README.md
```

## Özellikler

- ✅ Kotlin dilinde yazılmış modern Android uygulaması
- ✅ Jetpack Compose kullanımı
- ✅ Material Design 3 tema
- ✅ Responsive UI tasarımı
- ✅ Turkish (Türkçe) mesaj

## Gereksinimler

- Android Studio (Hedgehog veya daha yeni)
- Android SDK 24+ (Minimum API Level)
- Target SDK 34
- Kotlin 1.9+
- Gradle 8.0+

## Kurulum ve Çalıştırma

1. Android Studio'da projeyi açın
2. Gradle dosyalarını senkronize edin
3. Bir emülatör veya fiziksel cihaz bağlayın
4. Projeyi derleyin ve çalıştırın

```bash
./gradlew build
./gradlew installDebug
```

## Uygulama Açıklaması

### MainActivity.kt

Ana ekranı oluşturur ve Compose kullanarak UI'ı tanımlar. Ekranın merkezinde iki metin görüntülenir:
- "Merhaba Dünya!" (başlık)
- "Kotlin Android Uygulamasına Hoşgeldiniz" (alt metin)

### Theme Dosyaları

- **Theme.kt**: Material3 tema yapılandırması
- **Color.kt**: Uygulama renkleri
- **Type.kt**: Tipografi ayarları

## Derleme Bilgileri

- **applicationId**: com.example.merhabadunya
- **versionCode**: 1
- **versionName**: 1.0

## Geliştirme

Daha fazla özellik eklemek istiyorsanız:

1. Yeni Composable fonksiyonları `MainActivity.kt` veya yeni dosyalarda oluşturun
2. Gerekliyse bağımlılıkları `build.gradle.kts` dosyasına ekleyin
3. Projeyi derleyin ve test edin

## Lisans

Bu proje açık kaynaklıdır ve serbestçe kullanılabilir.

## İletişim

Sorularınız için umutcode ile iletişime geçebilirsiniz.
