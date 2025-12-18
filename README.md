# TidyPhone Landing Page

Landing page for the TidyPhone iOS app, hosted on GitHub Pages.

## Setup for GitHub Pages

1. Push this repository to GitHub: `https://github.com/juzkay/TidyPhoneLandingPage`

2. Go to your repository settings on GitHub

3. Navigate to **Pages** in the left sidebar

4. Under **Source**, select:
   - Branch: `main` (or `master`)
   - Folder: `/ (root)`

5. Click **Save**

6. Your site will be available at: `https://juzkay.github.io/TidyPhoneLandingPage/`

## Custom Domain Setup

To use your custom domain:

1. Add a file named `CNAME` in the root directory with your domain name:
   ```
   yourdomain.com
   ```

2. Configure your DNS settings:
   - **A Record**: Point to GitHub Pages IP addresses:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - **CNAME Record**: Point `www` subdomain to `juzkay.github.io`

3. Enable HTTPS in GitHub Pages settings (automatic after DNS propagation)

## Updating the App Store Link

When your app is submitted to the App Store, update the App Store download link in `index.html`:

```html
<a href="YOUR_APP_STORE_URL" class="app-store-btn" id="app-store-link">
```

## Replacing the App Icon

Replace `assets/App Icon.svg` with your actual app icon. Recommended size: 1024x1024px.

## SEO Features

This landing page includes comprehensive SEO optimization:

- **Meta Tags**: Optimized title, description, and keywords
- **Open Graph Tags**: For better social media sharing
- **Structured Data**: JSON-LD schema for search engines
- **Semantic HTML**: Proper HTML5 semantic elements
- **Robots.txt**: Search engine crawler instructions
- **Sitemap.xml**: Site structure for search engines
- **Keywords**: Integrated naturally throughout content including:
  - iPhone storage cleaner
  - Delete duplicate photos
  - Compress videos
  - Remove screenshots
  - Clean contacts
  - Storage almost full
  - Free up iPhone storage

All keywords are naturally integrated into the content for better search engine rankings.

## Local Development

Simply open `index.html` in a web browser, or use a local server:

```bash
# Python 3
python3 -m http.server 8000

# Node.js (with http-server)
npx http-server
```

Then visit `http://localhost:8000`

