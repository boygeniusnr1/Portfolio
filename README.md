# Senior Developer Portfolio

A high-performance, bento-grid portfolio designed to bridge the gap between functional code and 3D-influenced aesthetics. Built with **Astro 6** and **Tailwind CSS v4**.

## 🛠 Tech Stack
- **Framework:** [Astro 6.0+](https://astro.build/) (SSR Focus)
- **Styling:** [Tailwind CSS v4](https://tailwindcss.com/) (Utility-first, modern engine)
- **Content:** [Astro Content Collections v2](https://docs.astro.build/en/guides/content-collections/) (Markdown-driven project archive)
- **Typography:** `@tailwindcss/typography` (Optimized prose rendering)
- **Design Pattern:** Bento-box layouts with physical object mimicry (subtle shadows/depth)

## 🚀 Key Features
- **Zero Client-Side JS:** Optimized for LCP and Core Web Vitals.
- **Physical UI:** Custom shadow and transition utilities mimicking physical depth.
- **Automatic Dark Mode:** System-level theme detection with adaptive bento cards.
- **Auto-Indexing Projects:** Drop `.md` files into `src/content/projects/` for instant publishing.
- **Glassmorphism Toolbar:** Fixed-position floating navigation with backdrop filters.

## 📁 Project Structure
- `src/components/`: Reusable Astro UI components.
- `src/content/`: Markdown-based project data.
- `src/layouts/`: Base layout with global meta tags and navigation.
- `src/pages/`: File-based routing for Home and Project Archive.
- `src/styles/`: Tailwind v4 theme configuration and global overrides.

## 🏗 Setup & Deployment
```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

## 🎨 Design Rules
- **Grid:** Use `CSS Grid` over Flexbox for layout consistency.
- **Aesthetics:** Prioritize subtle transitions (`cubic-bezier`) and high-performance blur filters.
- **Performance:** Maintain a "Performance First" mindset; evaluate every script's impact on LCP.
