# One post a year

The one-post-a-year theme is a lightweight theme for [Hugo](https://gohugo.io), built with simplicity and speed in mind.

**[Demo site](https://jarv.github.io/one-post-a-year/)**

Are you starting a tech blog or already have one that has posts like this?

[<img width="600" alt="image" src="https://user-images.githubusercontent.com/749175/258733617-ba1f0276-45fa-4495-97cc-420257cdc4e5.png">](https://jarv.github.io/one-post-a-year/)

If so, then this might be the perfect theme for you!

So you might ask, what makes this theme so special?

- Some themes have summaries on the main page, you probably don't have time to write a long post anyway so there is none of that, just the links.
- Like article summaries, most Hugo themes have pagination for articles. With only one post per year it is pretty unlikely that it will ever be necessary so there is no pagination.
- Limited use of dates next to articles because it's probably not something you want to highlight.
- Only uses semantic html tags, so yeah, it is pretty modern.
- Maybe you like social media icons? Nothing like that here, so if you like that stuff this is probably not the theme for you.
- Uses [Atkinson Hyperlegible](https://en.wikipedia.org/wiki/Atkinson_Hyperlegible) as the main font.
- Light and Dark theme.
- RSS feed shows the full article.

Design inspired by [100-bytes-of-css-to-look-great-everywhere](https://dev.to/swyx/100-bytes-of-css-to-look-great-everywhere-19pd)

## Screenshots

<table>
<tr><td>⬜️ Light</td><td><img width="600" alt="image" src="https://github.com/jarv/one-post-a-year/assets/749175/b6fd30ae-b35a-40fe-8621-1a9c52b2a458"></td></tr>
<tr><td>⬛️ Dark</td><td><img width="600" alt="image" src="https://github.com/jarv/one-post-a-year/assets/749175/9016c2c3-778c-4ee5-85d4-98e65775017c"></td></tr>
<tr><td>📱Mobile</td><td><img width="300" alt="image" src="https://github.com/jarv/one-post-a-year/assets/749175/a8fa82b5-0bb4-4274-ac62-e6b0fecad987"></td></tr>
</table>


## Documentation

### Quick start using Hugo

```bash
hugo new site quickstart
cd quickstart
git init
git submodule add https://github.com/jarv/one-post-a-year.git themes/one-post-a-year
echo "theme = 'one-post-a-year'" >> hugo.toml
hugo server
```

### Code Highlighting

This theme includes a light and dark style for code highlighting.
To use it, add the following configuration to your `hugo.toml`.

```
[markup]
  defaultMarkdownHandler = 'goldmark'
  [markup.highlight]
    noClasses = false
    # https://xyproto.github.io/splash/docs/longer/all.html
    # Classes included in this theme for the 'github' and 'solarized-dark' styles
```

---
Why? I use this for my own site [jarv.org](https://jarv.org) which sometimes occasionally has more than one update in a year.

