---
title: how to retire an API
permalink: /
show_sidebar: true
menubar: menu
nav_order: 1
---

Yes, This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](https://jekyllrb.com/)

```mermaid
sequenceDiagram
    participant API
    participant Developer

    Alpha->>Beta: Develop Alpha version
    Alpha->>Beta: Develop Alpha version
    Beta-->>Stable: Alpha version ready

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

You can find the source code for Minima at GitHub:.
[jekyll][jekyll-organization] /
[minima](https://github.com/jekyll/minima)

You can find the source code for Jekyll at GitHub:
[jekyll][jekyll-organization] /
[jekyll](https://github.com/jekyll/jekyll)


[jekyll-organization]: https://github.com/jekyll
