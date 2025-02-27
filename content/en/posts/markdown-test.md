---
title: Markdown test
date: 2023-08-02
---

**Contents:**

[[toc]]

Lorem ipsum dolor **sit amet**, consectetur adipiscing elit (C). Sed nec __risus elementum__, tempor tortor non, bibendum libero. Suspendisse potenti. Vivamus dapibus *tortor neque*, sed aliquet lacus _elementum nec_. Morbi vel ligula vitae leo placerat sollicitudin quis at eros. Pellentesque tristique mi a tortor auctor, sit amet elementum augue pulvinar. Donec non orci in ~~ipsum mollis~~ tempor. Integer libero est, H~2~O pharetra ++vitae++ facilisis quis 🇬🇧.

## Quotes, code and typography

> Maecenas vel quam id eros tristique sollicitudin. Nunc tincidunt orci malesuada, vehicula mauris ut, sollicitudin lacus. Quisque eget vestibulum quam. 

Aenean ac tincidunt felis (r). Fusce eu ==arcu blandit==, consectetur odio ullamcorper, maximus erat (R). Fusce aliquam sapien a commodo aliquet. Phasellus placerat sagittis euismod. Curabitur vitae est id nunc ornare --- scelerisque in vitae nisl. In non mi leo...

<!-- FM:Snippet:Start data:{"id":"Quote","fields":[{"name":"quote","value":"Maecenas vel quam id eros tristique sollicitudin. Nunc tincidunt orci malesuada, vehicula mauris ut, sollicitudin lacus. Quisque eget vestibulum quam."},{"name":"author","value":"Scott Evans"},{"name":"cite","value":"Website"},{"name":"url","value":"https://scott.ee"}]} -->
<blockquote>
  <p>Proin sit amet neque vitae leo posuere pellentesque vel non augue. Sed efficitur ipsum neque, non gravida ipsum vestibulum eget.</p>
  <figcaption>— Scott Evans, <cite><a href="https://scott.ee">Website</a></cite></figcaption>
</blockquote>
<!-- FM:Snippet:End -->

Cras quis sollicitudin eros (c). Fusce eget velit `quis nulla pharetra eleifend id vitae nisl`. Aenean vehicula sem vitae nunc semper porta. Donec porta leo vitae massa accumsan consequat. Praesent quis sodales orci, ut elementum quam. Phasellus ultrices lectus in tempus varius+-. Duis est nulla -- imperdiet dapibus ultricies non 19^th^, hendrerit non mauris(tm).

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

Donec tincidunt mauris id metus iaculis tempor. Proin sit amet neque vitae leo posuere pellentesque vel non augue. Sed efficitur ipsum neque, non gravida ipsum vestibulum eget. Fusce augue lacus, vestibulum efficitur tincidunt et, posuere sed sem. Etiam tortor lorem, vestibulum ac lectus vitae, feugiat egestas augue. Proin id suscipit mi.

---

## Lists

### Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa


1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar

### Unordered

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ Very easy!

---

### Notices and links

<div class="notice notice-notice">General notice</div>

<div class="notice notice-warning">Warning notice</div>

<div class="notice notice-error">Error notice</div>

### Heading level 3

