# Sportiva

A responsive Bengali-language IPTV web player using the public iptv-org M3U playlist.

## Features
- Loads the Bengali playlist from `https://iptv-org.github.io/iptv/languages/ben.m3u`
- Search and favorites (saved locally in the browser)
- HLS playback where supported, plus native browser playback
- Mobile-friendly layout, refresh control, fullscreen, and copy-stream-link action
- No backend or API key required

## Deploy with GitHub Pages
1. Create a repository named `Sportiva`.
2. Add `index.html` to the repository root.
3. In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Open the published Pages URL after deployment finishes.

## Important
This player only presents links from the selected public playlist. It does not host channels or guarantee that every stream is online, authorized in every region, or compatible with every browser. Some streams may fail due to provider restrictions, CORS, mixed-content rules, or unsupported formats. HLS.js is loaded from jsDelivr; native HLS support varies by browser.

## Credits
- **Developer:** Tahlil
- **Assistant:** Claude
- **Playlist:** [iptv-org](https://github.com/iptv-org/iptv)
