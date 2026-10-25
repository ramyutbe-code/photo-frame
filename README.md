# Photo Frame — GitHub Pages + ImgBB

A small, static, full-screen slideshow. The website itself contains no photos; it loads direct image URLs from ImgBB.

## 1. Add your ImgBB images
1. Upload a travel photo to ImgBB.
2. Copy its **direct image URL** (usually starts with `https://i.ibb.co/`), not the ImgBB page URL.
3. In `index.html`, find `const PHOTOS = [` and add each URL as a quoted string, separated by commas:

```js
const PHOTOS = [
  "https://i.ibb.co/example-id/photo-one.jpg",
  "https://i.ibb.co/example-id/photo-two.jpg"
];
```

4. Save the file. You can test it by opening `index.html` in a browser.

## 2. Publish with GitHub Pages
1. Create/sign in to a GitHub account at https://github.com.
2. Create a **public** repository named `photo-frame`.
3. Upload `index.html` and `README.md` to the repository root.
4. Open repository **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch `main` and folder `/(root)`, then Save.
7. Wait a few minutes. The published URL should be `https://YOUR-USERNAME.github.io/photo-frame/`.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Controls
- Previous / next buttons
- Pause / play
- Shuffle on/off
- 5, 10, 15 or 30 second interval
- Fullscreen button
- Keyboard: left/right arrows, Space to pause/play, F for fullscreen
- Touch: swipe left/right

## Important privacy note
GitHub Pages websites are public. Do not add family/private photos or secrets. Anyone who finds the page can view the slideshow, and direct image URLs may be shareable independently. Use this version only for non-sensitive travel/scenery photos.

## ImgBB note
Third-party image links can change, be removed, or have usage limits. Keep your own backup of the original photos. Test a few images first before adding your full collection.
