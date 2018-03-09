# Setup
You can setup a personal or project page through GitHub.
A personal page has the following domain name: `<username>.github.io` whereas a project page has the
domain name: `<username>.github.io/<myproject>`.
You can have an number of project pages however you can have only one personal page.

## Personal page (`<username>.github.io`)

### 1. Fork the repository
Fork the repository from [here](https://github.com/kbsezginel/gh-pages-template).

### 2. Rename the repository
Go to *Settings* -> *Repository name* and write down `<username>.github.io`.

## Project page (`<username>.github.io/<myproject>`)

### 1. Fork the repository
Fork the repository from [here](https://github.com/kbsezginel/gh-pages-template).

### 2. Enable GitHub Pages
Go to *Settings* -> *GitHub Pages* in your fork of the repository.
Under *source* select *master branch*.

> You can also serve the website from *docs* folder. This is especially useful for project pages
to keep the website files and project files separate. You basically need to keep all the files for the
webpage in a folder named *docs* and in step 2 under *source* select *master branch/docs folder*.
More info [here](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/).

# Settings

## Adding pages
To add a new page you need to create a new markdown file with the name of your choice.
For example here *setup.md* file is used to generate content for *setup* page.

### Layouts
There are currently two layouts: default and full.
In the default layout a sidebar containing navigation is present whereas in full layout the full page is reserved for page content.
The full layout can be selected by adding a yaml front matter to the markdown/html file:
```
---
layout: full
---
```

## Adding links to the navigation bar
The navigation bar can be controlled by modifying the *_config.yml* file.
Under navigation enter the title you would like to see on the sidebar and enter the relative link to that page.

# Tutorials
More tutorials on github pages can be found here:
- [GitHub pages basics](https://help.github.com/categories/github-pages-basics/)
- [GitHub basic writing and formatting syntax](https://help.github.com/articles/basic-writing-and-formatting-syntax/)
- [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Setting up your GitHub Pages site locally with Jekyll](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)
- [Jekyll front matter](https://jekyllrb.com/docs/frontmatter/)
