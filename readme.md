# BAR NuttyB Tips

## Description

This repo aims to 
- store tips and guides on how to play Beyond All Reason
- share the content of these guides to many people

## How to test

Install dependencies (python +)
```bash
python -m pip install -r requirements.txt
```

Serve the content
```bash
cd mkdocs
python -m mkdocs serve
```

## How to build

Build the website content
```bash
cd mkdocs
python -m mkdocs build
mv site/ ..
```

## How to deploy

Merge modifications into `stable` branch.
```bash
git checkout stable
git merge dev
git checkout dev
git rebase stable
```

Run deploy command in stable
```bash
git checkout stable
cd mkdocs
python -m mkdocs gh-deploy
```

## Sources

Tips are from `https://pastebin.com/17vpGEzv`.

Theme is from `https://github.com/squidfunk/mkdocs-material`.

Dino image from `https://img.icons8.com/?size=100&id=16033&format=png&color=000000`.