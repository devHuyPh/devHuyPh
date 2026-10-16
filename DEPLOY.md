# Deploy Premium Profile V2

1. Extract ZIP under `/home/huy/Bản tải về/`. Directory: `devHuyPh-premium-v2`.
2. Run:

```bash
cd ~/devHuyPh
cp -r "/home/huy/Bản tải về/devHuyPh-premium-v2/." .
git add README.md assets .github
git commit -m "design: premium dark tech GitHub profile v2"
git push origin main
```

3. Hard refresh GitHub profile (Ctrl+Shift+R).

## Snake animation (optional)

The README intentionally excludes Snake until the SVGs exist. Go to GitHub repository > Actions > Generate contribution snake > Run workflow. When run succeeds, confirm `output` branch exists and the generated SVG files are accessible. Then append:

```html
### `05 // CONTRIBUTION ANIMATION`
<p align="center"><img src="https://raw.githubusercontent.com/devHuyPh/devHuyPh/output/github-contribution-grid-snake-dark.svg" width="100%" alt="Contribution snake" /></p>
```

If workflow cannot push, verify Settings > Actions > General > Workflow permissions: Read and write permissions, and branch protections. GitHub Actions must be enabled. After enabling, rerun manually.

Activity graph is excluded because the previous remote image endpoint did not load. GitHub's native contribution calendar still appears on the profile outside the README.
