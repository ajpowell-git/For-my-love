# For-my-love 💕

A personal multi-page love website built with pure HTML, CSS, and JavaScript.

## 📁 File Structure

```
For-my-love/
├── index.html       ← Home page (red, white & pink)
├── devotion.html    ← Bible verses & poetry (purple & blue)
├── gallery.html     ← Photo gallery (white, gold & navy)
├── reasons.html     ← Why I love you (peach & coral)
├── letter.html      ← Love letter (deep rose & champagne)
├── images/          ← 📸 PUT YOUR PHOTOS HERE
│   ├── photo1.jpg
│   ├── photo2.jpg
│   └── ...
└── README.md
```

## ✏️ Personalization Checklist

Before you publish, search each file for `✏️` — every one marks something to change:

- [ ] Replace `[Her Name]` with her actual name
- [ ] Replace `[Your Name]` with your name
- [ ] Add your own reasons in `reasons.html`
- [ ] Write your letter in `letter.html`
- [ ] Add personal notes to Bible verses in `devotion.html`
- [ ] Write your own poem in `devotion.html`
- [ ] Write your anecdote/memory in `devotion.html`
- [ ] Add photos to the `images/` folder and update `gallery.html`

## 🚀 Hosting on GitHub Pages

1. Make sure all your files are in your repo (`For-my-love`)
2. Push everything to the `main` branch:
   ```bash
   git add .
   git commit -m "Add love website files"
   git push origin main
   ```
3. Go to your repo on GitHub → **Settings** → **Pages**
4. Under "Source", select **Deploy from a branch**
5. Select **main** branch, **/ (root)** folder → click **Save**
6. Wait ~1-2 minutes, then visit:
   `https://ajpowell-git.github.io/For-my-love/`

That's the link you share with her! 🎉

## 📸 Adding Photos

1. Create a folder called `images` inside the repo
2. Drop your photos in (jpg, png, webp all work)
3. Open `gallery.html` and find each `SLOT` comment
4. Replace the placeholder `<div class="placeholder">` with:
   ```html
   <img src="images/YOUR-FILENAME.jpg" alt="description"/>
   ```
5. Update the caption text and the `onclick` src path to match

## 💡 Tips

- Keep photo file names simple — no spaces (use `our-trip.jpg` not `our trip.jpg`)
- Compress large photos before uploading (use squoosh.app — free)
- The site works on mobile too, so she can view it on her phone
