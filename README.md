# ThaiLifeCost 🇹🇭

**The smartest way to compare the cost of living across Thailand.**

A modern, interactive web application that helps you understand and compare the real cost of living in all 77 provinces of Thailand — plus major cities and tourist hotspots.

<img width="2200" height="1197" alt="Capture d’écran 2026-04-12 à 11 44 04" src="https://github.com/user-attachments/assets/a700f36a-965a-4dfc-a8c7-7c9d1a64e9e1" />

### Features

- **Interactive Dark Map** – Visualize the cost of living with a beautiful choropleth map (green = affordable → red = expensive)
- **77 Provinces + Major Cities** – Toggle between official provinces and popular cities (Bangkok, Phuket, Chiang Mai, Pattaya, Hua Hin, Koh Samui)
- **Smart Province Highlighting** – Click on Pattaya → Chonburi lights up, Hua Hin → Prachuap Khiri Khan, etc.
- **3 Lifestyle Modes**
  - Thai Style (local & cheap)
  - Farang Average (standard expat)
  - Hi-So (luxury lifestyle)
- **Single / Couple / Family** – Costs automatically scale based on household size
- **Seasonal Pricing** – Low Season vs High Season for major tourist cities
- **Realistic Monthly Estimates** – Especially for Transport and Meals (no more misleading single-trip prices)
- **Fully Responsive** – Works perfectly on mobile and desktop

### Data Sources

- Primary data from **Numbeo** (crowdsourced and regularly updated)
- Official Thai government indices for regional validation
- Realistic seasonal adjustments for tourist areas

### Tech Stack

- **Next.js 15** (App Router)
- **TypeScript**
- **Tailwind CSS + shadcn/ui**
- **React Leaflet** (interactive map with GeoJSON)
- **Recharts** for visualizations

### Live Demo

[View ThaiLifeCost](https://praphakan.github.io/ThaiLifeCost/)  

### How to Run Locally

```bash
git clone https://github.com/yourusername/ThaiLifeCost.git
cd ThaiLifeCost
npm install
npm run dev
Open http://localhost:3000
Project Goals

Help digital nomads, retirees, and travelers make informed decisions about where to live in Thailand
Provide transparent and realistic cost breakdowns
Combine official data with real expat experience

Contributing
Feel free to open issues or submit pull requests.
Especially welcome:

More accurate local price data
Additional provinces or cities
Translation improvements

Disclaimer
All prices are averages and should be used as estimates only.
Real cost of living can vary significantly depending on your lifestyle, neighborhood, and personal choices.

Made with ❤️ for anyone dreaming of living in Thailand
