---
title: "Demo"
slug: "demo"
date: 2022-09-30
toc: true
tocBorder: true
---

# 1 Basic settings

## 1.1 TOC

```toml
toc = true
tocBorder = true
```

## 1.2 Light/Dark

`/config.toml`
  ```toml
  appearance = "auto"
  ```


# 2 Markdown

## 2.1 Heading

### H3

#### H4

##### H5

###### H6

## 2.2 Paragraph

Incididunt ex adipisicing ea ullamco consectetur in voluptate proident fugiat tempor deserunt reprehenderit ullamco id dolore laborum. Incididunt ex adipisicing ea ullamco consectetur in voluptate proident fugiat tempor deserunt reprehenderit ullamco id dolore laborum. Incididunt ex adipisicing ea ullamco consectetur in voluptate proident fugiat tempor deserunt reprehenderit ullamco id dolore laborum.

Officia dolore laborum aute incididunt commodo nisi velit est est elit et dolore elit exercitation. Enim aliquip magna id ipsum aliquip consectetur ad nulla quis. Incididunt pariatur dolor consectetur cillum enim velit cupidatat laborum quis ex. Incididunt ex adipisicing ea ullamco consectetur in voluptate proident fugiat tempor deserunt reprehenderit ullamco id dolore laborum. Incididunt ex adipisicing ea ullamco consectetur in voluptate proident fugiat tempor deserunt reprehenderit ullamco id dolore laborum. Incididunt ex adipisicing ea ullamco consectetur in voluptate proident fugiat tempor deserunt reprehenderit ullamco id dolore laborum. Incididunt ex adipisicing ea ullamco consectetur in voluptate proident fugiat tempor deserunt reprehenderit ullamco id dolore laborum.

## 2.3 hr

---

## 2.4 List

### Ordered List

1. Longan
2. Lychee
3. Excepteur ad cupidatat do elit laborum amet cillum reprehenderit consequat quis.
    Deserunt officia esse aliquip consectetur duis ut labore laborum commodo aliquip aliquip velit pariatur dolore.
5. Melon
    - Cantaloupe
    - Honeydew
6. Miracle fruit

### Unordered List

- Olive
- Orange
    - Blood orange
    - Clementine
- Ut aute ipsum occaecat nisi culpa Lorem id occaecat cupidatat id id magna laboris ad duis. Fugiat cillum dolore veniam nostrud proident sint consectetur eiusmod irure adipisicing.

## 2.5 Blockquote

> Suspendisse tempus dolor nec risus sodales posuere. Proin dui dui, mollis a consectetur molestie, lobortis vitae tellus.
> 
> **Note** that you can use _Markdown syntax_ within a blockquote.

## 2.6 Code

Here is some `inline code`!

{{< highlight javascript >}}
const ultimateTruth = 'this theme is the best!';
console.log(ultimateTruth);
{{< / highlight >}}

```go
package main

import (
    "fmt"
    "net/http"
)

func handler(w http.ResponseWriter, r *http.Request) {
    fmt.Fprintf(w, "Hi there, I love %s!", r.URL.Path[1:])
}

func main() {
    http.HandleFunc("/", handler)
    http.ListenAndServe(":8080", nil)
}
```

## 2.7 Footnote

footnote footnote footnote footnote footnote footnote[^1]

[^1]: footnote footnote footnote footnote footnote footnote footnote footnote.

## 2.8 Table

| Table Heading 1 | Table Heading 2 | Center align    | Right align     | Left align(default) |
| :-------------- | :-------------- | :-------------: | --------------: | :-------------- |
| Item 1            | Item 2            | Italics             | Bold              | Code              |
| Item 1            | Item 2            | _italics_          | **bold**        | `code`           |

## 2.9 Link

[Bing](https://www.bing.com/)

## 2.10 Mark

juki7ujtyhre <mark>uyjthree</mark> juki7ujtyhre juki7ujtyhre juki7ujtyhre juki7ujtyhre

# 3 Shortcodes

>  use double {{}}

## 3.1 Details

{{< details summary="Click me" >}}
A lot of text or something else.
{{< /details >}}

## 3.2 Iconcode

{{< iconcode href="https://www.bing.com/" src="/icon/email.svg" width="50px" >}}

## 3.3 PDF

{< pdf src="/HaiyanKong_demo.pdf" >}

## 3.4 Figure (default)

{< figure src="/HaiyanKong_demo.png" width="600px" caption="caption">}
