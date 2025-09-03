# My GitHub Pages Blog

## Setup Instructions

1. Create a new GitHub repository named `username.github.io` (replace username with your GitHub username)
2. Push this code to that repository:
```bash
git init
git add .
git commit -m "Initial blog setup"
git remote add origin https://github.com/username/username.github.io.git
git push -u origin main
```

3. Go to repository Settings > Pages
4. Under "Source", select "main" branch
5. Wait a few minutes for your site to be published

Your blog will be available at `https://username.github.io`

## Adding New Posts
Create new markdown files in `_posts` directory with the format:
`YYYY-MM-DD-title.md`
