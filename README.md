# Lyra Automation Landing Page

A high-converting landing page for Lyra Automation — 24/7 AI voice and chat assistants for HVAC and plumbing businesses.

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `index.html` | Complete landing page with all sections |
| `README.md` | This file — setup and deployment guide |
| `DEPLOYMENT.md` | Detailed deployment options |
| `DOMAIN-GUIDE.md` | Custom domain setup instructions |

---

## ✨ Features

- **8 Sections**: Hero, Problem, Solution, Demo, Pricing, Testimonials, CTA, FAQ
- **Mobile-responsive**: Works perfectly on all devices
- **Fast loading**: <3 seconds on standard connections
- **SEO optimized**: Meta tags, Open Graph, Schema.org structured data
- **Smooth animations**: Fade-in effects, hover states
- **Interactive FAQ**: Collapsible questions
- **Cal.com integration**: Ready for booking embed
- **Chatbot demo placeholder**: Ready for iframe embed

---

## 🎨 Customization Checklist

Before deploying, update these items in `index.html`:

### 1. Branding
- [ ] Replace "🌸 Lyra" with your logo (line 255)
- [ ] Update favicon (add favicon link in `<head>`)
- [ ] Adjust colors in Tailwind config if needed (lines 85-100)

### 2. Contact Information
- [ ] Update email address (line 719, 742, 778)
- [ ] Set up Cal.com account and replace iframe URL (line 631)
- [ ] Add phone number if desired

### 3. Chatbot Demo
- [ ] Replace demo iframe URL with your actual chatbot (line 462)
- [ ] Or remove iframe and use a static screenshot/link

### 4. Pricing (if different)
- [ ] Update setup fees (lines 504, 540)
- [ ] Update monthly fees (lines 508, 544)
- [ ] Adjust features in each plan

### 5. Testimonials
- [ ] Replace placeholder testimonial with real client (lines 574-589)
- [ ] Add more testimonials as you get them

### 6. SEO
- [ ] Update `og:url` meta tag (line 18)
- [ ] Verify all meta descriptions reflect your business
- [ ] Update Schema.org data (lines 27-43)

### 7. Analytics (optional)
- [ ] Add Google Analytics 4 tracking code
- [ ] Or add Plausible/ Fathom analytics

---

## 🚀 Quick Start

### Option 1: Static Hosting (Recommended)

Upload `index.html` to any static hosting service:

- **Netlify**: Drag & drop to deploy
- **Vercel**: Connect GitHub repo or drag & drop
- **Cloudflare Pages**: Fast, free, great for custom domains
- **GitHub Pages**: Free, good for simple sites

### Option 2: Carrd.co (Alternative)

If you prefer Carrd:
1. Sign up at [carrd.co](https://carrd.co)
2. Choose a template or start blank
3. Recreate sections manually (no direct HTML import on free tier)
4. This HTML can serve as reference for content/copy

### Option 3: Traditional Web Hosting

Upload `index.html` to your web server via FTP/SFTP.

---

## 📱 Testing Checklist

Before going live, test:

- [ ] Page loads on mobile (iOS Safari, Android Chrome)
- [ ] All buttons are clickable
- [ ] FAQ accordion works
- [ ] Smooth scroll to sections
- [ ] Cal.com iframe loads (or fallback shows)
- [ ] Demo section displays correctly
- [ ] No console errors (F12 → Console)
- [ ] PageSpeed Insights score > 90

---

## 🔧 Technical Details

### Dependencies
- **Tailwind CSS**: Loaded via CDN (fast, cached)
- **Google Fonts**: Inter font family
- **No JavaScript frameworks**: Pure HTML/CSS/JS for speed

### Performance Optimizations
- Lazy loading on iframes
- Preconnect hints for fonts
- Minimal custom CSS
- No external images (emoji-based visuals)

### Browser Support
- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

---

## 📞 Support

For questions or customization help:
- Email: hello@lyra-automation.com
- Book a call: [Cal.com link]

---

## 📝 License

This landing page template is created for Lyra Automation. Feel free to modify for your use.
