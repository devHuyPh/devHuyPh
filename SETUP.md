# Installation for github.com/devHuyPh

The repository `devHuyPh/devHuyPh` already exists and is empty. Do not create it again.

## Fast path (Ubuntu)

```bash
git clone https://github.com/devHuyPh/devHuyPh.git
cd devHuyPh
# Copy README.md, assets/hero.svg and .github/workflows/snake.yml from this kit into the repo.
git add README.md assets/hero.svg .github/workflows/snake.yml
git commit -m "feat: premium dark tech GitHub profile"
git push origin main
```

## Enable the snake

1. In GitHub: `devHuyPh/devHuyPh` → Settings → Actions → General → Workflow permissions → Read and write permissions → Save, if your repository settings allow that change. The workflow explicitly requests `contents: write`.
2. Go to Actions → Generate contribution snake → Run workflow.
3. After success, the workflow creates the `output` branch. Its animation appears in the README; allow caching to refresh.

## Polish checklist

- Add verified email, LinkedIn, website (none are invented in this kit).
- Review skills; remove anything you don't actually use.
- Add project screenshots and factual feature descriptions to public repositories.
- In profile Edit profile, add short bio: `Full-Stack Developer | Laravel • Vue • Systems • Automation`.
- Pin your 4–6 best public repositories. Private repos cannot be surfaced as public repo cards.

## Dependencies / failure modes

- Stats, typing animation, icons and activity graph use third-party image endpoints: outages/rate limits can cause empty cards.
- GitHub stats are based on visible activity and third-party service calculations, not a measure of engineering skill.
- GitHub may render some SVG animation behaviors differently; banner has a static fallback.
- Avoid secrets, private project/client names, and unverifiable claims in a public profile.
