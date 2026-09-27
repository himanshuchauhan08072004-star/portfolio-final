# Portfolio — Himanshu Chauhan

A developer portfolio with two live, embedded, try-it-yourself demos instead of static screenshots.

## LIVE : https://portfolio-final-alpha-liart.vercel.app/

## Important: files must stay in the same folder (no subfolders)

When uploading to GitHub, upload `index.html`, `himanshu.jpg`, and `Himanshu_Chauhan_Resume.pdf` all together as loose files at the top level of the repo — **not** inside a subfolder. The code expects them at the root (e.g. `himanshu.jpg`, not `assets/himanshu.jpg`), because GitHub's drag-and-drop upload doesn't reliably preserve folder structure.

## Sections

1. **Hero** — headline + live embedded Shrinkit demo
2. **Work** — Shrinkit (image compressor) and Peblo Story Buddy (web demo + Flutter source), each with their own live embedded demo, plus three smaller "concept" project cards with no live link
3. **About** — photo, bio, quick facts
4. **Resume** — direct PDF download button
5. **Footer** — contact, GitHub, LinkedIn

## Before sharing this link with anyone

Both embedded demos pull from separate Vercel deployments:
- `https://image-compressor-seven-theta.vercel.app` (Shrinkit)
- `https://peblo-web-demo.vercel.app` (Peblo web demo)

**Check Vercel → each project → Settings → Deployment Protection → "Vercel Authentication" is OFF for both.** If it's on, the deployment requires a login, and both the live link and the embed will show a 404 to anyone who isn't logged into your Vercel account — including recruiters.

If an embed ever fails to load for any other reason, a fallback message with a direct "Open ↗" link appears automatically after a few seconds, so the page never shows a broken blank box.

## Stack

Plain HTML, CSS, and vanilla JavaScript. No frameworks, no build step. Deploys as a static site on Vercel's free Hobby plan.

## Author

Himanshu Chauhan — himanshuchauhan08072004@gmail.com
