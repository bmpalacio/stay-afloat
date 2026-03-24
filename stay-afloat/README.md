# Stay Afloat.

Stay afloat as long as you can. The game gets harder over time. Avoid obstacles, don’t hit the ground or fly too high—and watch the scenery change every 25 seconds.

**Play:** Open `index.html` in a browser, or use one of the publishing options below.

---

## Publishing to a real website

Your game is a single `index.html` file (no build step), so it’s easy to host.

### Option 1: GitHub Pages (free)

The game is in the **stay-afloat** repo under the `stay-afloat/` folder.

1. On GitHub: **Settings → Pages** (left sidebar).
2. Under **Source**, choose **Deploy from a branch**.
3. Branch: **main**, folder: **/ (root)**.
4. Save. After a minute or two, the site will be at:
   - **https://bmpalacio.github.io/bmoney/**  
   Your game will be at: **https://bmpalacio.github.io/stay-afloat/stay-afloat/**

To have the game at a **clean URL** (e.g. `username.github.io/stay-afloat`):

- Create a **new repo** (e.g. `stay-afloat`).
- Copy only `index.html` into the **root** of that repo (no `stay-afloat` folder).
- In that repo: **Settings → Pages → Deploy from branch → main → / (root)**.
- Your game will be at: **https://bmpalacio.github.io/stay-afloat/**

### Option 2: Netlify (free, custom domain)

1. Go to [netlify.com](https://www.netlify.com) and sign in (e.g. with GitHub).
2. **Add new site → Import an existing project** → connect **GitHub** and choose **bmoney**.
3. Set **Base directory** to `stay-afloat` (or leave blank if you use a repo that has only the game).
4. **Publish directory** leave as `.` (or `stay-afloat` if base is the repo root).
5. Deploy. You’ll get a URL like `random-name.netlify.app`. In **Domain settings** you can add a custom domain.

### Option 3: Vercel (free)

1. Go to [vercel.com](https://vercel.com) and import your GitHub repo.
2. If the game is in `stay-afloat/`, set **Root Directory** to `stay-afloat`.
3. Deploy. You’ll get a URL like `your-project.vercel.app`.

---

## Controls

- **Desktop:** ↑ fly up, ← → move left/right. Enter or Space to restart after game over.
- **Mobile/tablet:** Use the on-screen Up / Left / Right buttons, or keyboard if available.

Works in modern browsers on desktop, tablet, and phone.
