---
published: true
title: "Kubernetes'ga kirish"
category: "Kubernetes"
order: 7
duration: "18:15"
description: "Klaster nima, Pod qanday ishlaydi va nega hamma Kubernetes haqida gapiradi."
---

## Klaster qanday ishlaydi

<iframe src="/kubernetes-diagram.html"
        style="width:100%;aspect-ratio:16/9;border:1px solid var(--color-neutral-700);border-radius:var(--radius-md);background:#10121c"
        loading="lazy" title="Kubernetes klaster diagrammasi"></iframe>

Diagrammada boshqaruv qatlami (API server, etcd, scheduler, controller manager) va ikkita worker node ko'rsatilgan: binafsha kvadratlar — istalgan holat (kubectl → API server → etcd → kubeletlar), nuqtalar — kube-proxy orqali podlarga boradigan xizmat trafigi.
