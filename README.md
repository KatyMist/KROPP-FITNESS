<div align="center">

# 🏋️ KROPP Fitness

**Адаптивный лендинг фитнес-клуба**<br>
**A responsive landing page for a fitness club**

<a href="https://katymist.github.io/KROPP-FITNESS/"><img src="https://img.shields.io/badge/Открыть_сайт-KROPP_Fitness-1f3a2b?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=0f1f17" alt="Открыть сайт"></a>

<img src="https://skillicons.dev/icons?i=html,css,figma" alt="HTML5, CSS3, Figma">

<a href="#-русский"><img src="https://img.shields.io/badge/RU-Русский-1f3a2b?style=flat-square&labelColor=0f1f17" alt="Русский"></a>
<a href="#-english"><img src="https://img.shields.io/badge/EN-English-1f3a2b?style=flat-square&labelColor=0f1f17" alt="English"></a>

<br><br>

<img src="https://github.com/user-attachments/assets/16306dbb-549e-430c-ac70-3d0fc63de03d" alt="KROPP Fitness — главная страница" width="100%">

</div>

---

## 🇷🇺 Русский

### О проекте

**KROPP Fitness** — учебный проект по вёрстке: одностраничный сайт фитнес-клуба в тёмной теме с крупной типографикой. Вёрстка адаптирована под десктоп, планшет и смартфон.

> 📺 Сайт сделан по видеокурсу Александра Ламкова (Friendly Frontend): **[«Адаптивная верстка сайта с нуля для начинающих»](https://www.youtube.com/playlist?list=PL0MUAHwery4rqkzKF1mDBCIH_eZgjY6uN)**

### Секции страницы

| Секция | Класс |
|---|---|
| Шапка с навигацией | `.header` |
| Баннер с анонсом события | `.banner` |
| Мотивация | `.motivation` |
| Виды тренировок | `.training-types` |
| Видео и форма «Join us» | `.join-us` |
| Карта филиалов | `.location` |
| Галерея «Family» | `.family` |
| Калькулятор | `.calculate` |
| Подвал с подпиской и соцсетями | `.footer` |

### Что реализовано

- **Адаптивная вёрстка** — медиазапросы для 1920, 1280, 1024 и 767 px, «резиновые» размеры через `clamp()`
- **Сетки** — раскладка блоков на CSS Grid и Flexbox
- **CSS-переменные** — цвета и общие значения вынесены в `:root`
- **Декоративные заголовки** — крупный текст на фоне заголовка через `::before` / `::after` и `data-title`
- **Формы** — подписка, «Join us» и калькулятор
- **Собственные шрифты** — Heebo и Yantramanav в формате `woff2`
- **Оптимизация** — ленивая загрузка изображений (`loading="lazy"`), заданные `width` / `height`
- **Доступность** — скрытые заголовки (`visually-hidden`), `aria-label`, учёт `prefers-reduced-motion`

### Технологии

- **HTML5** — семантическая разметка (`header`, `main`, `section`, `footer`)
- **CSS3** — Grid, Flexbox, переменные, псевдоэлементы, медиазапросы
- **Figma** — работа с макетом

### Запуск

```bash
git clone https://github.com/KatyMist/KROPP-FITNESS.git
cd KROPP-FITNESS
open index.html
```

Или откройте **[демо](https://katymist.github.io/KROPP-FITNESS/)** на GitHub Pages.

---

## 🇬🇧 English

### About

**KROPP Fitness** is a front-end layout study project: a dark-themed single-page website for a fitness club with bold typography. The layout adapts to desktop, tablet and mobile screens.

> 📺 The website was built following a video course by Alexander Lamkov (Friendly Frontend): **["Responsive website layout from scratch for beginners"](https://www.youtube.com/playlist?list=PL0MUAHwery4rqkzKF1mDBCIH_eZgjY6uN)** (in Russian)

### Page sections

| Section | Class |
|---|---|
| Header with navigation | `.header` |
| Event banner | `.banner` |
| Motivation | `.motivation` |
| Types of training | `.training-types` |
| Video and "Join us" form | `.join-us` |
| Branches map | `.location` |
| "Family" gallery | `.family` |
| Calculator | `.calculate` |
| Footer with subscription and social links | `.footer` |

### Features

- **Responsive layout** — media queries for 1920, 1280, 1024 and 767 px, fluid sizes via `clamp()`
- **Layouts** — CSS Grid and Flexbox
- **CSS custom properties** — colors and shared values in `:root`
- **Decorative headings** — large backdrop text via `::before` / `::after` and `data-title`
- **Forms** — subscription, "Join us" and calculator
- **Custom fonts** — Heebo and Yantramanav in `woff2`
- **Optimization** — lazy-loaded images (`loading="lazy"`), explicit `width` / `height`
- **Accessibility** — visually hidden headings, `aria-label`, `prefers-reduced-motion` support

### Tech stack

- **HTML5** — semantic markup (`header`, `main`, `section`, `footer`)
- **CSS3** — Grid, Flexbox, custom properties, pseudo-elements, media queries
- **Figma** — working from a design mockup

### Getting started

```bash
git clone https://github.com/KatyMist/KROPP-FITNESS.git
cd KROPP-FITNESS
open index.html
```

Or open the **[live demo](https://katymist.github.io/KROPP-FITNESS/)** on GitHub Pages.

---

<div align="center">

Сделано с 💛 · Made with 💛 by [KatyMist](https://github.com/KatyMist)

</div>
