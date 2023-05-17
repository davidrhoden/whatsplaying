---
layout: layouts/paintings.njk
title: Paintings
date: 2023-05-16
# permalink: "/paintings/{% if pagination.pageNumber > 0 %}{{ pagination.pageNumber + 1 }}/{% endif %}index.html"
pagination:
  data: collections.paintings
  size: 8
  alias: paintings
  reverse: true
eleventyNavigation:
  key: Paintings
  order: 4

---