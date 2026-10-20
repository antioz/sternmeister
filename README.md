# SternMeister

Лендинг SternMeister: тексты — с [sternmeister.de](https://sternmeister.de/) (с правками заказчика), цвета — палитра SternMeister. Две версии с переключателем внизу страницы.

- **Версия 1** — https://antioz.github.io/sternmeister/ (`index.html`): дизайн [praxeology-pokaz v2](https://antioz.github.io/praxeology-pokaz/v2/) «Будущее» — Inter Tight + JetBrains Mono, прямые углы, тонкие рамки, моно-метки, слово по буквам на первом экране.
- **Версия 2** — https://antioz.github.io/sternmeister/v2/ (`v2/index.html`): дизайн [praxeology-pokaz v1](https://antioz.github.io/praxeology-pokaz/v1/) «Балтика» — CSS v1 перенесён построчно, заменены только цвета; шрифты v1 (Geist + Spectral) лежат в `v2/assets/`.
- Тексты обеих версий одинаковые. Картинки — общая `media/` (сняты с оригинала; превью видео — `media/video/<vimeo id>.jpg`, преподаватели — `media/team/01–16.jpg` по порядку на странице).
- Палитра: `#292c29` тёмный · `#f3ebde` кремовый · `#4e684c` зелёный · `#26331f` тёмно-зелёный · `#a2b698` шалфей · `#ff7000` оранжевый.
- Отсчёт до старта — до `data-to` у `#cd` (2026-10-26 09:00 Berlin). Формы — демо: заявка открывает письмо на hello@sternmeister.de.
- Сняты 20.10.2026: первая версия на вёрстке pokaz v9 (есть в истории git).
- Запуск: `python3 -m http.server`, открыть `index.html`.
