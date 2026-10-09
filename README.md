# Driftless Dog Co LLC — Official Website

> Gentle, patient, and fear-free inspired canine grooming salon based in Sparta, Wisconsin (Monroe County).

[![GitHub Pages](https://img.shields.io/badge/Hosted_with-GitHub_Pages-395e40?style=for-the-badge&logo=github)](https://pages.github.com/)
[![Built With](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Icons](https://img.shields.io/badge/Lucide_Icons-f59e0b?style=for-the-badge)](https://lucide.dev/)

---

## 🐾 About The Project

This repository hosts the official single-page responsive website for **Driftless Dog Co LLC**. Built without bulky dependencies or build tools, the entire site is self-contained in `index.html` and ready for instant deployment via **GitHub Pages**.

### Key Features
- **Dynamic Price & Duration Estimator**: Live quotes based on dog size/weight, service package, and add-on spa treatments.
- **Booking Request Modal**: Automatically calculates estimates, generates reservation tracking codes, and provides print-ready check-in checklists.
- **Interactive Coat Care Advisor**: Provides custom salon frequency recommendations and Wisconsin seasonal coat tips for curly/doodle, double-coated, smooth, and wire-haired breeds.
- **Local Sparta, WI Branding**: Optimized for Monroe County pet owners, highlighting 1-on-1 care, walk-in nail trims, and rabies policy details.
- **Filterable Before & After Gallery**: Interactive showcase with real customer testimonials.
- **Accordion FAQs**: Clear guidance on dog health, drop-off, matting, and behavioral handling.

---

## 📁 Repository Structure

```text
driftless-dog-co/
├── index.html     # Complete production website (HTML5, Tailwind, JS, Lucide)
└── README.md      # Documentation and deployment instructions
```

---

## 🚀 Quick Setup & Deployment to GitHub Pages

### 1. Clone or Download This Repository
```bash
git clone https://github.com/YOUR-USERNAME/driftless-dog-co.git
cd driftless-dog-co
```

### 2. Local Preview
Because this site has no build step, you can view it directly:
- Double-click `index.html` in your file explorer to open it in your web browser.
- Or use VS Code's **Live Server** extension.

### 3. Deploy to GitHub Pages (Free Hosting)
1. Push `index.html` and `README.md` to your `main` branch:
   ```bash
   git add .
   git commit -m "Launch Driftless Dog Co website"
   git push origin main
   ```
2. On GitHub, navigate to your repository **Settings**.
3. Under the **Code and automation** section on the left, click **Pages**.
4. Set **Source** to `Deploy from a branch`.
5. Under **Branch**, select `main` and keep the directory set to `/(root)`.
6. Click **Save**.

Your website will be live in about 60 seconds at:  
`https://YOUR-USERNAME.github.io/driftless-dog-co/`

---

## 🛠️ Customization Guide

All styling and logic are centralized in `index.html`:

| Section | Location in `index.html` | Notes |
| :--- | :--- | :--- |
| **Phone & Address** | Topbar & `#contact` | Update `(608) 269-DOGS` and `118 N Water St` |
| **Pricing & Services** | `#booking-estimator` & `state` object | Adjust base prices in the JavaScript object |
| **Colors** | `<script>` Tailwind config | Modify `driftless`, `bark`, and `honey` palettes |
| **Form Endpoint** | `#contactForm` | Point `action=""` to Formspree or EmailJS if desired |

---

## 📍 Business Information
* **Company:** Driftless Dog Co LLC
* **Location:** 118 N Water St, Sparta, WI 54656
* **County:** Monroe County, Wisconsin
* **Services:** Full breed cuts, Bath & Brush, Undercoat De-shedding, Walk-in Nail Trims

---

*Licensed under the [MIT License](LICENSE).*