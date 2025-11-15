## 1. Валідація HTML

Використаний сервіс:
https://validator.w3.org/

### Отримані помилки:

**Error:** Element `<img>` must have an `alt` attribute.  
**Причина:** Тег `<img>` обов’язково має містити текстовий опис для доступності та SEO.

**Error:** Stray end tag `</div>`.  
**Причина:** Закриваючий тег `</div>` стояв без відповідного `<div>`.

**Error:** The “charset” attribute on the “meta” element is obsolete.  
**Причина:** Мій meta-тег був написаний так:
```html
<meta charset="UTF8">