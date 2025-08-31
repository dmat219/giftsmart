# GiftSmart Pro Website

A modern, responsive website for GiftSmart Pro - the intelligent birthday and gift management app.

## 🌟 Features

- **Responsive Design** - Works perfectly on all devices
- **Modern UI/UX** - Clean, professional design with smooth animations
- **SEO Optimized** - Proper meta tags and semantic HTML
- **Fast Loading** - Optimized CSS and JavaScript
- **Mobile First** - Designed with mobile users in mind

## 📱 Pages

1. **Home/About** (`index.html`) - Main landing page with app overview
2. **Features** (`features.html`) - Detailed feature breakdown
3. **Support** (`support.html`) - FAQ and contact information
4. **Privacy Policy** (`privacy.html`) - Complete privacy policy

## 🚀 Getting Started

### Prerequisites
- A web server or hosting service
- Domain name (e.g., `www.giftsmartapp.com`)

### Local Development
1. Clone this repository
2. Open any HTML file in your browser
3. Or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

## 🎨 Customization

### Colors
The main color scheme can be modified in `css/style.css`:
- Primary Blue: `#2563eb`
- Dark Gray: `#1f2937`
- Light Gray: `#f8fafc`

### Fonts
The website uses Inter font from Google Fonts. You can change this in the HTML files and CSS.

### Content
Update the content in each HTML file to match your specific needs.

## 📁 File Structure

```
giftsmart-website/
├── index.html          # Homepage
├── features.html       # Features page
├── support.html        # Support page
├── privacy.html        # Privacy policy
├── css/
│   └── style.css      # Main stylesheet
├── js/
│   └── script.js      # JavaScript functionality
└── README.md          # This file
```

## 🌐 Deployment

### GitHub Pages
1. Push this repository to GitHub
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Set custom domain if desired

### Netlify
1. Drag and drop the folder to Netlify
2. Set custom domain in settings
3. Configure DNS records

### Vercel
1. Connect your GitHub repository
2. Deploy automatically
3. Set custom domain in settings

## 🔧 Custom Domain Setup

### DNS Configuration
Add these records to your domain registrar:

**For GitHub Pages:**
```
Type: CNAME
Name: www
Value: yourusername.github.io
```

**For Netlify/Vercel:**
```
Type: CNAME
Name: www
Value: your-site.netlify.app (or vercel.app)
```

### SSL Certificate
Most hosting providers automatically provide SSL certificates for custom domains.

## 📱 App Store Integration

This website is designed to support your iOS app submission:

- **Privacy Policy URL**: `https://www.giftsmartapp.com/privacy.html`
- **Support URL**: `https://www.giftsmartapp.com/support.html`
- **Marketing URL**: `https://www.giftsmartapp.com`

## 🎯 SEO Features

- Semantic HTML structure
- Meta descriptions for each page
- Proper heading hierarchy
- Alt text for images
- Mobile-friendly design
- Fast loading times

## 🔒 Privacy & Security

- No tracking scripts
- No analytics (unless you add them)
- HTTPS ready
- Privacy-focused design

## 📞 Support

For website support or questions:
- **Email**: support@giftsmartapp.com
- **Issues**: Create an issue in this repository

## 📄 License

This website is created for GiftSmart Pro. All rights reserved.

## 🚀 Future Enhancements

Potential improvements:
- Blog section for app updates
- User testimonials
- App download tracking
- Contact forms
- Newsletter signup
- Social media integration

---

**Built with ❤️ for GiftSmart Pro**

