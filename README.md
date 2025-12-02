# OCCTET-CRA-self-assessment

OCCTET is a free, open-source self-assessment platform that helps organisations — especially SMEs — measure their preparedness against the EU Cyber Resilience Act (CRA). The project is part of the Open CyberSecurity Compliance Toolkit (OCCTET) and is funded by the EU Digital Europe Programme.


## What this repository contains
- Self-assessment web app (frontend) located at `exp.Frontend`
- UI components and static assets for the public-facing site and assessment flows


## Quick start — run the frontend locally

Prerequisites
- Node.js (recommended 16+)
- npm (or use an alternative package manager like `pnpm`/`yarn`)

Steps
1. Clone the repository
   - `git clone https://github.com/expertware/OCCTET-CRA-self-assessment.git`
2. Start the frontend
   - `cd OCCTET-CRA-self-assessment/exp.Frontend`
   - `npm install`
   - `npm run dev`
3. The Vite dev server will start (by default on `http://localhost:5173/`) and hot-reload on changes.

Build for production
- From `exp.Frontend` run:
  - `npm run build`
- The production build output will be produced in the configured `dist` folder.

## Contributing
Contributions are welcome. To contribute:
1. Fork the repository
2. Implement your change on a topic branch
3. Open a pull request with a clear description of the change and any manual testing steps

If you plan larger feature work or architecture changes, open an issue first to discuss the approach.

## Issues & support
- Use the repository Issues for bug reports, feature requests, and questions.
- For project-related inquiries, refer to the project website: https://occtet.eu

