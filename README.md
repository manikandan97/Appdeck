# Manikandan | My Apps

A modern, responsive static website showcasing my app portfolio.

## 🌟 Features

- **Clean & Modern Design**: Minimal UI with gradient accents
- **Fully Responsive**: Works perfectly on mobile, tablet, and desktop
- **No Backend Required**: Pure static HTML, CSS, and JavaScript
- **Fast Loading**: Uses TailwindCSS via CDN
- **Interactive Cards**: Smooth hover effects and transitions
- **Easy to Update**: Simply modify the apps array in the JavaScript section

## 🚀 Apps Showcase

This portfolio features 8 applications:

1. **RSMK Dev** - Personal developer website
2. **Ledger** - Personal finance tracker
3. **Contact** - Digital business card/contact manager
4. **Share** - File sharing tool
5. **Link Shortener** - Simple URL shortener
6. **Sticker Maker** - WhatsApp sticker creator
7. **My Tools** - Collection of personal utilities
8. **InstaCaptioner** - AI-powered Instagram caption generator

## 📦 Tech Stack

- HTML5
- TailwindCSS (via CDN)
- Vanilla JavaScript
- Google Fonts (Inter)

## 🛠️ Setup

Simply open `index.html` in any modern web browser. No build process or dependencies required!

## 📱 Hosting on GitHub Pages

1. Push this repository to GitHub
2. Go to repository Settings → Pages
3. Select the branch to deploy from (usually `main` or `master`)
4. Your site will be available at `https://[username].github.io/[repository-name]/`

### Custom Domain Setup

This site is configured to use the custom domain: **apps.rsmk.dev**

To set up the custom domain:
1. The CNAME file in the repository root points to `apps.rsmk.dev`
2. Configure your DNS provider to add a CNAME record:
   - **Type**: CNAME
   - **Name**: apps (or the subdomain you want)
   - **Value**: [username].github.io (or your hosting provider's domain)
3. Enable HTTPS in GitHub Pages settings (recommended)

## ✏️ Customization

To add or modify apps, edit the `apps` array in the `<script>` section of `index.html`:

```javascript
const apps = [
    {
        name: "App Name",
        description: "App description",
        url: "https://your-app-url.com",
        color: "from-blue-500 to-blue-600" // TailwindCSS gradient
    },
    // Add more apps...
];
```

## 📄 License

Feel free to use this template for your own portfolio!

---

Built with ❤️ by Manikandan
