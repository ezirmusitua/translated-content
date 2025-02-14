---
title: Document.URL
slug: Web/API/Document/URL
tags:
  - API
  - Document
  - Property
translation_of: Web/API/Document/URL
---
{{APIRef("DOM")}}

Возвращает строку URL документа HTML.

## Синтаксис

```
string = document.URL
```

## Пример

### JavaScript

```
document.getElementById("url").textContent = document.URL;
```

### HTML

```html
<p id="urlText">
  URL:<br/>
  <span id="url">URL goes here</span>
</p>
```

### Результат

{{EmbedLiveSample("Пример", "100%", 100)}}

## Спецификации

{{Specifications}}

## Браузерная поддержка

{{Compat}}

## Смотрите также

- {{domxref("HTMLDocument")}}
