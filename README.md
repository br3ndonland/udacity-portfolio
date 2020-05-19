# README

<a href="https://www.udacity.com/">
	<img src="https://s3-us-west-1.amazonaws.com/udacity-content/rebrand/svg/logo.min.svg" width="300">
</a>

**Udacity Full Stack Web Developer Nanodegree program**

Project 2. Portfolio site

Brendon Smith

br3ndonland

## Description

This was my second project for the Udacity Full Stack Web Developer nanodegree program. Students were provided with a design mockup (screenshot) of a developer portfolio webpage, and had to replicate the design with HTML and CSS.

<img src="docs/img/design-mockup-portfolio-thumbnail-square.png" alt="Portfolio website mockup">

I based the webpage on [Bootstrap](http://getbootstrap.com/) v4.0.0. In the main webpage _index.html_, I linked to the Bootstrap core CSS through their Content Delivery Network (CDN). I also included [Prism syntax highlighting](http://prismjs.com/) CSS and JavaScript files, and _portfolio.css_ for additional custom styling.

I provided a toggle button in the navigation menu that uses jQuery JavaScript to change the page color scheme.

I used the webpage design to create a full website with Jekyll, and hosted the site with GitHub Pages. The website includes a homepage, an "About" page where I introduce myself and my Udacity work, a "Methods" page explaining how I built the site in detail, a "Rubric" page providing the Udacity project documentation, and a "Review" page documenting the Udacity code review.

## Repository contents

**All files for the GitHub pages site reside in the _docs/_ directory. HTML, CSS, and JS files above the _docs/_ directory were used only to submit the homepage for the Udacity project.**

- _css/_
  - _portfolio.css:_ CSS stylesheet for the webpage
- _docs/_
  - Files for GitHub Pages Jekyll website.
- _img/_
  - Images used in the webpage
- _js/_
  - _portfolio.js_: jQuery JavaScript for the webpage
- _index.html_: Main webpage. A modified version of the page is stored as _docs/index.html_ for the GitHub Pages website.
- _README.md_: concise description of the repository for GitHub

## Running the Jekyll site

The Udacity project only requires a simple webpage, which is at _[index.html](./index.html)_. I also made a full GitHub Pages website using [Jekyll](https://jekyllrb.com/), in the _docs/_ directory. To run the Jekyll site:

- [Clone](https://help.github.com/en/articles/cloning-a-repository) (or [fork](https://help.github.com/en/articles/about-forks) then clone) this repo.
- Install Ruby v2.6+ as explained in the [Jekyll docs](https://jekyllrb.com/docs/installation/) for your operating system. Bundler should already be installed along with Ruby.
- Install the site and generate [Gemfile.lock](https://jekyllrb.com/docs/ruby-101/#gemfile): `bundle install --path vendor/bundle`. This installs Ruby gems to _./vendor/bundle_, which avoids having to write to the system RubyGems directory.
- Serve the site: `bundle exec jekyll serve`
- View the site in a browser at [localhost:4000](http://localhost:4000).
