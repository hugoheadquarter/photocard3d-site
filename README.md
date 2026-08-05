# photocard3d.com

Static marketing + legal site for **Poca 3D**, served by GitHub Pages at
[photocard3d.com](https://photocard3d.com).

Plain HTML and one stylesheet — no build step, no Jekyll (`.nojekyll`).
Editing a file and pushing to `main` publishes it.

| Path | Purpose |
|---|---|
| `index.html` | Landing page |
| `privacy/` | Privacy Policy — linked from the app's paywall and Settings |
| `terms/` | Terms of Use — linked from the app's paywall and Settings |
| `support/` | Support / FAQ — the App Store Connect *Support URL* |
| `CNAME` | Custom domain binding for GitHub Pages |

Both legal pages are the URLs submitted to App Store Connect. They must stay
reachable for as long as the app is on sale — App Review checks them.
