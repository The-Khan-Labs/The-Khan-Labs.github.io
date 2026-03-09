# the-khan-labs.github.io

Org Pages for The-Khan-Labs. Redirects to the theme demo.

## Why 2 repos?

| Repo | Purpose | URL |
|------|---------|-----|
| **khanlab-docusaurus-theme** | Theme code + live demo | [the-khan-labs.github.io/khanlab-docusaurus-theme](https://the-khan-labs.github.io/khanlab-docusaurus-theme/) |
| **The-Khan-Labs.github.io** | Root redirect | [the-khan-labs.github.io](https://the-khan-labs.github.io/) → theme demo |

- **Theme repo**: Contains the actual theme (`custom.css`), demo Docusaurus site, docs. Deploys via GitHub Actions to `/khanlab-docusaurus-theme/`.
- **Org pages repo**: Serves at root. This repo just redirects visitors to the theme demo so `the-khan-labs.github.io` goes somewhere useful.

## Setup

1. Create repo **The-Khan-Labs.github.io** on GitHub (org name + .github.io)
2. Push: `git push -u origin main`
3. Pages: Settings → Pages → Source: **Deploy from a branch** → main → **/ (root)**

## Theme repo Pages

For `khanlab-docusaurus-theme`, Pages must use **GitHub Actions** (not branch).  
Settings → Pages → Source: **GitHub Actions**.
