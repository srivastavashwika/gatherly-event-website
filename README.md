# Gatherly — Event Management Website

A responsive event discovery and registration website built with **HTML5, CSS3 and vanilla JavaScript**.

## Features
- Editorial-style homepage with responsive navigation and event showcase
- Search events by title, category, venue or description
- Category filters for Music, Technology, Art & Culture and Lifestyle
- Event detail modal with venue, date, description and registration CTA
- Registration form with name, email and phone validation
- Successful registration confirmation
- Local Storage for registrations, saved/favourite events and theme preference
- Dark/light mode, countdown timer, mobile menu and UI transitions
- Responsive layouts for desktop, tablet and mobile

## Run locally
No build step or dependencies are required. Open `index.html` in a browser, or run a local static server:

```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

## Deploy to Vercel
1. Import this GitHub repository into Vercel.
2. Framework Preset: **Other**. Build Command: leave blank. Output Directory: `.`.
3. Click **Deploy**.

## Notes
Event names, dates, venues and prices are illustrative demo content. Registration data is stored only in the visitor's browser using Local Storage; this static demo does not send data to a server. Replace sample event details and connect a backend before using it for real registrations.
