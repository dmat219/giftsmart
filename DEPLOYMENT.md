# Website Deployment Guide

## Linking Your Domain to GitHub Pages

### 1. Enable GitHub Pages
1. Go to your repository: https://github.com/dmat219/giftsmart
2. Click **Settings** tab
3. Scroll to **Pages** in left sidebar
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**

### 2. Configure Custom Domain
1. In **Pages** section, under **Custom domain**
2. Enter: `www.giftsmartapp.com`
3. Check **Enforce HTTPS**
4. Click **Save**

### 3. DNS Configuration
Configure your domain registrar's DNS settings:

**CNAME Record:**
- **Type:** CNAME
- **Name:** www
- **Value:** `dmat219.github.io`
- **TTL:** 3600

**A Record (for root domain):**
- **Type:** A
- **Name:** @
- **Value:** `185.199.108.153`
- **TTL:** 3600

### 4. Automatic Deployment
The GitHub Actions workflow (`.github/workflows/deploy.yml`) will automatically deploy your website whenever you push changes to the `website/` folder.

### 5. Verify Setup
- Wait for DNS propagation (up to 48 hours)
- Check GitHub Pages status in repository settings
- Visit `www.giftsmartapp.com` to confirm it's working

## Making Updates
1. Edit files in the `website/` folder
2. Commit and push changes: `git add website/ && git commit -m "Update website" && git push`
3. GitHub Actions will automatically deploy the updates

## Troubleshooting
- Check GitHub Pages status in repository settings
- Verify DNS records are correct
- Ensure CNAME file contains `www.giftsmartapp.com`
- Check GitHub Actions tab for deployment status
