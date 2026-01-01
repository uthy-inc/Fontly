# 🎨 Fontly: Interactive Font Preview Gallery

> **The ultimate, high-performance web application for previewing, testing, and integrating a curated collection of 95+ premium fonts.**

Fontly is a Progressive Web App (PWA) designed to streamline the process of selecting and integrating custom fonts into your projects. Hosted on Vercel's global CDN, it provides a lightning-fast, interactive environment to test fonts with live rendering, advanced filtering, and one-click CSS code copying.

---

## ✨ Key Features

| Feature Category | Description |
| :--- | :--- |
| **Full Font Collection** | Features **95+ curated fonts** (TTF and OTF formats) for live preview and testing. |
| **Interactive Preview** | Live rendering with individual font size controls (12-72px range) and custom sample text input per font. |
| **Smart Filtering** | Real-time search by font name and category, with filter badges for **Serif, Sans-serif, Display, Script, Decorative, and 3D** fonts. |
| **Code Management** | One-click copy functionality for the complete, syntax-highlighted `@font-face` CSS code for every font. |
| **Global Controls** | Universal sample text override and a global slider for bulk font size adjustment. |
| **PWA & UI/UX** | Installable on any device, with **Light/Dark theme toggle**, responsive design, and smooth CSS transitions. |
| **Performance** | Fonts are served via Vercel's CDN with optimized caching headers (`Cache-Control: immutable`) and `font-display: swap` for fast loading. |

---

## 🚀 Quick Start

### 1. View the Live Application

Experience the gallery immediately:

[**👉 Launch Fontly Live Demo**](https://fontly-virid.vercel.app)

### 2. Integrate Fonts into Your Project

To use any font in your own project, simply:

1.  **Copy the CSS:** In the Fontly app, click the **"Show CSS"** button for your desired font and use the **"Copy CSS"** button.
2.  **Paste the CSS:** Paste the copied `@font-face` block into your project's main CSS file.
3.  **Apply the Font:** Use the `font-family` name in your CSS:

```css
/* Example of copied @font-face code */
@font-face {
  font-family: 'Angelbanditdemoregular';
  src: url('https://fontly-virid.vercel.app/fonts/ttf/AngelBanditDemoRegular.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
  font-display: swap;
}

/* Applying the font */
.my-heading {
  font-family: 'Angelbanditdemoregular', sans-serif;
}
```

### 3. Clone and Contribute

If you wish to clone the repository, modify the code, or add more fonts:

```bash
# Clone the repository
git clone https://github.com/uthumany/Fontly.git
cd Fontly

# The project is a static site.
# To run locally, you can use any simple web server:
npx http-server .
```

---

## 🛣️ Roadmap & Changelog

### Changelog

| Version | Date | Changes |
| :--- | :--- | :--- |
| **v2.0.0** | 2026-01-02 | **Major Update:** Implemented all core features (Search, Filtering, Global Controls, PWA, UI/UX enhancements). Fixed font display issue to show all 95 fonts. |
| **v1.1.0** | 2026-01-02 | Added 60 new fonts to the collection (Total: 95). |
| **v1.0.0** | 2026-01-02 | Initial deployment of the Fontly PWA. Automated hosting of 35 fonts via GitHub and Vercel CDN. |

### Future Roadmap

- **Font Uploader:** Allow users to upload their own font files for private, temporary preview.
- **Variable Font Support:** Implement controls for weight, width, and slant axes for variable fonts.
- **Webfont Conversion:** Add a feature to convert TTF/OTF to WOFF/WOFF2 formats on the fly.
- **Advanced Filtering:** Filter by weight, style, and language support.

---

## 🤝 License

This project is licensed under the MIT License. The included font files are provided for demonstration and preview purposes; please check the individual font licenses for commercial use.

***

*Developed by Manus AI*
