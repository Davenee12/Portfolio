# Davenee James - Analytics & Power BI Portfolio

A modern, single-page portfolio website showcasing Power BI dashboards, SQL expertise, and data analytics work.

## 🌐 Live Site

Visit the portfolio at: [Your Domain Here]

## 📊 About This Portfolio

This website features:
- **Live Power BI Dashboards:** Interactive dashboards for institutional research and analytics
- **SQL Examples:** Real-world SQL queries for cohort analysis and HR analytics
- **Professional Design:** Modern, dark-themed UI with smooth interactions
- **Responsive Layout:** Optimized for desktop, tablet, and mobile devices

## 📁 Analysis Documents

This repository includes comprehensive analysis documentation:

### 1. [SCORECARD.md](SCORECARD.md) 
**Quick Overview** - Start here!
- Overall score: 78/100 ⭐⭐⭐⭐☆
- Category-by-category breakdown
- Priority matrix for improvements
- ROI analysis for each phase

### 2. [QUICK_FIXES.md](QUICK_FIXES.md)
**Copy-Paste Solutions** - Ready to implement!
- 12 copy-paste code snippets
- Critical fixes (< 1 hour total)
- High-impact improvements
- Testing checklist

### 3. [ANALYSIS.md](ANALYSIS.md)
**Deep Dive** - Comprehensive report
- 10 detailed analysis sections
- 50+ specific issues identified
- Code examples and solutions
- 5-phase improvement plan

## 🚀 Quick Start

### Prerequisites
- Modern web browser
- Text editor (VS Code recommended)
- Basic knowledge of HTML/CSS/JavaScript

### Local Development
1. Clone this repository
2. Open `index.html` in your browser
3. No build process required - it's a single-file website!

### Making Changes
The entire website is in `index.html`:
- Lines 12-277: CSS styles
- Lines 280-826: HTML content
- Lines 828-898: JavaScript functionality

## ✅ Quick Wins (90 Minutes)

Implement these for immediate improvement:

1. **Add SEO Meta Tags** (30 min) - See QUICK_FIXES.md #3
2. **Fix External Links** (15 min) - See QUICK_FIXES.md #4
3. **Add Skip Navigation** (15 min) - See QUICK_FIXES.md #1
4. **Add Image Dimensions** (30 min) - See QUICK_FIXES.md #6

**Impact:** Improves overall score from 78 to 82 (C+ to B)

## 📈 Current Status

### Strengths
- ✅ Modern design with excellent CSS
- ✅ Responsive and mobile-friendly
- ✅ Fast load time
- ✅ Clean, semantic HTML

### Areas for Improvement
- ⚠️ Accessibility (62/100) - Needs WCAG compliance
- ⚠️ SEO (58/100) - Missing meta tags and structured data
- ⚠️ Security (65/100) - Missing CSP and link protection

See [SCORECARD.md](SCORECARD.md) for detailed breakdown.

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Grid, Flexbox, Custom Properties
- **Vanilla JavaScript** - No frameworks
- **External Services:**
  - Google Fonts (Bebas Neue, Barlow, JetBrains Mono)
  - Imgur (image hosting)
  - Power BI (embedded dashboards)

## 📱 Browser Support

| Browser | Support |
|---------|---------|
| Chrome 90+ | ✅ Full |
| Firefox 88+ | ✅ Full |
| Safari 14+ | ✅ Full |
| Edge 90+ | ✅ Full |
| IE 11 | ❌ Not supported |
| Mobile Safari 14+ | ✅ Full |
| Chrome Android 90+ | ✅ Full |

## 🧪 Testing

Run these tests after making changes:

### Automated Testing
```bash
# Lighthouse (in Chrome DevTools)
F12 → Lighthouse tab → Generate report

# HTML Validation
https://validator.w3.org/

# Accessibility
https://wave.webaim.org/
```

### Manual Testing
- [ ] Keyboard navigation (Tab, Enter, Esc)
- [ ] Screen reader (NVDA, JAWS, VoiceOver)
- [ ] Mobile devices (iOS, Android)
- [ ] Social media previews (LinkedIn, Twitter)

## 📊 Features

### Dashboard Gallery
- Filterable by type (All, Live, Demo)
- Searchable by keyword
- Modal preview with full-size images
- Direct links to Power BI dashboards

