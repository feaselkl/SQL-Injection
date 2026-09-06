# SQL Injection

Slides for the SQL Injection presentation, served at
<https://www.catallaxyservices.com/media/SQL-Injection/>.

Pushing to `main` publishes this repository to that URL automatically via
`.github/workflows/deploy-slides.yml`.

The demo code (an ASP.NET workbench plus the accompanying SQL scripts) lives
separately in [feaselkl/SQLInjection](https://github.com/feaselkl/SQLInjection).

Shared `reveal.js` and `WebsiteAssets` directories are not part of this
repository; they sit alongside it on the server, which is why `index.html`
references them as `../reveal.js/` and `../WebsiteAssets/`.
