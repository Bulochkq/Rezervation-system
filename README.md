# Velocity Bike & Ski Service Reservation Page

A custom, fully responsive service landing page built with HTML and inline CSS, designed for integration into the **OrchidCore CMS** for **Velocity Servis / PRO CYCLING** in Bratislava, Slovakia.

This repository contains the landing page code optimized for Local SEO, indexing, and mobile responsiveness.

---

## 🛠️ Features

1. **Local SEO & Structured Data**:
   * Pre-configured **JSON-LD Schema** (`BicycleStore` graph) for both branches: **Petržalka** (Medveďovej 1/A) and **Lamač** (Lamačská cesta 8/A).
   * Schema contains precise geotags, contact numbers, and opening hours for optimal local search rendering (Google Maps).
2. **Open Graph Integration**:
   * Pre-configured `og:image` meta tag pointing to the absolute header banner URL to ensure beautiful link previews in messengers (Viber, Telegram, WhatsApp) and social networks.
3. **Optimized Asset Indexing**:
   * Invisible `<img>` tags wrapper with visually hidden CSS utility attributes replacing standard `display: none;`. This ensures background image `alt` texts are indexed by Googlebot without triggering hidden content flags.
4. **Interactive Online Booking**:
   * Responsive modal reservation popup window.
   * Dynamically loads separate online booking forms for Lamač and Petržalka branches from external subdomains (`servis.procycling.sk` & `servis.velocity.sk`) only when opened, improving initial page load time.
5. **Modern Layout & Design**:
   * Clean red-white brand colors matching PRO CYCLING identity.
   * Built using custom Flexbox and CSS Grid layout blocks.
   * 100% mobile-friendly and responsive.

---

## 📁 Repository Structure

* `index.html`: The source code containing structured data, service catalog, price lists, guides, map locations, and modal reservation frames. This is the exact code block to paste into your CMS text/HTML editor.
* `README.md`: This file.

---

## 🚀 How to Integrate into CMS (OrchidCore / Shoptet / WordPress)

To deploy or update this page on your e-shop website:

1. Open `index.html` and copy its entire content.
2. Log in to your e-shop administration panel.
3. Navigate to the **Web Pages / Sections** manager and select the **Servis** page.
4. Toggle the text editor to **HTML view (source code)**.
5. Paste the copied code and save the changes.

### ⚠️ Critical SEO Settings inside CMS Admin Panel
Make sure to configure the page settings in your CMS panel as follows to avoid SEO bugs:
* **Page Title**: `Servis bicyklov Bratislava – profesionálny cykloservis pre každý typ bicykla`
* **Meta Description**: `Profesionálny servis bicyklov a elektrobicyklov všetkých značiek v Bratislave. Rýchla diagnostika, výhodné balíčky a spoľahlivý zákaznícky servis.`
* **og:image**: Upload or select the image `https://www.procycling.sk/uploads/image_bank/img-4332.jpg`.
