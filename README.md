# BugFreeCode Editor (Static)

## What this is
A static, client-side code editor + live preview + DSA problems browser.

## Deploy (easy)
Because this project is **pure HTML/CSS/JS**, you can deploy by uploading these files to any static hosting provider:

- `index.html`
- `login.html`
- `signup.html`
- `analyze.html`
- `dsa.html`
- `dsa_problems.js`
- `README.md`
- `TODO.md`

### Option A: Local preview
In the project folder, run a simple static server:

```bash
npx serve -l 3000
```

Then open: `http://localhost:3000/index.html`

### Option B: Any static host
Upload the files to GitHub Pages / Netlify / Vercel static, etc.

## Notes / limitations
- **Python execution** uses **Pyodide** (runs in-browser). First load can take time.
- **JS analysis** uses **JSHint** (via CDN). If CDN is blocked, analysis may not work.
- Live preview uses an **iframe** and `postMessage` console forwarding.

