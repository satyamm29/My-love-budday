# My-love-budday

This is a simple static birthday page. Below are instructions to test locally and deploy to Netlify.

Local testing

1. Run a quick static server from the project root:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

2. (Optional) Use Netlify CLI for a closer dev experience:

```bash
npm install -g netlify-cli
netlify dev
```

Deploy to Netlify

- Option A — connect this GitHub repo in the Netlify app (recommended): create a new site from Git, pick this repo, and set the publish directory to `.` (root).
- Option B — drag and drop the project folder in the Netlify Sites > Deploys > Drag and drop area.

Netlify CLI quick deploy (from repo root):

```bash
netlify deploy --prod --dir=.
```

If you want a specific build configuration, add or edit `netlify.toml`.
