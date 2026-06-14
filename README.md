# Banking Knowledge Graph — Demo Walkthrough

Self-contained HTML prototypes (no server, no build) for the UOS Knowledge Graph,
running on the real California Credit Union graph (synthetic / public-sourced, no member data).

**Open `index.html`** for the landing page, or jump straight to `console.html`.

| File | What it is |
|---|---|
| `index.html` | Landing page that links everything |
| `console.html` | The KG console — 9 views, live attestation loop, Ask-the-Agent, folded navigator |
| `navigator.html` | Full 756-node graph navigator (also embedded inside the console) |
| `architecture.html` | Interactive architecture diagram + data model |
| `explainer.html` | Plain-language "what we'd add" notes |

## Host it free on GitHub Pages (public)

1. On github.com → **New repository** → name it (e.g. `kg-demo`) → **Public** → Create.
2. On the repo page → **Add file → Upload files** → drag in **everything in this folder** (index.html, console.html, navigator.html, architecture.html, explainer.html, robots.txt, README.md) → **Commit changes**.
3. **Settings → Pages** → under *Build and deployment*, Source = **Deploy from a branch**, Branch = **main**, folder = **/ (root)** → **Save**.
4. Wait ~1 minute → your URL appears at the top of the Pages settings:
   `https://rmahabal.github.io/kg-demo/`

### Taking it down later
- **Settings → Pages → un-publish**, or flip the repo to **Private**, or **delete the repo** — any of these takes the site offline immediately.
- `robots.txt` already tells search engines not to index it.

> Note: while live, a GitHub Pages site is publicly reachable by URL and the page source is viewable. The data here is synthetic, but the framing is internal — share the link deliberately.
