# Velocity Bike Service Booking Portal

A high-performance, SEO-optimized service landing page interface designed for **Velocity Servis / PRO CYCLING** in Bratislava, Slovakia. Engineered for seamless integration into enterprise content management systems (such as OrchidCore CMS), with a strong focus on Local SEO, web performance, and mobile accessibility.

---

## 🛠️ Technical Highlights & Features

### 1. Advanced Local SEO & Structured Data (JSON-LD)
* **Schema.org Integration**: Implements a structured **JSON-LD graph** (`BicycleStore` schema) covering both primary service centers:
  * **Petržalka Branch** (Medveďovej 1/A)
  * **Lamač Branch** (Lamačská cesta 8/A)
* **Rich Snippets Optimization**: Configured with precise coordinates, telephone endpoints, localized operating hours, prices, and same-as social profile anchors to maximize indexing quality in Google Maps and local search engine queries.
* **Invisible Image Wrapper**: Uses modern CSS clipping (`clip: rect(0,0,0,0); position: absolute;`) instead of `display: none` to ensure search engine crawler bots read and index key background image alt-texts without layout shifting or triggering hidden content flags.

### 2. Performance-Driven Iframe Integration
* **Deferred Lazy Loading**: external booking calendars from branch subdomains (`servis.procycling.sk` and `servis.velocity.sk`) are injected dynamically only when the booking modal is triggered.
* **Web Vitals Optimization**: Prevents heavy widget files from slowing down the initial page render, boosting LCP (Largest Contentful Paint) and TBT (Total Blocking Time) scores.

### 3. Responsive UX & Viewport Management
* **Mobile Viewport Fix**: Built a custom modal viewport wrapper targeting mobile screens (`max-width: 991px`) using dynamic viewport heights (`100dvh` / `height: 100%`) and top-aligned spacing. This guarantees the modal header and close target never slide under mobile browser chrome or native address bars (e.g. on iOS Safari).
* **Maximized Calendar Workspace**: Dynamically strips down horizontal paddings, card borders, and shadows on small viewports so the iframe booking calendars stretch to 100% of the mobile screen width, giving users maximum interactable space.
* **Accessibility Standards**: Enhanced touch-target sizing for closing targets (`44px` minimum) and isolated hover transition states to `@media (hover: hover)` to eliminate sticky touch highlighting on handheld devices.

---

## 💻 Tech Stack

* **Markup**: Semantic HTML5
* **Styles**: Modern CSS3 (Grid Layouts, Flexbox, Dynamic Viewport Units, Media Queries)
* **Scripting**: Vanilla ES6 JavaScript (State controllers, lazy loaders, keyboard event listeners)
* **SEO**: JSON-LD Microdata schema graphs, Open Graph metadata profiles
