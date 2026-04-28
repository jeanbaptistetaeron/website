# Jean-Baptiste Tatsumi Taëron — Personal Website Project Info

## GitHub
Repo: https://github.com/jeanbaptistetaeron/website.git
Branch: main

## Netlify
URL: https://tatsumitaeron.com
Auto-deploys on push to main.

## Local file path
/Users/tatsumitaeron/Library/Mobile Documents/com~apple~CloudDocs/_pro/T_work/tatsumi_taeron_website/

## Rules
- Always provide the push command after sharing an updated HTML file.

## Push commands
```bash
cd "/Users/tatsumitaeron/Library/Mobile Documents/com~apple~CloudDocs/_pro/T_work/tatsumi_taeron_website"

# Everything
git add .
git commit -m "Update with latest changes"
git push

# Index only
git add index.html
git commit -m "Update index file"
git push

# Specific sections
git add signs/index.html && git commit -m "Update signs index file" && git push
git add structures/index.html && git commit -m "Update structures index file" && git push
git add surfaces/index.html && git commit -m "Update surfaces index file" && git push
git add love-letters/index.html && git commit -m "Update love-letters index file" && git push
git add systems/index.html && git commit -m "Update systems index file" && git push
git add dessin/index.html && git commit -m "Update dessin index file" && git push
git add construction/index.html && git commit -m "Update construction index file" && git push

# Images/videos
git add dessin/ && git commit -m "Update dessin folder with HTML and images" && git push
git add work/video/ && git commit -m "Update videos in work/video folder" && git push
```
