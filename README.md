# Aivid — free short-form video maker

A single-page website (`index.html`, no build step, no server) that makes captioned short videos for TikTok, Reels and Shorts. Everything is rendered and encoded in the visitor's browser, so hosting is free and nothing is uploaded.

## Tools
- **Text → Video**: script → animated word-by-word captions on gradient or your own images. Includes a hook generator, an optional voiceover (upload or record with the mic), background music, and 9:16 / 16:9 / 1:1 output.
- **Audio → Video**: MP3/WAV → video with a cover, title, live visualizer (bars, circle or wave), progress bar and optional captions.
- **Auto-Caption Video**: add captions, a headline and a progress bar to an existing clip, and reframe it to 9:16 (blurred fill or crop).
- **Chat Story → Video**: animated text-message conversation with typing dots, message sounds and optional music.

Captions accept plain text (timed automatically) or SRT/VTT (exact timing).

## Publish for free
- **GitHub Pages**: push this repo, then Settings → Pages → Deploy from branch → `master` / root.
- **Netlify / Cloudflare Pages / Vercel**: drag-and-drop the folder, or connect the repo. There is no build command, and the output dir is `/`.

Exports are MP4 in Chrome, Edge and Safari, and WebM in Firefox. Rendering runs in real time, so keep the tab visible while exporting.
