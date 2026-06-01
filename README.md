# Velocity Bike & Ski Service Reservation Page

A high-performance, mobile-responsive service landing page designed for **Velocity Servis / PRO CYCLING** in Bratislava, Slovakia. Engineered for seamless integration into enterprise content management systems (such as OrchidCore CMS), with a strong focus on Local SEO optimization, performant asset delivery, and cross-device accessibility.

---

## 🛠️ Technical Architecture & Features

### 1. Local SEO & Structured Data (JSON-LD)
* Implements a consolidated **Schema.org JSON-LD graph** (`BicycleStore` type) for both primary branches:
  * **Petržalka** (Medveďovej 1/A)
  * **Lamač** (Lamačská cesta 8/A)
* Configured with precise geo-coordinates, localized operating hours, unique `@id` anchors, and direct links to Google Maps. This ensures rich snippet rendering and optimal indexability in Google Maps and local search queries.

### 2. Search Engine Optimization (SEO) & Indexability
* **Invisible Image Wrapper**: Avoids the standard `display: none;` property (which can trigger search engine hidden content flags). Uses a modern clipping pattern (`clip: rect(0,0,0,0); position: absolute;`) to allow crawlers to read and index background image `alt` texts without impacting the visual layout.
* **Open Graph Protocol**: Structured `og:image` tags linking to high-quality banners to provide clean, engaging link previews in messaging applications (Viber, Telegram, WhatsApp) and social networks.

### 3. Dynamic Booking & Performance Optimization
* **Deferred Iframe Injection**: The reservation system dynamically embeds external booking widgets from branch subdomains (`servis.procycling.sk` and `servis.velocity.sk`) on demand. 
* By loading iframe `src` attributes only when the user opens the modal, the initial page load speed is significantly increased, boosting Core Web Vitals (specifically LCP and FID).

### 4. Interface & Layout Design
* Built using **Semantic HTML5** and customized **CSS Flexbox / Grid** configurations.
* Employs standard vanilla CSS variables and embedded layout blocks to ensure full compatibility inside restrictive CMS text blocks.
* Designed with micro-animations (e.g., hover offsets, interactive modal closures) to elevate the user experience.
* Multilingual support indicators for Slovak, English, German, and Ukrainian.

---

## 💻 Tech Stack
* **Markup**: HTML5 (Semantic elements)
* **Styling**: CSS3 (Vanilla, responsive layout grids, responsive design tokens)
* **Logic**: Vanilla JavaScript (dynamic modal control, keyboard listener for Esc, lazy iframe injection)
* **SEO**: JSON-LD Structured Data, Open Graph Protocol
