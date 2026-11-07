# Neon Horizon — Solar Punk 3D City Game

Bu proje, tarayıcıda çalışan ve `Three.js` ile üretilen daha büyük bir **solar punk 3D şehir prototipi**. Oyun, oyuncunun şehirde dolaşmasını, enerji kristallerini toplamaya çalışmasını ve dronların saldırısına karşı hayatta kalmasını hedefler.

## Özellikler

- 3D şehir ortamı ve büyük açık harita
- Solar punk temalı aydınlatma ve renk paleti
- Güneş enerjisi / enerji bar sistemi
- Dron düşmanları ve ateş mekaniği
- Enerji kristalleri toplayarak kuleyi temizleme hedefi
- Başlangıç menüsü ve scor / görev ekranı

## Çalıştırma

```bash
cd OYUN
python -m http.server 8000
```

Sonra tarayıcıda şu adrese gir:

```text
http://localhost:8000
```

Not: Bu oyun, web tarayıcısında çalışır ve CDN üzerinden Three.js kütüphanesini yükler.

## Kontroller

- W A S D: Oyuncu hareketi
- Fare: Bakış açısı
- Sol tık: Ateş et
- Shift: Sprint
- R: Enerji yenileme

## Not

Bu, GTA V seviyesine ulaşan tam bir AAA oyunu değil; fakat daha büyük, daha profesyonel ve daha zengin bir 3D prototip olarak tasarlandı. İstersen bir sonraki adımda bunu:

- arabalı açık dünya versiyonu
- zombi savunma sürümü
- sürüş + görev sistemi
- daha büyük şehir + NPC / araç / mini map
- Unreal Engine benzeri daha devrimci bir versiyon

şekline dönüştürebilirim.
