---
title: GlobalEventHandlers.onloadend
slug: Web/API/XMLHttpRequest/loadend_event
translation_of: Web/API/GlobalEventHandlers/onloadend
original_slug: Web/API/GlobalEventHandlers/onloadend
---
{{ApiRef}}

Свойство **`onloadend`** от {{domxref("GlobalEventHandlers")}} примесь {{event("Event_handlers", "event handler")}} передаёт код для вызова в момент возникновения события {{event("loadend")}} (когда процесс загрузки ресурса окончился и остановился)

## Синтаксис

```
img.onloadend = funcRef;
```

При возникновении события `loadend` будет вызвана функция обработчик `funcRef`.

## Примеры

```html
<img src="myImage.jpg">
```

```js
// 'loadstart' fires first, then 'load', then 'loadend'

image.addEventListener('load', function(e) {
  console.log('Image loaded');
});

image.addEventListener('loadstart', function(e) {
  console.log('Image load started');
});

image.addEventListener('loadend', function(e) {
  console.log('Image load finished');
});
```

## Спецификации

| Specification                                                                                            | Status                           | Comment            |
| -------------------------------------------------------------------------------------------------------- | -------------------------------- | ------------------ |
| {{SpecName("HTML WHATWG", "webappapis.html#handler-onloadend", "onloadend")}} | {{Spec2("HTML WHATWG")}} | Initial definition |

## Поддержка браузерами

{{Compat}}
