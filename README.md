# 汉字 Study — Chinese Vocabulary PWA

A spaced repetition flashcard app for learning Chinese.  
Works on iPhone and Mac. Installs like a native app. No App Store needed.

---

## How to install (free, 5 minutes)

### Step 1 — Host it on GitHub Pages

1. Go to [github.com](https://github.com) and create a free account (if you don't have one)
2. Click **New repository** → name it `hanzi-study` → set to **Public** → click **Create**
3. Upload all files from this folder: `index.html`, `manifest.json`, `sw.js`
4. Go to **Settings → Pages → Source** → select `main` branch → click **Save**
5. Your app will be live at: `https://YOUR-USERNAME.github.io/hanzi-study`

---

### Step 2 — Add to iPhone home screen

1. Open Safari on your iPhone
2. Go to your GitHub Pages URL
3. Tap the **Share** button (box with arrow)
4. Scroll down and tap **"Add to Home Screen"**
5. Tap **Add** — the app icon appears on your home screen!

---

### Step 2 (Mac) — Add to Dock

1. Open Safari on your Mac
2. Go to your GitHub Pages URL
3. Click **File → Add to Dock**  
   *(or click the share icon in the toolbar → Add to Dock)*
4. The app appears in your Dock like any native app

---

## Icons (optional)

The app works without custom icons, but you can add them:
- Create a 192×192 PNG named `icon-192.png`
- Create a 512×512 PNG named `icon-512.png`  
- Upload them to the same GitHub repository
- Use any Chinese character or design you like!

A simple way: use [favicon.io](https://favicon.io/favicon-generator/) to generate PNG icons.

---

## Features

- **Spaced repetition** — words due today are shown first; easy words come back later
- **Flashcards** — tap to reveal pinyin + English; rate Again / Hard / Easy
- **Quiz** — multiple choice with score tracking
- **Bulk import** — paste a list in `hanzi, pinyin, english` format
- **Tags** — organize words by lesson or topic
- **Offline** — works with no internet after first load

---

## Adding your own words

**Single word:** Use the "Add" tab or Quick Add on the home screen.

**Bulk import:** Paste into the "Paste a list" box, one per line:
```
你好, nǐ hǎo, hello
谢谢, xiè xie, thank you
水, shuǐ, water
吃, chī, to eat
```

Note: words reset when you close the browser tab (in-memory only).  
To save words permanently, use localStorage — ask Claude to add that feature.
