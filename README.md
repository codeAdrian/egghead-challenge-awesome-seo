# Awesome SEO snippets

> “No website can stand without a strong backbone. And that backbone is technical SEO.” — Neil Patel

Getting the website SEO right from the start can be a challenge. With these snippets, you can set up a basic SEO markup in just few minutes and fine tune it to perfection afterwards.

These snippets are so awesome, they can:

- Add title, description, sharing tags and canonical links to HTML `<head>` tag
- Add boilerplate `robots.txt` rules
- Add boilerplate `sitemap.xml` rules
- Add Google Schema markup

## :scroll: HEAD tags (HTML & React support)

### Prefix

`seo:head`

Initializes basic SEO tags and social share tags (Facebook, Twitter, etc.). Use these snippet inside HTML `<head>` element.

Can be used in HTML and React (JSX and TSX) files.

### Result

![](https://res.cloudinary.com/adrianbece/image/upload/v1600845501/egghead/seo-head.png)

## :robot: robots.txt

### Prefix

`seo:robots`

Initializes basic robots.txt file. It sets up a basic "allow-all" rule. You only need to include hostname and path to a `sitemap.xml` file.

Can be used in plaintext files, but it should be used mainly in `robots.txt` file.

### Result

![](https://res.cloudinary.com/adrianbece/image/upload/v1600845501/egghead/seo-robots.png)

## :deciduous_tree: sitemap.xml

Initializes XML structure for sitemap. You can duplicate the `<loc>` line as much as you need and add your own URL.

Can be used in xml files, but it should be used mainly in `sitemap.xml`. 

### Prefix

`seo:sitemap`

### Result

![](https://res.cloudinary.com/adrianbece/image/upload/v1600845501/egghead/seo-sitemap.png)

## :building_construction: Google Schema (HTML & React support)

Adds some basic snippets for [Google Structured Data](https://developers.google.com/search/docs/data-types/article). These snippets allow Google to better understand the content of your website and display them in a special way on search results page. These need to be used inside HTML `<script>` tags.

Can be used in HTML and React (JSX and TSX) files.

### Prefix

`seo:schema:[schema-name]`

### Result

![](https://res.cloudinary.com/adrianbece/image/upload/v1600845501/egghead/seo-schema.png)
