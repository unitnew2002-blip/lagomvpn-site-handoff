# LagomVPN — главная страница

Вёрстка главной страницы LagomVPN: один файл `index.html` (HTML, CSS и JS внутри) и папка `assets` с картинками, видео и шрифтами.

## Как открыть

Запустить любой статический сервер из корня репозитория, например:

```bash
npx serve .
```

или

```bash
python3 -m http.server 8000
```

## Что внутри

- `assets/img` — изображения (WebP)
- `assets/video` — фоновые видео (MP4)
- `assets/fonts` — Manrope (запасной шрифт; основной — Suisse Intl, подключается через `local()`)
- Анимации: GSAP 3.12.5 + ScrollTrigger, плавный скролл — Lenis 1.3.21 (подключены с CDN)
- `?static` в адресе отключает анимации
