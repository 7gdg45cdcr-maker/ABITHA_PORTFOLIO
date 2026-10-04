# Abitha Chokka — Personal Portfolio

A responsive, recruiter-friendly personal portfolio built with **HTML, CSS, and vanilla JavaScript**. No framework, build step, or paid service is required.

## Files

- `index.html` — portfolio content and page structure
- `styles.css` — dark navy/blue responsive design
- `script.js` — mobile navigation, current year, and reveal animations
- `assets/Abitha-Chokka-Resume.pdf` — add your resume PDF here before publishing

## Run locally

1. Download and unzip the project.
2. Add your latest resume PDF at `assets/Abitha-Chokka-Resume.pdf`.
3. Open `index.html` in a browser.

For a local server (optional), open a terminal in this folder and run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Before publishing — important checks

1. **Resume:** place your current resume at `assets/Abitha-Chokka-Resume.pdf`. If you use a different filename, update the link in `index.html`.
2. **Project repositories:** the project buttons currently point to your GitHub profile because exact repository URLs were not provided. Replace each with the direct public repository URL.
3. **Dates and descriptions:** confirm internship dates, official program names, education details, and descriptions against your records. Edit these directly in `index.html`.
4. **Certifications:** keep only certificates you completed. Add credential URLs if available.
5. **Email:** the contact email is `abithachokka@gmail.com`; change it in `index.html` if needed.
6. **Skills:** remove any technology you cannot comfortably discuss in an interview.
7. **Privacy:** only publish contact details you want recruiters and the public to see.

## Free deployment option A — GitHub Pages

1. Sign in to GitHub and create a **public** repository, for example `abitha-portfolio`.
2. Upload `index.html`, `styles.css`, `script.js`, the `assets` folder, and this README to the repository root.
3. Ensure `index.html` is at the root (not inside another nested folder).
4. Open the repository's **Settings → Pages**.
5. Under build/deployment, choose **Deploy from a branch**.
6. Select the `main` branch and `/(root)`, then save.
7. Wait for the deployment to finish. The Pages section will show your public URL, usually `https://YOUR-USERNAME.github.io/abitha-portfolio/`.

Every time you push a change to the selected branch, GitHub Pages can publish the updated static site. If Pages is not available, check the repository visibility and GitHub plan/settings.

## Free deployment option B — Netlify

1. Create a free account at Netlify.
2. Choose **Add new site / Import an existing project** and connect your GitHub account.
3. Select your portfolio repository.
4. Since this is plain HTML/CSS/JS, leave the build command blank and set the publish directory to the repository root (`.`).
5. Deploy. Netlify will provide a public `*.netlify.app` URL.
6. For updates, push changes to the connected repository and Netlify will redeploy.

You can also use Netlify's manual deploy flow by dragging the project folder contents into its deploy area, but connecting GitHub is easier for future updates.

## Add the portfolio to LinkedIn

1. Open your LinkedIn profile and choose **Add profile section**.
2. Add the portfolio URL under **Featured** (recommended) and/or **Contact info → Website**.
3. Use a title such as **Personal Portfolio | Software Development Projects**.
4. Add the same URL to your resume under your contact links. Keep the URL short and readable.

## Final recruiter checklist

- [ ] Resume download works after adding the PDF
- [ ] LinkedIn and GitHub links open the correct profiles
- [ ] Both project buttons link to the correct repositories
- [ ] No placeholder, incorrect, or unverified claims remain
- [ ] Site works on a phone and desktop
- [ ] Portfolio URL is added to LinkedIn and resume
