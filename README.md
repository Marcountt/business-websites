<div align="center">

# 🌐 Business Websites

**Seven mobile-first websites for small businesses — a coffee shop, a dental clinic, a coworking space, a clothing store, and three booking sites for the Belarusian market: a restaurant, a yoga studio and a barbershop.**

<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>

<!-- After enabling GitHub Pages, check that this link works -->
**[🔗 Live demos](https://marcountt.github.io/business-websites/)**

</div>

---

## 💡 About

Each site is a single HTML file with no frameworks and no build step: it loads fast, works on a 360 px phone screen without horizontal scrolling and can be hosted anywhere for free.

> **Demo projects.** The businesses are invented. Blocks marked **“To fill in”** are placeholders for a real client's reviews, payment and return terms.

| Site | Business | Highlights |
|---|---|---|
| [☕ Juniper Lane Roasters](coffee-roastery/) | Coffee shop | Catalog, cart, checkout, coffee quiz, EN / RU |
| [🦷 Willowbrook Dental Studio](dental-clinic/) | Dental clinic | Online booking with date and time slots, price list, EN / RU |
| [🧑‍💻 Sawtooth Works](coworking/) | Coworking space | Interactive floor plan, plans and prices, tour booking |
| [🧥 Skandic Shop](clothing-store/) | Clothing store | Catalog, filters, cart, order via Telegram |

### 🇧🇾 Booking sites for Belarus (RU / EN)

Three individually designed sites, each with its own layout and booking flow. Russian is the main language (written in the HTML, so search engines index it), with an EN switch.

| Site | Business | Highlights |
|---|---|---|
| [🔥 Ember & Oak](restaurant/) | Restaurant | Printed-style menu with tabs, slide-in table booking with time chips and guest counter |
| [🧘 Still Water](yoga-studio/) | Yoga studio | Weekly schedule grid, class-based booking dialog, review carousel, first-visit FAQ |
| [💈 Iron & Blade](barbershop/) | Barbershop | Barber profiles, 4-step booking wizard that respects each barber's working days |

Localized for Belarus:
- prices in **BYN**;
- **+375** phone validation with an input mask;
- Minsk addresses, **Viber / Telegram** and **Yandex Maps** links;
- payment by cash, cards (incl. Belkart) and **ERIP**;
- a required personal-data consent with a privacy policy template under **Law of the Republic of Belarus No. 99-Z** (marked for legal review).

The booking forms run in the browser and send nothing. They check the date, the 30-minute time slots within opening hours, the phone number and the consent, then show a confirmation.

## ✨ What every site has

- One clear headline and one main button on each screen
- Honest forms: data is sent as JSON to a configurable endpoint; if none is set, the visitor sees a clear message and an alternative (email, phone or Telegram) — nothing is lost
- Per-field form validation with clear error messages
- Delivery, payment, returns and contacts in one easy-to-find block
- Map links that open directions, Open Graph tags and a favicon
- No secrets in the browser code — API keys belong on the server

## 🚀 Run locally

Download the repository and open any `index.html` in a browser.

To receive real orders, set `CONFIG.formEndpoint` at the top of the page script to your server or form-service URL.

---

<div align="center">

**Need a website like this for your business?**

<a href="https://t.me/Macount"><img src="https://img.shields.io/badge/Telegram-@Macount-2AABEE?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/></a>
<a href="mailto:marcountt@gmail.com"><img src="https://img.shields.io/badge/Email-marcountt@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

© 2026 Mark. All rights reserved.

</div>
