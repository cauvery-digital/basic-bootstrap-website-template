# System/status Pages with Page codes

For a professional business website, besides 404.html, restricted.html, and redirected.html, there are several useful system/status pages worth preparing.

Recommended page set

|Page|Purpose|
|--|---|
| 404.html| Page does not exist|
| 403.html| Access forbidden|
| 401.html| Authentication required|
| 500.html| Internal server error|
| 503.html| Website temporarily unavailable|
| maintenance.html| Planned maintenance|
| coming-soon.html| Website/section not launched yet|
| restricted.html| Access restricted|
| redirected.html| Page has moved|
| offline.html| Internet/server connection unavailable|
| session-expired.html| User session has expired|
| login-required.html| Login required|
| access-denied.html| User doesn't have required permission|
| form-error.html| Form submission failed|
| contact-success.html| Form submitted successfully|
| search-no-results.html| Search returned no results|

For your XYZ Web Solutions website, I would particularly create these first:

```
/
├── index.html
│
├── 404.html
├── 403.html
├── 401.html
├── 500.html
├── 503.html
│
├── maintenance.html
├── coming-soon.html
├── restricted.html
├── redirected.html
│
├── login-required.html
├── session-expired.html
├── access-denied.html
├── offline.html
│
├── form-error.html
├── contact-success.html
├── search-no-results.html
│
├── contact.html
├── privacy-policy.html
├── terms.html
├── disclaimer.html
├── cookie-policy.html
│
└── robots.txt
```

The most important ones

## 403.html — Forbidden

Used when the server understands the request but refuses access.

```
<h1>403</h1>
<h2>Access Forbidden</h2>
<p>You don't have permission to access this page.</p>
<a href="index.html">Back to Home</a>
```

## 401.html — Authentication Required

```
<h1>401</h1>
<h2>Authentication Required</h2>
<p>Please sign in to continue.</p>
<a href="login.html">Sign In</a>
```

## 500.html — Server Error

```
<h1>500</h1>
<h2>Something Went Wrong</h2>
<p>We're experiencing a temporary server problem.</p>
<a href="index.html">Back to Home</a>
```

## 503.html — Service Unavailable

```
<h1>503</h1>
<h2>Service Temporarily Unavailable</h2>
<p>We're working on the website. Please try again later.</p>
<a href="index.html">Back to Home</a>
```

## maintenance.html

```
<h1>🛠️</h1>
<h2>We'll Be Back Soon</h2>
<p>
    Our website is currently undergoing scheduled maintenance.
</p>
```

## SEO recommendation

For utility/error pages that shouldn't appear in Google, you can use:

```
<meta name="robots" content="noindex, nofollow">
```

For example:

```
<head>
    <meta charset="UTF-8">

    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">

    <meta name="robots"
          content="noindex, nofollow">

    <title>404 | Page Not Found</title>
</head>
```

One important distinction: 404, 403, 500, etc. should ideally be returned with their corresponding HTTP status codes, not just displayed as ordinary HTML pages. On Netlify, for example, 404.html can be used as the site's custom 404 page automatically.

## robots.txt file

For your business website, a good SEO-focused robots.txt should allow search engines to crawl your public pages while excluding utility/error pages, admin areas, and other non-search content.

```
# =========================================================
# robots.txt
# XYZ Web Solutions
# =========================================================

User-agent: *

# Allow public website content
Allow: /

# ---------------------------------------------------------
# Error / utility pages
# ---------------------------------------------------------
Disallow: /404.html
Disallow: /404-1.html
Disallow: /404-2.html
Disallow: /403.html
Disallow: /401.html
Disallow: /500.html
Disallow: /503.html
Disallow: /restricted.html
Disallow: /redirected.html
Disallow: /maintenance.html
Disallow: /coming-soon.html
Disallow: /offline.html
Disallow: /session-expired.html
Disallow: /login-required.html
Disallow: /access-denied.html
Disallow: /form-error.html
Disallow: /contact-success.html
Disallow: /search-no-results.html

# ---------------------------------------------------------
# Private / administrative areas
# ---------------------------------------------------------
Disallow: /admin/
Disallow: /administrator/
Disallow: /dashboard/
Disallow: /private/
Disallow: /account/
Disallow: /user/
Disallow: /login/
Disallow: /register/

# ---------------------------------------------------------
# Development / temporary files
# ---------------------------------------------------------
Disallow: /test/
Disallow: /tests/
Disallow: /temp/
Disallow: /tmp/
Disallow: /backup/
Disallow: /backups/

# ---------------------------------------------------------
# System / configuration files
# ---------------------------------------------------------
Disallow: /.git/
Disallow: /.github/
Disallow: /.env
Disallow: /config/
Disallow: /logs/

# ---------------------------------------------------------
# Sitemap
# ---------------------------------------------------------
Sitemap: https://www.example.com/sitemap.xml
```

Important: replace your domain

Change:

```
Sitemap: https://www.example.com/sitemap.xml
```

to your real domain, for example:

```
Sitemap: https://www.xyzwebsolutions.com/sitemap.xml
```

Recommended SEO structure

Your root directory could look like:

```
/
├── index.html
├── about.html
├── services.html
├── portfolio.html
├── contact.html
│
├── privacy-policy.html
├── terms.html
├── disclaimer.html
├── cookie-policy.html
│
├── 404.html
├── 403.html
├── 401.html
├── 500.html
├── 503.html
├── restricted.html
├── maintenance.html
├── contact-success.html
│
├── robots.txt
└── sitemap.xml
```

Important: robots.txt controls crawling; it is not a reliable way to prevent a URL from appearing in search results. For pages such as 404.html and contact-success.html, keep the noindex meta tag you added earlier as well.

For example:

```
<meta name="robots" content="noindex, nofollow">
```

For your public SEO pages (index.html, about.html, services.html, portfolio.html, etc.), don't add noindex.