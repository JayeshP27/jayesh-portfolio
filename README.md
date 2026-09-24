# Jayesh Phadkar — Portfolio

Personal portfolio for product design, R&D and NPI work. Static HTML/CSS/JS — no build step — hosted on GitHub Pages.

## Structure

```
index.html                 Home: hero, work, about, experience, skills, certifications, snapshots, contact
work/*.html                One page per case study
assets/css/style.css       All styles (light + dark theme tokens at the top)
assets/js/main.js          Nav, theme toggle, lightbox, snapshot filters, scroll reveal
assets/img/                Optimized images
assets/Jayesh_Phadkar_Resume.pdf
```

## Edit locally

Open the folder in VS Code and use the **Live Server** extension (right-click `index.html` → *Open with Live Server*), or just double-click `index.html`.

## Publish changes

```bash
git add .
git commit -m "Update portfolio"
git push
```

GitHub Pages redeploys automatically within a minute or two.
