---
$title: Используйте предварительную загрузку веб-шрифтов
$order: 140
tags:
- lcp
---

Предварительная загрузка позволяет вам сообщить браузеру о критически важных ресурсах, которые нужно загрузить как можно скорее — даже раньше, чем они будут обнаружены в HTML-коде. Это особенно полезно для ресурсов, использующихся в рамках первого окна просмотра или на всей странице (например, шрифтов). Для предварительной загрузки ресурсов добавьте к соответствующим тегам атрибут `rel="preload"`, как показано ниже:

```
<link href="font.woff2" rel="preload">
```
