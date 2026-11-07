# NEON FRONTIER — Son Savunma

Tarayıcıda çalışan, Three.js ile hazırlanmış bir birinci şahıs 3B arena/survival oyunu. Düşman robot dalgalarını temizle, mühimmatını yönet ve mümkün olduğunca uzun süre hayatta kal.

## Oynama

`index.html` dosyasını bir web sunucusunda aç (ES modülleri nedeniyle `file://` yerine sunucu kullan):

```bash
python -m http.server 8000
```

Ardından `http://localhost:8000` adresine git. Three.js ve yazı tipleri CDN'den yüklenir; internet bağlantısı gerekir.

- **WASD / ok tuşları:** hareket
- **Fare:** nişan al
- **Sol tık:** ateş et
- **Shift:** depar
- **R:** yeniden doldur
- **Esc:** duraklat / devam et

En iyi deneyim için masaüstü tarayıcı, WebGL desteği ve kulaklık önerilir.
