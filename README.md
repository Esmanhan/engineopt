# engineopt — сайт GEO

Сайт GEO-продукта: делаем бизнес видимым для ChatGPT, Gemini, Claude, DeepSeek и Qwen.

Один файл `index.html`: 3D-сцена из частиц на Three.js (r128, cdnjs), страницы через хэш:
`#home`, `#services`, `#cases`, `#faq`, `#contacts`. Весь текст лежит прямо в HTML, есть JSON-LD (ProfessionalService, FAQPage).

## Запуск

Открыть `index.html` в браузере или выложить на любой статический хостинг (GitHub Pages, Vercel, Cloudflare Pages).

## Что заполнить

- Контакты — объект `CONTACTS` в начале скрипта в `index.html` (telegram, whatsapp, phone, email). Пустые поля на сайте не показываются.
- Название бренда — сейчас везде «GEO».
