# Aryan Patade — Cinematic Portfolio

A high-performance personal portfolio built with Next.js 16, GSAP, Three.js, and CSS Modules. Designed to showcase AI development, Data Engineering, and system design projects.

**GitHub:** [Aryan-123-app/cinematic-portfolio](https://github.com/Aryan-123-app)

---

## Stack

| Layer      | Technology                                       |
| ---------- | ------------------------------------------------ |
| Framework  | Next.js 16.2 (App Router, React Compiler)        |
| Animations | GSAP 3 + Three.js                                |
| Styling    | CSS Modules + Tailwind v4 (tokens only)          |
| Icons      | react-icons                                      |
| Fonts      | Geist, Baloo 2, Dancing Script (via next/font)   |

---

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Aryan-123-app/cinematic-portfolio.git
   cd cinematic-portfolio
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure Environment Variables:**
   Copy `.env.example` to `.env.local`:
   ```bash
   cp .env.example .env.local
   ```
   *Note: For local development, `NEXT_PUBLIC_SITE_URL` is configured to `http://localhost:3000`.*

4. **Run the development server:**
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) to view it.

To build for production:
```bash
npm run build
npm start
```

---

## Customizing Your Portfolio

### 1. Update Profile & Content Data
All personal information and content are decoupled from the code and managed via JSON files:
* **`data/profile.json`**: Update your name, roles, stats, bio, experiences, publications, and social links.
* **`data/content.json`**: Update section taglines, button copy, and non-personal website text.

### 2. Configure Design Tokens
To change the color theme or typography, open [app/globals.css](file:///c:/Users/LENOVO/Downloads/cinematic-portfolio-main/cinematic-portfolio-main/app/globals.css) and edit the CSS Custom Properties (variables) defined under `:root`:
* `--accent`: Primary interactive/accent color.
* `--hero-start` / `--hero-mid` / `--hero-end`: Background gradient colors for the Hero section.
* `--text-primary`: Primary text color.

### 3. Replace Assets
Replace files in `public/assets/` with your own details:
* `hero3.png` (Portrait photo for Hero section)
* `about-me.mp4` (Intro video background for About section)
* `about.webp` (Profile image for About section & SEO)
* `work-experience.webp` (Background image for Work Experience timeline)
* `footer-video.mp4` (Desktop footer looping video)
* `footer-mobile.webp` (Mobile footer static background)
* `project-*.png` (Project preview screenshots matching filenames in `profile.json`)

---

## Deployment

### Vercel (Recommended)
This project is configured for one-click deployment on Vercel:
1. Push your code to GitHub.
2. Import the repository into Vercel.
3. Add the following Environment Variable in your Vercel project settings:
   * **Key**: `NEXT_PUBLIC_SITE_URL`
   * **Value**: `https://your-domain.vercel.app` (e.g. `https://aryanpatade.vercel.app`)
4. Click deploy. Vercel will build and host the site automatically.

---

## License

MIT. Free to fork, adapt, and use for your own portfolio.

---

## Author

**Aryan Patade** — AI & Data Engineer
* **Email**: aryanpatade8@gmail.com
* **GitHub**: [Aryan-123-app](https://github.com/Aryan-123-app)
* **LinkedIn**: [Aryan Patade](https://www.linkedin.com/in/aryan-patade-a277451a9)
* **Medium**: [@aryanpatade8](https://medium.com/@aryanpatade8)
* **Instagram**: [@therealaryan.45](https://www.instagram.com/therealaryan.45/)
