# Rahul Ranjan — Personal Portfolio

A dark, space-themed personal academic portfolio site for GitHub Pages

## ✨ Features

- **Animated nebula background** with floating particles
- **Timeline layout** for research experience with glowing dots
- **Dark space palette** with blue/purple/gold accents
- **Fully responsive** — works on mobile, tablet, and desktop
- **Hamburger menu** for mobile navigation
- **Print-friendly** styles for generating PDF
- **Semantic HTML5** for accessibility

## 🚀 Deploy to GitHub Pages

1. Go to GitHub and create a **new repository** named exactly:
   ```
   <your-username>.github.io
   ```
   (e.g., `rahulranjan022.github.io`)

2. Clone the repo and copy these files into it:
   ```bash
   git clone https://github.com/RahulR-anjan/RahulR-anjan.github.io.git
   cd RahulR-anjan.github.io
   ```
   
   Copy `index.html` and `style.css` into this folder.

3. Push to GitHub:
   ```bash
   git add .
   git commit -m "Initial portfolio site"
   git push origin main
   ```

4. Go to **Settings → Pages** and set the source to `main` branch, `/ (root)`.

5. Your site will be live at `https://RahulR-anjan.github.io` within a few minutes! 🎉

## ✏️ Customize

Look for `<!-- CUSTOMIZE: ... -->` comments in `index.html` to update:

| Section | What to change |
|---------|---------------|
| Hero | Name, tagline, bio |
| Contact chips | Email, LinkedIn, GitHub URLs |
| Education | Degree, institution, dates |
| Research | Your projects and publications |
| Skills | Your technical toolkit |
| Certifications | Workshops and courses |

### Change Theme Colors

Edit the `:root` CSS variables in `style.css`:

```css
:root {
  --nebula:      #6b9cf4;   /* Primary accent (blue) */
  --aurora:      #a87ef5;   /* Secondary accent (purple) */
  --gold:        #e8c97a;   /* Tertiary accent (gold) */
}
```

## 📄 License

Free to use and modify for personal portfolios.
