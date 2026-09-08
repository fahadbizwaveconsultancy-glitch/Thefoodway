# 🔥 The Food Way — Official Website

Premium fast food website — dark editorial design, glassmorphism menu, cinematic animations.

## 📁 Folder Structure
```
food-way/
├── index.html          ← Main website
└── assets/
    ├── fonts/          ← 8 embedded font files
    └── img/            ← 11 images (logo, favicon, food photos)
```

**⚠️ Important:** Poora folder ek saath deploy karein — index.html aur assets dono zaroori hain.

## 🚀 Deploy (Free)

### Netlify (2 minute — easiest)
1. [app.netlify.com/drop](https://app.netlify.com/drop) kholein
2. Poora `food-way` folder drag & drop karein
3. Live link mil jayega (e.g. `thefoodway.netlify.app`)
4. Site settings → Change site name se custom naam le sakte hain

### Vercel
1. [vercel.com](https://vercel.com) → Add New Project → folder upload
2. Framework: **Other** → Deploy

### GitHub Pages
1. GitHub repo banayein, poora folder upload karein
2. Settings → Pages → Branch: `main` → Save

### cPanel / Hosting (agar domain hai)
1. cPanel → File Manager → `public_html`
2. `index.html` + `assets` folder upload kar dein

## 📞 Details
- **Restaurant:** The Food Way — C-76, Block-4, Near Main Gate Saadi Town, Karachi
- **Phones:** 0315-0020299 · 0334-3648007
- **Order buttons:** WhatsApp (923150020299) pre-filled messages

## ✏️ Edit Karna Ho To
`index.html` kholein:
- **Menu items/prices:** `const MENU = [...]` (script mein)
- **Deals:** `const DEALS = [...]`
- **Phone numbers:** `923150020299` find & replace
- **Address/Hours:** Contact section mein

Made with 🔥 in Karachi
