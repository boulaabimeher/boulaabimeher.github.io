# Meher BOULAABI - Academic Portfolio

Professional academic portfolio website built with Jekyll and the Midnight theme.

## 🌐 Live Website

Visit: [https://boulaabimeher.github.io](https://boulaabimeher.github.io)

## 📋 About

This portfolio showcases my research, teaching, and professional activities as a PhD researcher specializing in interpretable deep learning for medical imaging.

### Key Sections

- **Home** - Overview and quick links
- **Education & Research** - Academic background and research positions
- **Publications & Supervision** - Research papers and student mentoring
- **Teaching** - Course portfolio and teaching philosophy
- **Technical Skills** - Programming, frameworks, and tools
- **Professional Activities** - Industry experience and certifications

## 🛠️ Setup

This site uses the [Midnight theme](https://github.com/pages-themes/midnight) for GitHub Pages.

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/boulaabimeher/boulaabimeher.github.io.git
cd boulaabimeher.github.io
```

2. Install dependencies:
```bash
bundle install
```

3. Run locally:
```bash
bundle exec jekyll serve
```

4. Visit `http://localhost:4000` in your browser

### File Structure

```
.
├── _config.yml           # Site configuration
├── index.md              # Home page
├── education.md          # Education & research page
├── publications.md       # Publications & supervision page
├── teaching.md           # Teaching experience page
├── skills.md             # Technical skills page
├── professional.md       # Professional activities page
├── images/               # Images folder
│   └── me_croped.jpg     # Profile photo
└── README.md            # This file
```

## 📝 Updating Content

### Profile Photo

Replace `images/me_croped.jpg` with your photo (recommended size: 400x400px, circular crop)

### Personal Information

Edit `_config.yml` to update:
- Name, email, location
- ORCID, GitHub, LinkedIn usernames
- Download CV link
- Site description and tagline

### Page Content

Edit the respective `.md` files:
- `index.md` - Homepage
- `education.md` - Education and research
- `publications.md` - Publications and supervision
- `teaching.md` - Teaching experience
- `skills.md` - Technical skills
- `professional.md` - Professional activities

## 🎨 Customization

### Theme Configuration

The Midnight theme is configured in `_config.yml`:

```yaml
remote_theme: pages-themes/midnight@v0.2.0
plugins:
  - jekyll-remote-theme
```

### Custom Styling

To add custom CSS, create `assets/css/style.scss`:

```scss
---
---

@import "{{ site.theme }}";

/* Your custom styles here */
```

## 📄 License

This portfolio is based on the [Midnight theme](https://github.com/pages-themes/midnight) which is licensed under CC0-1.0.

Content © 2026 Meher BOULAABI. All rights reserved.

## 📧 Contact

- **Email:** boulaabi@cril.fr
- **Location:** Lens, France
- **GitHub:** [@boulaabimeher](https://github.com/boulaabimeher)
- **LinkedIn:** [boulaabi-meher](https://www.linkedin.com/in/boulaabi-meher/)

## 🔄 Updates

Last updated: February 2026

---

Built with ❤️ using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
