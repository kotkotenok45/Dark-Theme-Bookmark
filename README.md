# Dark-Theme-Bookmark

> Простая и быстрая тёмная тема для любого сайта в один клик. Без установки тяжёлых расширений, браузерных разрешений и стороннего кода.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Size](https://img.shields.io/badge/size-3KB-brightgreen.svg)
![Platform](https://img.shields.io/badge/platform-Chrome%20%7C%20Firefox%20%7C%20Edge%20%7C%20Safari-orange.svg)

---

## ✨ Особенности

- 🚀 **Мгновенный запуск:** Работает через обычную закладку браузера (букмарклет).
- 🖼️ **Умная инверсия:** Включает ночной режим, не испортив цвета на изображениях, видео, SVG и картинках-фонах.
- 🔒 **100% Приватность:** Код выполняются прямо в вашем браузере. Никаких трекеров и сбора данных.
- ⚡ **Легковесность:** Занимает менее 3 КБ и не расходует оперативную память в фоновом режиме.

---

## 🚀 Быстрый старт

### Способ 1: Через GitHub Pages (Рекомендуется)
1. Перейдите на страницу проекта: `https://твой-логин.github.io/название-репозитория/`
2. Включите панель закладок (`Ctrl + Shift + B` или `Cmd + Shift + B`).
3. Зажмите кнопку **«🌙 Тёмная тема»** мышкой и перетащите её на панель закладок.

---

### Способ 2: Вручную
1. Создайте новую закладку в вашем браузере.
2. В поле **Название** введите: `🌙 Тёмная тема`.
3. В поле **URL / Адрес** вставьте следующий JS-код:

```javascript
javascript:(function(){var id='dark-mode-toggle-style';var oldStyle=document.getElementById(id);if(oldStyle){oldStyle.remove();}else{var style=document.createElement('style');style.id=id;style.innerHTML='html { filter: invert(100%) hue-rotate(180deg) !important; } img, video, svg, canvas, [style*="background-image"] { filter: invert(100%) hue-rotate(180deg) !important; }';document.head.appendChild(style);}})();
