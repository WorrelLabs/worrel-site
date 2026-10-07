# Worrel landing page

Tek sayfalık statik site, derleme adımı yok. Tasarım ve metin senin gönderdiğin dosyadan alındı.

## GitHub Pages'e yükleme

1. GitHub'da yeni bir repo aç.
2. Bu klasördeki tüm dosyaları (`.nojekyll` dahil) repo köküne yükle.
3. Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)` → Save.
4. Custom domain alanına `worrel.id` yaz (repoda `CNAME` dosyası zaten var).

## DNS (alan adı sağlayıcında)

| Tür | Ad | Değer |
|---|---|---|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | `<github-kullanıcı-adın>.github.io` |

DNS yayılması 24 saate kadar sürebilir. Domain doğrulanınca Settings → Pages'te Enforce HTTPS'i işaretle.

Kaynak: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## Orijinal dosyaya göre değişenler

- Logo iki kez base64 olarak gömülüydü (594 KB). Tek `logo.png` dosyasına çıkarıldı (119 KB).
- Eklendi: favicon, apple-touch-icon, sosyal paylaşım görseli (`og-image.png`), canonical ve Open Graph etiketleri, `404.html`, `robots.txt`.
- Metin, renk ve düzen değiştirilmedi.
