# 🏷️ My Morrisons Coupons

A sleek, single-file web app that lets you **scan, store, and manage** your Morrisons supermarket coupons — powered by **OpenAI Vision AI**.

> Upload a photo of any coupon and let AI extract the details automatically. No backend, no database — everything runs in your browser.

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📸 **AI Coupon Scanner** | Upload a coupon photo and OpenAI Vision reads the store name, discount, product, and expiry date |
| 🔍 **AI-Powered Search** | Instant local filtering as you type, plus an AI search button for natural language queries like *"fuel discounts"* or *"expiring this week"* |
| 📅 **Expiry Calendar** | Interactive month-view calendar highlighting days with expiring coupons — navigate months with one click |
| 🏷️ **Smart Auto-Grouping** | Coupons are automatically sorted into tabs: *All*, *Expiring Soon*, *This Week*, *This Month*, *Expired*, and by store name |
| 📊 **Stats Dashboard** | At-a-glance summary cards showing total coupons, expiring soon count, number of stores, and potential savings |
| ⏳ **Expiry Status** | Each coupon shows a human-readable countdown: *Today*, *Tomorrow*, *3 days*, or *Expired* |
| 💾 **Local Storage** | All data is saved in your browser's `localStorage` — no account needed, works offline after first load |
| 🎨 **Modern UI** | Glassmorphism design, smooth animations, Inter font, gradient accents, and fully responsive layout |

## 🚀 Quick Start

1. **Open the app** — visit the [GitHub Pages link](https://lakira23.github.io/Morison-s-coupon-code-vault/morrisons-coupons.html) or open `morrisons-coupons.html` locally in any modern browser
2. **Add your OpenAI API key** — enter it in the *OpenAI Settings* section and click *Save* (stored only in your browser)
3. **Scan a coupon** — click *Choose file*, select a coupon photo, then hit *✨ Read coupon*
4. **Browse & search** — use the search bar, group tabs, or calendar to find your coupons

## 🖼️ Screenshots

The app features a clean, modern interface with:
- A **search bar** with AI-powered natural language search
- **Stats cards** showing your coupon summary at a glance
- An **expiry calendar** with highlighted dates
- **Grouped tabs** for quick filtering
- **Coupon cards** with status badges and smooth animations

## 🔑 API Key

This app requires an **OpenAI API key** to scan coupon photos. You can get one from [platform.openai.com](https://platform.openai.com/api-keys).

- Your key is stored **only in your browser's local storage**
- It is **never sent anywhere** except directly to OpenAI's API
- You can clear it at any time with the *Clear* button

> ⚠️ **Security note:** Since this is a client-side app, your API key is visible to anyone with access to your browser's developer tools. For production use, a backend proxy is recommended.

## 🛠️ Tech Stack

- **HTML5** — single-file, zero dependencies
- **CSS3** — custom properties, glassmorphism, responsive grid, animations
- **Vanilla JavaScript** — no frameworks, no build step
- **OpenAI Responses API** — GPT-4.1 Mini with Vision for coupon extraction and AI search
- **Google Fonts** — Inter typeface

## 📁 Project Structure

```
Morison-s-coupon-code-vault/
├── morrisons-coupons.html   # The entire app — HTML, CSS, and JS in one file
└── README.md                # This file
```

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## 📄 Licence

This project is open source. Feel free to use and modify it for your own needs.
