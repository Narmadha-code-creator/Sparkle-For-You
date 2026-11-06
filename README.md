# A Special Diwali Surprise for Gokul 🪔✨

One self-contained `index.html` (HTML, CSS, vanilla JS, Canvas, Web Audio). No build tools, no backend, no frameworks.

## Deploy on GitHub Pages
1. Create a new repository on github.com (for example `gokul-diwali`), set to Public.
2. Click **Add file → Upload files**, drag in `index.html` and `README.md`, then **Commit changes**.
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
4. Wait 1 to 2 minutes. Your site will be at `https://YOUR-USERNAME.github.io/gokul-diwali/`.
5. Send that link to Gokul (the 🔗 button on the page can share it too).

## Edit the sender name
Open `index.html` and find the block marked `EDIT YOUR CONTENT HERE` near the top of the script:
`const CONFIG={SENDER:"Narmadha S D", ...}`. The name appears only in the final section, so Gokul discovers it at the end.

## Edit messages
In the same block:
- `LETTER` is the personal letter (one variable). The letter sign-off is intentionally just a heart so the name stays hidden until the end; add a name there if you prefer.
- `QUOTES` holds the 12 rotating wishes.
- `SURPRISES` holds the 5 gift surprises (text, title, accent color).
- `TH` (at the end of the script) holds the 5 heartfelt messages in "A Thousand Hearts, One Special Person". The 16 romantic quotes are the last 16 entries of `QUOTES`.
- The "One last thing, Gokul..." message is plain HTML in the final section.
Other headings and hero text are plain HTML in `index.html`.

## Edit colors and theme
Change the CSS variables at the top of the `<style>` block (`:root{--rp:...}`): royal purple, violet, pink, saffron, gold, turquoise, cream.

## Notes
- Sound is off until the first tap on "Discover your surprise", and can be toggled with the speaker button (top right).
- Respects `prefers-reduced-motion`. Fonts load from Google Fonts (fallbacks are included if offline).
