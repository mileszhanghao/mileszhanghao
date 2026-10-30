### Miles Zhang

Recent University of Washington graduate — **B.A. Geography: Data Science (June 2026)**, minors in **Applied Mathematics** and **Data Science**. I build data pipelines, GIS analyses and backend services, and I like projects where the data is messy and the answer has to hold up. English / Mandarin / Cantonese.

**Looking for:** entry-level data analyst, GIS and backend roles in the Seattle area.

📍 Redmond, WA · ✉️ hzhang44@uw.edu

---

## Portfolio

Every project has a live demo, tests that run on every push, and a README that explains the design choices and trade-offs.

| Project | What it is | Stack | Demo |
|---|---|---|---|
| [Shadelines](https://github.com/mileszhanghao/shadelines) | Seattle's 1936 redlining map vs. today's tree canopy | Python · GeoPandas · MapLibre | [map](https://mileszhanghao.github.io/shadelines/) |
| [Fenders](https://github.com/mileszhanghao/fenders) | Daily pipeline: bike counters + weather | Python · dbt · DuckDB · Actions | [dashboard](https://mileszhanghao.github.io/fenders/) |
| [SiuYeh 宵夜](https://github.com/mileszhanghao/siuyeh) | Food ordering | Java · Spring Boot · PostgreSQL | [demo](https://mileszhanghao.github.io/siuyeh/) |
| [Porchlight](https://github.com/mileszhanghao/porchlight) | Condo community app | TypeScript · NestJS · PostgreSQL | [demo](https://mileszhanghao.github.io/porchlight/) |
| [Footnote](https://github.com/mileszhanghao/footnote) | PDF Q&A with cited pages | TypeScript · RAG · MCP | [demo](https://mileszhanghao.github.io/footnote/) |
| [Drizzle](https://github.com/mileszhanghao/drizzle) | Photo sharing with AI images | Go · PostgreSQL | [demo](https://mileszhanghao.github.io/drizzle/) |
| [Spindle](https://github.com/mileszhanghao/spindle) | Android record player | Kotlin · Compose · Media3 | [APK](https://mileszhanghao.github.io/spindle/) |

### Data and GIS

**[Shadelines](https://github.com/mileszhanghao/shadelines)**: Seattle's 1936 redlining map against today's tree canopy and census data · [**interactive map**](https://mileszhanghao.github.io/shadelines/)
Python, GeoPandas, MapLibre GL. Areas graded A in 1936 have 39% tree canopy today, against 27% in C and D areas; the share of residents who are people of color goes from 22% to 52%. Canopy is split onto the 1936 boundaries by area, and people through 2020 census blocks (dasymetric weighting). The citywide result matches the city's own figure (28.2% vs 28.1%).

**[Fenders](https://github.com/mileszhanghao/fenders)**: does rain keep Seattle off its bikes? A daily data pipeline · [**dashboard**](https://mileszhanghao.github.io/fenders/)
Python, Parquet, DuckDB, dbt, GitHub Actions. Every morning it pulls six city bike counters and hourly weather, models them in dbt, and publishes only if 21 data tests pass. On the first full load the tests caught duplicated months, conflicting rows and sensor error values. Answer: rain cuts riding by about half, weekend riders far more than commuters.

### Backend and full stack

These four, and Spindle below, started as projects in LaiOffer's software engineering program (2025). In 2026 I rebuilt and renamed each one: I fixed the bugs and security problems I found in the original course code, and added tests and CI. Each README lists what changed and why.

**[SiuYeh 宵夜](https://github.com/mileszhanghao/siuyeh)**: late-night food ordering for three made-up Seattle spots · [**live demo**](https://mileszhanghao.github.io/siuyeh/)
Java 21, Spring Boot 3.5, PostgreSQL, Flyway, Spring Security, React + TypeScript. The add-to-cart race is fixed with an atomic upsert, and checkout records orders with `DELETE … RETURNING`. Testcontainers integration tests include a 20-thread concurrency test.

**[Porchlight](https://github.com/mileszhanghao/porchlight)**: community app for a condo building, with notices, a calendar, room booking and a moderated board · [**live demo**](https://mileszhanghao.github.io/porchlight/)
TypeScript, NestJS, PostgreSQL, Drizzle ORM, React. A solo rewrite of my five-person Flag Camp team project, where I was co-tech lead and worked on the front end. Double bookings are impossible: a PostgreSQL exclusion constraint rejects overlaps, tested with two simultaneous requests.

**[Footnote](https://github.com/mileszhanghao/footnote)**: ask a PDF, and every answer comes with page footnotes · [**live demo**](https://mileszhanghao.github.io/footnote/)
TypeScript, Node, OpenAI tool calling, Model Context Protocol, React. A RAG pipeline indexes each upload once, and an agent loop chooses between document search and an MCP web-search server. The demo runs the same retrieval code entirely in the browser.

**[Drizzle](https://github.com/mileszhanghao/drizzle)**: photo sharing for a rainy city, with AI image generation · [**live demo**](https://mileszhanghao.github.io/drizzle/)
Go, PostgreSQL full-text search, JWT, OpenAI Images, React. The rebuild fixes the course version's plain-text passwords, hard-coded JWT key, sign-up race, and API key exposed in the browser.

### Android

**[Spindle](https://github.com/mileszhanghao/spindle)**: a record player for public-domain recordings · [**listen and download the APK**](https://mileszhanghao.github.io/spindle/)
Kotlin, Jetpack Compose, Media3, Hilt, Room, Ktor. Playback runs in a media session service with background, notification and lock-screen controls. CI runs an emulator test that browses, plays and favorites, and saves screenshots.

## Geospatial and data work (UW coursework)

**Washington State forest disturbance, 2004–2024** — spatial analysis across 271 ecoregions and 36 counties; annual disturbed area grew from about 17 km² to about 128 km² over the period.
**Uneven Shade: Seattle tree-canopy equity, 2016–2021** — mapped census-tract canopy change against Environmental Justice Priority Areas using Seattle Open Data. Shadelines grew out of this.
→ both in [geospatial-data-portfolio](https://github.com/mileszhanghao/geospatial-data-portfolio)

**Douban Chinese film ratings (AMATH 383)** — regression model with Lasso feature selection.

## Community

**[christians-in-seattle-uw](https://github.com/mileszhanghao/christians-in-seattle-uw)** — bilingual (English/Chinese) website for a UW student group, live at [cisuw.com](https://cisuw.com).

---

**Languages:** Python · SQL · Java · TypeScript/JavaScript · Go · Kotlin · R
**Data & GIS:** GeoPandas · dbt · DuckDB · Parquet · ArcGIS Pro · QGIS · MapLibre · R Shiny
**Backend:** Spring Boot · NestJS · Node/Express · Go net/http · PostgreSQL · Docker · GitHub Actions
**Frontend & mobile:** React · Vite · Tailwind CSS · Jetpack Compose
