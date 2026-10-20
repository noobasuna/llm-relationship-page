# TAN PEI SZE — Human–AI Safety Research

A standalone research website for GitHub Pages. Includes AIES, HRGuard, the industry guardrail comparison, user model poisoning, and the research roadmap.

## Publish on GitHub Pages

1. Create a public GitHub repository named `noobasuna.github.io` for the address `https://noobasuna.github.io/`.
   If that repository already contains your personal homepage, use a separate repository such as `ai-safety-research` to preserve it. The project address will be `https://noobasuna.github.io/ai-safety-research/`.
2. Unzip this download on your computer.
3. Upload the extracted files and the entire `papers` folder to the repository root. Upload the contents, not the ZIP itself. `index.html` must be at the top level.
4. In the repository, open Settings > Pages. Under Build and deployment, choose Deploy from a branch, then `main` and `/ (root)`, and save.
5. Open the site URL shown by GitHub once deployment completes.

The site uses relative links and works at either a user-site root or a project subpath. No installation, build command, server, API key, or ChatGPT account is required.

## Files

- `index.html`: complete page, styling, chart data, and chart interaction.
- `papers/hrguard.pdf`: supplied HRGuard manuscript.
- `papers/user-model-poisoning.pdf`: supplied ICASSP manuscript.
- `.nojekyll`: serves the site as static files.

## Edit

Edit `index.html` and commit the changes. GitHub Pages republishes from the selected branch. Open the file locally for a quick preview.

The industry scatter plot switches between four generators and their equal-weight mean. Full results tables remain available below the charts. The AIES community questions section has been removed.

## Publication note

Both supplied manuscript PDFs are included and linked from the website. A public repository makes these files publicly accessible. Omit a PDF and its corresponding link if you do not intend to publish it.
