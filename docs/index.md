---
title: how to retire an API
permalink: /
show_sidebar: true
menubar: menu
nav_order: 1
---
# API Lifecycle
```mermaid
%%{init: { 'theme': 'default' }}%%
%%{ 'version': '9.1.3' }%%

gantt
    title API Lifecycle
    dateFormat  YYYY-MM-DD

    section Alpha
    Develop Alpha version: done,    alpha1, 2020-01-01, 30d
    section Beta
    Develop Beta version: active,  beta1, after alpha1, 60d
    section Stable
    Release Stable version: milestone, done,  stable1, after beta1, 1d
    section Legacy
    Issue Deprecation notice: milestone, done,  legacy1, 2020-09-01, 1d
    Available for use, no new integrations: done, legacy2, after legacy1, 365d
    section Deprecated
    Deprecated: milestone, done, deprecated1, startdate 2021-03-01, 1d
    section Retired
    Retired: milestone, done, retired, after legacy2 ,1d

```

You can find the source code for Minima at GitHub:.
[jekyll][jekyll-organization] /
[minima](https://github.com/jekyll/minima)

You can find the source code for Jekyll at GitHub:
[jekyll][jekyll-organization] /
[jekyll](https://github.com/jekyll/jekyll)


[jekyll-organization]: https://github.com/jekyll
