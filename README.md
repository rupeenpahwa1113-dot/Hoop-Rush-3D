Hoop Rush 3D

A 3D basketball game that runs entirely in the browser. The whole game is one file, index.html.

Run it locally

Open index.html in a browser, or serve the folder:

python3 -m http.server 8000
Deploy on Render (Static Site)
Render dashboard > New > Static Site > connect this repo.
Build Command: leave empty (or echo ok).
Publish Directory: .
Create Static Site. Render gives you an https URL to share.

(render.yaml in this repo does the same thing if you use Blueprints.)

Notes
Accounts, friends and online play use Supabase through the keys inside index.html.
