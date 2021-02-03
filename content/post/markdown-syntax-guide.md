+++
title = "Markdown Syntax Guide"
author = "Thomas J. Fan"
date = 2021-02-03T14:12:09-05:00
tags = ["markdown"]
+++

# Headings


The following HTML `<h1>`—`<h6>` elements represent six levels of section headings. `<h1>` is the highest section level while `<h6>` is the lowest.

# H1
## H2
### H3
#### H4
##### H5
###### H6

## Paragraph

Xerum, quo qui aut unt expliquam qui dolut labo. Aque venitatiusda cum, voluptionse latur sitiae dolessi aut parist aut dollo enim qui voluptate ma dolestendit peritin re plis aut quas inctum laceat est volestemque commosa as cus endigna tectur, offic to cor sequas etum rerum idem sintibus eiur? Quianimin porecus evelectur, cum que nis nust voloribus ratem aut omnimi, sitatur? Quiatem. Nam, omnis sum am facea corem alique molestrunt et eos evelece arcillit ut aut eos eos nus, sin conecerem erum fuga. Ri oditatquam, ad quibus unda veliamenimin cusam et facea ipsamus es exerum sitate dolores editium rerore eost, temped molorro ratiae volorro te reribus dolorer sperchicium faceata tiustia prat.

Itatur? Quiatae cullecum rem ent aut odis in re eossequodi nonsequ idebis ne sapicia is sinveli squiatum, core et que aut hariosam ex eat.

## Images

### Left

![NYC Python Logo](/blog/images/nyc_python_meetup_logo.png)

### Center

![NYC Python Logo center](/blog/images/nyc_python_meetup_logo.png?style=align-center)

## Blockquotes

The blockquote element represents content that is quoted from another source, optionally with a citation which must be within a `footer` or `cite` element, and optionally with in-line changes such as annotations and abbreviations.

#### Blockquote without attribution

> Tiam, ad mint andaepu dandae nostion secatur sequo quae.
> **Note** that you can use *Markdown syntax* within a blockquote.


## Tables

Tables aren't part of the core Markdown spec, but Hugo supports supports them out-of-the-box.

   Name | Age
--------|------
    Bob | 27
  Alice | 23

## Code Blocks

#### Code block with backticks

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```

## List Types

#### Ordered List

1. First item
2. Second item
3. Third item

#### Unordered List

* List item
* Another item
* And another item

#### Nested list

* Item
1. First Sub-item
2. Second Sub-item

## Rich content

See https://gohugo.io/content-management/shortcodes/ for details

### Twitter

{{< tweet 877500564405444608 >}}

### Github gist

{{< gist spf13 7896402 >}}

### Youtube

{{< youtube w7Ft2ymGmfc >}}
