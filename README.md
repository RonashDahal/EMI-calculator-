# 📱 Mobile EMI Calculator

> A lightweight, pixel-perfect, and mobile-first EMI (Equated Monthly Installment) calculator designed for mobile retail financing in Nepalese Currency (Rs.).

[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](https://opensource.org/licenses/MIT)
[![Language: HTML/CSS/JS](https://img.shields.io/badge/Language-Pure%20Vanilla-orange.svg)]()
[![Platform: Mobile/Webview](https://img.shields.io/badge/Platform-Mobile%20%7C%20Webview-blue.svg)]()

---

## ✨ Features

* 📱 **True Mobile-First UI** – Optimized touch targets, zero-scrolling viewports, and native mobile scaling.
* 🔢 **Percentage-Based Down Payment** – Automatically updates the remaining financed loan balance on the fly when down payment % is tweaked.
* 🇳🇵 **Nepalese Currency Formatting** – Outputs all metrics using the South Asian standard (`en-IN` Lakh/Crore grouping system) prefixed with `Rs.`.
* ⚡ **Instant Reactive Computations** – Updates calculated fields in real-time as you type or pick a tenure option. No reload required.
* 🕊️ **Zero Dependencies** – Written in single-file pure Vanilla HTML5, CSS3, and modern JS. No frameworks or packaging engines required.

---

## 🛠️ Visual Showcase & Layout

The UI uses a minimalist card layout with a high-contrast emerald brand indicator theme:

* **Background**: Clean Minimalist Slate (`#f4f6f9`)
* **Card Surface**: Pure White (`#ffffff`)
* **Accents & Highlights**: Active Emerald (`#059669`)
* **Form Optimization**: Implements `-webkit-appearance: none` for uniform, border-radius clipping inside iOS and Android in-app webviews.

---

## 📐 Mathematical Framework

The application processes reducing balance loan calculation model amortization utilizing the standard formula:
