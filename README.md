# Esoterica Kütüphane

[Esoterica](https://github.com/hechecik/esoterica) sitesinin yorum kütüphanesi. Site bu repoyu
derleme sırasında alt modül olarak içine alır; çalışma anında buradan hiçbir şey çekilmez.

## Yapı

```
ortak/        her fal türünün paylaştığı parçalar (ton sözlüğü, açılış ve kapanışlar)
remil/        remil (ilm-i remil) kütüphanesi
  haneler.yaml          12 hane: anlam, konu, çerçeve cümleleri
  sekiller/<ad>.yaml    16 şekil: portre, hâkim rolü, tanık rolü, uzlaştırıcı rolü
  hucreler/<ad>.yaml    şekil × 12 hane yorum hücreleri
  gelinme.yaml          işgal, kavuşma, mutasyon, nakil ve gelinme yok metinleri
  iskelet.yaml          anlatı iskeleti şablonları
```

## Yazım kuralları

- Her cümle özgün Türkçe. Kamu malı klasiklerden anlam alınır, metin kopyalanmaz.
- Her hücrede en az 12 varyant hedeflenir (ilk sürümde 6); tonlar: `olumlu`, `notr`, `temkinli`.
- Şablonlarda ek belirteci: `{sekil|in}` -> "Beyâz'ın". Ekler: in, e, i, de, den, ler, le, si, dir, ki.
- Korkutucu kehanet yok: ölüm, kaza, hastalık tahmini yazılmaz. Son söz okuyucuda kalır.
- Her dosyanın başında `kaynak` alanı: hangi gelenek ya da kamu malı esere dayandığı.

## Lisans

Metinler: CC BY-NC-SA 4.0 (ticari olmayan kullanım, atıf ve aynı lisansla paylaşım).
Şema ve betikler: MIT. Ayrıntı için `LICENSE` dosyasına bakın.
