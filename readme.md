# Neural Earth Fields website

This repository contains the Jekyll site for the Neural Earth Fields Benchmark & Hackathon. The site is intentionally lightweight and uses only Jekyll, Liquid, HTML, and SCSS.

## Local development

Install the Ruby dependencies and start the local server:

```bash
bundle install
bundle exec jekyll serve
```

The site will be available at [http://localhost:4000](http://localhost:4000).

## GitHub Pages deployment

Because this repository is named `neuralearthfields.github.io` and belongs to the `neuralearthfields` organization, GitHub Pages can publish it at [https://neuralearthfields.github.io/](https://neuralearthfields.github.io/).

In the GitHub repository, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select the default branch and the `/ (root)` folder, then save. GitHub Pages will build and publish the Jekyll site after changes are pushed to that branch.

The site is configured with an empty `baseurl`, as required for this organization-level Pages site.
