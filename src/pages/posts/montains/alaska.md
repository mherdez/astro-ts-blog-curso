---
layout: '@layouts/Layoutmd.astro'

title: Alaska Montain
autor: Gregory Fly
desc: Lorem ipsum dolor sit amet consectetur adipisicing elit. In architecto ipsa sapiente laboriosam dolore inventore eos amet ipsam, consequatur magni ab aliquid maiores earum vero illum eius tempore nihil. Maiores!
image: https://cdn.pixabay.com/photo/2023/01/15/10/08/montain-7719834_640.jpg

---

# Alaska Montain
![imagen](https://cdn.pixabay.com/photo/2023/01/15/10/08/montain-7719834_640.jpg)

### autor: Gregory Fly

Lorem ipsum dolor sit amet consectetur adipisicing elit. In architecto ipsa sapiente laboriosam dolore inventore eos amet ipsam, consequatur magni ab aliquid maiores earum vero illum eius tempore nihil. Maiores!

Lorem ipsum dolor sit amet consectetur adipisicing elit. In architecto ipsa sapiente laboriosam dolore inventore eos amet ipsam, consequatur magni ab aliquid maiores earum vero illum eius tempore nihil. Maiores!

Lorem ipsum dolor sit amet consectetur adipisicing elit. In architecto ipsa sapiente laboriosam dolore inventore eos amet ipsam, consequatur magni ab aliquid maiores earum vero illum eius tempore nihil. Maiores!

~~~astro
---
const { frontmatter } = Astro.props;
---

<!doctype html>
<html lang="es">
	<head>
		<meta charset="UTF-8" />
		<meta name="description" content="Astro description" />
		<meta name="viewport" content="width=device-width" />
		<link rel="icon" type="image/svg+xml" href="/favicon.svg" />
		<meta name="generator" content={Astro.generator} />
		<title>Post</title>
	</head>
	<body>
		<slot />
	</body>
</html>

<style>
	html {
		font-family: roboto, sans-serif;
		background: #13151a;
    color: #fff;
	}
</style>

~~~