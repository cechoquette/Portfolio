# Catherine Choquette — Portfolio

A personal software engineering portfolio built with Angular.

The site is designed to be minimal, bilingual, and intentionally restrained, with a focus on clear structure, typography, and selected technical work rather than visual clutter.

## Stack

- Angular 21+
- TypeScript
- SCSS
- Angular Router
- Transloco
- GitHub
- Azure Static Web Apps

## Current Structure

```text
src/
├── app/
│   ├── core/
│   │   └── layout/
│   │       ├── header/
│   │       └── footer/
│   ├── pages/
│   │   ├── home/
│   │   ├── projects/
│   │   ├── about/
│   │   └── contact/
│   ├── app.ts
│   ├── app.html
│   ├── app.scss
│   ├── app.routes.ts
│   └── app.config.ts
├── styles.scss
├── index.html
└── main.ts
```

## Design Direction

The visual system is intentionally sparse.

The goal is an editorial, high-end feel built around:

- generous negative space
- restrained typography
- minimal navigation
- subtle borders and colour
- selective use of photography
- no decorative animation or unnecessary visual noise

The homepage acts as a quiet entry point rather than a full one-page portfolio. Projects, background, and contact information are handled through dedicated routes.

## Internationalization

The site is being built with English and French support from the start using Transloco.

Planned structure:

```text
src/assets/i18n/
├── en.json
└── fr.json
```

A small `EN / FR` language control will be added to the interface.

## Planned Pages

- Home
- Projects
- About
- Contact

Individual project case studies will be added under the Projects section as the portfolio grows.

## Deployment

The site is intended to be deployed through GitHub to Azure Static Web Apps with a custom domain.

## Status

Early development.

The application shell, routing, core layout, and initial visual foundation are in place. Content, project case studies, responsive refinements, internationalization, and deployment are still being built.
