<div align="center">

<h1 align="center">KROPP FITNESS</h1>

<p align="center">
  <b>Адаптивный лендинг фитнес-клуба</b><br>
  <b>A responsive landing page for a fitness club</b>
</p>

<p align="center">
  <a href="https://katymist.github.io/KROPP-FITNESS/"><img src="https://img.shields.io/badge/Открыть_сайт-KROPP_Fitness-1f3a2b?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=0f1f17" alt="Открыть сайт"></a>
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,figma,github" alt="HTML5, CSS3, Figma, GitHub">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/RU-Русский-1f3a2b?style=flat-square&labelColor=0f1f17" alt="Русский">
  <img src="https://img.shields.io/badge/EN-English-1f3a2b?style=flat-square&labelColor=0f1f17" alt="English">
</p>

<img width="2880" height="1600" alt="KROPP Fitness — скриншот сайта" src="https://github.com/user-attachments/assets/4789b2fa-1e88-441c-a7fe-c0ab2d576f39" />

</div>

> [!NOTE]
> **О проекте.** Учебная вёрстка по видеокурсу Александра Ламкова (Friendly Frontend) [«Адаптивная верстка сайта с нуля для начинающих»](https://www.youtube.com/playlist?list=PL0MUAHwery4rqkzKF1mDBCIH_eZgjY6uN). Макет и дизайн принадлежат автору курса, вёрстку и адаптив я повторяла вслед за уроками.
>
> **About the project.** A layout study based on Alexander Lamkov's (Friendly Frontend) video course ["Responsive website layout from scratch for beginners"](https://www.youtube.com/playlist?list=PL0MUAHwery4rqkzKF1mDBCIH_eZgjY6uN) (in Russian). The mockup and design belong to the course author; I reproduced the markup and responsive layout by following the lessons.

---

## О сайте · About

Одностраничный лендинг фитнес-клуба в тёмной теме с крупной типографикой. Вёрстка адаптирована под десктоп, планшет и смартфон.

A single-page landing for a fitness club, with a dark theme and bold typography. The layout adapts to desktop, tablet and mobile screens.

| Секция · Section | Что в ней · Content |
|---|---|
| `.header` | Логотип и навигация<br>Logo and navigation |
| `.banner` | Анонс события<br>Event announcement |
| `.motivation` | Мотивационный блок<br>Motivation block |
| `.training-types` | Виды тренировок<br>Types of training |
| `.join-us` | Видео и форма «Join us»<br>Video and "Join us" form |
| `.location` | Карта филиалов<br>Branches map |
| `.family` | Галерея «Family»<br>"Family" gallery |
| `.calculate` | Калькулятор<br>Calculator |
| `.footer` | Подписка и соцсети<br>Subscription and social links |

## Возможности · Features

| Русский | English |
|---|---|
| Адаптив: 1920, 1280, 1024 и 767 px | Responsive: 1920, 1280, 1024 and 767 px |
| «Резиновые» размеры через `clamp()` | Fluid sizes via `clamp()` |
| Раскладка на CSS Grid и Flexbox | CSS Grid and Flexbox layouts |
| CSS-переменные в `:root` | CSS custom properties in `:root` |
| Декоративные заголовки через `::before` / `::after` и `data-title` | Decorative backdrop headings via `::before` / `::after` and `data-title` |
| Формы: подписка, «Join us», калькулятор | Forms: subscription, "Join us", calculator |
| Ленивая загрузка изображений, заданные `width` / `height` | Lazy-loaded images, explicit `width` / `height` |
| Скрытые заголовки и `aria-label` | Visually hidden headings and `aria-label` |
| Учёт `prefers-reduced-motion` | `prefers-reduced-motion` support |

## Технологии · Tech Stack

| | |
|---|---|
| **Разметка · Markup** | HTML5 (`header`, `main`, `section`, `footer`) |
| **Стили · Styles** | CSS3: Grid, Flexbox, custom properties, pseudo-elements, media queries |
| **Шрифты · Fonts** | Heebo, Yantramanav (`woff2`) |
| **Макет · Design** | Figma |
| **Хостинг · Hosting** | GitHub Pages |

## Структура проекта · Project Structure

```
KROPP-FITNESS/
├── index.html
├── styles.css
├── fonts/
├── icons/
└── images/
```

## Запуск локально · Running Locally

```bash
git clone https://github.com/KatyMist/KROPP-FITNESS.git
cd KROPP-FITNESS
open index.html
```

Сборка не нужна, достаточно открыть `index.html` в браузере.<br>
No build step needed, just open `index.html` in a browser.

## Автор · Author

**Екатерина Туманова · Ekaterina Tumanova** — Frontend Developer & Designer

[Портфолио · Portfolio](https://katymist.github.io/Portfolio/) · [GitHub](https://github.com/KatyMist)

---

<div align="center">
<sub>Учебный проект по курсу Friendly Frontend · A learning project based on the Friendly Frontend course<br>© Александр Ламков — макет и дизайн · © Alexander Lamkov — mockup and design</sub>
</div>
