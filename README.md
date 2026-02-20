# Serve and Deploy Notes

You have to be in the `mkdocs` directory:
```bash
cd mkdocs
conda activate icecream
```

Run the site locally:
```bash
mkdocs serve
```

Git check in for code continuity:
> Just use vscode's git extension, but add files one at a time...
```bash
# git add . # VERY BAD PRACTICE, DON'T DO!!!
git add docs/base-recipes/custard-base.md
```

Deploy to GitHub:
```bash
mkdocs gh-deploy
```