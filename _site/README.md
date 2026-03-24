# Kagami

[![Build Status](https://travis-ci.org/kamikat/jekyll-theme-kagami.svg?branch=master)](https://travis-ci.org/kamikat/jekyll-theme-kagami)
[![Gem Version](https://badge.fury.io/rb/jekyll-theme-kagami.svg)](https://badge.fury.io/rb/jekyll-theme-kagami)

Based on Kagami theme by Kamikat.

### Navigation bar

For whatever reason, the nav bar no longer worked in the Kagami theme. My needs are very simple, so I made a very simple navbar.

To add pages to the navbar, create the page and set up as usual:

```yaml
layout: page
title: literally anything
lang: zh-Hans
position: 100
navtitle: literally-anything
navbar: true
```

Now edit navlist.yml in the data folder:

```yaml
nav_list_title: navlist
navs:
  - title: literally anything
    url: /subfolder/anything.html
```

## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

