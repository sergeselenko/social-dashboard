# Social Dashboard

TV social media + ad performance dashboard for Serge (Selenko). Static GitHub Pages site.

- Open index.html (or the Pages URL), enter passcode 2023. Unlock persists for the browser session.
- Live: https://sergeselenko.github.io/social-dashboard/
- Figures live in data.json and refresh daily: the page fetches data.json on load and every 30 minutes. index.html carries the same data embedded as a fallback.
- Sources: Postiz (organic channels + per-post stats), Meta Ads (HVAC campaign), GA4 (Trades), Search Console. A metric a source does not report shows as —, never zero-filled.
- Builder: ~/workspace/social-dashboard-build/build_data.py regenerates data.json from the two dashboard getdashboard dumps.
