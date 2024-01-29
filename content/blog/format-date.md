---
title: "Format date for posts"
description:
date: 2024-01-27T13:04:13-08:00
lastmod: 2024-01-28T19:52:51-0800

categories:
    - featured

draft: true

---

Let's see what some code highlighting looks like.

## PowerShell

``` pwsh
$dtmFormat = '%Y-%m-%dT%H:%M:%S%Z00'
get-date -UFormat $dtmFormat
```

## Bash

``` Bash
date +'%Y-%m-%dT%H:%M:%S%z'
```