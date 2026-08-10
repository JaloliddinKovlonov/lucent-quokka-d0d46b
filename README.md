# uzdevops.uz — Astro sayt

DevOps darslari o'zbek tilida. Astro 5 + content collections.

## Ishga tushirish

```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # dist/ ga static build
```

## Yangi dars qo'shish

`src/content/lessons/` ga yangi .md fayl qo'shing:

```yaml
---
title: "Dars nomi"
description: "Qisqa tavsif"
category: "Docker"
order: 13
duration: "20:00"
video: "https://www.youtube-nocookie.com/embed/VIDEO_ID"
published: true
---
Dars matni markdown'da...
```

`published: false` bo'lsa katalogda "Tez kunda" deb ko'rinadi.

## Deploy (uzdevops.uz)

**Netlify:** repoga push → Netlify'da import → build: `npm run build`, publish: `dist`.
Keyin Domain settings → uzdevops.uz qo'shing, DNS'da A yozuv `75.2.60.5`.

**Vercel:** import → framework Astro avtomatik aniqlanadi → Add Domain.
