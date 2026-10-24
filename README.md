# Sunfyre Görselleri

Sunfyre ürün görselleri.

## Klasör yapısı

```
urunler/
  <urun-adi>/
    01.jpg
    02.jpg
    ...
```

- Her ürünün kendi klasörü vardır. Klasör adları küçük harf, Türkçe karaktersiz ve tireyle yazılır (ör. `urun-adi-siyah`).
- Varyanta özel görseller alt klasördedir: `urunler/<urun-adi>/<varyant>/01.jpg`
- `01` ana görseldir; numaralar görsel sırasını belirler.

## Görsel standartları

- Format: JPG (şeffaflık gerekirse PNG)
- En uzun kenar en fazla 2000 px
- Tüm görsellerden EXIF/konum verisi silinir

## Kurallar

- Bu repo herkese açıktır. Buraya yalnızca yayınlanmaya hazır ürün görselleri eklenir.
- Kullanımdaki bir görsel silinmez veya yeniden adlandırılmaz; yerine yeni numarayla eklenir.
