---
title: "Hello World"
date: 2023-04-11T23:19:57+09:00
draft: true
hidden: false
tags: [
    "test"
]
---

## Hello! World

test用の記事。

### 記事一覧

Obsidianのdataviewで記事一覧表示。

```dataview
TABLE WITHOUT ID file.link AS "title", file.frontmatter.draft AS "draft", file.frontmatter.hidden AS "hidden", file.tags AS "tags", file.mday AS "last_modified"
FROM "content"
SORT file.cday desc
```
