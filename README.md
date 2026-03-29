# Personal Website — Ashutosh Sharma

A clean, responsive personal website for academic and professional portfolio.

## Hosting on GitHub Pages

1. Go to your repo on GitHub: **Settings → Pages**
2. Under **Source**, select **Deploy from a branch**
3. Set branch to `main` and folder to `/ (root)`
4. Click **Save**
5. Your site will be live at `https://ashutoshuiuc.github.io/website/` within a few minutes

### Making the repo public

GitHub Pages for free accounts requires a **public** repository (unless you have GitHub Pro). To make it public:

1. Go to **Settings → General** (scroll to bottom)
2. Under **Danger Zone**, click **Change visibility**
3. Select **Public** and confirm

### Using a custom domain (optional)

1. In **Settings → Pages**, enter your custom domain
2. Create a `CNAME` file in the repo root with your domain name
3. Configure DNS with your domain provider (CNAME record pointing to `ashutoshuiuc.github.io`)

## Local Development

Just open `index.html` in a browser — no build tools required.

## Updating Content

- Edit `index.html` directly to update sections
- Replace the avatar placeholder with a real photo in `assets/img/`
- Update publication links (search for `TODO` in index.html)
