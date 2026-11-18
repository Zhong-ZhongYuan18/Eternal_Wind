# ZhongZhongYuan Portfolio

A minimalist personal portfolio for architecture, photography and academic research, built with Astro and prepared for GitHub Pages.

## 1. Before publishing

1. Create a GitHub repository named `zhongzhongyuan-portfolio` (or choose another repository name).
2. Open `astro.config.mjs`.
3. Replace `YOUR-GITHUB-USERNAME` with your GitHub username.
4. Set `base` to `'/zhongzhongyuan-portfolio'` if using a project repository. If your repository is named `YOUR-GITHUB-USERNAME.github.io`, set `base: '/'`.
5. Replace the sample projects and placeholder images in `src/data/projects.js` with your own work.
6. Update the About and Contact pages with your real biography, CV and contact details.

## 2. Run locally

Install Node.js 20 or later, then run:

```bash
npm install
npm run dev
```

Open the local URL shown in the terminal.

## 3. Build and preview

```bash
npm run build
npm run preview
```

The production website is generated in `dist/`.

## 4. Deploy to GitHub Pages

1. Push this project to the `main` branch of your GitHub repository.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **GitHub Actions** as the source.
4. The included `.github/workflows/deploy.yml` builds and deploys the website on every push to `main`.
5. After the workflow succeeds, your site will be available at `https://YOUR-GITHUB-USERNAME.github.io/zhongzhongyuan-portfolio/`.

## 5. Add and edit content

- Architecture projects: `src/data/projects.js` → `architectureProjects`
- Photography: `src/data/projects.js` → `photographyProjects`
- Research: `src/data/projects.js` → `researchProjects`
- Personal information: `src/pages/about.astro`
- Contact links: `src/pages/contact.astro`
- Global design: `src/styles/global.css`

Use descriptive image filenames and place your own images under `public/images/`. Then update the corresponding image paths in `src/data/projects.js` to `/zhongzhongyuan-portfolio/images/...` for a project repository, or `/images/...` for a user-site repository.

## 6. Important content note

All current project descriptions and research entries are illustrative placeholders, not claims about completed work or publications. Replace them with accurate information before making the website public. The remote Unsplash images are temporary visual placeholders; use your own images for the final portfolio.
