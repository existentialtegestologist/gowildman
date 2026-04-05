# ✈️ GoWild Flight Finder

> **v1.2.0 — "The Sea Turtle"**  
> *A premium, high-speed flight discovery tool for Frontier Airlines GoWild pass holders.*

GoWild Flight Finder is a high-performance, single-file web application designed to help Frontier Airlines GoWild pass holders find flights, check schedules, and navigate the "Rules of the Wild" without fighting the official Frontier website.

**[Live Demo](https://visualsynthesis.github.io/gowildsearch/)**

---

## ✨ Features

### 🔍 Precision Search
- **Hub-Specific Intelligence**: Deeply optimized for Frontier's primary hubs (**ATL, DEN, MCO**).
- **Instant Filtering**: Live stats for Direct, Domestic, International, or Connecting routes.
- **Smart Controls**: Swap origin/destination or clear selections with a single click.
- **Route Status**: Real-time detection of nonstop vs. connecting flights with visual badges.

### 📅 Booking Logic & Rules
- **Dynamic Booking Windows**: Implementing strict GoWild constraints (1-day for domestic, 10-day for international) with clear visual feedback.
- **Blackout Calendar**: Comprehensive 2025–2027 visual carousel highlighting blackout dates so you never waste a search.
- **"GoWild in 30 Seconds"**: A collapsible rules panel covering pricing, bags, seats, and the "no-show" policy.

### 💡 The Knowledge Base
- **137+ Fact-Checked Entries**: Curated advice on travel hacks, airport-specific guides, and baggage strategies.
- **GPT-Like Search**: Ask a question (e.g., "bag fees" or "ATL destinations") and get an instant, formatted response.
- **Airport Code Gravity**: Queries like "DEN intl flights" automatically prioritize relevant Denver results.

### 💎 Premium Interface
- **Modern Aesthetic**: Glassmorphism design system using Google's **Outfit** and **Inter** typography.
- **Responsive & Lightweight**: A single ~2,000 line HTML/JS file that works flawlessly on mobile and desktop.
- **Zero Dependencies**: Pure Vanilla JS, HTML, and CSS. No build step, no server, no lag.

---

## 🚀 Getting Started

Simply open `frontier/index.html` in any modern web browser.

1. **Select an Origin**: Type a code (e.g., "ATL") or pick from the dropdown.
2. **Set Dates**: Choose between **Exact** dates or **Flexible** mode (which shows the full booking window).
3. **Find Flights**: Results appear instantly with direct links to Frontier's booking page.
4. **Ask Questions**: Use the search bar to get help with policies or tips.

---

## 🛠️ Developmental Background

This project exists because browsing Frontier's site is slow and "discovery" is nearly impossible for pass holders. This tool solves the discovery gap by pre-calculating routes and rules.

- **Tech Stack**: HTML5, Vanilla JavaScript, CSS3 (Custom Variables/Glassmorphism).
- **Tracking**: Google Analytics (GA4) for feature-specific engagement tracking.
- **Update Frequency**: Routes and seasonal data are manually audited against public schedules.

---

## 🐆 Version History

- **v1.2.0 "The Sea Turtle"** (Current): Added swap/clear controls, modernized UI, and strict booking window constraints.
- **v1.1.0 "The Timber Wolf"**: Expanded to 137 FAQ entries, connecting flight support, and GA4 tracking.
- **v1.0.0 "The Flamingo"**: Initial release with flight discovery, flex dates, and blackout calendar.

---

*Disclaimer: This tool is not affiliated with, endorsed by, or sponsored by Frontier Airlines. It is a community-built utility for GoWild pass holders.*
