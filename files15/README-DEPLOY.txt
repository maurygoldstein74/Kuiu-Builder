FIELD KIT v1.40 - DEPLOY (GitHub -> Netlify)
1. Your GitHub repo root must contain exactly: index.html, netlify.toml, netlify/ folder (and this readme, harmless).
   Upload the CONTENTS of this unzipped folder - not the folder itself.
2. Commit. Netlify auto-builds (~1 min).
3. Verify: https://YOURSITE.netlify.app/.netlify/functions/anthropic
   -> JSON "Method not allowed" = LIVE.  White "Page not found" = check repo root per step 1.
App Setup tab must show v1.40 after deploy.
