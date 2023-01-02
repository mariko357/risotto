# Changes:
- Improved SEO.
- Index page now displays last post.
- Changed language selection to be more user-friendly.
- Fixed logo pointing to main language in multilingual mode.
- Added pagination.
- 404 page can now be created with .md file.
- Added support for favicons.
- Added support for KaTeX

---

# Configuration:

## Language selection:
```
[params.avLangs]
  [params.avLangs.en]
    name = "English"
    text = "🇬🇧 This page is also available in"
    link = "English"
  [params.avLangs.ua]
    name = "Українська"
    text = "🇺🇦 Ця сторінка також доступна"
    link = "Українською"
```
**Will produce the following:**

![](https://i.imgur.com/RKTcjip.png)

![](https://i.imgur.com/dRJ3MZo.png)

## Pagination:
- `paginate` - Hugo's  built-in parameter. Number of posts per page.
- `params.adjLinks` - Number of adjent links to display in the page selector.

## SEO:
- `twitterCreator: "@yourname"` -  	@username for the website used in the card footer.
- `twitterSite: "@yourname"` - @username for the content creator / author.
- `twitterImage: "/path/to/img"` - Path to Twitter cards image.
- `ogImage: "/path/to/img"` - Path to OG image.
- `ogType: "article"` - Type of the content for OG.

[Twitter Cards](https://developer.twitter.com/en/docs/twitter-for-websites/cards/guides/getting-started)

[The Open Graph protocol](https://ogp.me/)

## KaTeX:
`katex: true` - to turn on KaTeX in front matter.