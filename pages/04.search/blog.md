---
title: Search
published: false
hide_git_sync_repo_link: true
blog_url: /blog
show_sidebar: true
show_breadcrumbs: true
show_pagination: true
content:
    items:
        - '@self.children'
    limit: 5
    order:
        by: date
        dir: desc
    pagination: true
    url_taxonomy_filters: true
bricklayer_layout: true
display_post_summary:
    enabled: true
icon: search
hide_from_post_list: true
---

This page uses the open source [TNTSearch plugin](https://github.com/trilbymedia/grav-plugin-tntsearch) and includes the ability for fuzzy (i.e. approximate) searches.
