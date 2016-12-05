# Blog
last updated: 12-2-16, by: Shahar Zimmerman

## Develop
Follow these steps to run & develop the project on a local webserver.

#### Dependencies
Ruby gems: `jekyll`, `jekyll-sitemap`, `pygments.rb`

This project supports rvm; as soon as you enter the directory, rvm will create a gemset for you named `jekyll`, to which you can install the dependencies with this command:

    gem install jekyll jekyll-sitemap pygments.rb

#### Clone & update submodules
    git clone https://github.com/szimmer1/blog.git
    cd blog
    git checkout gh-pages
    git submodule init
    git submodule update --checkout
    
#### Run
    jekyll serve

Original README from forked repo:

# Leonids Jekyll Themes

**[Leonids](http://renyuanz.github.io/leonids)** is a two column responsive Jekyll theme perfect for powering your GitHub hosted blog. The idea is inspired by PureCSS blog layout.

## What is Leonids?

* Responsive templates. Looking good on mobile, tablet, and desktop.
* Gracefully degrading in older browsers. Compatible with Internet Explorer 9+ and all modern browsers.
* Minimal embellishments -- content first.
* Simple and clear permalink structure.
* Support for Disqus Comments
* Support for multi-authors
* Random color for Tags

![screenshot of Leonids theme](https://raw.githubusercontent.com/renyuanz/leonids/gh-pages/img/screenshot-1.jpg)

and ![full support for code syntax highlighting](https://raw.githubusercontent.com/renyuanz/leonids/gh-pages/img/screenshot-2.jpg)

See a [live version of Leonids](http://renyuanz.github.io/leonids/) hosted on GitHub.

## Getting Started

Leonids jekyll theme takes advantage of Sass and data files to make customizing easier. These features require Jekyll 2.x and will not work with older versions of Jekyll.

To learn how to install and use this theme check out the [Setup Guide](http://renyuanz.github.io/leonids/theme-setup/) for more information.
