# The Met Landing Page

A responsive landing page inspired by The Metropolitan Museum of Art. It brings visitor information and featured museum content together in a compact, mobile-friendly experience.

This project is based on the [THE MET design in Figma](https://www.figma.com/design/lSR1m42L9YwzQwzzxKwHpw/THE-MET?node-id=8590-29&p=f).

[View the live demo](https://petrenko1694-spec.github.io/petrenko-landing-page-portfolio/)

## Features

- Responsive layout for mobile, tablet, and desktop screens
- Navigation menu with links to the page's main sections
- Museum hours and contact details for The Met Fifth Avenue and The Met Cloisters
- Exhibition highlights and online museum content
- Contact form with required-field and email validation
- SCSS styling, with linting and production build scripts

The contact form is a front-end demonstration: submitting it validates the fields and clears them, but does not send or store a message. Some exhibition and content links are placeholders.

## Getting Started

### Requirements

- Node.js (current LTS version recommended)
- npm

### Install and run

```sh
git clone https://github.com/petrenko1694-spec/petrenko-landing-page-portfolio.git
cd petrenko-landing-page-portfolio
npm install
npm start
```

The development server automatically opens the page in your default browser.

### Useful commands

```sh
npm run build  # Create a production build
npm test       # Run linting and project checks
npm run lint   # Run linters only
```

The page source is in `src/`. Edit `src/index.html` for content and `src/styles/` for styles. Images and icons are in `src/images/` and `src/icons/`.

## Maintainer

This portfolio project is maintained by [petrenko1694-spec](https://github.com/petrenko1694-spec). It is an independent demo and is not an official website of The Metropolitan Museum of Art.
