# FinStarter — лендинг

Упрощённая версия сайта FinStarter: одна страница с якорным меню плюс форма обратной связи.
Чистый HTML/CSS/JS, без сборки — `index.html` открывается двойным кликом.

## Структура

- `index.html` — главная. Разделы и их якоря: `#foundation`, `#who`, `#modules`, `#options`,
  `#roadmap`, `#faq`, `#about`. Каждый пункт меню ведёт на свой раздел.
- `contact.html` — Contact us (единственная отдельная страница).
- `styles.css` — общие стили, десктоп 1920 по макету Figma.
- `responsive.css` — адаптив: ≤1360 (шапка ужимается, от логотипа остаётся иконка),
  ≤1080 (бургер), ≤768 (планшет), ≤640 (телефон).
- `site.js` — поведение: бургер, выпадайка Login, модалка Book a Demo, FAQ-аккордеон,
  анимации hero, появление блоков при скролле, роадмапы.
- `contact.css`, `contact.js` — страница Contact us.
- `assets/` — картинки и иконки, выгруженные из Figma.

## Что не подключено

- Отправка форм (модалка Book a Demo и Contact us) — в коде помечено `TODO`, нужен бэкенд или CRM.
- Ссылки Business login / Customer portal / Privacy Policy / Terms of Service — заглушки `#`.

## Локальный просмотр

```
python -m http.server 8766
```
