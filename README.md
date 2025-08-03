# Portfolio Website

A modern, responsive portfolio website built with Vue 3, TypeScript, and Tailwind CSS.

## 🚀 Features

- **Modern Design**: Clean, professional design with blue theme
- **Responsive**: Works perfectly on all devices
- **Interactive**: Smooth animations and hover effects
- **Multi-language**: Support for English and Vietnamese
- **Real Projects**: Showcase with actual project images
- **Downloadable Resume**: Direct PDF download
- **Contact Form**: Easy way for potential employers to reach you

## 🛠️ Tech Stack

- **Frontend**: Vue 3 + TypeScript
- **Styling**: Tailwind CSS
- **Build Tool**: Vite
- **Deployment**: GitHub Pages

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/portfolio.git
cd portfolio
```

2. Install dependencies:
```bash
npm install
```

3. Run development server:
```bash
npm run dev
```

4. Build for production:
```bash
npm run build
```

## 🚀 Deployment

### Automatic Deployment (Recommended)

This repository is configured with GitHub Actions for automatic deployment. Simply push to the `main` branch and your site will be automatically deployed to GitHub Pages.

### Manual Deployment

1. Build the project:
```bash
npm run build
```

2. Deploy to GitHub Pages:
```bash
npm run deploy
```

## ⚙️ Configuration

### GitHub Pages Setup

1. Go to your repository settings on GitHub
2. Navigate to "Pages" in the sidebar
3. Set source to "GitHub Actions"

### Custom Domain (Optional)

If you want to use a custom domain:

1. Add your domain to the repository settings
2. Update the `base` in `vite.config.ts`:
```typescript
export default defineConfig({
  plugins: [vue(), tailwindcss()],
  base: '/', // Change from '/portfolio/' to '/'
})
```

## 📁 Project Structure

```
portfolio/
├── src/
│   ├── components/
│   │   ├── Home.vue
│   │   ├── Education.vue
│   │   ├── Skills.vue
│   │   ├── Experience.vue
│   │   ├── Projects.vue
│   │   ├── Resume.vue
│   │   ├── Contact.vue
│   │   └── LanguageSwitcher.vue
│   ├── assets/
│   │   └── images/
│   ├── locales/
│   ├── App.vue
│   └── main.ts
├── .github/workflows/
│   └── deploy.yml
├── vite.config.ts
└── package.json
```

## 🎨 Customization

### Colors
The portfolio uses a blue theme. To change colors, update the Tailwind classes in the components.

### Content
- Update project information in `src/components/Projects.vue`
- Modify experience details in `src/components/Experience.vue`
- Change education information in `src/components/Education.vue`
- Update skills in `src/components/Skills.vue`

### Resume
Replace `public/QuocAnhNguyen_Backend.pdf` with your own resume file.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
