[English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md) | [Français](README.fr.md) | [Español](README.es.md) | [العربية](README.ar.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Русский](README.ru.md) | [Deutsch](README.de.md)
n<div align="center">

<img src=".banner.svg" width="100%" alt="banner">

</div>


# Awesome Video Prompts

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Prompts](https://img.shields.io/badge/Prompts-200+-orange.svg)](#prompt-collections)

**توقف عن كتابة موجهات غامضة. أكثر من 200 موجه فيديو مُجرب لـ Sora وRunway وPika وKling.**

---

## المشكلة

**موجه سيء:**
> "قطة تمشي"

**النتيجة:** قطة عشوائية، مكان عشوائي، جودة عشوائية. حاول مرة أخرى. ومرة أخرى. ومرة أخرى.

---

## الحل

**موجه جيد:**
> "قطة برتقالية مخططة تمشي ببطء في زقاق مرصوف بالمبلطات تحت المطر عند الغسق. تتبعها الكاميرا من الخلف على ارتفاع القطة، عدسة 35 مم. إضاءة الشارع الدافئة تخلق ظلالاً طويلة. الأوحال تعكس النيون فوق. التقطت بكاميرا ARRI Alexa، درجة سينمائية، حبيبات فيلم."

**النتيجة:** بالضبط ما تصورته. من المحاولة الأولى.

---

## البدء السريع

1. **تصفح** مجموعات الموجهات أدناه
2. **انسخ** موجه يناسب مشروعك
3. **الصقه** في أداة الفيديو بالذكاء الاصطناعي
4. **عدّل** التفاصيل لتطابق رؤيتك
5. **ولّد** — واحصل على نتائج تعمل فعلاً

---

## ورقة مهندس الموجهات

### تشريح موجه الفيديو

```
[الموضوع] + [الحدث] + [البيئة] + [الكاميرا] + [الإضاءة] + [الأسلوب] + [الجودة]
```

### حركات الكاميرا الأساسية

| الحركة | مثال الموجه |
|----------|----------------|
| بان | Camera pans left to right |
| تيلت | Camera tilts up from ground to sky |
| دولي | Camera dollies toward the subject |
| تراكينغ | Camera tracks alongside the crane |
| كرين | Camera cranes up to 30ft overhead |
| درون | Aerial drone shot descending from 200ft |
| أوربيت | Camera orbits 360° around the subject |
| ستيديكام | Steadicam follows through the hallway |
| محمولة يدوياً | Slight handheld shake, documentary feel |
| ثابتة | Camera locked on tripod, no movement |

### الإضاءة الأساسية

| الإضاءة | مثال الموجه |
|----------|----------------|
| ساعة ذهبية | Warm light, long shadows, 30 min before sunset |
| ساعة زرقاء | Deep blue ambient, 20 min after sunset |
| إضاءة حافة | Strong backlight on subject edges |
| حجمية | Light shafts through fog/dust |
| غائمة | Soft, diffused, no hard shadows |
| نيون | Pink, blue, electric green reflections |
| ضوء شموع | Warm flickering, intimate shadows |
| كياروسكورو | Single hard light, deep shadows |

### نصائح احترافية

- **سمِّ العدسة**: "21mm wide angle" أو "200mm telephoto" — البؤرة البعدية تُغيّر كل شيء
- **سمِّ مصور سينمائي**: "In the style of Roger Deakins" يُعطي الذكاء الاصطناعي هدفاً واضحاً
- **صِف المزاج وليس المشهد فقط**: "A sense of quiet loneliness" > "empty room"
- **حدث واحد لكل موجه**: لا تربط 10 أحداث. ركّز على لحظة واحدة.
- **أدرج إشارات سلبية**: "No camera shake, no lens flare" — أخبره ما يجب تجنبه

---

## مجموعات الموجهات

### Sora (OpenAI)

| الفئة | الوصف | الموجهات | الملف |
|----------|-------------|---------|------|
| 🎬 لقطات سينمائية | لقطات تأسيس وتتبع وزوم دولي وعروض جوية وتسارع زمني | 25+ | [cinematic-shots.md](prompts/Sora/cinematic-shots.md) |
| 📖 مشاهد سردية | أفعال شخصيات وحوار ولحظات عاطفية وصراع/حل | 25+ | [narrative-scenes.md](prompts/Sora/narrative-scenes.md) |
| 🛍️ عرض منتجات | كشف المنتج وفتح صندوق ولقطات نمط حياة ولقطات قريبة | 20+ | [product-showcase.md](prompts/Sora/product-showcase.md) |

### Runway Gen-3

| الفئة | الوصف | الموجهات | الملف |
|----------|-------------|---------|------|
| 🎨 رسوم متحركة | رسوم مائية سائلة وتأثيرات جسيمات وتحويلات هندسية ونصوص | 25+ | [motion-graphics.md](prompts/Runway/motion-graphics.md) |
| 📸 مشاهد واقعية | أشخاص وحيوانات وبيئات وطقس ومركبات | 25+ | [realistic-scenes.md](prompts/Runway/realistic-scenes.md) |
| 🖌️ نقل أسلوب | انطباعي وسايبربانك وأفلام نوار وStudio Ghibli وWes Anderson | 20+ | [style-transfer.md](prompts/Runway/style-transfer.md) |

### Pika

| الفئة | الوصف | الموجهات | الملف |
|----------|-------------|---------|------|
| 📱 محتوى قصير | نمط TikTok/Reels/Shorts وميمز وحلقات مُرضية | 25+ | [short-form-content.md](prompts/Pika/short-form-content.md) |
| ✏️ أسلوب رسوم متحركة | رسوم 2D وعرض 3D وفن بيكسل وصلصال متحرك | 20+ | [animation-style.md](prompts/Pika/animation-style.md) |
| ✨ تأثيرات وتحولات | تشويه وانفجارات وتأثيرات طقس والتلاعب بالزمن | 20+ | [effects-and-transformations.md](prompts/Pika/effects-and-transformations.md) |

### Kling

| الفئة | الوصف | الموجهات | الملف |
|----------|-------------|---------|------|
| 🏃 محور إنساني | رياضة وطبخ وحرف وأداء | 25+ | [human-centric.md](prompts/Kling/human-centric.md) |
| 🌿 طبيعة وحيوانات | مناظر طبيعية وحياة برية وطقس ومواسم | 20+ | [nature-and-animals.md](prompts/Kling/nature-and-animals.md) |
| 🏯 جماليات صينية | رسم حبري ومعمار قتالي وفنون قتالية وشعر وثقافة تقليدية | 20+ | [chinese-aesthetics.md](prompts/Kling/chinese-aesthetics.md) |

### الأدلة

| الدليل | الوصف | الملف |
|-------|-------------|------|
| 📚 هندسة الموجهات | مفردات الكاميرا ومفردات الإضاءة ومرجع أفلام وأخطاء شائعة | [prompt-engineering.md](prompts/通用技巧/prompt-engineering.md) |
| 🎨 كلمات الأسلوب | أكثر من 200 كلمة أسلوبية منظمة حسب الفئة: أسلوب بصري ولون ونسيج ومزاج | [style-keywords.md](prompts/通用技巧/style-keywords.md) |

---

## مقارنة الأدوات

| الميزة | Sora | Runway Gen-3 | Pika | Kling |
|---------|------|-------------|------|-------|
| **الأفضل لـ** | سردي، سينمائي | رسوم متحركة، تجريدية | وسائل تواصل، رسوم متحركة | حركة إنسانية، طبيعة |
| **أقصى مدة** | 60s | 10s | 4s | 10s |
| **واقعية** | ★★★★★ | ★★★★ | ★★★ | ★★★★ |
| **رسوم متحركة** | ★★★ | ★★★★ | ★★★★★ | ★★★ |
| **حركة إنسانية** | ★★★★ | ★★★ | ★★★ | ★★★★★ |
| **نقل أسلوب** | ★★★ | ★★★★★ | ★★★★ | ★★★ |
| **نسب الأبعاد** | 16:9, 9:16, 1:1 | 16:9, 9:16, 1:1 | 16:9, 9:16, 1:1, 4:5 | 16:9, 9:16 |

### متى تستخدم أي أداة

- **Sora**: عندما تحتاج مشهداً كاملاً مع سرد وحركة كاميرا وجودة سينمائية
- **Runway**: عندما تحتاج رسوم متحركة أو بصرية تجريدية أو نقل أسلوب قوي
- **Pika**: عندما تحتاج محتوى قصير ومؤثر لوسائل التواصل الاجتماعي أو أساليب رسوم متحركة
- **Kling**: عندما يتمحور فيديوك حول حركة إنسانية أو طبخ أو رقص أو جماليات صينية

---

## المساهمة

نرحب بمساهمات الموجهات! راجع [CONTRIBUTING.md](CONTRIBUTING.md) للتنسيق والإرشادات.

**كيف تساهم:**
1. انسخ هذا المستودع
2. أضف موجهك المُختبر وفقاً [لتنسيق القالب](CONTRIBUTING.md#prompt-format)
3. قدّم طلب سحب
4. نراجع وندمج

---

## هيكل المشروع

```
awesome-video-prompts/
├── README.md                          ← أنت هنا
├── LICENSE                            ← رخصة MIT
├── CONTRIBUTING.md                    ← إرشادات المساهمة
├── CHANGELOG.md                       ← سجل الإصدارات
├── prompts/
│   ├── Sora/                          ← موجهات OpenAI Sora
│   │   ├── cinematic-shots.md         ← 25+ موجه سينمائي
│   │   ├── narrative-scenes.md        ← 25+ موجه سردي
│   │   └── product-showcase.md        ← 20+ موجه منتجات
│   ├── Runway/                        ← موجهات Runway Gen-3
│   │   ├── motion-graphics.md         ← 25+ موجه رسوم متحركة
│   │   ├── realistic-scenes.md        ← 25+ موجه واقعي
│   │   └── style-transfer.md          ← 20+ موجه نقل أسلوب
│   ├── Pika/                          ← موجهات Pika
│   │   ├── short-form-content.md      ← 25+ موجه وسائل تواصل
│   │   ├── animation-style.md         ← 20+ موجه رسوم متحركة
│   │   └── effects-and-transformations.md ← 20+ موجه تأثيرات
│   ├── Kling/                         ← موجهات Kling
│   │   ├── human-centric.md           ← 25+ موجه حركة إنسانية
│   │   ├── nature-and-animals.md      ← 20+ موجه طبيعة
│   │   └── chinese-aesthetics.md      ← 20+ موجه جماليات صينية
│   └── 通用技巧/                       ← تقنيات عامة
│       ├── prompt-engineering.md      ← دليل هندسة الموجهات الكامل
│       └── style-keywords.md          ← مرجع أكثر من 200 كلمة أسلوبية
└── .github/
    ├── workflows/ci.yml               ← خط أنابيب CI
    ├── ISSUE_TEMPLATE/                ← قوالب المشكلات
    └── pull_request_template.md       ← قالب طلب سحب
```

---

## انظر أيضًا

- [awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts) — مجموعة موجهات ChatGPT
- [awesome-prompts](https://github.com/DAGWorks-Inc/awesome-prompts) — مجموعة موجهات متعددة الوسائط
- [awesome-ai-tools](https://github.com/mahseema/awesome-ai-tools) — قائمة أدوات ذكاء اصطناعي منتقاة
- [awesome-generative-ai](https://github.com/steven2358/awesome-generative-ai) — موارد الذكاء الاصطناعي التوليدي
- [awesome-stable-diffusion](https://github.com/underctrlanatomy/awesome-stable-diffusion) — موارد Stable Diffusion
- [awesome-midjourney-prompts](https://github.com/willwulfken/awesome-midjourney-prompts) — مجموعة موجهات Midjourney

---

## الترخيص

مرخص بموجب MIT License — راجع ملف [LICENSE](LICENSE) للتفاصيل.

حقوق النشر (c) 2026 liangzhengtao
