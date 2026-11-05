---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# featured-image value can be one objectid for a photo object in this collection, a relative path to an image in this project, or a full url to any image. If left blank, no featured image will appear at top of About page.
about-featured-image: demo_031
# set background-position for featured image, "center", "top", "bottom"
position: bottom
# major heading to display over featured image
heading: About the Collection
# paragraph text below heading in featured image
sub-heading: 
# additional padding added to the feature to increase size. Give value in em or px, e.g. "5em".
padding: 6em
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

## About Fall Collection

This site is built with the Collection Builder framework to display a small collection of Fall and Halloween themed images from the Library of Congress.

## About the Library Content

This collection demo displays content from library-related digitized
materials from the Library of Congress.
Content and metadata for this collection were retrieved
from the Library of Congress' ["Free to Use" Libraries](https://www.loc.gov/free-to-use/libraries/)
set of images.

{% include feature/image.html objectid="demo_001" width="75" %} 

{% include cb/about_the_about.md %} 
