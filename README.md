# DevOps Internship · Task 6

 **Host a static website using GitHub Pages.**

## Preview

Open `index.html` locally or deploy via GitHub Pages to view a responsive single-page site that highlights the task objective, mini guide, checklist, and customization ideas.

## Run Locally

```bash
# from the repo root
python -m http.server 8000
# then visit http://localhost:8000
```

Any static file server works—just make sure `index.html` stays at the repository root.

## Deploy on GitHub Pages

1. Create a new repository and push these files (or fork/import this repo).
2. In the GitHub UI, navigate to `Settings → Pages`.
3. Under **Build and deployment**, choose `Deploy from a branch`, select the `main` branch and the `/ (root)` folder, then click **Save**.
4. Wait for the Pages action to turn green, then use the published URL as your deliverable.

## Customize

- Update the hero text with your name or cohort info.
- Add more sections (timeline, resources, contact form, etc.).
- Adjust styles in `styles.css`, experiment with gradients, or add dark mode.
- Replace Google Fonts with self-hosted assets if needed for restricted environments.


