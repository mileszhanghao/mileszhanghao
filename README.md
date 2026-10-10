### Hao (Miles) Zhang

Recent University of Washington graduate — **B.A. Geography: Data Science (June 2026)**, minors in **Applied Mathematics** and **Data Science**. I work across backend development, geospatial analysis and statistical modeling. English / Mandarin / Cantonese.

📍 Redmond, WA · ✉️ hzhang44@uw.edu

---

## Software projects

These started as projects in LaiOffer's software engineering program (2025). In 2026 I rebuilt each one: I fixed the bugs and security problems I found in the original course code, and added tests and CI. Each README lists what changed and why.

**[onlineorder](https://github.com/mileszhanghao/onlineorder)** — food ordering web app · [**live demo**](https://mileszhanghao.github.io/onlineorder/)
Java 21, Spring Boot 3.5, PostgreSQL, Flyway, Spring Security, React + TypeScript. The add-to-cart race is fixed with an atomic upsert, and checkout records orders with `DELETE … RETURNING`. Testcontainers integration tests include a 20-thread concurrency test.

**[agentai](https://github.com/mileszhanghao/agentai)** — ask questions about a PDF
TypeScript, Node, OpenAI tool calling, Model Context Protocol, React. A RAG pipeline indexes each upload once. An agent loop chooses between document search and an MCP web-search server, and every answer cites its sources. An offline mode runs without API keys.

**[socialai](https://github.com/mileszhanghao/socialai)** — photo/video sharing with AI image generation
Go, PostgreSQL full-text search, JWT, OpenAI Images, React. The rebuild fixes the course version's plain-text passwords, hard-coded JWT key, sign-up race and API key exposed in the browser.

## Geospatial and data work (UW coursework)

**Washington State forest disturbance, 2004–2024** — spatial analysis across 271 ecoregions and 36 counties; annual disturbed area grew from about 17 km² to about 128 km² over the period.
**Uneven Shade: Seattle tree-canopy equity, 2016–2021** — mapped census-tract canopy change against Environmental Justice Priority Areas using Seattle Open Data.
→ both in [geospatial-data-portfolio](https://github.com/mileszhanghao/geospatial-data-portfolio)

**Douban Chinese film ratings (AMATH 383)** — regression model with Lasso feature selection.

## Community

**[christians-in-seattle-uw](https://github.com/mileszhanghao/christians-in-seattle-uw)** — bilingual (English/Chinese) website for a UW student group, live at [cisuw.com](https://cisuw.com).

---

**Languages:** Java · TypeScript/JavaScript · Go · Python · R · SQL
**Backend:** Spring Boot · Node/Express · Go net/http · PostgreSQL · Docker · GitHub Actions
**Frontend:** React · Vite · Ant Design
**Data & GIS:** ArcGIS Pro · QGIS · R Shiny
