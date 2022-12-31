---
layout: page
title: dispatches from the wasteland of culture
permalink: /about/
---

# [de-struct](https://rdelaureal.github.io/destruct-zine/)

#### video demo:  <URL HERE>

#### description

**de-struct** is a blog created by Ryan de Laureal using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/), inspired by the perspectives of the [Situationist International](https://monoskop.org/Situationist_International) as well as the design principles of the [Bauhaus](https://monoskop.org/Bauhaus), [Constructivism](https://monoskop.org/Constructivism), and other art movements of 20th century.

Jekyll is written in Ruby and makes use of the Liquid templating language. **de-struct**'s design modifies and builds upon Minima, Jekyll's base theme, using HTML, Liquid, CSS, and Sass. The files within the *_includes* and *_layouts* folders overwrite Minima's default HTML templates, while *assets/main.scss* modifies the default styling, creating **de-struct**'s unique theme. The site's main settings are configured in *_config.yml* and Jekyll's Ruby gems are set in the *Gemfile*. New original posts are added to the *_posts* directory.

The site's main HTML template is *_layouts/default.liquid*. Snippets of code corresponding to the site's head, header, and footer are inserted by Jekyll into this template from the files in the *_includes* folder, and the site's main post and page content is inserted into the `content` tag. The site's `<head>` tag is contained in *head.html*, which sets the site's main stylesheet and links to Google Fonts for the typogragraphy used in the site's design. In *header.liquid* and *footer.liquid* the site's title and main navigation bar are configured.

The site's other three main templates are *home.liquid*, *page.liquid*, and *post.liquid*, each of which extend *default.liquid*. In *home.liquid* the posts from the *_posts* directory are rendered as a list in reverse chronological order, which displays on homepage when the site is visited. The *page.liquid* file sets the formatting of all static pages, which can be added by creating a new HTML or markdown file in the main directory and adding the required front matter (for example, see the front matter at the top of this README file, which is configured to display as an "about" page on the live site). The page will then be rendered to the nav bar in the site's footer and accessible from there. The layout for posts in the *_posts* directory is configured in the *post.liquid* file.

When the site is deployed, the Liquid and Sass templates are converted to HTML and CSS, and copied to the *_site* directory, which hosts the site. The *_site/index.html* file is the site's final rendered homepage, and the *_site/assets/main.css* file is the site's final rendered stylesheet.
