---
title: 'Свойство layout'
description: Любой файл (первого уровня) в дирректории `layouts` будет создавать кастомизированный макет доступный через свойство `layout` в компоненте страницы.
menu: Свойство Layout
category: components-glossary
---

> Любой файл (первого уровня) в дирректории `layouts` будет создавать кастомизированный макет доступный через свойство `layout` в компоненте страницы.

- **Тип:** `String` или `Function` (по умолчанию: `'default'`)

Используйте ключ `layout` в компоненте вашей страницы для определения макета.

```js
export default {
  layout: 'blog',
  // ИЛИ
  layout(context) {
    return 'blog'
  }
}
```