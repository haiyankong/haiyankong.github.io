---
title: "Demo"
slug: "demo"
date: 2022-09-30
custom_js: [mouse_coords]
toc: true
tocBorder: true
---

# Basic settings

## TOC

```toml
toc = true
tocBorder = true
```

## Styles

`/config.toml`
  ```toml
  appearance = "auto"
  ```


# Markdown

## Paragraph

Incididunt ex adipisicing ea ullamco consectetur in voluptate proident fugiat tempor deserunt reprehenderit ullamco id dolore laborum.

Officia dolore laborum aute incididunt commodo nisi velit est est elit et dolore elit exercitation. Enim aliquip magna id ipsum aliquip consectetur ad nulla quis. Incididunt pariatur dolor consectetur cillum enim velit cupidatat laborum quis ex.

## hr

---

## List

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

## Blockquote

> Suspendisse tempus dolor nec risus sodales posuere. Proin dui dui, mollis a consectetur molestie, lobortis vitae tellus.

## Code

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

## Footnote

footnote footnote footnote footnote footnote footnote[^1]

[^1]: footnote footnote footnote footnote footnote footnote footnote footnote.


## Table

Table1

| Table Heading 1 | Table Heading 2 | Center align    | Right align     | Table Heading 5 |
| :-------------- | :-------------- | :-------------: | --------------: | :-------------- |
| Item 1          | Item 2          | Item 3          | Item 4          | Item 5          |
| Item 1          | Item 2          | Item 3          | Item 4          | Item 5          |

# Shortcodes

## Details

{{< details summary="Click me" >}}
A lot of text or something else.
{{< /details >}}

## Figure

{{< figure 
    src="/demo.png"
    alt="demo"
    width="600px"
    caption="11111111"
    >}}

## Icon-svg

{{< icon-svg href="https://www.bing.com/" target="_blank" src="/icon/email-outlook.svg" alt="Icon" width="50px" >}}

## Link

{{< link "https://www.bing.com/" >}}Bing{{< /link >}}