---
layout: default
title: Contact
nav_order: 7
---

# Search

Just the docs uses [lunr.js](http://lunrjs.com) to add a client-side search interface powered by a JSON index that Jekyll generates. All search results are shown in an auto-complete style interface (there is no search results page). By default, all generated html pages are indexed  using the following data points:

- Page title
- Page content
- Page URL

## Set up search

### 1. Generate search index

Before you can use search, you must initialize the feature by running this
