---
title: Getting started
date: 2023-08-06
---
<img data-src="https://res.cloudinary.com/paulapplegate-com/image/upload/c_limit,w_auto/dpr_auto,f_auto,q_auto/hillshire-farm-2_fx2mno.jpg" class="cld-responsive">

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
npm run build
```

To use [Front Matter CMS](https://frontmatter.codes/), install [VSCodium](https://vscodium.com/) or [Visual Studio Code](https://code.visualstudio.com/) and enable the extension (if it doesn't enable automatically). It will open each time you launch your project.
