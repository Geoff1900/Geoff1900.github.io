---
title: checklists
permalink: /checklists/
show_sidebar: true
menubar: menu
---


```mermaid
sequenceDiagram
    participant API
    participant Developer

    Developer->>API: Develop Alpha version
    API-->>Developer: Alpha version ready

    Developer->>API: Develop Beta version
    API-->>Developer: Beta version ready

    Developer->>API: Develop Stable version
    API-->>Developer: Stable version ready

    Developer->>API: Deprecate API on 01/09/2020
    API-->>Developer: Deprecation notice issued

    Developer->>API: Develop Legacy version
    API-->>Developer: Legacy version ready

    Developer->>API: Retire API on 01/03/2022
    API-->>Developer: API retired
```

This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](https://jekyllrb.com/)

You can find the source code for Minima at GitHub:
[jekyll][jekyll-organization] /
[minima](https://github.com/jekyll/minima)

You can find the source code for Jekyll at GitHub:
[jekyll][jekyll-organization] /
[jekyll](https://github.com/jekyll/jekyll)


[jekyll-organization]: https://github.com/jekyll
