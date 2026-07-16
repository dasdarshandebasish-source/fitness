DEBASISH DISCIPLINE DASHBOARD v4 — CONSOLIDATED RELEASE
======================================================

INCLUDED
- Editable day-by-day timeline
- Editable planned meals and actual meal logging
- Editable workouts and rainy-day indoor alternatives
- Editable study topics, start times and planned durations
- Actual workout and study records
- Apple Calendar exports with 10-minute alerts
- Automatic overall, fitness, meal and study scores
- Four circular percentage wheels
- Detailed score breakdowns and 30-day history
- End-of-day score snapshots
- iPhone Home Screen PWA support and offline caching

SCORING
Overall score:
- Fitness: 25%
- Meals: 25%
- Study: 35%
- Routine discipline: 15%

The score measures adherence and logging. It is not medical advice and does not
judge whether you followed the original menu exactly.

PUSH TO YOUR WORKING GITHUB REPOSITORY
1. Open the working discipline-dashboard repository.
2. Upload and replace index.html.
3. Also replace sw.js so iPhone receives the new cache version.
4. Upload the manifest and icon files only if they are missing.
5. Commit the changes.
6. Wait for the GitHub Pages deployment to turn green.

IPHONE REFRESH
Because the dashboard is installed as a web app, the old service-worker cache may
remain temporarily:
1. Open the GitHub Pages URL in Safari and refresh it.
2. Close and reopen the Home Screen app.
3. If v4 still does not appear, remove the Home Screen icon, open the site in
   Safari, and use Share > Add to Home Screen again.

DATA
Replacing GitHub files does not delete browser localStorage at the same website
address. Export a JSON backup before updating as an extra precaution.
