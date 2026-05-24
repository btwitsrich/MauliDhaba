# 🍛 ॥ माउली ढाबा ॥ Premium POS System 🧾

Welcome to the **Mauli Dhaba Premium Point of Sale (POS)** application—a lightning-fast, highly responsive, and visually stunning single-page restaurant management system. Designed custom-tailored for **॥ माउली ढाबा ॥** (Khalapur, Dist. Raigad · Since 1991).

This POS provides an elite interface for restaurant staff to manage active orders, apply customized cooking instructions, track daily session statistics, configure taxation/discounts, and instantly print or save beautiful invoices offline.

---

## ✨ Upgraded Premium Features

### 1. 👑 Elite Luxury Design
- **Visuals**: Deep black-cherry theme with glowing gold (`#D4AF37`) gradients and rich crimson accents.
- **Typography**: Dual-font design featuring **Cinzel** for authentic, high-end branding and **Plus Jakarta Sans** for crisp, fluid interface controls.
- **Glassmorphism**: Glassmorphic panels with smooth micro-animations, glowing status indicators, and hover-triggered scale transformations.

### 2. 📜 Past Invoices & Reprint Manager
- **Offline Storage**: Seamless integration with `localStorage` keeps a complete chronological log of all generated invoices locally.
- **History Drawer**: Access all past invoices in a beautiful sliding panel. Search or filter by **Bill Number**, **Table**, or **Date**.
- **Instant Reprint**: Click any past invoice to preview its original receipt, then re-download the PDF or print a hard copy instantly.

### 3. 🍳 Kitchen Cooking Notes (Prep Instructions)
- **Inline Customizer**: Clicking the note icon next to any active item opens a glowing input for custom preparation notes (e.g., *"Extra Spicy"*, *"No Butter"*, *"Double Cheese"*, *"Less Salt"*).
- **Kitchen Ready**: Notes display beautifully in the order panel and print clearly on the thermal receipt right beneath the item, ensuring the kitchen staff never misses a customer preference.

### 4. 📊 Session Revenue & Stats Dashboard
- **Live Metrics**: A sliding drawer displaying real-time analytics for the current active billing session:
  - **Total Revenue**: Cumulative gross sales (₹).
  - **Bill Count**: Total number of orders finalized.
  - **Average Ticket Size**: Average spending per table.
  - **Veg vs. Non-Veg Sales**: A beautiful glowing progress bar showcasing the sales ratio.
  - **Top Bestsellers**: Live leaderboard of the most ordered items.

### 5. ⚙️ Dynamic Bill Settings (GST & Discounts)
- **GST Toggle**: Easily apply or remove standard restaurant GST (CGST 2.5% + SGST 2.5%) instantly.
- **Discounts**: Apply custom discounts (from 0% to 50%) dynamically calculating in real time.
- **Smart Round-Off**: Automatic round-off of grand totals to the nearest Rupee for clean cash transactions.

### 6. 🖨️ Dual-Mode Receipt Output
- **Thermal Print**: Formatted with optimized media query CSS to feed directly to standard **80mm thermal receipt printers** in a single click.
- **Save PDF**: Downloads clean, vector-sharp **A4 PDF invoices** directly to the device using `html2pdf.js`.

### 🔊 Premium Audio-Visual Polish
- **Acoustic Feedback**: Generates organic mechanical click sounds using the browser's native **Web Audio API** when adding items or navigating screens (no external audio assets required).
- **Glow Pulse**: Menu cards emit a subtle golden ripple/pulse animation upon clicking, providing positive visual reinforcement.

---

## 🛠️ Technology Stack
- **Structure**: Semantic HTML5 elements.
- **Styling**: Modern CSS3 (Custom properties, Flexbox, CSS Grid, Glassmorphism, Print Media Queries).
- **Logic**: Vanilla ES6+ JavaScript.
- **PDF Generation**: `html2pdf.js` library.

---

## ⚡ Deployment & Running Guide

### 1. Run it Locally
Since the entire application is fully contained in a highly optimized single-page file, you can run it instantly without complex builds:
1. Double-click `index.html` to open it directly in any browser (Chrome, Edge, Safari, Firefox).
2. Start adding items, editing quantities, and saving PDFs!

### 2. Deploy Live on Netlify (For Free)
Netlify makes hosting static websites incredibly fast and free:
- **Option A (Connected Deployment - Recommended)**:
  1. Go to [Netlify](https://www.netlify.com/) and sign in using your GitHub account.
  2. Click **Add new site** -> **Import from an existing project**.
  3. Choose **GitHub** and select your `MauliDhaba` repository.
  4. Leave all build settings blank (since it's a static HTML file).
  5. Click **Deploy Site**. Netlify will build it and give you a live URL in 10 seconds! Any future push to GitHub will automatically update your live site.
  
- **Option B (Drag and Drop)**:
  1. Open [Netlify Drop](https://app.netlify.com/drop).
  2. Drag and drop your project folder containing `index.html` directly into the upload area.
  3. Your website is instantly live!

---

*Made with ❤️ for ॥ माउली ढाबा ॥*
