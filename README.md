# Aivid — free short-form video maker

A single-page website (`index.html`, no build step, no server) that makes captioned short videos for TikTok, Reels and Shorts. Everything is rendered and encoded in the visitor's browser, so hosting is free and nothing is uploaded.

## Tools
- **Text → Video**: script → AI-narrated video with animated word-by-word captions. Includes a hook generator, 21 free AI voices (or your own recording), background music, and 9:16 / 16:9 / 1:1 output.
- **Chat Story → Video**: animated text-message story read aloud by two AI voices, shown split-screen over a moving background, with typing dots and message sounds.
- **Audio → Video**: MP3/WAV → video with a cover, title, live visualizer (bars, circle or wave), progress bar and optional captions.
- **Auto-Caption Video**: add captions, a headline and a progress bar to an existing clip, and reframe it to 9:16 (blurred fill or crop).

Backgrounds: animated parkour run, satisfying bounce, neon highway, hyper tunnel, lava lamp and warp speed; your own looping clips or images; or AI images generated per sentence (via the free Pollinations.ai service).

AI voices use the open-source Kokoro-82M model through [kokoro-js](https://www.npmjs.com/package/kokoro-js). It runs entirely in the browser: about 90 MB downloads once, then it's cached.

Captions accept plain text (timed automatically) or SRT/VTT (exact timing).

## Publish for free
- **GitHub Pages**: push this repo, then Settings → Pages → Deploy from branch → `master` / root.
- **Netlify / Cloudflare Pages / Vercel**: drag-and-drop the folder, or connect the repo. There is no build command, and the output dir is `/`.

Exports are MP4 in Chrome, Edge and Safari, and WebM in Firefox. Rendering runs in real time, so keep the tab visible while exporting.
