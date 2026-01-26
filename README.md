# DigiCards Website

Modern landing page for DigiCards - the smart business card scanner app.

## Preview Locally

Open `index.html` directly in your browser, or use a local server:

```bash
cd /home/sha-f-linux/my-Projects/website
python3 -m http.server 8080
```

Then visit: http://localhost:8080

## Deploy to GitHub Pages (Free)

### Step 1: Create a GitHub Repository

1. Go to https://github.com/new
2. Name it `digicards-website` (or any name you prefer)
3. Make it **Public**
4. Click "Create repository"

### Step 2: Push the Website

```bash
cd /home/sha-f-linux/my-Projects/website
git init
git add .
git commit -m "Initial website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/digicards-website.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Source", select **Deploy from a branch**
4. Choose **main** branch and **/ (root)** folder
5. Click **Save**

Your site will be live at: `https://YOUR_USERNAME.github.io/digicards-website/`

## Custom Domain (Optional)

To use a custom domain like `digicards.app`:

1. Buy a domain from Namecheap, Google Domains, etc.
2. In GitHub Pages settings, enter your custom domain
3. Add DNS records at your domain provider:
   - A record: `185.199.108.153`
   - A record: `185.199.109.153`
   - A record: `185.199.110.153`
   - A record: `185.199.111.153`
   - CNAME: `www` → `YOUR_USERNAME.github.io`

## Design Features

- Modern 2025-2026 UI/UX trends
- Glassmorphism elements
- Gradient backgrounds
- Mobile-first responsive design
- Smooth scroll animations
- Bento grid layout
- CSS-only animations (no JavaScript dependencies)
- Fast loading (no external JS libraries)

## Files

- `index.html` - Main HTML structure
- `styles.css` - All styling with CSS variables

## Customization

Edit CSS variables in `styles.css` to change colors:

```css
:root {
    --primary: #6366f1;        /* Main brand color */
    --primary-dark: #4f46e5;   /* Darker shade */
    --primary-light: #818cf8;  /* Lighter shade */
    /* ... */
}
```
