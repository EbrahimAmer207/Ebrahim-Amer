<div align="center">

# 🚀 Ebrahim Abdelmonem | Front-End Developer Portfolio

[![React](https://img.shields.io/badge/React-18.3-61DAFB?logo=react&logoColor=white)](https://react.dev)
[![Vite](https://img.shields.io/badge/Vite-5.4-646CFF?logo=vite&logoColor=white)](https://vitejs.dev)
[![Supabase](https://img.shields.io/badge/Supabase-2.101-3FCF8E?logo=supabase&logoColor=white)](https://supabase.com)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-7952B3?logo=bootstrap&logoColor=white)](https://getbootstrap.com)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> A modern, interactive portfolio website with a powerful admin dashboard and real-time content management

[Live Demo](#) • [Report Bug](../../issues) • [Request Feature](../../issues)

</div>

---

## 📋 Table of Contents

- [Features](#-features)
- [Quick Start](#-quick-start)
- [Project Structure](#-project-structure)
- [Dashboard](#-dashboard)
- [Technology Stack](#️-technology-stack)
- [Screenshots](#-screenshots)
- [Customization](#-customization)
- [License](#-license)

---

## ✨ Features

A modern, responsive portfolio website built with **React**, **Vite**, and **Supabase**. Featuring a powerful admin dashboard for managing portfolio content, command palette navigation, and comprehensive sections showcasing projects, skills, and experience.

### 📄 Interactive Portfolio Sections

| Section | Description |
|---------|-------------|
| 🎯 Hero | Eye-catching introduction with call-to-action |
| 👤 About | Personal background and professional summary |
| 🛠️ Tech Stack | Core technologies and tools expertise |
| 📚 Experience & Education | Timeline of work experience and education |
| 💼 Projects | Portfolio of completed projects with details |
| 🎨 Services | Services offered to clients |
| ⚡ Skills | Visual display of technical skills |
| 📧 Contact | Contact form for inquiries |

### 🎛️ Admin Dashboard

- ✅ Secure authentication system
- ✅ Real-time content editing
- ✅ Project & experience management
- ✅ Supabase database synchronization
- ✅ Reset to default content option
- ✅ One-click content publishing

### 🎮 Developer Experience

- ⌨️ Command Palette (Cmd/Ctrl + K) for quick navigation
- ✨ Smooth scroll animations & transitions
- 📱 Fully responsive design (mobile, tablet, desktop)
- 🌙 Dark theme by default
- ⚡ Optimized images & fast loading
- 🎨 Bootstrap + Custom CSS styling

### 🗄️ Backend Integration

- 📊 Supabase PostgreSQL database
- 🔄 Real-time content synchronization
- 🔐 Secure JWT authentication
- 🌐 Remote portfolio management

## 🚀 Quick Start

### Prerequisites

- ![Node.js](https://img.shields.io/badge/Node.js-16+-339933?logo=node.js&logoColor=white) or higher
- ![npm](https://img.shields.io/badge/npm-8+-CB3837?logo=npm&logoColor=white) or yarn

### Installation Steps

```bash
# 1️⃣ Clone the repository
git clone <repository-url>
cd portfolio

# 2️⃣ Install dependencies
npm install

# 3️⃣ Create environment file
echo "VITE_SUPABASE_URL=your_url" > .env.local
echo "VITE_SUPABASE_ANON_KEY=your_key" >> .env.local

# 4️⃣ Start development server
npm run dev
```

Visit **http://localhost:5173** 🎉

### Build for Production

```bash
npm run build     # Creates optimized production build
npm run preview   # Preview production build locally
```

## 📁 Project Structure

```
📦 portfolio
├── 📄 index.html              # HTML entry point
├── 📄 package.json            # Dependencies & scripts
├── 📄 vite.config.js          # Vite configuration
├── 📄 .env.local              # Environment variables
│
├── 📂 src/
│   ├── 🎨 App.jsx            # Main app component
│   ├── 🎨 main.jsx           # React entry point
│   │
│   ├── 📂 components/        # React components
│   │   ├── Navigation.jsx       # Navigation bar
│   │   ├── HeroSection.jsx      # Hero/landing
│   │   ├── AboutSection.jsx     # About me
│   │   ├── ExperienceSection.jsx# Work experience
│   │   ├── EducationSection.jsx # Education
│   │   ├── ProjectsSection.jsx  # Projects showcase
│   │   ├── SkillsSection.jsx    # Skills display
│   │   ├── ServicesSection.jsx  # Services offered
│   │   ├── CoreStackSection.jsx # Tech stack
│   │   ├── ContactSection.jsx   # Contact form
│   │   ├── PortfolioDashboard.jsx# Admin dashboard
│   │   ├── DashboardAccessGate.jsx# Auth gate
│   │   ├── CommandPalette.jsx   # Quick navigation
│   │   ├── CTASection.jsx       # Call to action
│   │   ├── SectionHeading.jsx   # Reusable heading
│   │   └── SectionShowcaseCarousel.jsx# Carousel
│   │
│   ├── 📂 data/              # Content data
│   │   ├── portfolioContent.js # Content structure
│   │   └── portfolioData.js    # Content values
│   │
│   └── 📂 lib/               # Utilities & services
│       ├── supabaseClient.js    # Supabase setup
│       ├── dashboardAuth.js     # Authentication
│       ├── dashboardSecurity.js # Security utils
│       ├── portfolioRemote.js   # Remote sync
│       ├── getDelayStyle.js     # Animation utils
│       └── useMediaQuery.js     # Responsive hook
│
├── 📂 public/
│   ├── 🎨 CSS/style.css      # Global styles
│   ├── 🖼️ Img/               # Images & assets
│   └── 📂 Files/             # Download files
│
└── 📂 supabase/
    └── 📊 portfolio_content.sql # Database schema
```

## 🎛️ Admin Dashboard

Access the admin dashboard to manage your portfolio content:

```
📍 Steps to access:
  1. Open the portfolio website
  2. Look for the dashboard access button
  3. Authenticate with your credentials
  4. Start editing content in real-time
  5. Changes sync to Supabase automatically
```

**Features:**
- 🔒 JWT-based authentication
- 📝 Live content editor
- 📊 Project management
- 🎯 Skills & experience editor
- 💾 Auto-save functionality
- 🔄 Database synchronization
- ⚠️ Reset option with confirmation

**Security Best Practices:**
- Keep your credentials confidential
- Use strong, unique passwords
- Regularly update your password
- Monitor access logs (if available)
- Don't share dashboard links

## 🛠️ Technology Stack

| Category | Technology | Version | Purpose |
|----------|-----------|---------|---------|
| **Frontend** | React | 18.3.1 | UI library |
| | Vite | 5.4.12 | Build tool & dev server |
| | Bootstrap | 5.3.2 | Component framework |
| **Backend** | Supabase | 2.101.0 | Backend & database |
| | PostgreSQL | - | Database (via Supabase) |
| **Styling** | CSS3 | Latest | Custom styles & animations |
| **Icons** | Font Awesome | 6.4.0 | Icon library |
| **Fonts** | Outfit | Latest | Primary font |
| | Fira Code | Latest | Code/monospace font |

### Browser Support

| Browser | Support | Version |
|---------|---------|---------|
| Chrome | ✅ | Latest |
| Firefox | ✅ | Latest |
| Safari | ✅ | Latest |
| Edge | ✅ | Latest |
| Mobile Browsers | ✅ | Latest |

## 📸 Screenshots

### 🎯 Hero Section
*Impressive introduction with professional design and call-to-action buttons*

### 📚 Experience & Education
*Timeline view of work experience and educational background*

### 💼 Projects Showcase
*Interactive project cards with descriptions and live links*

### ⚡ Skills Display
*Visual representation of technical skills and expertise*

### 🎛️ Admin Dashboard
*Powerful content management interface with real-time editing*

## 🎨 Customization Guide

### 📝 Modify Content

Edit `src/data/portfolioContent.js` to customize:

```javascript
// Navigation links
export const navLinks = [
  { id: 'home', label: 'Home' },
  { id: 'about', label: 'About' },
  // ... add your sections
];

// Default portfolio content
export const getInitialPortfolioContent = () => ({
  name: 'Your Name',
  title: 'Your Title',
  // ... your data
});
```

### 🎨 Update Styles

**Global styles:** `public/CSS/style.css`
**Component-specific:** Modify inline styles or CSS Modules

**CSS Variables:**
```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --font-family: 'Outfit', sans-serif;
}
```

### 🌙 Change Theme

Update `index.html`:
```html
<body data-theme="dark">  <!-- Change to "light" -->
```

Or switch dynamically in JavaScript:
```javascript
document.body.setAttribute('data-theme', 'light');
```

### 🔗 Deploy to Production

**Vercel** (Recommended for Vite):
```bash
npm install -g vercel
vercel
```

**Netlify:**
```bash
npm run build
# Drag & drop dist/ folder to Netlify
```

**GitHub Pages:**
Update `vite.config.js`:
```javascript
export default defineConfig({
  base: '/portfolio/',
  plugins: [react()],
});
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Make** your changes
4. **Commit** your work (`git commit -m 'Add amazing feature'`)
5. **Push** to the branch (`git push origin feature/amazing-feature`)
6. **Open** a Pull Request

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

You are free to:
- ✅ Use commercially
- ✅ Modify the code
- ✅ Distribute copies
- ✅ Use privately

Just include the original license notice.

## 📞 Contact & Support

Have questions or need help? Let's connect!

<div align="center">

**📧 Email:** [your-email@example.com](mailto:your-email@example.com)

**🔗 Links:**
- [LinkedIn](https://linkedin.com/in/your-profile)
- [GitHub](https://github.com/your-username)
- [Portfolio](https://your-portfolio.com)
- [Twitter/X](https://twitter.com/your-handle)

</div>

---

<div align="center">

### ⭐ If you found this helpful, please consider giving it a star! ⭐

**Made with ❤️ by Ebrahim Abdelmonem**

[Back to top](#-ebrahim-abdelmonem--front-end-developer-portfolio)

</div>
