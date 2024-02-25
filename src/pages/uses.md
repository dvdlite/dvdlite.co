---
title: Uses
seo:
  title: Uses
  description: The applications, tools, and platforms that I currently use
permalink: /uses/index.html
layout: page
preloads:
  href: '/assets/fonts/robotomono/robotomono-regular.woff2'
  as: 'font'
  type: 'font/woff2'
  crossorigin: true
---
Below are the applications, tools, and services I am currently using on a regular basis. I am somewhat of a minimalist, so I've been shedding 3rd party apps lately and falling back to default applications where it makes sense to do so. Fair warning, I play mostly in the &#63743; and Linux ecosystems.

<!-- loop uses-bits -->

{% set itemList = collections.dvduses %}

<!-- details -->

{% include 'components/details.njk' %}
