# MI Practice Simulator — NHC Florida
## Deploy to Netlify (Free) — Step-by-Step

### What you need
- Free GitHub account: https://github.com
- Free Netlify account: https://netlify.com
- Your Anthropic API key: https://console.anthropic.com/settings/keys

---

### Step 1 — Put this folder on GitHub
1. Go to https://github.com/new
2. Name it `mi-simulator`, leave it Public, click Create
3. Click "uploading an existing file"
4. Upload the contents of this folder: `public/` folder, `netlify/` folder, `netlify.toml`
5. Click Commit changes

### Step 2 — Connect to Netlify
1. Go to https://app.netlify.com
2. Click Add new site → Import an existing project → GitHub
3. Select your `mi-simulator` repo
4. Build settings auto-detect — leave as-is
5. Click Deploy site

### Step 3 — Add your API key (keeps it hidden from users)
1. In Netlify: Site configuration → Environment variables
2. Add a variable: Key = `ANTHROPIC_API_KEY`, Value = your key (sk-ant-...)
3. Save, then go to Deploys → Trigger deploy → Deploy site

### Step 4 — Share with members
Your site will have a URL like `yoursite.netlify.app` — share it and members just open and go.

---

### Cost
~$0.03–0.08 per full session. A cohort of 20 members doing 3 sessions each ≈ $2–5 total.
Set a spending limit at: https://console.anthropic.com/settings/limits

### Updating later
Edit files on GitHub (pencil icon) → commit → Netlify redeploys automatically in ~1 minute.
