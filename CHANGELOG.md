# Değişiklik günlüğü

Biçim: [Keep a Changelog](https://keepachangelog.com/tr/1.1.0/). Sürümleme: [SemVer](https://semver.org/lang/tr/).

## [1.1.0] - 2026-11-26

- **CirclePin — by thezencirs:** Uygulama adı her zaman üstte sabitleme kimliğini doğrudan yansıtacak şekilde **CirclePin** (`CirclePin.exe`) olarak güncellendi.
- Eski başlangıç (`Run`) ve ayar kayıtları otomatik olarak `CirclePin` altına taşınır.

## [1.0.0] - 2026-11-04

İlk sürüm.

- `Win + Ctrl + T` ile ön plandaki pencereyi her zaman üstte sabitleme / bırakma.
- Sabitlenen pencerenin etrafında mavi çerçeve; pencereyle birlikte hareket eder, küçültülünce gizlenir, kapanınca kaldırılır.
- Tepsi menüsü: sabitlenen pencere sayısı, tüm sabitlemeleri kaldır, Windows ile başlat.
- Yüksek DPI (%125, %150...) desteği.
- Yönetici yetkisiyle çalışan pencere sabitlenemezse açıklayıcı uyarı.
- Programın içinden güncelleme: GitHub Releases'ten son sürümü denetler, SHA256 ile doğrular, kendini günceller (otomatik denetim kapatılabilir).
