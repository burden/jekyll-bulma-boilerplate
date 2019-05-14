[![Build Status](https://travis-ci.org/burden/jekyll-bulma-boilerplate.svg?branch=master)](https://travis-ci.org/burden/jekyll-bulma-boilerplate)
# jekyll-bulma-boilerplate

A nifty boilerplate for Jekyll made magnificent with the help of Bulma.

**[Demo](https://jekyll-bulma-boilerplate.burden.cc/)**

![jekyll-bulma-boilerplate](https://raw.githubusercontent.com/burden/jekyll-bulma-boilerplate/master/screenshot.png)

## Features

- [Bulma 0.7.4](https://github.com/jgthms/bulma/tree/0.7.4)
- [jQuery 3.2.1](https://github.com/jquery/jquery/tree/3.2.1)
- Dependency management: [yarn](https://yarnpkg.com)
- Asset pipeline: [jekyll-assets](https://rubygems.org/gems/jekyll-assets)
  - [JS uglifier](https://rubygems.org/gems/uglifier/versions/3.2.0)
- HTML compression: [compress.html](http://jch.penibelst.de/)
- Testing: [html-proofer](https://github.com/gjtorikian/html-proofer)
- Analytics: [Google Analytics](https://www.google.com/analytics/)

## Dependencies
Your development environment should have ruby and the gem package manager setup already.

1. Install bundler `gem install bundler`
2. Install [yarn](https://yarnpkg.com/en/docs/install)

## Getting Started

```
$ bundle install
$ yarn install
$ bundle exec jekyll serve
```

## Deploy

### Deploy to Github Pages from Travis

1. Point Travis to repository
2. Configure Travis
3. Generate a [Personal Access Token](https://github.com/settings/tokens) from Github
  - The only scope needed is repo:public_repo
4. Set `GITHUB_API=<token>` on Travis
  - Make sure `Display value in build log` toggle is set to `Off`!

### Deploy to Netlify  

  [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/burden/jekyll-bulma-boilerplate)
  
  #### Wait, what happens when I click that button?

  Good question. Here's what it will do...

  1. Netlify will clone the git repository of this project into your Github account. This action will require your permission from Github, and of course a Netlify account. 
  2. Netlify will then create a new site for you, and configure it to use your shiny new repo. Right away you'll be able to deploy changes simply by pushing changes to your repo.
  3. Enjoy your new website 🎉
