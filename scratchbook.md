# Scratchbook

This is just a simple Markdown file used to work on ideas or write down things so do not forget it. It can be ideas for articles, step by step guide for setting up something (that might be turned into an article later), etc.

## Getting started with Hugo

```bash
hugo new site ...
cd ...

add a remote

git init 
git remote add origin https://github.com/octocat/Spoon-Knife
```

Many great themes, use one of the standard ones.

### Creating theme

create repo

git submodule add git@github.com:2ttech/hugo-material-theme.git themes/material-theme

hugo new theme material-theme-2

just change theme.toml and copy files to git repo

set theme in config.toml

npm init
npm install --save material-components-web@4.0.0

// version 5+ uses @use in scss files

create script to copy files
chmod 755 script

create main.scss and import material-components-web

add define main in index.html

hugo server -D --disableFastRender

reload page and it works

