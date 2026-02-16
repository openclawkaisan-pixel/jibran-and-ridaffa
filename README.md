jibran-and-ridaffa

This is a simple static site (single page) created for Jibran & Ridaffa. Files included:

- index.html
- style.css

How to publish (quick):

1) GitHub Pages (recommended, free):
   - Create a new public repository on GitHub named `jibran-and-ridaffa`.
   - In your local machine, unzip these files, `cd` into the folder, then run:
     ```
     git init
     git add .
     git commit -m "Initial commit"
     git branch -M main
     git remote add origin https://github.com/<your-username>/jibran-and-ridaffa.git
     git push -u origin main
     ```
   - In the repo Settings → Pages, select branch `main` and folder `/ (root)`. Save. Your site will be live at `https://<your-username>.github.io/jibran-and-ridaffa`.

2) Netlify or Vercel: Drag-and-drop the site folder to Netlify's "Sites" area (after signup) or connect the GitHub repo to either service.

If you need, I can generate a simple script to push to a repo once you create it.