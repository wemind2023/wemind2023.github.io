# Wemind

This website uses [CloudCannon](http://cloudcannon.com/), the Cloud CMS for Jekyll.

## Features

* Contact form
* Pre-built pages
* Pre-styled components
* Blog with pagination
* Post category pages
* Disqus comments for posts
* Staff and author system
* Configurable footer
* Optimised for editing in [CloudCannon](http://cloudcannon.com/)
* RSS/Atom feed
* SEO tags
* Google Analytics

## Setup

1. Site and author details in `_config.yml`.
2. Google Analytics and Disqus keys in`_config.yml`.
3. CMS settings at [CloudCannon](https://app.cloudcannon.com/)

## Develop

Built with [Jekyll](http://jekyllrb.com/) version 3.3.1, but should support newer versions as well.

Dependencies can be installed with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

~~~bash
$ bundle exec jekyll serve
~~~

## Editing

### Posts

* Add, update or remove a post in the *Posts* collection.
* The **Staff Author** field links to members in the **Staff** collection.
* Documentation pages are organised in the navigation by category, with URLs based on the path inside the `_docs` folder.
* Change the defaults when new posts are created in `_posts/_defaults.md`.

### Contact Form

* Preconfigured to work with CloudCannon, but easily changed to another provider (e.g. [FormSpree](https://formspree.io/)).
* Sends email to the address listed in company details.

### Staff

* Reused around the site to save multiple editing locations.
* Add `excluded_in_search: true` to any documentation page's front matter to exclude that page in the search results.

### Navigation

* Exposed as a data file to give clients better access.
* Set in the *Data* / *Navigation* section.

### Footer

* Exposed as a data file to give clients better access.
* Set in the *Data* / *Footer* section.
