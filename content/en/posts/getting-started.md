---
title: Getting started
date: 2023-08-07
---

<html>
  <head>
	<title>
	  Auto Responsive Images with Cloudinary
	</title>
	<script src="https://unpkg.com/cloudinary-core@latest/cloudinary-core-shrinkwrap.js" type="text/javascript">
	</script>
  </head>
  <body>
	<img data-src="https://res.cloudinary.com/paulapplegate-com/image/upload/c_limit,w_auto/f_auto,q_auto/v1744484129/responsive_images/maksym-mazur-Window_Girl-Christmas_crivce.jpg
	class="cld-responsive">
	<script type="text/javascript">
	  var cl = cloudinary.Cloudinary.new({
		cloud_name: "paulapplegate-com"
	  });
	  cl.responsive();
	</script>
  </body>
</html>


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
