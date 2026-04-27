# Chester Alejandro — Portfolio

Personal portfolio website showcasing my work as a front-end developer.
Built with Astro, styled with vanilla CSS using a custom design system.

<br />

## Tech Stack

- **Framework** — [Astro](https://astro.build/)
- **Styling** — Vanilla CSS with CSS custom properties
- **Fonts** — Poppins (display), Nunito Sans (body) via Google Fonts
- **Deployment** — Coming soon

## Project Structure

```bash
📁 ca-portfolio/
├── .gitignore
├── astro.config.mjs
├── package-lock.json
├── package.json
├── README.md
├── tsconfig.json
├── 📁 .astro/
│   ├── settings.json
│   └── types.d.ts
├── 📁 .vscode/
│   ├── extensions.json
│   └── launch.json
├── 📁 public/
│   ├── favicon.svg
│   └── 📁 images/
│       ├── chester.jpg
│       ├── placeholder.webp
│       └── 📁 icons/
│           ├── envelope.svg
│           ├── eye.svg
│           ├── github.svg
│           ├── paper-plane.svg
│           └── play.svg
└── 📁 src/
    ├── 📁 components/
    │   ├── Contact.astro
    │   ├── Footer.astro
    │   ├── Hero.astro
    │   ├── Nav.astro
    │   └── Projects.astro
    ├── 📁 css/
    │   └── index.css
    ├── 📁 layouts/
    │   ├── Layout.astro
    │   └── SectionLayout.astro
    └── 📁 pages/
        └── index.astro

```

## Getting Started

### Prerequisites

- Node.js 18+
- npm

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/chesteralejandro/ca-portfolio.git

    cd ca-portfolio
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Start the development server:

    ```bash
    npm run dev
    ```

4. Open your browser and visit `http://localhost:4321`

## Available Scripts

| Command           | Description                      |
| ----------------- | -------------------------------- |
| `npm run dev`     | Start development server         |
| `npm run build`   | Build for production             |
| `npm run preview` | Preview production build locally |

## Design System

The portfolio uses a custom CSS design system with the following tokens:

- **Primary color** — `#1c2541` (Deep Navy)
- **Accent color** — `#f39c12` (Amber)
- **Display font** — Poppins
- **Body font** — Nunito Sans

## License

This project is open source and available under the [MIT License](LICENSE).
