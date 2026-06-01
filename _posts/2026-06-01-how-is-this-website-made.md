---
layout: post
title: "How I built this website"
date: 2025-10-01
---

For my Professional Networking module at Howest, I needed to set up an 
e-portfolio that would be publicly accessible via a URL. In this post I'll 
explain how I built it, what choices I made, and how easy it is to add new 
content.

## Platform choice

I considered several options: Notion, WordPress and GitHub Pages. I ended up 
choosing **GitHub Pages with Jekyll** for a few reasons:

- It's free and stays accessible after graduation
- It fits exactly what the assignment describes: a repository with files where 
each file represents an article
- Adding a new post is as simple as creating a new Markdown file and pushing 
it to the repository
- Exporting to PDF is trivial — just use "Save as PDF" in the browser

## How it works

The site runs on **Jekyll**, a static site generator that is built into GitHub 
Pages. I don't need to install anything locally, everything happens directly 
on GitHub. The theme I'm using is **Minima**, the default Jekyll theme, which 
gives a clean and professional look without any extra configuration.

The repository structure is straightforward:

- `_config.yml` — site settings like title, description and theme
- `index.md` — the home page
- `about.md` — the about page
- `_posts/` — a folder where every blog post lives as its own Markdown file

## Adding a new post

Adding a new post takes about two minutes:

1. Go to the `_posts/` folder in the GitHub repository
2. Click **Add file → Create new file**
3. Name it in the format `YYYY-MM-DD-title.md`
4. Add the front matter at the top and write the content in Markdown
5. Commit directly to main — the site updates automatically within a minute

That's it.

## Hosting

The site is hosted for free on **GitHub Pages** at 
[jitsewindens.github.io](https://jitsewindens.github.io). No domain name was 
registered, the default GitHub Pages URL is sufficient for this portfolio.

## Conclusion

GitHub Pages with Jekyll turned out to be the right choice for this project. 
The setup took about 30 minutes and since then adding new content has been 
quick and painless. For anyone looking for a simple, free and reliable way to 
host a portfolio, I'd definitely recommend this approach.
