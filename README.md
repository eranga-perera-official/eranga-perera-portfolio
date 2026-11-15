# Eranga Perera — Personal Portfolio

A responsive, dark editorial portfolio for Eranga Perera. This personal portfolio is kept separate from Zentro Digital.

## Project files
- `index.html` — public homepage, reads its content from `content.json`
- `content.json` — profile, projects, experience, services and links
- `admin/index.html` — browser-based editor for updating `content.json`
- `assets/` — add approved project images and a CV here

## Enable GitHub Pages
1. Open this repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then Save.
4. GitHub will show the public website URL in the Pages panel. The expected project URL is `https://eranga-perera-official.github.io/eranga-perera-portfolio/`.

## Edit the portfolio
Open the published website's `/admin/` path. Create a GitHub fine-grained personal access token restricted to this repository with **Contents: Read and write** permission. Use it in the editor to load and publish `content.json`. Do not share the token or paste it into chat.

## Before sharing publicly
- Add your preferred email, WhatsApp and social profile URLs in `content.json`.
- Add your actual portfolio images and replace any sample project summaries with final approved case-study copy.
- Only publish client and employer work that you are authorised to show.

## Recovery
The previous website is preserved on branch `backup/pre-portfolio-replacement-2026-11-15`.
