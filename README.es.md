[English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md) | [Français](README.fr.md) | [Español](README.es.md) | [العربية](README.ar.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Русский](README.ru.md) | [Deutsch](README.de.md)

<div align="center">

<img src=".banner.svg" width="100%" alt="banner">

</div>


# Awesome Video Prompts

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Prompts](https://img.shields.io/badge/Prompts-200+-orange.svg)](#colecciones-de-prompts)

**Deja de escribir prompts vagos. Más de 200 prompts de generación de vídeo probados para Sora, Runway, Pika y Kling.**

---

## El problema

**Prompt malo:**
> "a cat walking"

**Resultado:** Un gato aleatorio, un lugar aleatorio, una calidad aleatoria. Inténtalo de nuevo. Y otra vez. Y otra vez.

---

## La solución

**Buen prompt:**
> "A ginger tabby cat walks slowly along a rain-soaked cobblestone alley at dusk. Camera follows from behind at cat height, 35mm lens. Warm streetlamp light creates long shadows. Puddles reflect the neon signs above. Shot on ARRI Alexa, cinematic color grade, film grain."

**Resultado:** Exactamente lo que imaginaste. A la primera.

---

## Inicio rápido

1. **Explora** las colecciones de prompts a continuación
2. **Copia** un prompt que se adapte a tu proyecto
3. **Pégalo** en tu herramienta de vídeo con IA
4. **Ajusta** los detalles según tu visión
5. **Genera** — y obtén resultados que realmente funcionan

---

## Guía rápida de prompt engineering

### Anatomía de un prompt de vídeo

```
[Sujeto] + [Acción] + [Entorno] + [Cámara] + [Iluminación] + [Estilo] + [Calidad]
```

### Movimientos de cámara esenciales

| Movimiento | Ejemplo de prompt |
|------------|-------------------|
| Paneo | Camera pans left to right |
| Inclinación | Camera tilts up from ground to sky |
| Travelling | Camera dollies toward the subject |
| Seguimiento | Camera tracks alongside the runner |
| Grúa | Camera cranes up to 30ft overhead |
| Drone | Aerial drone shot descending from 200ft |
| Órbita | Camera orbits 360° around the subject |
| Steadicam | Steadicam follows through the hallway |
| A mano | Slight handheld shake, documentary feel |
| Estático | Camera locked on tripod, no movement |

### Iluminaciones esenciales

| Iluminación | Ejemplo de prompt |
|-------------|-------------------|
| Hora dorada | Warm light, long shadows, 30 min before sunset |
| Hora azul | Deep blue ambient, 20 min after sunset |
| Luz de contorno | Strong backlight on subject edges |
| Volumétrica | Light shafts through fog/dust |
| Nublado | Soft, diffused, no hard shadows |
| Neón | Pink, blue, electric green reflections |
| Velas | Warm flickering, intimate shadows |
| Claroscuro | Single hard light, deep shadows |

### Consejos de profesional

- **Nombra el lente**: "21mm wide angle" o "200mm telephoto" — la distancia focal lo cambia todo
- **Nombra un director de fotografía**: "In the style of Roger Deakins" le da a la IA un objetivo claro
- **Describe el ambiente, no solo la escena**: "A sense of quiet loneliness" > "empty room"
- **Una acción por prompt**: No encadenes 10 acciones. Concéntrate en un instante.
- **Incluye indicaciones negativas**: "No camera shake, no lens flare" — dile qué evitar

---

## Colecciones de prompts

### Sora (OpenAI)

| Categoría | Descripción | Prompts | Archivo |
|-----------|-------------|---------|---------|
| 🎬 Planos cinematográficos | Planos establecedores, seguimientos, zooms travelling, vistas aéreas, timelapses | 25+ | [cinematic-shots.md](prompts/Sora/cinematic-shots.md) |
| 📖 Escenas narrativas | Acciones de personajes, diálogos, momentos emocionales, conflicto/resolución | 25+ | [narrative-scenes.md](prompts/Sora/narrative-scenes.md) |
| 🛍️ Presentación de producto | Lanzamiento de producto, unboxing, planos de estilo de vida, primeros planos | 20+ | [product-showcase.md](prompts/Sora/product-showcase.md) |

### Runway Gen-3

| Categoría | Descripción | Prompts | Archivo |
|-----------|-------------|---------|---------|
| 🎨 Motion graphics | Animaciones líquidas, efectos de partículas, transformaciones geométricas, texto | 25+ | [motion-graphics.md](prompts/Runway/motion-graphics.md) |
| 📸 Escenas realistas | Personas, animales, entornos, clima, vehículos | 25+ | [realistic-scenes.md](prompts/Runway/realistic-scenes.md) |
| 🖌️ Transferencia de estilo | Impresionismo, ciberpunk, cine negro, Studio Ghibli, Wes Anderson | 20+ | [style-transfer.md](prompts/Runway/style-transfer.md) |

### Pika

| Categoría | Descripción | Prompts | Archivo |
|-----------|-------------|---------|---------|
| 📱 Contenido corto | Estilo TikTok/Reels/Shorts, memes, bucles satisfactorios | 25+ | [short-form-content.md](prompts/Pika/short-form-content.md) |
| ✏️ Estilo animación | Animación 2D, renderizado 3D, pixel art, claymation | 20+ | [animation-style.md](prompts/Pika/animation-style.md) |
| ✨ Efectos y transformaciones | Metamorfosis, explosiones, efectos climáticos, manipulación temporal | 20+ | [effects-and-transformations.md](prompts/Pika/effects-and-transformations.md) |

### Kling

| Categoría | Descripción | Prompts | Archivo |
|-----------|-------------|---------|---------|
| 🏃 Centrado en humanos | Danza, deportes, cocina, artesanía, actuaciones | 25+ | [human-centric.md](prompts/Kling/human-centric.md) |
| 🌿 Naturaleza y animales | Paisajes, fauna, clima, estaciones, macro/micro | 20+ | [nature-and-animals.md](prompts/Kling/nature-and-animals.md) |
| 🏯 Estética china | Pintura tinta, arquitectura antigua, artes marciales, poesía, cultura tradicional | 20+ | [chinese-aesthetics.md](prompts/Kling/chinese-aesthetics.md) |

### Guías

| Guía | Descripción | Archivo |
|------|-------------|---------|
| 📚 Prompt engineering | Vocabulario de cámara, vocabulario de iluminación, referencia de película, errores comunes | [prompt-engineering.md](prompts/通用技巧/prompt-engineering.md) |
| 🎨 Palabras clave de estilo | Más de 200 palabras clave de estilo organizadas por categoría: estilo visual, color, textura, ambiente | [style-keywords.md](prompts/通用技巧/style-keywords.md) |

---

## Comparación de herramientas

| Característica | Sora | Runway Gen-3 | Pika | Kling |
|----------------|------|-------------|------|-------|
| **Mejor para** | Narrativa, cinematográfico | Motion graphics, abstracto | Redes sociales, animación | Movimiento humano, naturaleza |
| **Duración máx** | 60s | 10s | 4s | 10s |
| **Fotorrealismo** | ★★★★★ | ★★★★ | ★★★ | ★★★★ |
| **Animación** | ★★★ | ★★★★ | ★★★★★ | ★★★ |
| **Movimiento humano** | ★★★★ | ★★★ | ★★★ | ★★★★★ |
| **Transferencia de estilo** | ★★★ | ★★★★★ | ★★★★ | ★★★ |
| **Relaciones de aspecto** | 16:9, 9:16, 1:1 | 16:9, 9:16, 1:1 | 16:9, 9:16, 1:1, 4:5 | 16:9, 9:16 |

### Cuándo usar cada herramienta

- **Sora**: Cuando necesitas una escena completa con narrativa, movimiento de cámara y calidad cinematográfica
- **Runway**: Cuando necesitas motion graphics, visuales abstractos o una fuerte transferencia de estilo
- **Pika**: Cuando necesitas contenido corto y contundente para redes sociales o estilos de animación
- **Kling**: Cuando tu vídeo se centra en el movimiento humano, la cocina, la danza o la estética china

---

## Contribuir

¡Aceptamos contribuciones de prompts! Consulta [CONTRIBUTING.md](CONTRIBUTING.md) para el formato y las directrices.

**Cómo contribuir:**
1. Haz fork de este repositorio
2. Añade tu prompt probado siguiendo el [formato de plantilla](CONTRIBUTING.md#prompt-format)
3. Envía un Pull Request
4. Revisamos y fusionamos

---

## Estructura del proyecto

```
awesome-video-prompts/
├── README.md                          ← Estás aquí
├── LICENSE                            ← Licencia MIT
├── CONTRIBUTING.md                    ← Directrices de contribución
├── CHANGELOG.md                       ← Historial de versiones
├── prompts/
│   ├── Sora/                          ← Prompts de OpenAI Sora
│   │   ├── cinematic-shots.md         ← 25+ prompts cinematográficos
│   │   ├── narrative-scenes.md        ← 25+ prompts narrativos
│   │   └── product-showcase.md        ← 20+ prompts de producto
│   ├── Runway/                        ← Prompts de Runway Gen-3
│   │   ├── motion-graphics.md         ← 25+ prompts de motion graphics
│   │   ├── realistic-scenes.md        ← 25+ prompts realistas
│   │   └── style-transfer.md          ← 20+ prompts de transferencia de estilo
│   ├── Pika/                          ← Prompts de Pika
│   │   ├── short-form-content.md      ← 25+ prompts para redes sociales
│   │   ├── animation-style.md         ← 20+ prompts de animación
│   │   └── effects-and-transformations.md ← 20+ prompts de efectos
│   ├── Kling/                         ← Prompts de Kling
│   │   ├── human-centric.md           ← 25+ prompts de movimiento humano
│   │   ├── nature-and-animals.md      ← 20+ prompts de naturaleza
│   │   └── chinese-aesthetics.md      ← 20+ prompts de estética china
│   └── 通用技巧/                       ← Técnicas generales
│       ├── prompt-engineering.md      ← Guía completa de prompt engineering
│       └── style-keywords.md          ← Referencia de 200+ palabras clave de estilo
└── .github/
    ├── workflows/ci.yml               ← Pipeline de CI
    ├── ISSUE_TEMPLATE/                ← Plantillas de issue
    └── pull_request_template.md       ← Plantilla de PR
```

---

## Ver también

- [awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts) — Colección de prompts de ChatGPT
- [awesome-prompts](https://github.com/DAGWorks-Inc/awesome-prompts) — Colección de prompts multimodales
- [awesome-ai-tools](https://github.com/mahseema/awesome-ai-tools) — Lista seleccionada de herramientas de IA
- [awesome-generative-ai](https://github.com/steven2358/awesome-generative-ai) — Recursos de IA generativa
- [awesome-stable-diffusion](https://github.com/underctrlanatomy/awesome-stable-diffusion) — Recursos de Stable Diffusion
- [awesome-midjourney-prompts](https://github.com/willwulfken/awesome-midjourney-prompts) — Colección de prompts de Midjourney

---

## Licencia

Este proyecto está bajo la licencia MIT — consulta el archivo [LICENSE](LICENSE) para más detalles.

Copyright (c) 2026 liangzhengtao
