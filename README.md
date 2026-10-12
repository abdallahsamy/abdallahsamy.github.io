# Dr. Abdallah Samy — Academic GitHub Pages Website

A responsive teal-and-white personal academic website built with HTML, CSS, and JavaScript. No build tools, paid hosting, or external libraries are required.

## Before publishing: personalise these details

- **Official position and affiliation:** Verify the exact wording of your Associate Professor position, Ain Shams University affiliation, and Director of the One Health Unit at the Medical Ain Shams Research Institute (MASRI), Faculty of Medicine.
- **Publications:** Replace the sample entries in `index.html` with verified citations and direct DOI/journal links. The sample entries are placeholders, not real publication records.
- **Profiles:** Replace generic ORCID and Google Scholar links with your exact public profile URLs.
- **Code repositories:** Replace generic GitHub links with the URLs of your actual repositories (for example, SDMECO and other tools, if public).
- **Contact:** Add a professional email address only if you want it displayed publicly.
- **Projects:** Review project summaries and remove anything you do not wish to describe publicly.

## Publish on GitHub Pages

### 1. Create the repository

1. Sign in to GitHub and visit https://github.com/new
2. Name the repository exactly `YOUR-GITHUB-USERNAME.github.io`, replacing the placeholder with your GitHub username.
3. Choose **Public**, then click **Create repository**. You can initialise it with a README or leave it empty.

For a personal user site, the repository name must match `username.github.io`. Your site URL will be `https://username.github.io/`.

### 2. Upload the website files

1. Download and unzip the website package.
2. Open your new repository on GitHub.
3. Select **Add file → Upload files**.
4. Upload `index.html`, `README.md`, and the `assets` folder with its contents. Preserve the folder structure.
5. Add a commit message such as `Add academic website`, then select **Commit changes**.

Expected structure:

```text
YOUR-GITHUB-USERNAME.github.io/
├── index.html
├── README.md
└── assets/
    ├── css/style.css
    ├── js/main.js
    └── img/favicon.svg
```

### 3. Enable GitHub Pages

1. Open the repository **Settings**.
2. Select **Pages** in the sidebar.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/(root)`.
5. Click **Save**.

GitHub will publish the site, often within a few minutes. Check **Settings → Pages** or the repository's **Actions** tab for status or errors.

### 4. Visit the website

Open `https://YOUR-GITHUB-USERNAME.github.io/`, replacing the placeholder with your actual GitHub username. If it is not visible immediately, wait a few minutes and refresh.

## Updating the site

Edit `index.html` on GitHub for text and links, `assets/css/style.css` for colours/layout, or `assets/js/main.js` for navigation behaviour. Commit your changes and GitHub Pages republishes the site automatically.

## Privacy, accessibility, and maintenance

- Everything committed to a public repository is public. Never add passwords, API keys, private correspondence, confidential data, or personal details you do not want indexed.
- Publish only papers, figures, and datasets you have permission to share.
- Review profile links, affiliation wording, and publication records periodically.
- This is a static site; it does not include a server-side form or database.
- Optional: connect a domain you own through **Settings → Pages → Custom domain**. A custom domain is not required.
