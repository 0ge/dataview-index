---
area: [[<% tp.file.cursor(1) %>]]
category: [[<% tp.file.cursor(2) %>]]
location:
 - <% tp.file.cursor(3) %>
tags:
 - id
---

# <% tp.file.title %>

**Purpose and scope:** <% tp.file.cursor(4) %>

```dataviewjs
let area = dv.current().area
let category = dv.current().category
let id = dv.current().file.name
let path = '"' + [area, category, id].join("/") + '"'

dv.list(dv.pages(path).file.link)
```
