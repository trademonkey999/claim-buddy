# Claim Buddy

Single-file web app for filing Government TA/DA, LTC and Permanent-Duty travel claims
under the Defence Services Travel Regulations, Edition 2025.

- **Live app:** https://trademonkey999.github.io/claim-buddy/ (GitHub Pages, branch `main`, root).
- Fully self-contained — no dependencies, no server, no network. Data is saved locally
  in the browser (localStorage); nothing is uploaded anywhere.

## Publish on GitHub Pages
1. Push this folder to a **public** GitHub repo.
2. Repo → **Settings → Pages** → Source: **Deploy from a branch** → Branch: **main** / **/(root)** → Save.
3. After ~1 minute the app is live at `https://<username>.github.io/<repo>/`.
4. Open that URL on your phone and "Add to Home Screen" to use it like an app.

> Note: each browser keeps its own claims (localStorage). Use Export/Import (if added) to move data between devices.
