MARDI GRAS CODE PUSHER - installable app (PWA)

1. Upload ALL files in this folder to any HTTPS static host (GitHub Pages, Netlify Drop, Cloudflare Pages, Vercel).
   (It must be served over https:// - opening index.html straight from your disk will play the game but won't install.)
2. Open the hosted link:
   - PC (Chrome / Edge): click the install icon in the address bar, or menu > Install app.
   - Android (Chrome): menu > Install app / Add to Home screen.
   - iPhone/iPad (Safari): Share > Add to Home Screen.
3. After the first load it works offline.

Updating: change files, then bump V='code-pusher-v2' in sw.js (e.g. v2) so devices fetch the new version.
Controls: Arrows/WASD move, Space/X smash, Shift/E hold to pull, H hint, R restart. On phones use the on-screen buttons.
