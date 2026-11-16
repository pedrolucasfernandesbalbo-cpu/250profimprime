# 250 Atividades para Imprimir – Landing Page

Landing page estática (HTML + CSS + JS puros, sem build).

## Estrutura

```
.
├── index.html
├── vercel.json
├── robots.txt
└── assets/
    └── img/
        ├── hero.jpg
        ├── monitor.jpg
        ├── og-image.jpg
        ├── preview-1.jpg
        ├── preview-2.jpg
        └── preview-3.jpg
```

## Antes de publicar (editar no `index.html`)

1. **og:image** – troque `SEU-DOMINIO.vercel.app` pelo domínio final.
2. **Pixel da Meta** – cole o script no `<head>` (`[COLE AQUI O PIXEL DA META]`) e descomente o bloco `InitiateCheckout` no final do arquivo.
3. **Google Tag Manager** – cole o script no `<head>` e o `<noscript>` logo após `<body>`.

## Deploy

Vercel → Add New Project → importar o repositório → Framework Preset: **Other** → Deploy (sem build command e sem output directory).
