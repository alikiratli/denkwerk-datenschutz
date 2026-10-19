# denkwerk-web

Denkwerk'in gizlilik politikası ve Impressum'u. GitHub Pages ile yayınlanır:

- <https://alikiratli.github.io/denkwerk-web/privacy-policy.html> (Datenschutzerklärung + Privacy Policy)
- <https://alikiratli.github.io/denkwerk-web/impressum.html>
- <https://alikiratli.github.io/denkwerk-web/datenschutz.html> — `privacy-policy.html#de`'ye yönlendirir

Kök adres (<https://alikiratli.github.io/denkwerk-web/>) iki sayfaya da
bağlantı verir.

Bu adresler Play Console'da iki yerde kullanılıyor:

- **Gizlilik politikası URL'i** (zorunlu) — yönlendirme değil,
  `privacy-policy.html` doğrudan verilir; Play'in denetimi sayfanın kendisini
  görsün
- Mağaza girişindeki **Web sitesi** alanı — kök adres

Depo yalnızca bu sayfalar için var. Uygulamanın kaynak kodu ayrı ve özel bir
depoda (Denkwerk); bu depo herkese açık, çünkü Play politikanın herkesçe
okunabilir bir adreste durmasını istiyor.

## Güncelleme

Sayfaların kaynağı Denkwerk deposundaki `docs/store/` klasörü. Orada
düzenleyip buraya kopyalamak, iki nüshanın ayrışmamasını sağlar:

```
cp <Denkwerk>/docs/store/*.html .
```

Dosya adları değiştirilmemeli: sayfalar birbirine göreli bağlantı veriyor.
Commit'ten sonra GitHub Pages birkaç dakika içinde yayına alır.

Uygulamanın veri davranışı değişirse (internet izni, satın alma, çökme
raporlama, analytics) politika **ve** Play'deki Data safety formu birlikte
güncellenmelidir. Impressum'daki adres § 5 DDG gereği ladungsfähig olmak
zorunda — taşınma hâlinde buranın güncellenmesi gerekir.
