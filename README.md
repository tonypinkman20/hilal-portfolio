# hilal-portfolio

Hilal için sade bir portfolyo demosu. [Hugo](https://gohugo.io/) ve [Stack teması](https://github.com/CaiJimmy/hugo-theme-stack) ile yapıldı, renkleri yeşil ve açık kahve tonlarına uyarlandı.

## Çalıştırma

```bash
git clone --recurse-submodules https://github.com/tonypinkman20/hilal-portfolio
cd hilal-portfolio
hugo server
```

Hugo extended 0.157.0 veya üstü gerekir.

## Düzenleme

İçerik [Pages CMS](https://app.pagescms.org) panelinden düzenlenir, ayarları `.pages.yml` içindedir. Elle düzenlemek için:

- Projeler: `content/post/`
- Görseller: `assets/uploads/`
- Hakkımda ve İletişim: `content/page/`
- Renkler: `assets/scss/custom.scss`
- Site ayarları: `config/_default/`

`content/` altındaki metinler ve görseller örnektir.
