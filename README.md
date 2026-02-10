# Brandon Barnes - 90s Sports-Inspired Personal Website 🏀

## 🎨 Design Inspiration

This site channels the bold, energetic aesthetics of 90s sports logos:
- **Phoenix Suns** - Purple & orange color combo
- **Montreal Expos** - Bold typography and vibrant blues
- **Teal Era** - That classic 90s teal we all love
- **Trading Cards** - Border treatments and stat displays
- **Championship Banners** - Section layouts with dramatic flair

## ⚡ What Makes This Fun

### Visual Style
- **Bold Bangers font** for headlines (think championship banners)
- **Racing Sans One** for that sporty edge
- **Vibrant color palette**: Suns purple (#1d1160), orange (#e56020), teal (#00a6a6), electric yellow (#ffd700)
- **Geometric patterns** inspired by basketball courts
- **Deep shadows** and **angled clip-paths** for that 3D trading card effect
- **Animated backgrounds** with retro patterns

### Interactive Elements
- Jersey number-style section badges
- Basketball emoji bounce animation
- Trading card hover effects
- Skill tags that rotate on hover
- Championship banner-style sections

## 📋 Your Info (Auto-Filled)

All your resume details have been pulled in:
- ✅ Contact: brandonbarnes0402@gmail.com, (512) 925-5953
- ✅ Location: Austin, TX
- ✅ Current role: Sr Mid-Market AE at Agicap
- ✅ All work history from LogicMonitor, Vanta, Texas A&M
- ✅ Stats: $1.3M ARR, 100%+ quota, #1 BDR
- ✅ Skills: Storytelling, improvisation, leadership, etc.
- ✅ Education: Texas A&M Sport Management (3 years!)

## 🚀 Quick Start

### Upload to Hostinger
1. Log into Hostinger
2. Go to File Manager
3. Navigate to `public_html`
4. Upload `index.html`
5. Your site is LIVE! 🎉

### Test Locally
Just open `index.html` in any browser

## ✏️ Customization Tips

### 1. Add Your Project Links

Update the media cards to link to your actual work:

```html
<!-- Change this: -->
<div class="media-card" data-link="#">

<!-- To this: -->
<div class="media-card" data-link="https://medium.com/@brandon/article">
```

Currently only Full Court Press is linked. Add URLs for:
- Podcast appearances
- Creative projects
- Basketball-related content
- Sales essays
- Industry analysis

### 2. Update LinkedIn URL

Find this line (around line 610):
```html
<a href="https://linkedin.com/in/brandon-barnes-sales" ...>
```
Replace with your actual LinkedIn URL.

### 3. Add More Work Experience

To add another job, copy a job-card block:
```html
<div class="job-card fade-in">
    <h3 class="job-title">Your Job Title</h3>
    <div class="job-meta">Company • Location • Dates</div>
    <ul class="job-description">
        <li>Achievement with 🏀 emoji bullet</li>
        <li>Another accomplishment</li>
    </ul>
</div>
```

### 4. Change Colors (If You Want)

The 90s palette is set in CSS variables (line ~35):
```css
--color-suns-purple: #1d1160;
--color-suns-orange: #e56020;
--color-teal: #00a6a6;
--color-electric-yellow: #ffd700;
```

Want different team colors? Update these!
- **Twins colors**: Navy (#002855) + Red (#D31145)
- **Rangers colors**: Royal blue (#003278) + Red (#C0111F)
- **Marlins teal**: (#00A3E0) + Black (#000000)

### 5. Better Contact Form

The current form uses `mailto:` which opens email clients. For a smoother experience:

**Option 1: Formspree** (Easiest)
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```
Sign up at formspree.io (free tier available)

**Option 2: Netlify Forms**
If you host on Netlify, just add:
```html
<form name="contact" netlify>
```

**Option 3: Google Forms**
Embed a Google Form for zero setup

### 6. Add a Favicon

Create a basketball-themed favicon:
```html
<!-- Add to <head> section -->
<link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text y='.9em' font-size='90'>🏀</text></svg>">
```

## 🎯 What's Working Out of the Box

- ✅ Fully responsive (looks great on phones, tablets, desktops)
- ✅ Mobile hamburger menu with 90s colors
- ✅ Smooth scroll navigation
- ✅ Active section highlighting
- ✅ Scroll-triggered animations on cards
- ✅ Jersey number section badges
- ✅ Trading card-style hover effects
- ✅ Animated gradient backgrounds
- ✅ Basketball bounce scroll indicator
- ✅ All your resume info auto-filled

## 📱 Mobile Optimized

The site adapts beautifully:
- **Desktop (1200px+)**: Full multi-column layouts
- **Tablet (768-1199px)**: Adjusted grid spacing
- **Mobile (<768px)**: Single column, hamburger menu, optimized touch targets

## 🎨 Design Features Breakdown

### Hero Section
- Championship banner gradient background
- Layered text shadows (purple → orange → black)
- Angled buttons with clip-path polygons
- Bouncing basketball scroll indicator

### About Section
- Trading card-style border with corner fold
- Diagonal pattern background
- Player stats grid with gradient cards
- Hover effects: rotation + lift

### Resume Section
- Championship banner cards with corner ribbons
- Left border accent (team color stripe)
- Basketball emoji bullets
- Skills displayed as retro tags

### Newsletter Section
- Rotating gradient pattern background
- All-star announcement vibe
- Layered text shadows
- Yellow & pink accents

### Contact Section
- Locker room-inspired layout
- Hover slide effect on contact links
- Bold borders and deep shadows
- Retro form styling

## 🔧 Advanced Tweaks

### Add More Stat Cards

```html
<div class="stat-card fade-in stagger-5">
    <span class="stat-number">X</span>
    <span class="stat-label">Your Metric</span>
</div>
```

### Customize Section Numbers

Change the jersey numbers in the badges:
```html
<span class="section-number">02</span>
```
Make them meaningful! Use your favorite numbers.

### Add More Skills

Just add more skill tags:
```html
<div class="skill-tag">Your Skill</div>
```

They'll automatically wrap and hover-rotate.

## 🐛 Troubleshooting

**Fonts not loading?**
- Check internet connection (Google Fonts required)
- Try refreshing the page

**Mobile menu stuck open?**
- Click outside the menu or refresh
- Check browser console for errors

**Colors look different?**
- Make sure you're viewing in a modern browser
- Some older browsers don't support all gradients

**Form not working?**
- mailto: requires email client installed
- Consider switching to Formspree (see customization section)

## 📊 SEO & Social

### Update Meta Tags

Lines 8-16 have your meta tags:
```html
<meta name="description" content="Your custom description">
<meta property="og:description" content="Description for social media">
```

### Add Social Image

Create a 1200x630px image with your 90s vibe and upload it:
```html
<meta property="og:image" content="https://brandonbarnes.me/og-image.jpg">
```

## 🎯 Content Checklist

Ready to go live:
- ✅ All resume info filled in
- ✅ Contact info (email, phone, LinkedIn)
- ✅ Full Court Press link working
- ⬜ Add LinkedIn URL
- ⬜ Add project links to media cards
- ⬜ Consider better form solution (Formspree)
- ⬜ Add social media OG image
- ⬜ Test on multiple devices

## 🌟 Pro Tips

1. **Keep the energy high** - The 90s aesthetic works because it's bold and fun. Don't dial it back!

2. **Add your personality** - Update the hero tagline or about section to reflect your unique voice

3. **Use real images** - When you're ready, replace emoji placeholders in media cards with actual screenshots

4. **Consider video** - A quick video in the hero section would be 🔥

5. **Update regularly** - Keep your stats fresh, add new projects, maintain that "current player" vibe

## 🏀 The Vibe Check

This site says:
- "I'm serious about sales but don't take myself too seriously"
- "I bring energy and creativity to everything I do"
- "I'm not afraid to stand out"
- "Nostalgia + professionalism can coexist"
- "Let's have fun while getting results"

## 🚀 Deployment

### Hostinger (Recommended)
1. Upload to `public_html/index.html`
2. Domain automatically points to it
3. Done!

### Netlify (Alternative)
1. Drag & drop the HTML file
2. Free SSL, CDN, custom domain
3. Super fast hosting

### Vercel (Another Option)
1. Import from GitHub or upload
2. Automatic deployments
3. Edge network speed

## 💡 Future Enhancements

Ideas for v2:
- [ ] Add a blog section for Full Court Press posts
- [ ] Create a highlights reel video section
- [ ] Add testimonials with trading card designs
- [ ] Build a "career timeline" with team logos
- [ ] Create downloadable PDF resume (designed to match)
- [ ] Add dark mode toggle (night game mode)
- [ ] Integrate with Substack API for latest posts

## 📞 Need Help?

If something's not working:
1. Check the browser console (F12) for errors
2. Validate HTML at validator.w3.org
3. Test in different browsers
4. Make sure JavaScript is enabled

## 🎉 Launch It!

Your site is ready to go. The 90s called—they want their energy back, but you're keeping it. 

Upload to Hostinger, share the link, and watch people smile when they see those Bangers headlines and teal gradients.

**Time to ball out! 🏀**

---

*Built with 90s nostalgia and 2026 technology. The best of both eras.*
