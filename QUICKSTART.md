# 🚀 Quick Start Guide

## Step 1: Upload Files to GitHub

1. **Upload all files from this folder to your repository**:
   - `_config.yml`
   - `_layouts/` folder (contains default.html)
   - `assets/` folder (contains custom CSS)
   - `index.md`
   - `education.md`
   - `publications.md`
   - `teaching.md`
   - `skills.md`
   - `professional.md`
   - `README.md`
   - `images/` folder

2. **Add your profile photo**:
   - Name it: `me_croped.jpg`
   - Upload to `images/` folder
   - Recommended size: 400x400px, circular crop

3. **Add your CV**:
   - Name it: `CV.pdf`
   - Upload to root directory (same level as index.md)
   - This will enable the "Download CV" button

## Step 2: Enable GitHub Pages

1. Go to your repository **Settings**
2. Click on **Pages** in the left sidebar
3. Under "Source", select **main** branch
4. Click **Save**
5. Wait 1-2 minutes for deployment

## Step 3: Verify Your Site

Visit: `https://yourusername.github.io`

Your portfolio should now be live! 🎉

## Step 4: Customize (Optional)

### Update Personal Information

Edit `_config.yml`:
```yaml
title: Your Name
tagline: Your tagline
description: Your description
author:
  name: Your Name
  email: your.email@example.com
  location: Your Location
```

### Update Download CV Link

In `_config.yml`, change:
```yaml
download_cv_url: "link-to-your-cv.pdf"
```

You can upload your CV PDF to GitHub and link to it:
```yaml
download_cv_url: "https://github.com/yourusername/yourusername.github.io/raw/master/CV.pdf"
```

### Update GitHub Username in Stats

In `index.md`, find this line:
```html
<img src="https://github-readme-stats.vercel.app/api?username=boulaabimeher...
```

Replace `boulaabimeher` with your GitHub username.

## Step 5: Update Content

Edit the `.md` files to update your information:
- `index.md` - Homepage
- `education.md` - Education and research
- `publications.md` - Publications and supervision  
- `teaching.md` - Teaching experience
- `skills.md` - Technical skills
- `professional.md` - Professional activities

## Troubleshooting

### Site not loading?
- Wait 2-3 minutes after first push
- Check Settings > Pages shows "Your site is live at..."
- Verify all files are in root directory (not in a subfolder)

### Images not showing?
- Check image filename matches exactly: `me_croped.jpg`
- Verify image is in `images/` folder
- Try hard refresh (Ctrl+F5 or Cmd+Shift+R)

### Theme not applying?
- Verify `_config.yml` has:
  ```yaml
  remote_theme: pages-themes/midnight@v0.2.0
  plugins:
    - jekyll-remote-theme
  ```

## Need Help?

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Midnight Theme Repository](https://github.com/pages-themes/midnight)
- [Jekyll Documentation](https://jekyllrb.com/docs/)

---

## What's Next?

1. ✅ Upload files to GitHub
2. ✅ Enable GitHub Pages
3. ✅ Add your profile photo
4. ✅ Update personal information
5. ✅ Customize content
6. 🎯 Share your portfolio!

**Pro Tip:** After making changes, commit and push to GitHub. Your site will automatically update within 1-2 minutes.

Good luck with your new portfolio! 🚀
