# Sabbir Hossain - Personal Portfolio Website

A sleek, responsive, single-page developer portfolio website designed for **Sabbir Hossain**, a 1st Semester Computer Science & Artificial Intelligence student at **Newton School of Technology**.

---

## 🌟 Highlights & Features

- **Single-Page Architecture (`index.html`)**: Everything (HTML, modern CSS, and lightweight vanilla JavaScript) is bundled in a clean, self-contained file. No build steps or bundlers required!
- **Dark & Light Mode Toggle**: Sleek dark aesthetic by default with instant toggle and `localStorage` persistence.
- **Glassmorphism & Ambient Glows**: Modern tech aesthetic with ambient glow effects, frosted glass cards, and smooth gradient borders.
- **Interactive Project Filtering**: Filter projects seamlessly between All, Web Apps, and Tools/Utilities.
- **Dynamic ScrollSpy & Navigation**: Sticky blur navbar with active section indicators and responsive mobile drawer menu.
- **Contact Form & Quick Email Copy**: Interactive contact form with toast notifications and one-click email copying.
- **100% Responsive**: Looks great on smartphones, tablets, laptops, and ultra-wide screens.

---

## 🚀 How to Run Locally

You can run this portfolio in two simple ways:

### Option 1: Directly in your browser
Simply double-click the `index.html` file or right-click and choose **Open With > Google Chrome** (or any browser).

### Option 2: Using a local web server (Recommended)
If you have Python installed, open your terminal in this folder and run:

```bash
# Python 3
python3 -m http.server 3000
```

Then visit [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🛠️ Personalization & Customization

You can easily customize this portfolio by opening `index.html` in VS Code or any text editor:

1. **Social Links**: Search for `github.com`, `linkedin.com`, or `twitter.com` in `index.html` and replace them with your actual profile handles.
2. **Email Address**: Search for `sabbir.hossain@nst.edu` and update it to your actual student or personal email.
3. **Projects**: In the `#projects` section, update project titles, descriptions, stack tags, and demo links to reflect your own assignments and hackathon projects.
4. **Skills**: Add or modify tech badges in the `#skills` section as you learn new languages and frameworks in subsequent semesters.

---

## 🌐 Deploy to GitHub Pages (Free)

1. Initialize git in this directory:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio release"
   ```
2. Create a repository on [GitHub](https://github.com) named `portfolio` (or `<your-username>.github.io`).
3. Push your code:
   ```bash
   git remote add origin https://github.com/<your-username>/portfolio.git
   git branch -M main
   git push -u origin main
   ```
4. Go to your repo's **Settings > Pages**, select the `main` branch, and click **Save**. Your website will be live at `https://<your-username>.github.io/portfolio/`!
