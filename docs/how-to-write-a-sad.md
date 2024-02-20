---
title: how to write a SAD 
permalink: /how-to-write-a-sad/
show_sidebar: true
menubar: menu
nav_order: 2
---
```mermaid
%%{init: { 'theme': 'default' }}%%
gantt
    title API Lifecycle
    dateFormat  DD-MMM-YY


    section Dev
    Develop Alpha version: done,  dev1, 01-01-2019, 30d
    Develop Beta version: done,  dev2, after dev1 alpha1, 60d

    section Stable
    Develop Stable version: done,  stable1, after dev2, 90d

    section Legacy
    Deprecated notice issued: milestone, done,  01-02-2019, 1d
    Available for use but no new integrations: active, 01-09-2020, 365d

    section Deprecated
    Deprecated date: milestone, active, 01-09-2021 
    Deprecation period, Available for use but no new integrations: active, dep2, 01-09-2021,  180d

    section Retired
    Retire API: milestone, active, 01-03-2022
    No longer available: active, 01-03-2022
   

   

```


# API Lifecycle Timeline

```mermaid
%%{init: { 'theme': 'default' }}%%
%%{ 'version': '9.1.3' }%%

gantt
    title API Lifecycle
    dateFormat  YYYY-MM-DD

    section Alpha
    Develop Alpha version          :done,    alpha1, 2020-01-01, 7d
    Develop Beta version           :active,  beta1, after alpha1, 14d

    section Stable
    Develop Stable version         :done,    stable1, after beta1, 21d
    Deprecate API                  :active,  deprecated, 2020-09-01, 30d

    section Legacy
    Develop Legacy version         :active,  legacy1, after deprecated, 14d

    section Deprecated
    Deprecated notice issued       :active,  deprecatedNotice, 2021-09-01, 30d

    section Retired
    Retire API                      :active,  retired, 2022-03-01, 7d

```
Yes, This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](https://jekyllrb.com/)

You can find the source code for Minima at GitHub:.
[jekyll][jekyll-organization] /
[minima](https://github.com/jekyll/minima)

You can find the source code for Jekyll at GitHub:
[jekyll][jekyll-organization] /
[jekyll](https://github.com/jekyll/jekyll)


[jekyll-organization]: https://github.com/jekyll

