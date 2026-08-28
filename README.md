# Al Sunnah Al Islam

A Jekyll-based website hosted on GitHub Pages dedicated to Islamic articles, books, and authentic Islamic resources based on the Quran and Sunnah.

## About

This site provides Islamic knowledge and resources aligned with the teachings of the Quran and authentic Sunnah (teachings of Prophet Muhammad ﷺ). On the blog, the truth will be spread and lies will be debunked with evidence from the Qur'an, Hadiths, and classical Islamic texts.

## Features

- Clean, responsive design with green theme
- Blog post functionality with categories/labels
- Search capability
- Archive by date
- Mobile-friendly navigation
- Popular posts widget
- Blog archive with hierarchy view
- Reader-friendly typography using Amiri and Tajawal fonts

## Site Settings

- **URL**: https://fali1917.github.io
- **Theme**: Custom Blogger template (ASAL.xml)
- **Site Title**: Al Sunnah Al Islam
- **Description**: Islamic Articles, Books, and Resources

## Building Locally

### Requirements
- Ruby 2.7 or higher
- Bundler (for Jekyll)

### Setup

```bash
# Clone the repository
git clone https://github.com/Fali17/Al-Sunnah-Al-Islam-1.git
cd Al-Sunnah-Al-Islam-1

# Install dependencies
bundle install

# Build and serve locally
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`

## Adding Posts

Create new post files in the `_posts` directory using the naming convention:
```
_posts/YYYY-MM-DD-post-title.md
```

Example:
```markdown
---
layout: post
title: "Understanding Islamic Principles"
date: 2026-08-28
categories: [Islamic Knowledge, Quran]
---

Your detailed post content here...
```

## Directory Structure

```
.
├── _posts/           # Blog posts (markdown files)
├── ASAL.xml          # Blogger template configuration
├── _config.yml       # Jekyll configuration
├── index.html        # Homepage
└── README.md         # This file
```

## Customization

### Theme Colors
The site uses a green color scheme:
- Primary Green: `#145a32`
- Dark Green: `#0d2818`
- Light Green: `#d5f5e3`
- Gold Accent: `#c8a951`

### Fonts
- Headers: Amiri (serif)
- Body: Tajawal (sans-serif)

## Features Included

✅ Responsive Design
✅ Mobile Navigation with Hamburger Menu
✅ Reading Progress Bar
✅ Back to Top Button
✅ Blog Archive with Hierarchical View
✅ Popular Posts Widget
✅ Blog Labels/Categories
✅ Search Functionality
✅ Comment System
✅ Social Media Integration Ready
✅ SEO Optimized (Open Graph, Twitter Cards, Schema.org)

## License

© 2024-2026 Ahlu Sunnah Al Islam. All rights reserved.

## Contributing

Contributions are welcome. Please feel free to submit pull requests or open issues for suggestions and improvements.

## Support

For issues, questions, or suggestions, please contact through the Contact page or open an issue on GitHub.
