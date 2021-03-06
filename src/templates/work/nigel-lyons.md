---
title: Nigel Lyons
slug: nigel-lyons
layout: layouts/post.njk
link: 
    href: https://nigelyons.video
    text: Website
siteCreated: 2018-03-04
postCreated: 2019-06-10
postModified: 2021-08-01
order: 6
cover:
    src: ./src/images/nigel-lyons_cover.png
    alt: nigelyons.video homepage
description: Portfolio site for Nigel Lyons, an independent video producer in Washington, DC
tags: [CSS Grid, Static Site, Node.js, Logo Design]
# scripts: [/js/imhance.js]
---
{% imgScroll src="./src/images/nigel-lyons_home.png", alt="Home page of nigelyons.video" %}

Nigel Lyons is an independent video producer in Washington, DC. In 2015, with Sediment Press, I designed his logo, business card and a portfolio site using WordPress. In 2018 I redesigned the site as a static single page that would highlight some of his best work. The main design considerations we had were: 

 - Effectively showcasing his video work.
 - Building a design system based on his existing branding.
 - Rock solid responsive design that looks great on any device.

As a single page site, a CMS would have added a lot of overhead. I could have written the site directly in HTML and CSS, completely forgoing a build step, but I chose to generate the site in Node to gain the benefit of some modern development tools. I used Pug for the templates, Stylus as a CSS preprocessor, Gulp as an asset bundler, and browserSync for live reloading. This stack allowed me to automate repetitive tasks without giving up granular control over the finished product. Pug's mixins were a huge time saver, they allowed me to treat the blocks and video cards as components, where I could pass in the data as a property to generate structured markup.

The main challenges I faced in creating a truly responsive site were the header design, whitespace management, and arrangement of content blocks. For the header I used to CSS grid to create a vertical version for narrow screens and a horizontal version wider devices. To keep whitespace proportional I made a margin system utilizing CSS custom properties that coordinated changing all the margins on the page by adjusting a few variables. CSS grid proved useful again in intrinsically laying out the video cards in flexible grid, and for rearranging the site layout on larger screen sizes.
