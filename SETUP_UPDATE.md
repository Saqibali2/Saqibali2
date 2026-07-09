# Setup

This version improves spacing and cleans the activity section.

## What changed

- Improved spacing between the top banner, the button row, and the typing line.
- Replaced the multi-line top typing area with a cleaner single-line statement.
- Removed the top-language activity cards.
- Kept only:
  - stats card
  - streak card
  - activity graph
- Kept the metro banner lower in the README as the Journey map section.

## Files

```txt
README.md
assets/
  saqib-banner-editorial.svg
  saqib-banner-metro.svg
```

## Push commands

```bash
git init
git add .
git commit -m "Improve spacing and clean activity section"
git branch -M main
git remote set-url origin https://github.com/Saqibali2/Saqibali2.git
git push -u origin main --force
```

If remote is not set:

```bash
git remote add origin https://github.com/Saqibali2/Saqibali2.git
git push -u origin main --force
```
