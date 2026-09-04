# Zhaoran Zhang — Academic Website

A minimal static academic website designed for GitHub Pages.

## Fastest way to publish

1. Create a GitHub repository named:

   `YOUR_GITHUB_USERNAME.github.io`

2. Upload these files to the root of the repository:

   - `index.html`
   - `styles.css`
   - `robots.txt`

3. Commit the files.

4. Open:

   `https://YOUR_GITHUB_USERNAME.github.io`

For a repository with exactly the `<username>.github.io` name, GitHub Pages normally serves the site directly from the repository.

## If you use another repository name

For example, `academic-website`:

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)`.
5. Save.

Your URL will usually be:

`https://YOUR_GITHUB_USERNAME.github.io/academic-website/`

## Recommended small edits

### Add Google Scholar / ORCID / GitHub

In `index.html`, find:

```html
<!-- Optional links:
```

Remove the surrounding HTML comment and replace:

- `YOUR_GOOGLE_SCHOLAR_URL`
- `YOUR_ORCID_URL`
- `YOUR_GITHUB_URL`

with your actual profile links.

### Add a CV later

Put a PDF such as `Zhaoran_Zhang_CV.pdf` in the same repository and add:

```html
<a href="Zhaoran_Zhang_CV.pdf">CV</a>
```

wherever you want the CV link to appear.

## Search visibility

The homepage already contains:

- Zhaoran Zhang
- 张昭然
- email address
- sensorimotor control
- motor learning
- computational neuroscience
- Shenzhen University

It also includes a descriptive page title, meta description, search-engine indexing instruction, and Schema.org `Person` metadata.

After the site is online, Google may take some time to index a new GitHub Pages site. Search visibility usually improves as the page is linked from places such as your institutional profile, Google Scholar, ORCID, GitHub profile, publications, or other academic pages.
