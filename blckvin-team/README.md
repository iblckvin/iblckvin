# blckvin-team

Video-editing portfolio. Static site: no build step.

## Structure
- `index.html` – the whole site (edit `WHATSAPP`, `INSTAGRAM`, `EMAIL` near the top of the script)
- `videos/` – portfolio reels (`<id>-<category>.mp4`); paths are relative so it works anywhere

## Deploy on Vercel
1. vercel.com → Add New → Project → import this repo
2. Framework Preset: **Other**; leave Build Command and Output Directory empty
3. Deploy

Or via CLI: `npx vercel --prod`