Cras quis sollicitudin eros [link with title](https://scott.ee "title text!"). Fusce eget velit quis nulla pharetra eleifend id vitae nisl. Aenean [normal link](https://scott.ee) vitae nunc semper porta. Donec porta leo vitae massa accumsan consequat. Praesent quis sodales orci, ut elementum quam. Phasellus ultrices lectus in tempus varius. Duis est nulla, imperdiet dapibus ultricies non, hendrerit non mauris.

#### Heading level 4

Aenean ac tincidunt felis. Fusce eu arcu blandit, consectetur odio ullamcorper, maximus erat. Fusce aliquam sapien a commodo aliquet. Phasellus placerat sagittis euismod. Curabitur vitae est id nunc ornare scelerisque in vitae nisl. In non mi leo.

https://github.com/scottsweb/elva

### Tables

| Title  | Description |
| ------ | ----------- |
| Fuseu  | Aenean ac tincidunt felis. Fusce eu arcu blandit, consectetur odio ullamcorper. |
| Maxim  | Fusce eu arcu blandit, consectetur odio ullamcorper, maximus erat. |
| Odio   | Praesent quis sodales orci. |

Right aligned columns

| Title  | Description |
| -------| -----------:|
| Fuseu  | Aenean ac tincidunt felis. Fusce eu arcu blandit, consectetur odio ullamcorper. |
| Maxim  | Fusce eu arcu blandit, consectetur odio ullamcorper, maximus erat. |
| Odio   | Praesent quis sodales orci. |


<div class="shadow-wrapper">
<picture class="responsive-picture">
  <source type="image/jxl" srcset="
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_2150/v1740617585/g5lgbbp26ptg7og1dzyy.jxl 2150w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_2098/v1740617585/g5lgbbp26ptg7og1dzyy.jxl 2098w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_2039/v1740617585/g5lgbbp26ptg7og1dzyy.jxl 2039w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_1721/v1740617585/g5lgbbp26ptg7og1dzyy.jxl 1721w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_1490/v1740617585/g5lgbbp26ptg7og1dzyy.jxl 1490w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_1228/v1740617585/g5lgbbp26ptg7og1dzyy.jxl 1228w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_914/v1740617585/g5lgbbp26ptg7og1dzyy.jxl 914w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_636/v1740617585/g5lgbbp26ptg7og1dzyy.jxl 636w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_250/v1740617585/g5lgbbp26ptg7og1dzyy.jxl 250w
  " sizes="(min-width: 1200px) 1200px, 100vw"/>
  <source type="image/avif" srcset="
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_2150/v1740617585/g5lgbbp26ptg7og1dzyy.avif 2150w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_2098/v1740617585/g5lgbbp26ptg7og1dzyy.avif 2098w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_2039/v1740617585/g5lgbbp26ptg7og1dzyy.avif 2039w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_1721/v1740617585/g5lgbbp26ptg7og1dzyy.avif 1721w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_1490/v1740617585/g5lgbbp26ptg7og1dzyy.avif 1490w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_1228/v1740617585/g5lgbbp26ptg7og1dzyy.avif 1228w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_914/v1740617585/g5lgbbp26ptg7og1dzyy.avif 914w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_636/v1740617585/g5lgbbp26ptg7og1dzyy.avif 636w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_250/v1740617585/g5lgbbp26ptg7og1dzyy.avif 250w
  " sizes="(min-width: 1200px) 1200px, 100vw"/>
  <source type="image/jpeg" srcset="
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_2150/v1740617585/g5lgbbp26ptg7og1dzyy.jpeg 2150w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_2098/v1740617585/g5lgbbp26ptg7og1dzyy.jpeg 2098w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_2039/v1740617585/g5lgbbp26ptg7og1dzyy.jpeg 2039w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_1721/v1740617585/g5lgbbp26ptg7og1dzyy.jpeg 1721w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_1490/v1740617585/g5lgbbp26ptg7og1dzyy.jpeg 1490w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_1228/v1740617585/g5lgbbp26ptg7og1dzyy.jpeg 1228w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_914/v1740617585/g5lgbbp26ptg7og1dzyy.jpeg 914w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_636/v1740617585/g5lgbbp26ptg7og1dzyy.jpeg 636w,
    https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_250/v1740617585/g5lgbbp26ptg7og1dzyy.jpeg 250w
  " sizes="(min-width: 1200px) 1200px, 100vw"/>
  <img src="https://res.cloudinary.com/paulapplegate-com/image/upload/c_fill,g_auto/c_scale,w_250/v1740617585/g5lgbbp26ptg7og1dzyy.jxl" alt="Responsive Image" loading="lazy"></img>
</picture>
</div>
