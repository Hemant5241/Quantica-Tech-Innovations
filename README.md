# Quantica Tech Innovations

**Quantica Tech Innovations** is a premium, fully responsive, and highly customizable website tailored for the modern corporate world and tech startups. 

This project provides a robust foundation for building professional portfolios, agency websites, and corporate landing pages. It has been designed and developed by **Hemant Bhosale** to reflect modern design standards and a comprehensive multi-page architecture.

## 🔗 Live Demo
**[View the Live Project on Netlify](https://quantica-tech-innovations.netlify.app)**

---

## 🌟 Key Features

- **Fully Responsive Design**: Looks perfect on desktops, tablets, and mobile devices.
- **Multi-Page Architecture**: Includes beautifully integrated, standalone pages for:
  - `index.html` (Home)
  - `about.html` (About Us)
  - `services.html` (Services & Offerings)
  - `portfolio.html` (Project Portfolio)
  - `team.html` (Team Members)
  - `blogs.html` (News & Articles)
  - `blog-details-*.html` (Individual Blog Pages)
  - `contact.html` (Contact Information)
- **Modern UI/UX**: Clean aesthetic, subtle animations, sticky navigation, and a strong visual hierarchy.
- **SASS Preprocessor**: Highly maintainable styling structure built on top of SCSS for easy theme customization.
- **Developer Friendly**: Clean code, modular components, and ready for deployment.

---

## 🛠️ Technology Stack

- **HTML5 & CSS3** (via SCSS)
- **Vanilla JavaScript** (with jQuery for legacy DOM manipulation)
- **FontAwesome & Custom Icons**
- **Sass (Dart Sass)** for styling compilation
- **npm-run-all & live-server** for local development

---

## 🚀 Getting Started

### Prerequisites

You will need the following installed on your machine:
- **Node.js** (v14.x or higher recommended)
- **npm** or **yarn**

### Installation

1. Clone or download the repository to your local machine.
2. Open a terminal in the root directory of the project.
3. Install the dependencies:
   ```bash
   npm install
   ```

### Running the Development Server

To start the local development server with Live Reloading and automatic SCSS compilation, simply run:

```bash
npm run dev
```

This command will:
1. Start the SCSS compiler in watch mode (`sass --watch`).
2. Launch a local web server (`live-server`) which automatically refreshes your browser whenever you save a file.

### Building for Production

If you want to compress and prefix your CSS for production deployment, run:

```bash
npm run build:css
```
This will compile the SCSS, add vendor prefixes for cross-browser compatibility, and compress the final `css/style.css` file.

---

## 📁 Directory Structure

```text
📦 quanticatech
├── 📂 css           # Compiled CSS files
├── 📂 fonts         # Custom fonts and icon packs
├── 📂 img           # Images, backgrounds, logos, and assets
├── 📂 js            # JavaScript files (main.js, vendors)
├── 📂 sass          # SCSS source files (abstracts, components, layout, pages)
├── 📄 *.html        # All HTML pages (index, about, services, blogs, etc.)
├── 📄 package.json  # Project dependencies and npm scripts
└── 📄 README.md     # Project documentation
```

---

## 👨‍💻 Author & Credits

- **Developed by:** Hemant Bhosale
- **Company:** Quantica Tech Innovations (2024)

*© 2024 Quantica Tech Innovations. All rights reserved.*
