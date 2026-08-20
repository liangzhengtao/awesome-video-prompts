[English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md) | [Français](README.fr.md) | [Español](README.es.md) | [العربية](README.ar.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Русский](README.ru.md) | [Deutsch](README.de.md)
n<div align="center">

<img src=".banner.svg" width="100%" alt="banner">

</div>


# Awesome Video Prompts

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Prompts](https://img.shields.io/badge/Prompts-200+-orange.svg)](#prompt-collections)

**Хватит писать расплывчатые промпты. Более 200 проверенных промптов для генерации видео от Sora, Runway, Pika и Kling.**

---

## Проблема

**Плохой промпт:**
> "a cat walking"

**Результат:** Случайная кошка, случайное место, случайное качество. Попробуйте снова. И снова. И снова.

---

## Решение

**Хороший промпт:**
> "A ginger tabby cat walks slowly along a rain-soaked cobblestone alley at dusk. Camera follows from behind at cat height, 35mm lens. Warm streetlamp light creates long shadows. Puddles reflect the neon signs above. Shot on ARRI Alexa, cinematic color grade, film grain."

**Результат:** Exactly what you imagined. С первой попытки.

---

## Быстрый старт

1. **Просмотрите** коллекции промптов ниже
2. **Скопируйте** промпт, подходящий для вашего проекта
3. **Вставьте** в ваш инструмент для генерации видео на ИИ
4. **Настройте** детали под ваше видение
5. **Генерируйте** — и получайте результаты, которые действительно работают

---

## Шпаргалка по промпт-инжинирингу

### Анатомия видео-промпта

```
[Субъект] + [Действие] + [Окружение] + [Камера] + [Освещение] + [Стиль] + [Качество]
```

### Основные движения камеры

| Движение | Пример промпта |
|----------|----------------|
| Панорамирование | Camera pans left to right |
| Наклон | Camera tilts up from ground to sky |
| Долли | Camera dollies toward the subject |
| Трекинг | Camera tracks alongside the runner |
| Кран | Camera cranes up to 30ft overhead |
| Дрон | Aerial drone shot descending from 200ft |
| Орбита | Camera orbits 360° around the subject |
| Стедикам | Steadicam follows through the hallway |
| С рук | Slight handheld shake, documentary feel |
| Статичная | Camera locked on tripod, no movement |

### Основное освещение

| Освещение | Пример промпта |
|----------|----------------|
| Золотой час | Warm light, long shadows, 30 min before sunset |
| Синий час | Deep blue ambient, 20 min after sunset |
| Контровой свет | Strong backlight on subject edges |
| Объёмный свет | Light shafts through fog/dust |
| Пасмурно | Soft, diffused, no hard shadows |
| Неон | Pink, blue, electric green reflections |
| Свечи | Warm flickering, intimate shadows |
| Кьяроскуро | Single hard light, deep shadows |

### Профессиональные советы

- **Назовите объектив**: "21mm wide angle" или "200mm telephoto" — фокусное расстояние меняет всё
- **Назовите кинооператора**: "In the style of Roger Deakins" даёт ИИ чёткую цель
- **Описывайте настроение, а не только сцену**: "A sense of quiet loneliness" > "empty room"
- **Одно действие на промпт**: Не цепляйте 10 действий. Сосредоточьтесь на одном моменте.
- **Включайте негативные указания**: "No camera shake, no lens flare" — скажите, чего избегать

---

## Коллекции промптов

### Sora (OpenAI)

| Категория | Описание | Промпты | Файл |
|----------|-------------|---------|------|
| 🎬 Кинематографичные кадры | Establishing shots, tracking shots, dolly zooms, aerial views, time-lapses | 25+ | [cinematic-shots.md](prompts/Sora/cinematic-shots.md) |
| 📖 Нарративные сцены | Character actions, dialogue, emotional moments, conflict/resolution | 25+ | [narrative-scenes.md](prompts/Sora/narrative-scenes.md) |
| 🛍️ Презентация продукта | Product reveals, unboxing, lifestyle shots, close-ups | 20+ | [product-showcase.md](prompts/Sora/product-showcase.md) |

### Runway Gen-3

| Категория | Описание | Промпты | Файл |
|----------|-------------|---------|------|
| 🎨 Моушн-графика | Liquid animations, particle effects, geometric transformations, text | 25+ | [motion-graphics.md](prompts/Runway/motion-graphics.md) |
| 📸 Реалистичные сцены | People, animals, environments, weather, vehicles | 25+ | [realistic-scenes.md](prompts/Runway/realistic-scenes.md) |
| 🖌️ Перенос стиля | Impressionist, cyberpunk, noir, Studio Ghibli, Wes Anderson | 20+ | [style-transfer.md](prompts/Runway/style-transfer.md) |

### Pika

| Категория | Описание | Промпты | Файл |
|----------|-------------|---------|------|
| 📱 Короткий формат | TikTok/Reels/Shorts style, meme-worthy, satisfying loops | 25+ | [short-form-content.md](prompts/Pika/short-form-content.md) |
| ✏️ Стиль анимации | 2D animation, 3D render, pixel art, claymation | 20+ | [animation-style.md](prompts/Pika/animation-style.md) |
| ✨ Эффекты и трансформации | Morphing, explosions, weather effects, time manipulation | 20+ | [effects-and-transformations.md](prompts/Pika/effects-and-transformations.md) |

### Kling

| Категория | Описание | Промпты | Файл |
|----------|-------------|---------|------|
| 🏃 Человек в центре | Dance, sports, cooking, crafts, performances | 25+ | [human-centric.md](prompts/Kling/human-centric.md) |
| 🌿 Природа и животные | Landscapes, wildlife, weather, seasons, micro/macro | 20+ | [nature-and-animals.md](prompts/Kling/nature-and-animals.md) |
| 🏯 Китайская эстетика | Ink wash painting, ancient architecture, martial arts, poetry, traditional culture | 20+ | [chinese-aesthetics.md](prompts/Kling/chinese-aesthetics.md) |

### Руководства

| Руководство | Описание | Файл |
|-------|-------------|------|
| 📚 Промпт-инжиниринг | Словарь камеры, словарь освещения, справочник по плёнке, типичные ошибки | [prompt-engineering.md](prompts/通用技巧/prompt-engineering.md) |
| 🎨 Стилистические ключевые слова | 200+ стилистических ключевых слов: визуальный стиль, цвет, текстура, настроение | [style-keywords.md](prompts/通用技巧/style-keywords.md) |

---

## Сравнение инструментов

| Характеристика | Sora | Runway Gen-3 | Pika | Kling |
|---------|------|-------------|------|-------|
| **Лучше для** | Нарратив, кинематограф | Моушн-графика, абстракция | Соцсети, анимация | Движение человека, природа |
| **Макс. длительность** | 60s | 10s | 4s | 10s |
| **Фотореализм** | ★★★★★ | ★★★★ | ★★★ | ★★★★ |
| **Анимация** | ★★★ | ★★★★ | ★★★★★ | ★★★ |
| **Движение человека** | ★★★★ | ★★★ | ★★★ | ★★★★★ |
| **Перенос стиля** | ★★★ | ★★★★★ | ★★★★ | ★★★ |
| **Соотношения сторон** | 16:9, 9:16, 1:1 | 16:9, 9:16, 1:1 | 16:9, 9:16, 1:1, 4:5 | 16:9, 9:16 |

### Когда какой инструмент использовать

- **Sora**: Когда нужна полная сцена с нарративом, движением камеры и кинематографическим качеством
- **Runway**: Когда нужна моушн-графика, абстрактная картинка или сильный перенос стиля
- **Pika**: Когда нужен короткий, яркий контент для соцсетей или стили анимации
- **Kling**: Когда ваше видео вращается вокруг движения человека, готовки, танцев или китайской эстетики

---

## Участие

Приветствуются вклады промптов! Смотрите [CONTRIBUTING.md](CONTRIBUTING.md) для формата и руководства.

**Как участвовать:**
1. Форкните репозиторий
2. Добавьте протестированный промпт по [шаблону](CONTRIBUTING.md#prompt-format)
3. Отправьте Pull Request
4. Мы проверим и сольём

---

## Структура проекта

```
awesome-video-prompts/
├── README.md                          ← Вы здесь
├── LICENSE                            ← Лицензия MIT
├── CONTRIBUTING.md                    ← Руководство по участию
├── CHANGELOG.md                       ← История версий
├── prompts/
│   ├── Sora/                          ← Промпты OpenAI Sora
│   │   ├── cinematic-shots.md         ← 25+ кинематографичных промптов
│   │   ├── narrative-scenes.md        ← 25+ нарративных промптов
│   │   └── product-showcase.md        ← 20+ промптов для продуктов
│   ├── Runway/                        ← Промпты Runway Gen-3
│   │   ├── motion-graphics.md         ← 25+ промптов моушн-графики
│   │   ├── realistic-scenes.md        ← 25+ реалистичных промптов
│   │   └── style-transfer.md          ← 20+ промптов переноса стиля
│   ├── Pika/                          ← Промпты Pika
│   │   ├── short-form-content.md      ← 25+ промптов для соцсетей
│   │   ├── animation-style.md         ← 20+ промптов анимации
│   │   └── effects-and-transformations.md ← 20+ промптов эффектов
│   ├── Kling/                         ← Промпты Kling
│   │   ├── human-centric.md           ← 25+ промптов движения человека
│   │   ├── nature-and-animals.md      ← 20+ промптов природы
│   │   └── chinese-aesthetics.md      ← 20+ промптов китайской эстетики
│   └── 通用技巧/                       ← Общие техники
│       ├── prompt-engineering.md      ← Полное руководство по промпт-инжинирингу
│       └── style-keywords.md          ← 200+ стилистических ключевых слов
└── .github/
    ├── workflows/ci.yml               ← CI-пайплайн
    ├── ISSUE_TEMPLATE/                ← Шаблоны issues
    └── pull_request_template.md       ← Шаблон PR
```

---

## Также смотрите

- [awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts) — Коллекция промптов ChatGPT
- [awesome-prompts](https://github.com/DAGWorks-Inc/awesome-prompts) — Мультимодальная коллекция промптов
- [awesome-ai-tools](https://github.com/mahseema/awesome-ai-tools) — Кураторский список ИИ-инструментов
- [awesome-generative-ai](https://github.com/steven2358/awesome-generative-ai) — Ресурсы генеративного ИИ
- [awesome-stable-diffusion](https://github.com/underctrlanatomy/awesome-stable-diffusion) — Ресурсы Stable Diffusion
- [awesome-midjourney-prompts](https://github.com/willwulfken/awesome-midjourney-prompts) — Коллекция промптов Midjourney

---

## Лицензия

Проект распространяется под лицензией MIT — подробности в файле [LICENSE](LICENSE).

Copyright (c) 2026 liangzhengtao
