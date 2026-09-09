# Ultimate Telegram Media Downloader - Getting Started Page

A simple, responsive GitHub Pages website for documenting how to use Ultimate Telegram Media Downloader.

## Files

```text
.
├── index.html
├── style.css
├── README.md
└── images/
```

## 1. Add your screenshots

Create the `images` folder and add your screenshots/GIFs.

Suggested filenames:

```text
images/
├── step-1-pin.png
├── step-2-telegram.png
├── step-3-select.png
├── step-4-download.png
├── step-5-folder.png
└── step-6-progress.png
```

The current HTML uses visual placeholders so the page works immediately. Replace each placeholder with an image when your screenshots are ready.

For example, replace:

```html
<div class="media-placeholder">
  <span>📸</span>
  <strong>Add your screenshot here</strong>
  <small>images/step-1-pin.png</small>
</div>
```

with:

```html
<img
  class="step-image"
  src="images/step-1-pin.png"
  alt="How to pin Ultimate Telegram Media Downloader"
/>
```

## 2. Customize the links

Search `index.html` for these placeholder links:

```text
https://chromewebstore.google.com/
mailto:support@example.com
href="#"
```

Replace them with:

- Your Chrome Web Store listing
- Your support email
- Your FAQ page
- Your privacy policy
- Any other relevant links

## 3. Customize the branding

The main colors are defined at the top of `style.css`:

```css
:root {
  --primary: #229ed9;
  --primary-dark: #1687bd;
}
```

Change these if you want a different brand color.

## 4. Publish with GitHub Pages

Create a GitHub repository, for example:

```text
ultimate-telegram-downloader-guide
```

Upload:

```text
index.html
style.css
README.md
images/
```

Then:

1. Open the repository on GitHub.
2. Go to **Settings**.
3. Open **Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select your `main` branch and `/ (root)`.
6. Click **Save**.
7. GitHub will provide your Pages URL.

It will typically look like:

```text
https://YOUR-USERNAME.github.io/ultimate-telegram-downloader-guide/
```

## 5. Recommended final structure

Once the page is complete, I recommend having these sections:

1. Quick Start
2. How to Pin the Extension
3. How to Select Media
4. How to Download
5. How to Pause/Resume
6. How to Organize Downloads
7. Supported Media Types
8. FAQ
9. Contact Support

For a polished onboarding experience, screenshots and short GIFs are especially useful for the steps where the user needs to click something.
