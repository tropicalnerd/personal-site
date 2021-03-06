---
title: Raven PMG
slug: raven-pmg
layout: layouts/post.njk
link:
    href: https://ravenpmg.com
    text: Website
order: 4
cover:
    src: ./src/images/raven-pmg_cover.png
    alt: ravenpmg.com homepage
description: Website for Raven, an event production company in New Orleans
tags: [WordPress, Custom Theme]
# scripts: [/js/imhance.js]
---
{% imgScroll src="./src/images/raven-pmg_home.png", alt="Full scrollable homepage of ravenpmg.com" %}

Raven needed a site that would showcase their innovativeness in the event design industry. They had a website on Squarespace but it was proving too rigid to fit their content as their company grew. They provided Photoshop comps for a desktop version. From those I designed mobile comps and then a fully responsive, mobile-first theme.

Raven has a large portfolio that is a major focus of the site. I put the bulk of the interactivity budget there, adding tag filtering using the Isotope library by David DeSandro. To improve performance I used srcsets, lazy-loading and CloudFlare site caching.

Another fun interactive UI element of the site is the polyhedron overlays on the Crew page. The crew is represented as a grid of polyhedrons until you hover or tap (on mobile) and the crew member is revealed. It's a small touch that reveals the personality of the team and adds a lot of character to the site.