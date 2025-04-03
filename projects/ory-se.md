---
layout: page
title: Ory AB
banner: /static/img/projects/ory-se-0.png
permalink: /projects/ory-se/
---

## Description

Website I designed and created for [Ory AB](http://www.ory.se)
(update: no longer the website I made. They've switched to WordPress now),
a company that manufactures trucks and trailers.
The website was built in modern HTML5 and CSS3 with a material-design-inspired card-style design,
and some JavaScript for things like the carousel and the lightbox.

### Live demonstration

You can see the final product over at [ory.robinlinden.eu](https://ory.robinlinden.eu).

### Responsive webdesign

Having a webpage that works across all common device sizes is more important now than ever as
Google Analytics shows users visiting the website with phones made up over 40% of visitors,
even before Ory had a mobile-friendly webpage.

#### What is it?

Responsive design means that you serve the same content to all devices,
and use CSS (usually with the help of media queries) to ensure that it looks great everywhere.

#### Examples

##### The navigation

<figure>
	<img alt="Desktop navigation."
         src="{{ site.baseurl }}/static/img/projects/ory-se/desktop-navigation.png"/>
	<figcaption>On the desktop, we push the menu as far away from the brand as we can.</figcaption>
</figure>


<figure>
	<img alt="Tablet navigation."
         src="{{ site.baseurl }}/static/img/projects/ory-se/tablet-navigation.png"/>
	<figcaption>When going from desktop to tablet-size,
    we reduce the spacing between the brand and the navigation part of the header.</figcaption>
</figure>


<figure>
	<img alt="Phone navigation."
         src="{{ site.baseurl }}/static/img/projects/ory-se/phone-navigation.png"/>
	<figcaption>And when there's no more space to consume between the brand and the navigation,
    we collapse it into a hamburger-menu.</figcaption>
</figure>
<p></p>

### Technologies used

* [Jekyll](https://jekyllrb.com/)
* [carouFredSel](https://github.com/gilbitron/carouFredSel)
* [Lightbox2](https://github.com/lokesh/lightbox2)
* [jQuery](https://jquery.com/)

## Things I learnt

* [WebKit ~~does not~~ didn't handle flex minimum width correctly.](https://bugs.webkit.org/show_bug.cgi?id=136041)
* Masonry-style layouts are fairly easy to do with CSS columns.
* How to generate an image gallery from a folder full of images automatically* in Jekyll.
* Scraping a website to get images, titles, and descriptions for an image gallery using Python.