### SQL Showcase
- Toggle between examples (Retention Analysis, Employee Roster)
- Syntax-highlighted code blocks
- Detailed explanations and stats
- Process workflow visualization

### Contact Section
- Email link
- LinkedIn profile
- Resume download
- Footer navigation

## 🎨 Design System

### Color Palette
```css
--bg-deep: #0a0a0a       /* Page background */
--bg-card: #161616       /* Card background */
--text: #ffffff          /* Primary text */
--text-muted: rgba(255,255,255,0.6)  /* Secondary text */
--accent: #3a8fd9        /* Brand blue */
--gold: #c9a227          /* Accent gold */
```

### Typography
- **Headings:** Bebas Neue (display font)
- **Body:** Barlow (sans-serif)
- **Code:** JetBrains Mono (monospace)

### Spacing Scale
- xs: 8px
- sm: 12px
- md: 20px
- lg: 40px
- xl: 60px

## 📝 Content Management

### Adding a New Dashboard

Edit the `dashboards` array in the `<script>` section (line 829):

```javascript
{
  type: "live",  // or "demo"
  title: "Your Dashboard Title",
  desc: "Brief description of the dashboard.",
  img: "https://i.imgur.com/YOUR_IMAGE.jpeg",
  link: "https://app.powerbi.com/view?r=YOUR_LINK",
  tags: ["Category1", "Category2"]
}
```

### Updating SQL Examples

1. Find the SQL panel section (lines 382-735)
2. Update the SQL code in the `<pre>` tags
3. Update the description and stats

## 🔒 Security

Current security measures:
- XSS protection via `escapeAttr()` function
- No inline event handlers
- HTTPS for all external resources

**To Do:**
- [ ] Add Content Security Policy
- [ ] Add `rel="noopener noreferrer"` to external links
- [ ] Replace `innerHTML` with safer DOM methods

See [ANALYSIS.md](ANALYSIS.md) Section 7 for details.

## 🎯 Roadmap

### Phase 1: Quick Wins (90 min) ✅ Ready to implement
- Add SEO meta tags
- Fix accessibility basics
- Secure external links
- Add image dimensions

### Phase 2: Accessibility (4-6 hours)
- WCAG 2.1 Level AA compliance
- Screen reader support
- Keyboard navigation improvements
- Focus management

### Phase 3: Performance (8-12 hours)
- Image optimization (WebP, srcset)
- CSS extraction
- Font optimization
- Resource hints

### Phase 4: Maintainability (8-16 hours)
- Separate CSS file
- External JSON for data
- Build process
- Unit tests

## 📚 Documentation

- **[SCORECARD.md](SCORECARD.md)** - Visual overview and scores
- **[QUICK_FIXES.md](QUICK_FIXES.md)** - Ready-to-use code snippets
- **[ANALYSIS.md](ANALYSIS.md)** - Comprehensive analysis and recommendations

## 🤝 Contributing

This is a personal portfolio, but suggestions are welcome!

1. Review the analysis documents
2. Create an issue with your suggestion
3. Reference specific sections from ANALYSIS.md

## 📄 License

Copyright © 2025 Davenee James. All rights reserved.

## 📧 Contact

**Davenee James**  
Data Analyst / BI Developer  
Southwestern Adventist University

- Email: daveneejames@gmail.com
- LinkedIn: [linkedin.com/in/davenee-james-848171228](https://www.linkedin.com/in/davenee-james-848171228/)
- Location: Dallas–Fort Worth Metroplex

---

## ⚡ Performance Stats

- **First Contentful Paint:** ~0.5s
- **Largest Contentful Paint:** ~1.2s
- **Time to Interactive:** ~0.8s
- **File Size:** 59 KB (uncompressed)
- **Total Requests:** ~15 (fonts, images)

## 🏆 Quality Scores

| Category | Score | Grade |
|----------|-------|-------|
| HTML Structure | 85/100 | B+ |
| CSS Quality | 88/100 | A- |
| JavaScript | 75/100 | C+ |
| Accessibility | 62/100 | D+ |
| SEO | 58/100 | D |
| Performance | 82/100 | B+ |
| Security | 65/100 | D+ |
| **Overall** | **78/100** | **C+** |

*Scores based on industry best practices and web standards.*

---

**Built with ❤️ and data**
