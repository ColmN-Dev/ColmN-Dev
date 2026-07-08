# Colm Nolan
## Full-Stack Web Developer

📧 colmjcnolan34@gmail.com

---

Full-stack developer completing a Full-Stack Software Development Diploma at UCD Professional Academy. Builds and deploys full-stack web applications using Python, Flask, and modern frontend technologies, with a focus on database design, API integration, and authentication systems. Comfortable owning a project end-to-end — from schema design through deployment.

---

## Skills & Technologies

**Frontend:** HTML5, CSS3, JavaScript, Jinja2
**Backend:** Python, Flask, SQL
**Databases:** PostgreSQL, SQLite, SQLAlchemy ORM, Flask-Migrate
**Frameworks & Runtime:** Flask, Astro, Node.js
**APIs & Integration:** REST APIs, Google Books API, TheMealDB API, CheapShark API
**Tools & Deployment:** Git, GitHub, Render, pgAdmin

---

## Projects

### BiblioTech — Full-Stack Flask Web Application

🔗 [Live Demo](https://bibliotech-ifum.onrender.com) · 🔗 [GitHub](https://github.com/ColmN-Dev/BiblioTech)

A book discovery and review platform built to a higher architectural standard than previous projects — application factory pattern, Blueprint routing, and a proper relational schema instead of a flat single-app structure.

- Structured the app with Flask's factory pattern and Blueprints, separating concerns across a four-table PostgreSQL schema (Users, Books, User_Library, Reviews)
- Built a Google Books API integration layer handling search, randomised carousel content, and detail lookups, with fallback handling for missing covers/authors
- Managed schema changes through Flask-Migrate and SQLAlchemy ORM rather than manual SQL
- Designed a custom UI system (Cinzel/Roboto type, dark mode, frosted-glass header) and a colour-coded flash message system for user feedback
- Hardened API key handling after an early exposure incident — rotated the key and enforced `.env` exclusion via `.gitignore`

### GlobalGrub — Full-Stack Flask Web Application

🔗 [Live Demo](https://globalgrub-tsyf.onrender.com/) · 🔗 [GitHub](https://github.com/ColmN-Dev/GlobalGrub)

A database-driven recipe app with authentication and personalised user data, deployed live on Render.

- Built session-based authentication with Flask-Bcrypt password hashing
- Integrated TheMealDB REST API for dynamic recipe search and filtering
- Added a persistent, user-specific favourites system backed by SQLAlchemy/SQLite
- Handled API and input edge cases (missing data, failed requests) without breaking the UI
- Deployed to Render with environment-aware config

### GameVault — Frontend Game Discovery Application

🔗 [Live Demo](https://colmn-dev.github.io/GameVault/) · 🔗 [GitHub](https://github.com/ColmN-Dev/GameVault)

A JavaScript SPA for browsing game deals via the CheapShark API.

- Built dynamic search and genre-browsing UI backed by live API data
- Implemented persistent dark mode via localStorage and regex-based client-side form validation
- Fully responsive across desktop, tablet, and mobile

### Saykan Combat Sports — Astro Static Website

🔗 [Live Demo](https://colmn-dev.github.io/Astro-Static-Project/) · 🔗 [GitHub](https://github.com/ColmN-Dev/Astro-Static-Project)

A multi-page marketing site built with Astro's component model.

- Built reusable, component-based page layouts with semantic, accessible markup
- Integrated image galleries and embedded multimedia
- Responsive across screen sizes

---

## Current Focus

Deepening backend architecture skills (schema design, ORM workflows, migrations) while tightening frontend consistency and deployment practices — using each project to intentionally raise the complexity bar over the last one.

---

## Career Goal

Looking to start a professional career in full-stack development, continuing to build real-world projects and grow through collaborative, production-grade engineering practice.
