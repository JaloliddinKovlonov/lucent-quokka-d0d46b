---
published: true
title: "Docker asoslari: birinchi container"
category: "Docker"
order: 5
duration: "22:05"
video: "https://www.youtube-nocookie.com/embed/3c-iBn73dDE"
description: "Docker nima, image va container o'rtasidagi farq, birinchi containerni ishga tushirish."
---

Docker — bu ilovalarni izolyatsiyalangan muhitda ishga tushirish texnologiyasi.

## Image va Container

- **Image** — bu ilovaning "qolipi" (shabloni)
- **Container** — bu image asosida ishga tushirilgan jonli nusxa

## Birinchi container

Nginx serverini ishga tushiramiz:

```bash
docker run -d -p 8080:80 nginx
```

Ishlab turgan containerlarni ko‘rish:

```bash
docker ps
```

Containerni to‘xtatish:

```bash
docker stop <container_id>
```

## Keyingi qadam

Keyingi darsda o‘zimizning Dockerfile yozamiz va shaxsiy image quramiz.
