jekyll-gulp-octopress
=============================

A starter project including full setup for Jekyll, GulpJS &amp; Octopress.

## Requirements

To use this starter project, you'll need the following things installed on your machine.

1. [Bundler](http://bundler.io/) - `$ gem install bundler`
2. [NodeJS](http://nodejs.org) - use the installer.
3. [GulpJS](https://github.com/gulpjs/gulp) - `$ npm install -g gulp` (mac users may need sudo)

## Local Installation

1. Clone this repo, or download it into a directory of your choice.
2. Inside the directory, run `bundle install`.
3. And run `npm install`

## Usage

**development mode**

This will give you file watching, browser synchronisation, auto-rebuild, CSS injecting etc etc.

```
$ gulp
```

**jekyll**

As this is just a Jekyll project, you can use any of the commands listed in their [docs](http://jekyllrb.com/docs/usage/)

**Octopress**

Here are the subcommands for Octopress.

```
init <PATH>         # Adds Octopress scaffolding to your site
new <PATH>          # Like `jekyll new` + `octopress init`
new post <TITLE>    # Add a new post to your site
new page <PATH>     # Add a new page to your site
new draft <TITLE>   # Add a new draft post to your site
publish <POST>      # Publish a draft from _drafts to _posts
unpublish <POST>    # Search for a post and convert it into a draft
isolate [POST]      # Stash all posts but the one you're working on for a faster build
integrate           # Restores all posts, doing the opposite of the isolate command
deploy              # deploy your site via S3, Cloudfront, Rsync, or to GitHub pages.
```

This project changed my needs, I owe credit to [shakyShane](https://github.com/shakyShane/jekyll-gulp-sass-browser-sync) and [Octopress](https://github.com/octopress/octopress)