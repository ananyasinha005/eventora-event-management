# Eventora — Event Management Website

A responsive event discovery and registration website built with **HTML5, CSS3 and vanilla JavaScript** for the K Explore – Web Designing task.

## Features
- Modern landing page with hero section, featured events and responsive navigation.
- Six sample events with event images, dates, venues, categories and descriptions.
- Live search across event title, venue, category and description.
- Category filters for Music, Technology, Art & Culture and Lifestyle.
- Event detail modal with event information and a countdown in days.
- Registration form with JavaScript validation for name, email, Indian mobile number and event selection.
- Registration confirmation after successful submission.
- Registrations saved in browser `localStorage` under `eventoraRegistrations`.
- Light/dark theme toggle, mobile menu, keyboard-accessible event cards and reduced-motion support.

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a browser.
3. No build tools or dependencies are required.

For the best development experience, use the VS Code **Live Server** extension.

## Project structure
```text
eventora-event-management/
├── index.html
├── style.css
├── script.js
└── README.md
```

## Customize the events
Edit the `events` array near the top of `script.js`. Each event has:
- `id`, `title`, `category`
- `date` in `YYYY-MM-DD` format
- `time`, `venue`, `image`, `description`, `tag`

The sample events and venues are demonstration content. Replace them with verified event information before publishing.

## Registration data
This is a front-end demo. Registration details are saved only in the visitor's browser using `localStorage`; there is no server, email delivery, or shared database. Do not use this demo to collect real sensitive personal information. A production version needs a secure backend and privacy notice.

## Deploy
### GitHub Pages
1. Create a GitHub repository and upload these files to the repository root.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select `main` and `/ (root)`, then save.
5. Wait for the published URL to appear in the Pages section.

### Netlify
1. Sign in to Netlify and choose **Add new site → Deploy manually**.
2. Drag the project folder (or its contents) into the deploy area.
3. Netlify will provide a public website URL.

## Credits
- Fonts: DM Sans and Space Grotesk via Google Fonts.
- Event photography: Unsplash remote image URLs.
- Built as a student front-end project.
