# Outlaw Coffee - Web Collaboration Project

**Brew the Revolution.** A professional website for Outlaw Coffee that combines competitive research, brand archetypes, Cialdini's persuasion methods, and a strategic sales funnel.

## 🌐 Live Site
[View the live website on GitHub Pages](https://anabhayana.github.io/williams_design/)

## 📋 Project Contents

### Research & Strategy
- **[Brand Archetype](archetype.html)** - The Outlaw personality and visual identity
- **[Cialdini's Persuasion Methods](cialdini.html)** - 6 psychological principles applied to marketing
- **[Sales Funnel (AIDA Model)](sales-funnel.html)** - Customer journey from awareness to action
- **[Competitive Landscape](competitive-landscape.html)** - Market positioning and differentiation

### Competitor Analysis
- **[Dunkin' Donuts Analysis](dunkin-donuts.html)** - Corporate convenience leader
- **[Dutch Bros Analysis](dutch-bros.html)** - Energetic challenger brand
- **[Tim Hortons Analysis](tim-hortons.html)** - Established tradition player

## 🎯 What Makes This Project Special

This project combines:
- ✅ **Quality Gates** - GitHub Actions for HTML validation, accessibility checks, and link verification
- ✅ **Static Site Generation** - Clean, fast HTML/CSS without external dependencies
- ✅ **Brand Strategy** - Grounded in archetype theory and psychological persuasion
- ✅ **Competitive Research** - Strategic analysis of major competitors
- ✅ **Professional Design** - Dark, bold visual identity aligned with brand values

## 🚀 Features

### Design System
- **Color Palette**: Black, Deep Crimson, Ash Gray, Burnt Copper
- **Typography**: Bold sans-serif (Bebas Neue style) + rough display fonts
- **Responsive**: Mobile-first design that works on all devices
- **Accessible**: WCAG 2.1 compliant with semantic HTML

### Technical Stack
- Pure HTML5
- CSS3 (no frameworks)
- GitHub Actions CI/CD
- GitHub Pages hosting

## 📁 Project Structure

```
williams_design/
├── index.html                      # Homepage
├── archetype.html                  # Brand archetype page
├── cialdini.html                   # Persuasion methods
├── sales-funnel.html               # Sales funnel strategy
├── competitive-landscape.html      # Market analysis
├── dunkin-donuts.html             # Competitor deep-dive
├── dutch-bros.html                # Competitor deep-dive
├── tim-hortons.html               # Competitor deep-dive
├── style.css                       # Unified styling
├── .github/workflows/quality-gates.yml  # CI/CD pipeline
└── docs/                          # Research documents
    ├── archetype.md
    ├── competitive_landscape.md
    ├── sales_funnel.md
    └── competitors/
```

## 🔧 Quality Gates (GitHub Actions)

The project includes automated quality checks:
- **HTML Validation** - html5validator
- **Accessibility Checks** - axe-core scanning
- **Link Validation** - Link checker for broken URLs
- **CSS Validation** - CSS syntax verification
- **Markdown Linting** - Documentation quality

To view the workflow: `.github/workflows/quality-gates.yml`

## 🚢 Deployment

The site is automatically deployed to GitHub Pages when pushing to the main branch.

### Manual Deployment
1. Ensure all changes are committed and pushed to `main`
2. GitHub Actions will automatically run quality gates
3. Upon success, the site deploys to GitHub Pages
4. View at: `https://anabhayana.github.io/williams_design/`

### Local Development
Simply open any `.html` file in your browser or use a local server:
```bash
python -m http.server 8000
# Then visit http://localhost:8000
```

## 📊 Marketing Strategy Summary

### The Outlaw Archetype
Rebellion, authenticity, and freedom from conformity. Targets independent thinkers, 20-40 year olds, who reject corporate coffee culture.

### Cialdini's Principles Applied
1. **Reciprocity** - Free brewing guides and content
2. **Commitment** - "Join the rebellion" membership
3. **Social Proof** - Customer testimonials and UGC
4. **Authority** - Founder expertise and credentials
5. **Liking** - Authentic brand voice and relatability
6. **Scarcity** - Limited edition roasts and time-limited offers

### Sales Funnel (AIDA)
- **Awareness** - Bold hero visuals and social campaigns
- **Interest** - Brand story and educational content
- **Desire** - Lifestyle imagery and community
- **Action** - Clear CTAs and frictionless checkout

## 👥 Team

Created as part of IS117 Web Collaboration assignment.

## 📝 License

This project is for educational purposes.
