# Ilori Foundation

Website for the Ilori Foundation, aligned with the UN Sustainable Development Goals (SDGs).

## Tech stack

- [Astro](https://astro.build) 5
- [Tailwind CSS](https://tailwindcss.com) 4

## Project structure

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── assets/
│   │   └── images/          # SDG assets, logo, founder photo, etc.
│   ├── components/
│   │   ├── About.astro
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── ImpactStats.astro
│   │   ├── LatestStories.astro
│   │   ├── Logo.astro
│   │   ├── MissionWindow.astro
│   │   └── SDGAlignment.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   ├── index.astro      # Home
│   │   ├── founder.astro    # Founder story
│   │   └── contact.astro    # Contact
│   └── styles/
│       └── global.css
├── astro.config.mjs
└── package.json
```

## Commands

| Command           | Action                                      |
| :---------------- | :------------------------------------------ |
| `yarn install`    | Install dependencies                        |
| `yarn dev`       | Start dev server at `localhost:4321`        |
| `yarn build`     | Build for production to `./dist/`           |
| `yarn preview`   | Preview the production build locally        |
| `yarn astro ...` | Run Astro CLI (e.g. `astro add`, `astro check`) |

## SDG alignment

The site highlights alignment with SDGs 2 (Zero Hunger), 3 (Good Health & Well-being), 5 (Gender Equality), and 10 (Reduced Inequalities), using the official UN SDG hex colours in the SDG Alignment section.
