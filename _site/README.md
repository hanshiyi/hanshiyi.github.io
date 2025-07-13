# Michael (Shiyi) Han - Academic Website

A modern academic website built with Jekyll and the [Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/). This site showcases research, publications, and professional experience in machine learning, natural language processing, and audio processing.

## 🎯 About

This is the personal academic website of **Michael (Shiyi) Han**, a researcher focused on machine learning, natural language processing, and audio processing. The site is built using Jekyll with the Minimal Mistakes theme for a clean, professional academic appearance.

## 🚀 Features

- **Modern Academic Design**: Clean, professional layout using Minimal Mistakes theme
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Blog System**: Markdown-based posts with automatic categorization
- **Research Showcase**: Dedicated pages for research projects and publications
- **Fast Performance**: Static site generation for optimal loading speeds
- **SEO Optimized**: Built-in search engine optimization features

## 🛠️ Technology Stack

- **Jekyll**: Static site generator
- **Minimal Mistakes Theme**: Professional academic theme
- **GitHub Pages**: Hosting platform
- **Markdown**: Content authoring
- **Sass/CSS**: Styling and customization

## 📁 Project Structure

```
hanshiyi.github.io/
├── _config.yml              # Jekyll configuration
├── Gemfile                  # Ruby dependencies
├── index.md                 # Homepage
├── _pages/                  # Static pages
│   ├── about.md            # About page
│   └── research.md         # Research page
├── _posts/                 # Blog posts
│   ├── 2024-01-15-understanding-transformer-architecture.md
│   └── 2018-12-21-notes-for-re-bio-abstract.md
├── _data/                  # Site data
│   └── navigation.yml      # Navigation menu
├── assets/                 # Static assets
│   ├── css/
│   │   └── main.scss       # Theme stylesheet
│   └── images/             # Images (currently empty)
└── _drafts/                # Draft posts
```

## 🚀 Getting Started

### Prerequisites

- Ruby (version 2.5 or higher)
- RubyGems
- Bundler

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/hanshiyi/hanshiyi.github.io.git
   cd hanshiyi.github.io
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run locally**
   ```bash
   bundle exec jekyll serve
   ```

4. **View the site**
   Open [http://localhost:4000](http://localhost:4000) in your browser

## 📝 Adding Content

### New Blog Posts

Create new posts in the `_posts/` directory with the format `YYYY-MM-DD-title.md`:

```yaml
---
title: "Your Post Title"
date: 2024-01-15
categories:
  - Machine Learning
  - Research
tags:
  - deep-learning
  - transformers
---
```

### New Pages

Add new pages in the `_pages/` directory:

```yaml
---
title: "Page Title"
permalink: /page-url/
layout: single
---
```

### Navigation

Update `_data/navigation.yml` to add new menu items:

```yaml
- title: "New Page"
  url: /new-page/
```

## 🎨 Customization

### Theme Settings

Key configuration options in `_config.yml`:

- **Site information**: Title, description, URL
- **Author details**: Name, bio, social links
- **Theme skin**: Choose from "air", "contrast", "dark", "dirt", "sunrise"
- **Navigation**: Menu structure and links

### Styling

The Minimal Mistakes theme provides extensive customization:

- **Color schemes**: Multiple built-in themes
- **Typography**: Academic-focused fonts
- **Layout options**: Various page layouts
- **Sidebar configurations**: Customizable sidebar content

## 🌐 Deployment

This site is configured for GitHub Pages deployment:

1. **Push changes to main branch**
   ```bash
   git add .
   git commit -m "Update site content"
   git push origin main
   ```

2. **Automatic deployment**
   GitHub Pages will automatically build and deploy your site to `https://hanshiyi.github.io`

## 📊 Current Status

- ✅ **Jekyll setup**: Complete with Minimal Mistakes theme
- ✅ **Content structure**: Homepage, About, Research pages
- ✅ **Blog system**: Sample posts with proper formatting
- ✅ **Navigation**: Working menu system
- ✅ **Styling**: Professional academic theme applied
- ✅ **Local development**: Ready for local testing

## 🔧 Configuration

### Key Files

- `_config.yml`: Main Jekyll configuration
- `Gemfile`: Ruby dependencies
- `assets/css/main.scss`: Theme stylesheet
- `_data/navigation.yml`: Navigation menu structure

### Plugins Used

- `jekyll-paginate`: Blog pagination
- `jekyll-sitemap`: Automatic sitemap generation
- `jekyll-feed`: RSS feed generation
- `jekyll-seo-tag`: SEO optimization
- `jekyll-archives`: Archive pages

## 📞 Contact

- **Email**: [shiyi_han@alumni.brown.edu](mailto:shiyi_han@alumni.brown.edu)
- **LinkedIn**: [Michael Han](https://www.linkedin.com/in/shiyi-michael-h-941620120/)
- **GitHub**: [hanshiyi](https://github.com/hanshiyi)

## 📄 License

This project is licensed under the MIT License. The Minimal Mistakes theme is also licensed under the MIT License.

## 🙏 Acknowledgments

- [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) Jekyll theme by Michael Rose
- [Jekyll](https://jekyllrb.com/) static site generator
- [GitHub Pages](https://pages.github.com/) hosting platform

---

*Last updated: January 2024* 