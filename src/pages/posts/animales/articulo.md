---
layout: '@layouts/Layoutmd.astro'

title: Post ejemplo
autor: Manuel
desc: Lorem ipsum dolor sit amet consectetur adipisicing elit. In architecto ipsa sapiente laboriosam dolore inventore eos amet ipsam, consequatur magni ab aliquid maiores earum vero illum eius tempore nihil. Maiores!
image: https://cdn.pixabay.com/photo/2023/10/23/17/53/bird-8336583_640.jpg

---

# Post ejemplo
![imagen](https://cdn.pixabay.com/photo/2023/10/23/17/53/bird-8336583_640.jpg)

### autor: Manuel

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