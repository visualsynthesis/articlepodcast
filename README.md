# Article Podcast

**Turn any news article into an instant audio podcast — no accounts, no API keys, no cost.**

Paste a URL, hit Listen, and hear the article read aloud with natural browser voices. It's a single HTML file with zero dependencies that runs entirely in your browser.

---

## How It Works

1. Paste any article URL into the search bar
2. Click **Listen**
3. The app fetches the article, extracts the text (stripping ads, navigation, sign-up banners, and other clutter), and reads it aloud using your browser's built-in speech synthesis

That's it. No server, no backend, no API keys.

## Features

- **Zero setup** — just open the HTML file in your browser
- **Voice selection** — choose from all voices available on your system, with UK English female auto-selected by default
- **Speed control** — 0.8x to 1.5x playback speed
- **Live voice switching** — change the voice mid-playback and it switches immediately
- **Progress bar** — see how far along you are, click to seek
- **Smart extraction** — strips out ads, navbars, audio players, newsletter promos, comment sections, and other non-article content so you only hear the actual article
- **Works offline** — once the article is fetched, playback uses local speech synthesis with no internet needed

## Getting Started

1. Download `article-to-podcast.html` and `favicon.ico` into the same folder
2. Open `article-to-podcast.html` in your browser
3. Paste an article URL and click Listen

### Best Voice Quality

For the most natural-sounding voices, use **Microsoft Edge** — it includes high-quality neural voices (marked with a star in the voice dropdown). Chrome and Safari work fine too, just with slightly more robotic voices.

## Hosting It

Since it's a single HTML file with no backend, you can host it anywhere for free:

- **GitHub Pages** — push as `index.html` to a repo, enable Pages in settings
- **Netlify** — drag and drop the file at [netlify.com/drop](https://app.netlify.com/drop)
- **Vercel** — deploy with one click from a GitHub repo
- **Anywhere** — any static file host works, it's just HTML

## Limitations

- Some sites with aggressive paywalls or bot detection (Bloomberg, WSJ, The Athletic) may block the article fetch
- Very long articles may take a moment to begin playback as the text is chunked for the speech engine
- Voice quality and available voices depend on your browser and operating system

## File Structure

```
article-podcast/
├── article-to-podcast.html   ← the entire app
├── favicon.ico               ← browser tab icon
└── README.md                 ← you're here
```

## License

MIT — do whatever you want with it.
