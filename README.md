# Sağlık Köprüsü – Web Sayfaları

"Sağlık Köprüsü" iOS uygulamasının App Store için gereken statik web sayfaları (ana sayfa, gizlilik politikası, destek). Uygulama kodu bu repoda değildir.

Yayın adresi: https://oferkal-code.github.io/saglik-koprusu/

| Sayfa | Adres |
| --- | --- |
| Ana sayfa | https://oferkal-code.github.io/saglik-koprusu/ |
| Gizlilik Politikası (App Store "Privacy Policy URL") | https://oferkal-code.github.io/saglik-koprusu/privacy.html |
| Destek (App Store "Support URL") | https://oferkal-code.github.io/saglik-koprusu/support.html |

## Yapı

- `index.html`, `privacy.html`, `support.html` – Türkçe + İngilizce içerik
- `assets/style.css` – ortak stil
- `assets/icon.svg` – uygulama simgesi
- `.nojekyll` – GitHub Pages'in Jekyll işlemesini kapatır

Saf HTML + CSS; derleme aracı veya JavaScript yok.

## GitHub Pages ayarı

1. Repo sayfasında **Settings > Pages**'e gidin.
2. **Source**: **Deploy from a branch**.
3. **Branch**: `main`, klasör: `/ (root)` → **Save**.
4. Birkaç dakika sonra site yukarıdaki adreste yayında olur.
