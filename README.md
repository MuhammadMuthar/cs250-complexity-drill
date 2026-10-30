# CS-250 Complexity Drill

A single-page study tool for Big O, Omega and Theta (CS-250 Data Structures and Algorithms): worked solutions for the array-operations quiz and Lab Quiz 4-6, an interactive bound plotter, and practice drills.

It is plain static HTML, CSS and JavaScript in `index.html`. There is no build step and no dependencies. The only external request is Google Fonts, and the page falls back to system fonts without it.

## Run locally

Open `index.html` in a browser, or run `python3 -m http.server` and visit http://localhost:8000.

## Deploy on Vercel

1. Push this repo to GitHub.
2. On vercel.com choose **Add New, Project** and import the repo.
3. Set **Framework Preset** to **Other**.
4. Leave **Build Command** and **Output Directory** empty (the root is served as is).
5. Click **Deploy**.
