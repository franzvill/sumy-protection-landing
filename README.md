# Захист і підтримка в громадах Сумщини

Landing page for the project **«Інтегрована відповідь у сфері захисту та підтримки вразливих груп населення в громадах Сумської області»** (Integrated protection response and support for vulnerable groups in communities of Sumy Oblast), implemented by БО «Мережа 100 відсотків життя Рівне» as an implementing partner of IOM Ukraine, funded by the German Federal Ministry for Economic Cooperation and Development through KfW.

**Live:** https://franzvill.github.io/sumy-protection-landing/

## Structure

```
index.html              single-page landing (Ukrainian)
assets/css/styles.css   all styles; design tokens live in :root
assets/fonts/           Onest + Unbounded (woff2, Cyrillic + Latin subsets)
assets/img/             partner and project logos
```

It's plain static HTML and CSS, with no build step and no JavaScript.

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

## Deployment

GitHub Pages serves the site from the root of the `main` branch. Every push to `main` deploys automatically.

## Credits

- Fonts: [Onest](https://fonts.google.com/specimen/Onest) and [Unbounded](https://fonts.google.com/specimen/Unbounded), both under the SIL Open Font License 1.1.
- Logos belong to their respective organizations and are used to identify project partners.
