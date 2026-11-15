# MP4 для Modrinth

Скопируйте содержимое блока кода в описание. Это исходные MP4 без перекодирования.

```html
<video controls loop muted width="1280">
  <source src="https://raw.githubusercontent.com/dcvke/horizons-unbound-media/main/video/end-storm.mp4" type="video/mp4">
</video>

<video controls loop muted width="1280">
  <source src="https://raw.githubusercontent.com/dcvke/horizons-unbound-media/main/video/nether-storm.mp4" type="video/mp4">
</video>

<video controls loop muted width="1280">
  <source src="https://raw.githubusercontent.com/dcvke/horizons-unbound-media/main/video/overworld-storm.mp4" type="video/mp4">
</video>

<video controls loop muted width="1280">
  <source src="https://raw.githubusercontent.com/dcvke/horizons-unbound-media/main/video/deep-dark-storm.mp4" type="video/mp4">
</video>

```

WebP для автоматической анимации без плеера: используйте `![описание](URL)` и ссылки на папку `webp-compact/` в README.

GitHub Raw отвечает на MP4 заголовком `application/octet-stream`, поэтому в примерах явно указан тип `video/mp4`. Синтаксис сверён с официальным рендерером Modrinth; вставка в живом редакторе Modrinth не выполнялась. Если нужен автоматический показ как у GIF, используйте WebP.
