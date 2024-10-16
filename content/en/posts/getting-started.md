---
title: Getting started
date: 2023-08-06
---

<img 
data-src="https://res.cloudinary.com/paulapplegate-com/image/upload/f_jxl,q_auto,g_auto/c_limit,w_auto/dpr_auto/e_shadow:75,x_20,y_20/kevin-wang-Weg7V2kMeyY-unsplash_afxelz.jxl" 
class="cld-responsive">


<img 
data-src="https://res.cloudinary.com/paulapplegate-com/image/upload/f_jxl,q_auto,g_auto/c_limit,w_auto/dpr_auto/e_shadow:75,x_20,y_20/guillaume-chabrol-qWXG372ZLDU-unsplash_spduxa.jxl" 
class="cld-responsive">



Make a directory and navigate to it:

``` bash
mkdir my-site-name
cd my-site-name
```

Clone the elva repository:

``` bash
git clone https://github.com/scottsweb/elva.git .
```

Install dependencies:

``` bash
npm install
```

Run Eleventy for site development. View the site at `http://localhost:8080`:

``` bash
npm run dev
```

Generate a production-ready build to the `dist` folder:

``` bash
npm run build:prod
```

You can set the environment variable `NODE_ENV=production` in your hosting control panel too and use `npm run build` as before.

To use [Front Matter CMS](https://frontmatter.codes/), install [VSCodium](https://vscodium.com/) or [Visual Studio Code](https://code.visualstudio.com/) and enable the extension (if it doesn't enable automatically). It will open each time you launch your project.
