# Devang Gaur - Personal Website

Personal website and portfolio showcasing work in payments technology, AI/ML product management, and thought leadership.

🌐 **Live Site**: [devanggaur.com](https://devanggaur.com)

## Overview

This is a modern, fully responsive personal website built with vanilla HTML, CSS, and JavaScript. The site features a clean, professional design with comprehensive SEO optimization and analytics tracking.

## Features

### Core Sections
- **About**: Professional introduction and career highlights
- **Experience**: Detailed work history at Adobe, PayPal, and Dell Technologies
- **Expertise**: Key areas of specialization in payments and AI/ML
- **Blog**: 8 detailed articles on product management and technology
- **Publications**: Featured industry articles and media coverage
- **Speaking**: Speaking engagements and conference appearances
- **Contact**: Professional networking and contact information

### Technical Features
- ✅ Fully responsive design
- ✅ Modern Professional layout with Midnight theme
- ✅ SEO optimized with meta tags, Open Graph, and Twitter Cards
- ✅ Schema.org structured data for LLM discoverability
- ✅ Google Analytics 4 with enhanced tracking:
  - Scroll depth tracking (25%, 50%, 75%, 100%)
  - Time on page tracking (30s, 60s, 120s, 300s)
  - External link click tracking
  - Custom event tracking for CTAs
- ✅ Custom domain setup (devanggaur.com)
- ✅ HTTPS enabled via GitHub Pages
- ✅ Sitemap.xml for search engines
- ✅ Robots.txt with LLM crawler allowances

### Design
- **Font**: Quicksand variable font
- **Color Scheme**: Midnight Professional theme
  - Primary: #0066cc (Blue)
  - Secondary: #00b4d8 (Cyan)
  - Accent: #00ff88 (Green)
  - Dark: #0a0e27
- **Layout**: Modern Professional with left-border accent on cards

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Fonts**: Quicksand (variable font)
- **Analytics**: Google Analytics 4
- **Hosting**: GitHub Pages
- **Domain**: GoDaddy DNS → GitHub Pages
- **Version Control**: Git & GitHub

## Project Structure

```
DevangGaurV1/
├── index.html                          # Main homepage
├── ebook.html                          # Ebook redirect page
├── robots.txt                          # Search engine directives
├── sitemap.xml                         # SEO sitemap
├── CNAME                               # Custom domain configuration
├── favicon.ico                         # Site favicon
├── blog/                               # Blog articles
│   ├── why-products-fail.html
│   ├── manipulation-matrix.html
│   ├── user-behavior.html
│   ├── mvp-vs-mlp.html
│   ├── virality-part-1.html
│   ├── virality-part-2.html
│   ├── spotify-tribe-model.html
│   └── disruptive-innovation.html
├── Pictures/                           # Image assets
│   ├── Headshots/
│   └── Industry Conferences/
├── thumbnails/                         # Video thumbnails
│   ├── life of a dollar/
│   └── lpms/
├── Bitter,Lora,Manrope,Plus_Jakarta_Sans,Roboto/
│   └── Quicksand/                      # Font files
├── *.png                               # Logo files
└── README.md                           # This file
```

## Blog Posts

1. **Why Do Products Fail?** - Painkiller vs Vitamin framework
2. **Manipulation Matrix** - Product engagement strategies
3. **Understanding User Behavior** - Psychology in product design
4. **MVP vs MLP** - Product development approaches
5. **Virality Part 1** - Building viral products
6. **Virality Part 2** - Scaling viral growth
7. **Spotify Tribe Model** - Agile team structures
8. **Disruptive Innovation** - Market disruption strategies

## SEO & Discoverability

The site is optimized for:
- **Search Engines**: Google, Bing, DuckDuckGo
- **Social Media**: Open Graph tags for LinkedIn, Twitter, Facebook
- **LLM Crawlers**: Allowed crawlers include:
  - GPTBot (OpenAI)
  - ChatGPT-User
  - Claude-Web (Anthropic)
  - anthropic-ai
  - PerplexityBot

## Analytics Events Tracked

- Page views
- Scroll depth (25%, 50%, 75%, 100%)
- Time on page (30s, 60s, 120s, 300s)
- External link clicks
- Video clicks
- Navigation clicks
- Slider interactions
- Ebook downloads

## Deployment

The site is automatically deployed via GitHub Pages:

1. Push changes to the `main` branch
2. GitHub Pages automatically builds and deploys
3. Changes are live at devanggaur.com within 1-2 minutes

### Custom Domain Setup

**DNS Configuration (GoDaddy)**:
```
Type: A     Name: @    Value: 185.199.108.153
Type: A     Name: @    Value: 185.199.109.153
Type: A     Name: @    Value: 185.199.110.153
Type: A     Name: @    Value: 185.199.111.153
Type: CNAME Name: www  Value: devanggaur.github.io
```

## Local Development

To run locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/devanggaur/devanggaur-website.git
   ```

2. Open `index.html` in a web browser, or use a local server:
   ```bash
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

## Special Pages

- **/ebook** - Redirects to Google Drive ebook with analytics tracking

## Credits

- Built by Devang Gaur with assistance from Claude (Anthropic)
- Design: Modern Professional with custom styling
- Icons & Logos: Custom brand assets

## License

© 2025 Devang Gaur. All rights reserved.

---

**Contact**: [LinkedIn](https://www.linkedin.com/in/devang-gaur/)
