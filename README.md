<div align="center">

# 🚴‍♂️ Velocity Servis

### Professional **bicycle & e-bike service** landing page · Bratislava

<br>

![Velocity Servis](https://www.procycling.sk/uploads/image_bank/cis-9314.jpg)

<br>

[![Live Site](https://img.shields.io/badge/Live-servis.velocity.sk-111111?style=for-the-badge&logo=googlechrome&logoColor=white)](https://servis.procycling.sk/sekcia/servis-bicyklov/)
&nbsp;
![Version](https://img.shields.io/badge/version-1.0.0-8E8E8E?style=for-the-badge)

<br>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SEO](https://img.shields.io/badge/Schema.org_JSON--LD-E37400?style=flat-square&logo=google&logoColor=white)

<br>

🇬🇧 **English** &nbsp;|&nbsp; [🇺🇦 Українською (Scroll down ↓)](#-українською)

</div>

---

## 🌟 About the Project

**Velocity Servis** is a highly optimized landing page designed to streamline online booking for bicycle and e-bike repairs in Bratislava. The page integrates the reservation systems of two main branches (**Velocity Servis Petržalka** and **Velocity Servis WESTEND**).

The primary goal is to provide a fast, user-friendly, and SEO-optimized entry point for customers to book their service appointments while learning about the offered services (from basic maintenance to suspension service, e-bike diagnostics, and carbon repair).

> 📍 **Locations:** Medveďovej 1/A (Petržalka) & Lamačská cesta 3B (WESTEND) &nbsp;·&nbsp; 💶 **Pricing:** From €60 / hour

---

## 📚 Table of Contents

- [Tech Stack](#-tech-stack)
- [Architecture Philosophy](#-architecture-philosophy)
- [Key Features & Nuances](#-key-features--nuances)
- [Page Structure](#-page-structure)
- [Project Layout](#-project-layout)
- [Deployment](#-deployment)

---

## 🛠 Tech Stack

| Layer | Technology | Notes |
|-------|-----------|-------|
| **Markup** | HTML5 | Semantic structure with inline styles for portability |
| **Styling** | Vanilla CSS | Flexbox, Grid, and responsive design directly in HTML |
| **Logic** | Vanilla JavaScript (ES6+) | Lightweight modal and iframe handling, zero dependencies |
| **SEO** | JSON-LD | Rich Snippets for Local Business (BicycleStore) |

---

## 🧠 Architecture Philosophy

This project is built as a highly portable and fast-loading single component that can be easily integrated into any CMS or e-commerce platform.

- ⚡ **Instant Loading:** No external CSS files or JS libraries are required. Everything is self-contained.
- 🪶 **Lazy-loaded Iframes:** The heavy reservation system calendars are only loaded when the user opens the modal, saving significant bandwidth and drastically improving the initial page load speed.
- 🔍 **SEO First:** Comprehensive Schema.org data ensures that both branch locations appear prominently in Google Local Search and Maps.

---

## 🚀 Key Features & Nuances

### 1. 📅 Dynamic Reservation Modal
- A clean, full-screen modal interface handles the booking process without redirecting the user.
- Contains step-by-step instructions and important warnings before loading the booking calendars.
- Embeds two separate reservation iframes corresponding to the two physical branches.

### 2. ⚡ Performance Optimization
- The `src` attributes of the booking iframes are initially empty (stored in `data-src`).
- Vanilla JS sets the `src` attributes only upon opening the modal, implementing a lightweight "lazy load".

### 3. 🔍 Local SEO & Rich Snippets
- Detailed `BicycleStore` JSON-LD markup for both branches.
- Includes exact GPS coordinates, opening hours, contact details, and price ranges.
- Proper use of `og:image` for social sharing.

### 4. 📱 Responsive Design
- Utilizes CSS Flexbox and Grid with smart `minmax` wrapping to ensure the layout looks perfect on everything from ultra-wide desktops to narrow mobile screens.

---

## 🗺 Page Structure

| Section | Purpose |
|--------|---------|
| **Hero** | Brand presentation & primary CTA to book |
| **Services (Naše služby)** | Overview of repairs, e-bike service, suspension, washing, and carbon repair |
| **Pricing (Cenník)** | Transparent hourly rates and minimum fees |
| **Process (Ako prebieha servis)** | Simple 3-step guide: Book -> Service -> Pick up |
| **Locations (Kde nás nájdete)** | Addresses, maps, and direct links for Petržalka and WESTEND |
| **Winter Service** | Banner linking to the seasonal ski & snowboard service |
| **Modal Window** | The actual booking interface with iframes |

---

## 📂 Project Layout

```
Rezervation-system/
├── index.html          # 🇸🇰 Main landing page & booking widget
├── README.md           # 📖 Project documentation (this file)
└── README priklad.md   # 📝 Template example (for reference)
```

---

## 🚀 Deployment

Because the project consists of a single `index.html` file with inline assets, deployment is incredibly simple:

1. Upload `index.html` to any web server or integrate the HTML code into an existing CMS page (like WordPress or PrestaShop).
2. Ensure the relative paths to images (e.g., `/uploads/image_bank/...`) point to the correct assets on your server, or update them to absolute URLs.

---

<br>

<div align="center">

<h2 id="-українською">🇺🇦 Українською</h2>

[🇬🇧 English (Scroll up ↑)](#️-velocity-servis)

</div>

---

## 🌟 Про Проєкт

**Velocity Servis** — це максимально оптимізована цільова сторінка (лендінг), створена для зручного онлайн-бронювання ремонту велосипедів та електровелосипедів у Братиславі. Сторінка об'єднує системи бронювання двох головних філій мережі (**Velocity Servis Petržalka** та **Velocity Servis WESTEND**).

Головна мета — надати клієнтам швидкий, зручний та SEO-оптимізований інструмент для запису на сервіс, а також ознайомити їх з переліком послуг (від базового обслуговування до ремонту підвіски, діагностики e-bikes та ремонту карбону).

> 📍 **Локації:** Medveďovej 1/A (Petržalka) та Lamačská cesta 3B (WESTEND) &nbsp;·&nbsp; 💶 **Ціни:** Від €60 / год

---

## 🛠 Технологічний Стек

| Шар | Технологія | Нюанс |
|-----|-----------|-------|
| **Розмітка** | HTML5 | Семантична структура з inline-стилями для легкої інтеграції |
| **Стилі** | Vanilla CSS | Flexbox, Grid та адаптивність прописані безпосередньо в HTML |
| **Логіка** | Vanilla JavaScript (ES6+) | Легковагове модальне вікно та обробка iframe, нуль залежностей |
| **SEO** | JSON-LD | Мікророзмітка для локального бізнесу (BicycleStore) |

---

## 🧠 Філософія Архітектури

Цей проєкт побудовано як максимально портативний та швидкий компонент, який можна легко вбудувати в будь-яку CMS або e-commerce платформу.

- ⚡ **Миттєве завантаження:** Не потрібні зовнішні CSS-файли чи JS-бібліотеки. Все міститься в одному файлі.
- 🪶 **Відкладене завантаження (Lazy-load) Iframe:** Важкі календарі систем бронювання завантажуються лише після відкриття модального вікна. Це економить трафік і кардинально пришвидшує первинне завантаження сторінки.
- 🔍 **SEO на першому місці:** Вичерпна розмітка Schema.org гарантує, що обидві філії будуть правильно відображатися в локальному пошуку Google та на картах.

---

## 🚀 Ключові Особливості та Нюанси

### 1. 📅 Динамічне модальне вікно бронювання
- Чистий повноекранний інтерфейс дозволяє забронювати час без переходу на інші сторінки.
- Містить покрокову інструкцію та важливі попередження перед завантаженням календарів.
- Вбудовує два окремі iframe для двох фізичних точок обслуговування.

### 2. ⚡ Оптимізація продуктивності
- Атрибути `src` для iframe з календарями спочатку порожні (URL зберігається в `data-src`).
- Vanilla JS встановлює атрибути `src` лише при відкритті модального вікна (простий lazy-load).

### 3. 🔍 Локальне SEO та Rich Snippets
- Детальна JSON-LD розмітка типу `BicycleStore` для обох філій.
- Включає точні GPS-координати, години роботи, контакти та ціновий діапазон.
- Правильне використання метатегів `og:image` для шерингу в соцмережах.

### 4. 📱 Адаптивний дизайн
- Використовуються CSS Flexbox та Grid з розумним перенесенням блоків (`minmax`), що робить сторінку ідеальною як на широких моніторах, так і на смартфонах.

---

## 🗺 Структура Сторінки

| Секція | Призначення |
|--------|-------------|
| **Hero (Шапка)** | Презентація бренду та головний заклик до дії (CTA) |
| **Naše služby (Послуги)** | Огляд ремонтів, сервісу e-bike, мийки, підвіски та карбону |
| **Cenník (Ціни)** | Прозорі погодинні ставки та мінімальні тарифи |
| **Ako prebieha servis (Процес)** | Прості 3 кроки: Бронювання -> Сервіс -> Отримання |
| **Kde nás nájdete (Локації)** | Адреси, карти та прямі посилання на філії |
| **Winter Service (Зимовий сервіс)**| Банер із переходом на сезонний сервіс лиж і сноубордів |
| **Modal Window (Модальне вікно)**| Сам інтерфейс бронювання з iframe |

---

## 📂 Структура Проєкту

```
Rezervation-system/
├── index.html          # 🇸🇰 Головна сторінка та віджет бронювання
├── README.md           # 📖 Документація проєкту (цей файл)
└── README priklad.md   # 📝 Приклад оформлення
```

---

## 🚀 Розгортання

Оскільки проєкт складається з єдиного файлу `index.html` із вбудованими ресурсами, розгортання є надзвичайно простим:

1. Завантажте `index.html` на будь-який вебсервер або просто вставте цей HTML-код у відповідну сторінку вашої CMS (наприклад, WordPress або PrestaShop).
2. Переконайтеся, що відносні шляхи до зображень (наприклад, `/uploads/image_bank/...`) ведуть на правильні файли на вашому сервері, або змініть їх на абсолютні URL-адреси.

---

<br>

<div align="center">

**Made for Velocity · Bratislava**

</div>
