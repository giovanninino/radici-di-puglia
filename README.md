# 🌿 Radici di Puglia — Website

Official website for **Radici di Puglia**, a private small-group tour experience in Carovigno, Puglia, Southern Italy.

Run by Giovanni Del Prete & Donatello Leobilla.

---

## 📁 Project Structure

```
radici-di-puglia/
├── index.html          ← Main page
├── css/
│   └── style.css       ← All styles
├── js/
│   └── main.js         ← Scroll animations, nav behaviour
├── images/
│   ├── van-side.jpg    ← Fiat Panorama side view
│   ├── van-rear.jpg    ← Fiat Panorama rear view
│   └── van-front.jpg   ← Fiat Panorama front view
└── README.md
```

---

## 🚀 How to Update the Website

### Change the booking email
In `index.html`, find the line:
```
href="mailto:info@radicidipuglia.com
```
Replace `info@radicidipuglia.com` with your real email address.

### Add your real photos
Drop new images into the `images/` folder and update the `src=""` references in `index.html`.

### Change prices
In `index.html`, search for `€50`, `€65`, `€80` and update as needed.

### Add a new experience card
Copy one of the `<div class="exp-card">` blocks in the mosaic section and update the text and Unsplash image URL.

---

## 🌐 Hosting (Netlify)

1. Go to [netlify.com](https://netlify.com) and create a free account
2. Click **"Add new site" → "Deploy manually"**
3. Drag and drop the entire `radici-di-puglia/` folder
4. Your site goes live instantly at a URL like `https://wonderful-name-123.netlify.app`
5. To use a custom domain (e.g. `radicidipuglia.com`), go to **Site settings → Domain management**

---

## 💻 GitHub (for version control)

1. Go to [github.com](https://github.com) and create a free account
2. Click **"New repository"** → name it `radici-di-puglia` → **Public** → Create
3. Upload all files by clicking **"uploading an existing file"**
4. Connect GitHub to Netlify for auto-deploy: every time you update a file on GitHub, Netlify rebuilds automatically

---

## 🔧 To-Do List

- [ ] Replace placeholder team photos with real photos of Giovanni & Donatello
- [ ] Add real email address to the booking button
- [ ] Register domain: `radicidipuglia.com` (suggested)
- [ ] Add Instagram link in footer
- [ ] Upload real tour photos to replace Unsplash placeholders
- [ ] Set up Google Analytics (free, track visitors)
- [ ] List experience on TripAdvisor Experiences
- [ ] Consider adding a simple contact form (Netlify Forms — free)

---

## 📸 Photos Needed

To make the site feel fully real, replace the Unsplash placeholders with your own photos of:
- The masseria / olive oil production
- Cheese/mozzarella making
- The coastline / Torre Guaceto
- Food tasting table
- Farm animals
- Giovanni and Donatello (team section)

---

Built with love for Puglia 🫒
