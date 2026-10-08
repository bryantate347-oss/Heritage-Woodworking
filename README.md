# Heritage Woodworking

A responsive, dependency-free website for Heritage Woodworking. Plain HTML, CSS, and JavaScript; no build command, account, or paid service required to run it.

## Start here

1. Open `index.html` in your browser to view the website.
2. Edit `site-config.js` in a text editor. Set `email` to your business email address. The inquiry button stays disabled until a valid email is added.
3. Replace the three illustrated examples with your actual project photographs. Put photos in `assets/`, then update each project’s `image`, `title`, `category`, and `description` in `site-config.js`. Use Outdoor, Furniture, or Custom for the category so the filters work.
4. Edit the business story in `index.html`. Confirm the service offerings, location, and wording before making the site public. Update the page title and description if you rename the business.

The current gallery uses original SVG illustrations, clearly labeled as examples, rather than photographs of completed work. No reviews, prices, or completed projects are claimed.

## Upload to GitHub

1. Sign in to GitHub and create a new repository named `heritage-woodworking`.
2. Unzip this download. Open the extracted `heritage-woodworking` folder.
3. On GitHub choose **Add file → Upload files** (or the upload link for an empty repository).
4. Upload the **contents** of this folder, including `assets/`. `index.html` must be at the top level of the repository, not inside another `heritage-woodworking` folder.
5. Commit the files. Make sure `.nojekyll` is included; command-line Git can include hidden files reliably.

## Publish with GitHub Pages

In the repository’s **Settings → Pages**, select **Deploy from a branch**, choose **main** and **/(root)**, then save. After deployment, GitHub shows your website address in that page. Relative asset paths support both a repository URL and a custom domain.

If Pages is unavailable for a private repository under your account plan, use a public repository or a hosting service that accepts static websites. Do not put passwords, personal information, or API keys in this repository.

## Optional command-line upload

Run from the extracted project folder, replacing YOUR-USERNAME:

```bash
git init
git add .
git commit -m "Create Heritage Woodworking website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/heritage-woodworking.git
git push -u origin main
```

## Contact behavior

This is a static website, not an order system. The form prepares a `mailto:` draft in the visitor’s configured email app. **The visitor must send the email themselves.** No inquiries are saved or automatically sent. A direct email link is provided once you configure the address. Use a separate form service or backend if you later want reliable automatic form delivery.

## Files

- `index.html`: sections, business story, metadata, and inquiry form
- `styles.css`: forest green, cream, and warm wood visual styling; mobile layout
- `site-config.js`: email, location, slogan, and gallery data
- `script.js`: gallery filters, mobile navigation, and email draft
- `assets/`: original illustrations and favicon; add your photos here

## Checks

JavaScript syntax and local asset references were checked during creation. Browser visual testing was not performed. Preview on phone and desktop before publication. Verify a real inquiry draft opens after adding your email.
