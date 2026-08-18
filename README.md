# culverapps.github.io — VibeCheck support & legal pages

GitHub Pages site for the **culverapps** GitHub account (used for the Google Play
developer profile website + mandatory privacy policy URL).

## Files
- `index.html` — landing / developer page
- `privacy-policy.html` — Play-compliant privacy policy (required by Google Play)

## Publish steps (one-time, your GitHub account)
1. GitHub account username is **`culverapps`** (already created).
2. Create a new repo named exactly **`culverapps.github.io`** (user-pages repo).
3. Upload `index.html` and `privacy-policy.html` to that repo.
4. Repo → Settings → Pages → Source: "Deploy from a branch" → branch `main` / root → Save.
5. Wait ~1 min. Site is live at `https://culverapps.github.io`.

## URLs to paste into Play Console
- Developer profile / identity website: `https://culverapps.github.io`
- Privacy Policy URL: `https://culverapps.github.io/privacy-policy.html`
- App support email: (set to an inbox you monitor — see note below)

## Notes
- The privacy policy references `privacy@vibecheck.app` by default. Swap it for a real
  inbox you control (e.g. culverapps@gmail.com) before publishing, or forward the domain.
- Google crawls these URLs; keep them live for the life of the app.
- To update the policy later, edit `privacy-policy.html` and re-push.
