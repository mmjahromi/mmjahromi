# Mohammad Jahromi

### Applied AI · Computer vision · Full-stack products

I build software that connects AI with practical workflows: discovering local businesses, planning better spaces, and reviewing dental images.

[GitHub](https://github.com/mmjahromi) · [Try Perko](https://canpoun.vercel.app)

---

## Selected projects

### 01 — Perko
**Local discovery, deals, events, and flyers in one place.**

Perko brings nearby businesses and offers into a searchable, map-based experience. People can explore local categories, discover events, and search retailer flyers without switching between separate tools.

- Location-aware discovery with map and list views, category filters, and search.
- Shared navigation across Explore, Deals, and Events.
- Event schedules that distinguish confirmed times from date-only listings.
- Flyer browsing with product search and retailer switching.

**Built with:** Next.js, React, TypeScript, Tailwind CSS, Mapbox, libSQL, Zustand, Jest, and Playwright.

[Explore the live app →](https://canpoun.vercel.app)

*Source repository is private.*

---

### 02 — Spacewright
**AI-assisted home staging and space planning.**

Spacewright organizes a home, office, salon, or clinic into a space project with individual zones. Users upload photos, discuss their goals, and compare budget, balanced, and premium design options.

- Local photo analysis and streaming chat through Ollama.
- Photo processing with orientation correction, resizing, and metadata removal.
- Cached analysis and bounded AI concurrency to control repeated work.
- Budget calculation, shopping search links, and an idempotent credit ledger.
- Shared TypeScript schemas across the React frontend and Express API.

**Built with:** React, Vite, TypeScript, Tailwind CSS, Express, SQLite, Zod, and Ollama.

**Stage:** Local MVP. Image generation and production payments are future work; shopping links do not represent live price quotes.

[Related public experiment: object removal with IOPaint →](https://github.com/mmjahromi/home-staging-tool)

*The public experiment is separate from the Spacewright MVP.*

---

### 03 — Denai
**A dental X-ray and CBCT analysis pipeline.**

Denai turns dental images into structured findings and review artifacts. It combines image preprocessing, pluggable detection, anatomy segmentation, and reporting in a reproducible Python workflow.

- DICOM, PNG, and JPG ingestion with CLAHE contrast enhancement.
- YOLO integration for 2D dental findings and DENTEX training workflows.
- DentalSegmentator integration for CBCT anatomy segmentation.
- DICOM de-identification utilities and slice montages.
- JSON and Markdown reports, annotated images, and an HTML review interface.
- Dataset merge safeguards for invalid labels, filename collisions, and exact duplicate images.

**Built with:** Python, OpenCV, pydicom, Pillow, Ultralytics YOLO, and nnU-Net.

**Stage:** Research and decision-support software. Findings require review by a licensed dental professional; Denai is not a validated medical device.

*Source repository is private.*

---

## How I approach engineering

- **Build around a workflow.** Connect models to usable interfaces, APIs, and outputs.
- **Keep systems modular.** Separate ingestion, processing, providers, storage, and presentation.
- **Make limits visible.** Distinguish implemented features, experiments, and future work.
- **Verify at the right level.** Use automated tests, browser checks, and reproducible evaluation where they matter.

## Technical focus

| Area | Tools and methods |
| --- | --- |
| Product engineering | TypeScript, React, Next.js, Express, REST APIs |
| Applied AI | Ollama, vision-language models, streaming inference, caching |
| Computer vision | Python, OpenCV, YOLO, segmentation, DICOM |
| Data and reliability | SQLite/libSQL, schema validation, dataset integrity, testing |

Browse my [public repositories](https://github.com/mmjahromi?tab=repositories) for more experiments in AI, computer vision, and software engineering.
