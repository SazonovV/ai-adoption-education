# AIpresentation on GitHub Pages

Репозиторий подготовлен для публикации через GitHub Pages.

## Что уже настроено

- `/.github/workflows/pages.yml` — автодеплой на GitHub Pages при пуше в `main` или `master`.
- `/index.html` — главная страница-навигация.
- `/presentations/part0/` — презентация «Часть 0: Введение в вайбкодинг».
- `/presentations/part1/` — основная презентация «Часть 1».
- `/reading/part0/` и `/reading/part1/` — красивое отображение markdown-конспектов.
- `/content/part0_vibecoding.md` и `/content/part1_foundations.md` — исходные markdown-файлы.

## Структура репозитория

```text
.
├── assets/                  # изображения и медиа
├── content/                 # исходные .md конспекты
├── presentations/
│   ├── part0/               # слайды части 0
│   ├── part1/               # слайды части 1 (основные)
│   └── legacy/              # служебная старая версия части 1
├── reading/                 # красивые HTML-страницы чтения markdown
│   ├── part0/
│   └── part1/
├── text/                    # меню для перехода к конспектам
└── index.html               # навигация по материалам
```

## Какие будут URL после публикации

Замените `<USERNAME>` и `<REPO>`:

- Презентация: `https://<USERNAME>.github.io/<REPO>/`
- Презентация Part 0: `https://<USERNAME>.github.io/<REPO>/presentations/part0/`
- Презентация Part 1: `https://<USERNAME>.github.io/<REPO>/presentations/part1/`
- Чтение Part 0 (HTML): `https://<USERNAME>.github.io/<REPO>/reading/part0/`
- Чтение Part 1 (HTML): `https://<USERNAME>.github.io/<REPO>/reading/part1/`
- Markdown Part 0: `https://<USERNAME>.github.io/<REPO>/content/part0_vibecoding.md`
- Markdown Part 1: `https://<USERNAME>.github.io/<REPO>/content/part1_foundations.md`

## Как включить Pages в GitHub

1. Запушить репозиторий в GitHub.
2. Открыть `Settings -> Pages`.
3. В `Build and deployment` выбрать `Source: GitHub Actions`.
4. Дождаться завершения workflow `Deploy to GitHub Pages`.
