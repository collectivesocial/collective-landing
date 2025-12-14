
# Collective Landing Page

**Build your collections. Share your world.**

This repository contains the landing page, blog, and public documentation for [Collective](https://collectivesocial.app) - a social app built around tracking and sharing your favorite media.

## About Collective

**Track what you love. Share what matters.**

Collective is your personal space to curate lists, track your progress, and share recommendations across books, movies, TV shows, and more—all built on the open social web.

### Core Features

- **Your Collections, Your Way**: Create unlimited lists for books, movies, TV shows, and beyond. Track what you've finished, what's in progress, and what's on your radar.
- **Share with Friends**: Easily share your collections and reviews with your network. Discover what your friends are watching, reading, and recommending.
- **Built on ATProto**: Your data belongs to you. Collective is built on the decentralized AT Protocol, giving you control and portability.
- **Progress That Travels**: Rate, review, and track your journey through every book, season, and film. Your progress stays with you, wherever you go.

Ready to start collecting? Join Collective today at [collectivesocial.app](https://collectivesocial.app)

---

## Template Information

This landing page is built using the [NeonMint template](https://github.com/EFEELE/NeonMint) - a minimalist and modern Astro template designed for developers and digital creatives.

![neonmint](https://github.com/user-attachments/assets/ae539704-2292-492f-882c-c90595b34717)

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ installed
- npm or pnpm package manager

### Installation & Development

1. **📦 Clone the Repository**
   ```bash
   git clone https://github.com/collectivesocial/collective-landing.git
   cd collective-landing
   ```

2. **📥 Install Dependencies**
   ```bash
   npm install
   ```

3. **⚡ Start Development Server**
   ```bash
   npm run dev
   ```
   The site will be available at `http://localhost:4321`

4. **🏗️ Build for Production**
   ```bash
   npm run build
   ```

5. **👀 Preview Production Build**
   ```bash
   npm run preview
   ```

---

## 🛠️ Template Information

### Original Template

This site is built using the **NeonMint** template. For the original template documentation and setup instructions, visit:
- Repository: [https://github.com/EFEELE/NeonMint](https://github.com/EFEELE/NeonMint)
- Installation: `npm create astro@latest -- --template EFEELE/neonmint`

## ⚙️ Configuration

The project is configured through several key files:

- `astro.config.mjs`: Main Astro configuration
- `tailwind.config.js`: TailwindCSS configuration
- `tsconfig.json`: TypeScript configuration

## 🎨 Customization

### 📄 Adding New Pages

Create new `.astro` files in the `src/pages` directory. The file name will determine the route.

### 🔧 Adding New Languages or Technologies

To incorporate a new programming language or technological tool into the site's capsules, follow these steps:

1. **🖼️ Add the SVG icon**: Place the SVG file of the language or tool in the `src/icons` folder.

        > **💡 Recommendation**: For SVG icons, I recommend using [SVGL](https://svgl.app/), an excellent library of high-quality vectors that offers optimized icons for most popular languages and technologies.

2. **📝 Register the language**: Open the `utils/languages.ts` file and add a new entry to the languages object following this format:

   ```typescript
   html: {
       name: "HTML 5",
       iconName: "html",
   },
   ```

   Where:
   - `html`: Is the unique identifier for the language
   - `name`: Is the name that will be displayed visibly in the interface
   - `iconName`: Is the name of the SVG file without the extension (must match exactly with the file name in `src/icons`)

Once these steps are completed, the new language or technology will be available for use in the site's capsules. You can select it when creating or editing projects or posts, and the corresponding icon will be displayed correctly in the interface.

If you encounter any issues during this process, try restarting the development server. In some cases, changes to configuration files or static resources require a restart to be detected correctly.

To verify that the new language has been added correctly, check the list of available technologies in the user interface after restarting the server.

---

### 🧷 Favicon Setup

To customize your site's favicon and web app icons, you can generate all the necessary variants using [favicon.io](https://favicon.io/favicon-converter/). Upload your logo or icon, and the tool will create a full set of optimized files for various devices and platforms.

Place the generated files in the `📂 public` directory as follows:

```bash
📂 public
├── 📄 android-chrome-192x192.png
├── 📄 android-chrome-512x512.png
├── 📄 apple-touch-icon.png
├── 📄 favicon-16x16.png
├── 📄 favicon-32x32.png
├── 📄 favicon.ico
└── 📄 site.webmanifest
```

> 💡 Don’t forget to update the contents of `site.webmanifest` to match your app’s name, description, and theme color for a complete PWA experience.

---

### 🎨 Styling

- Use TailwindCSS classes for styling
- Add custom styles in `src/styles/global.css`

### 🧩 Components

- Create reusable components in `src/components`
- Import icons using `astro-icon`

## 🚀 Deployment

The site is configured for deployment on Vercel, but can be deployed to any static hosting service.

## 🤝 Contributing

Contributions to improve the Collective landing page are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

---

## 📄 Credits & License

### Collective

Collective is built and maintained by the Collective Social team.

- Website: [collective.social](https://collective.social)
- GitHub: [github.com/collectivesocial](https://github.com/collectivesocial)

### NeonMint Template

This landing page uses the NeonMint template by EFEELE.

- Template Repository: [github.com/EFEELE/NeonMint](https://github.com/EFEELE/NeonMint)
- License: MIT

#### Template Contributors

<a href="https://github.com/EFEELE/NeonMint/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=EFEELE/NeonMint" />
</a>

---

This project is licensed under the MIT License.

