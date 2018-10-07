---
layout: page
title: Contribute
site_nav_category: contribute
site_nav_category_order: 400
is_site_nav_category: true
---

This is Hinge's fork of the Android Kotlin Style Guide. Portions of this page are reproduced from work created and <a href="http://code.google.com/policies.html">shared by the Android Open Source Project</a> and used according to terms described in the <a href="http://creativecommons.org/licenses/by/2.5/">Creative Commons 2.5 Attribution License.</a>

**We are looking forward to all of your contributions!**

## Development

You can run the site locally on your computer while making changes.

### Setup Ruby and Bundler

Ensure that you have Ruby and [Bundler](http://bundler.io/) installed.

    gem install bundler

_Note: If you encounter an error about `You don't have write permissions for the /Library/Ruby/Gems/2.3.0 directory` you might need to run this as `sudo`._

### One-time setup

    git clone git@github.com/Hinge/kotlin-guides.git
    mv ~/hinge/kotlin-guides
    mkdir bundle
    bundle install --path vendor/bundle

_Note: If you're on Mac OS and this fails installing nokogiri, run `brew unlink xz`, install, and then `brew link xz`._

### Running the site

    bundle exec jekyll serve

Point your browser at [http://127.0.0.1:4000/kotlin-guides/](http://127.0.0.1:4000/kotlin-guides/).
