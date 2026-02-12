# My Outstanding Jekyll Site 🌐

A highly polished Jekyll website starter inspired by the design sensibilities of modern government portals and broadcast platforms like [live.bh](https://www.live.bh) and [moi.gov.bh](https://www.moi.gov.bh) — clean, professional, responsive, and easy to maintain.

## ✨ Features

✔️ Complete Jekyll project structure  
✔️ Custom layouts, navigation, and components  
✔️ Hero banner, services/sections, footer, blog index  
✔️ Responsive design with modern typography  
✔️ Sass-based styling system for easy customization  
✔️ Ready to build out official content  

## 📁 Folder Structure

```
Bahrain-TV/
├── _config.yml              # Jekyll configuration
├── Gemfile                  # Ruby dependencies
├── .gitignore              # Git ignore rules
├── _data/
│   └── navigation.yml      # Navigation menu items
├── _includes/
│   ├── head.html          # HTML head section
│   ├── header.html        # Site header and navigation
│   ├── hero.html          # Hero banner section
│   └── footer.html        # Site footer
├── _layouts/
│   ├── default.html       # Default page layout
│   └── home.html          # Homepage layout with hero
├── _posts/                # Blog posts (YYYY-MM-DD-title.md)
│   └── 2026-02-12-welcome-to-our-new-site.md
├── assets/
│   ├── css/
│   │   └── main.scss      # Main stylesheet with Sass
│   └── img/               # Images directory
├── index.md               # Homepage content
├── about.md               # About page
├── blog.md                # Blog index page
└── contact.md             # Contact page
```

## 🚀 Quick Start

### Prerequisites

- Ruby (2.7 or higher)
- Bundler gem

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Bahrain-TV/Bahrain-TV.git
   cd Bahrain-TV
   ```

2. **Install dependencies**
   ```bash
   gem install bundler
   bundle install
   ```

3. **Run the development server**
   ```bash
   bundle exec jekyll serve
   ```

4. **View the site**
   Open your browser and visit: `http://localhost:4000`

The site will auto-regenerate when you make changes to files.

## 📝 Customization

### Site Configuration

Edit `_config.yml` to customize:
- Site title, email, description
- Base URL and site URL
- Plugins and theme settings

### Navigation

Modify `_data/navigation.yml` to add, remove, or reorder navigation items.

### Styling

Edit `assets/css/main.scss` to customize:
- Colors (primary, accent, background)
- Typography
- Layout spacing
- Responsive breakpoints

### Adding Blog Posts

Create a new file in `_posts/` with the format: `YYYY-MM-DD-title.md`

Example:
```markdown
---
layout: default
title: "Your Post Title"
date: 2026-02-12 10:00:00 +0300
categories: news
---

Your content here...
```

## 🎨 Design Philosophy

This site is inspired by:
- **Government Portals**: Clear hierarchy, accessible navigation
- **Broadcast Platforms**: Dynamic content, engaging visuals
- **Modern Web**: Responsive, fast, user-friendly

## 💡 Next Steps

Here are some ideas to extend the site:

✨ Add a **news/announcements section**  
✨ Implement **multilingual support** (Arabic/English)  
✨ Connect to external APIs for live feeds  
✨ Add **search functionality**  
✨ Integrate analytics  
✨ Add a contact form  
✨ Create custom components for specific content types  

## 📦 Built With

- [Jekyll](https://jekyllrb.com/) - Static site generator
- [Sass](https://sass-lang.com/) - CSS preprocessor
- [Normalize.css](https://necolas.github.io/normalize.css/) - CSS reset
- [Minima](https://github.com/jekyll/minima) - Base theme

## 📄 License

See the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

**Ready to launch!** 🚀✨
