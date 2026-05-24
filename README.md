# Yiyang Chen's Personal Homepage

This repository contains the source code for my academic personal website:

https://yiyangc1999.github.io

The site is built with Jekyll and hosted through GitHub Pages. It is based on the Academic Pages theme, with content customized for my research, publications, teaching, honors, and academic activities.

## Repository Structure

- `_pages/`: main website pages, including the homepage, news, publications, research, teaching, and honors.
- `_publications/`: publication content rendered on the publications page.
- `_teaching/`: teaching experience entries.
- `_data/`: navigation, author metadata, and other structured site data.
- `files/`: static files such as my CV PDF.
- `images/`: profile and website images.

## Updating Content

Most website content is written in Markdown. Common updates include:

- Homepage: `_pages/about.md`
- News: `_pages/news.md`
- Publications: `_publications/publications.md`
- Research experience: `_pages/research-experiences.md`
- Teaching: `_teaching/`
- Honors and awards: `_pages/honors-awards.md`
- Navigation bar: `_data/navigation.yml`
- CV PDF: `files/cv_YiyangCHEN.pdf`

After editing, commit and push changes to the `main` branch. GitHub Pages will rebuild and publish the site automatically.

## Running Locally

To preview the website locally, install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

The local site should be available at:

```text
http://localhost:4000
```

If `_config.yml` is changed, restart the Jekyll server so the configuration is reloaded.

## Acknowledgment

This website is adapted from the Academic Pages template, which is based on the Minimal Mistakes Jekyll theme.
