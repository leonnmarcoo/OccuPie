<div align="center">
  <img src="Resources/Navigation/Logo.png" alt="OccuPie logo: a blue pie next to the word OCCUPIE" width="400"/>
</div>

> **Ohhhh-ccupancy demand just got predictable.** 🥧  
> The landing page for OccuPie, a condo rental insights concept that estimates pricing and occupancy demand.

---

## 🥧 What Is This Repo?

This repo holds the **landing page** for OccuPie. It's a static, single-page site that introduces the idea, shows a first look at the UI, and meets the team. There's no app or model behind it here.

The data and regression work lives in **[condo_price_prediction](https://github.com/leonnmarcoo/condo_price_prediction)**.

---

## ✨ What's on the Page

- 🏙️ **Hero**: the pitch, with fade-up animations on load
- 🍽️ **What We Cooked**: three feature cards ("Find Your Slice on the Map", "Slice the Numbers with AI", and "A Bigger Bite with LLMs")
- 🧰 **Tech stack strip**: a scrolling row of the tools behind the project
- 👀 **Have a Taste of the UI**: three design previews
- 👩‍🍳 **Meet the Pie-oneers**: the team, with links to their GitHub profiles

Sections animate in as you scroll, powered by a small `IntersectionObserver` script.

---

## 📸 UI Previews

These are design mockups from the page's preview section, so the placeholder values are intentional.

<div align="center">
  <img src="Resources/Overview/UI%20Preview-3.png" alt="OccuPie landing page hero: Ohhhh-ccupancy demand just got predictable, above a city skyline" width="700"/>
</div>

<div align="center">
  <img src="Resources/Overview/UI%20Preview-2.png" alt="OccuPie app mockup: a property details form beside a map of Metro Manila" width="700"/>
</div>

<div align="center">
  <img src="Resources/Overview/UI%20Preview-1.png" alt="OccuPie results mockup: estimated monthly rental, occupancy demand, and nearby establishment counts" width="700"/>
</div>

---

## 🍳 Still in the Oven

The page describes where OccuPie is headed, so here's where each piece stands today:

| On the page | Where it stands |
| --- | --- |
| Condo pricing with Multiple Linear Regression | ✅ Trained in a notebook in [condo_price_prediction](https://github.com/leonnmarcoo/condo_price_prediction), not connected to any UI |
| Occupancy demand with Logistic Regression | 🚧 Demand labels exist, but the model hasn't been built yet |
| Map and nearby establishments | 🎨 Design mockup only |
| LLM explanations of the results | 🎨 Design mockup only |

The page itself has a few loose ends too: the **Try OccuPie** button doesn't link anywhere yet, the developer roles and bios are placeholder text, and the footer's social links are empty.

---

## 🛠️ Tech Stack

| | |
| --- | --- |
| **Markup and styling** | HTML and CSS |
| **Animation** | Vanilla JavaScript (`IntersectionObserver`) |
| **Typeface** | Poppins, from Google Fonts |

No frameworks, no build step, no dependencies.

---

## 🚀 How to Run

```bash
git clone https://github.com/leonnmarcoo/OccuPie.git
cd OccuPie
open index.html
```

On Windows or Linux, just double-click `index.html`. Prefer a local server? Run this, then visit <http://localhost:8000>:

```bash
python3 -m http.server 8000
```

---

## 👩‍🍳 Meet the Pie-oneers

- [Kurt Justine Almadrones](https://github.com/justjstine)
- [Lance Kenneth Dela Paz](https://github.com/lowvey)
- [Leon Marco Devela](https://github.com/leonnmarcoo)
- [Rae Paulos](https://github.com/rpaulos)

---

<div align="center">
  Thanks for taking a slice of OccuPie! 🥧
</div>
