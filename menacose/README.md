---
title: README
description: This page is not published
lang:
draft: true
permalink:
comments:
tags:
aliases:
enableToc:
cssclasses:
socialImage:
socialDescription:
created:
published:
---
# Quartz Properties

## 🧭 **Core Metadata**

|Flag|Meaning|
|---|---|
|**title**|The page’s title. Used in the `<title>` tag, the header on the page, backlinks, and the graph. If not defined, the first H1 heading is used.|
|**description**|A short text summary used for meta tags, search previews, and Open Graph cards. Doesn’t show up in the page body.|
|**lang**|Sets the language of the page’s HTML (e.g., `en`, `fr`, `ar`). Helps search engines and accessibility tools.|

---

## 🧩 **Publishing & Visibility**

| Flag          | Meaning                                                                                                                    |
| ------------- | -------------------------------------------------------------------------------------------------------------------------- |
| **draft**     | Boolean. If `true`, the page is skipped during build. Useful for incomplete work-in-progress notes. (Overrides `publish`.) |
| **permalink** | Custom URL path for the page. Overrides the automatically derived path from the filename. Example: `/projects/inkwave`.    |
| **comments**  | Boolean. Enables or disables the comments component (if you’ve integrated Giscus, Commento, etc.).                         |
| **tags**      | A list of tags associated with the page. Used in tag pages, related content, and the graph view.                           |
| **aliases**   | Alternative slugs/URLs that redirect to this page. Prevents broken links after renames.                                    |

---

## 🧮 **Layout & Appearance**

| Flag                  | Meaning                                                                                                                      |
| --------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| **enableToc**         | Boolean. Enables or disables the table of contents sidebar for this page. Defaults to `true`.                                |
| **cssclasses**        | Adds one or more CSS class names to the page’s `<body>` tag. Perfect for per-page theming or layout tweaks.                  |
| **socialImage**       | Sets the image used for the Open Graph and Twitter card previews.                                                            |
| **socialDescription** | Overrides the `description` when generating social preview cards. Useful if you want shorter or more marketing-focused text. |

---

## 📆 **Dates & Sorting**

| Flag        | Meaning                                                                             |
| ----------- | ----------------------------------------------------------------------------------- |
| **created** | The date the page was originally created. Used for sorting and displaying in lists. |
