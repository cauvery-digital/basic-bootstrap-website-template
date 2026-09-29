# basic-website-bootstrap-template

Below is a complete single-file index.html for a modern web development company using Bootstrap 5.3.x, with no custom CSS or JavaScript files required. It includes a responsive navbar, hero, services, about, technologies, process, portfolio, testimonials, CTA, and footer.

```html

```

Note: The Bootstrap CDN URLs above are intended to use Bootstrap 5.3.x. For production, use the official Bootstrap CDN snippet for the exact release you choose rather than relying on a copied integrity hash.
The page is structured so you can later split it into:

```
index.html
services.html
about.html
portfolio.html
contact.html
privacy-policy.html
terms.html
disclaimer.html
cookie-policy.html
```

and the sections can also be converted directly into a PHP/WordPress theme later.


## Meta Tag For noindex nofollow

To prevent a page from being indexed by search engines, add this inside the 

<head>:

```html
<meta name="robots" content="noindex, nofollow">
```

Recommended for your 404 pages

For 404-1.html and 404-2.html:

```html
<head>
    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <meta name="robots" content="noindex, nofollow">

    <title>Page Not Found | XYZ Web Solutions</title>
</head>
```

Other useful variations

No indexing, but allow links to be followed:

```html
<meta name="robots" content="noindex, follow">
```

Prevent indexing and prevent cached copies:

```html
<meta name="robots" content="noindex, nofollow, noarchive">
```

For a 404 page, I recommend:

```html
<meta name="robots" content="noindex, nofollow">
```

Also, the noindex meta tag is generally more appropriate than relying on robots.txt to keep a page out of search results.

