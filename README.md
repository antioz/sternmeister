# SternMeister

Лендинг SternMeister: цвета и тексты — с [sternmeister.de](https://sternmeister.de/), вёрстка — с [praxeology-pokaz v9](https://antioz.github.io/praxeology-pokaz/v9/).

- Сайт: https://antioz.github.io/sternmeister/
- Всё в одном `index.html`: стили, разметка, скрипт внизу. Тексты — дословно с оригинала (снято 20.10.2026), в его порядке; правятся прямо в разметке, FAQ тоже.
- Отсчёт на первом экране — до `data-to` у `#cd` (2026-10-26 09:00 Berlin). Формы — демо: заявка открывает письмо на hello@sternmeister.de.
- Видео — Vimeo по клику, превью в `media/video/<id>.jpg`; преподаватели — `media/team/01–16.jpg` по порядку на странице.
- Картинки — `media/`, сняты с оригинала.
- Палитра (в `:root`): `#292c29` тёмный · `#ffffff` · `#f3ebde` кремовый · `#4e684c` зелёный · `#a2b698` шалфей · `#ff7000` оранжевый. Шрифт Mulish.
- Классы фона секций: без класса — белый, `.cream`, `.green`, `.sage`, `.dark`.
- Запуск: `python3 -m http.server`, открыть `index.html`.
