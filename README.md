# apolloX

Modern and minimalistic blog theme powered by [Zola](getzola.org). See a live preview [here](https://jarp0l.github.io/apolloX).


Forked from [apollo](https://github.com/not-matthias/apollo), and modified/extended with the inspiration and ideas from [Pascal's scribbles](https://deterministic.space/) and [xypnox's xyBlag](https://www.xypnox.com/blag/) theme.

*Modified specifically for my own blog at https://jarp0l.github.io.*

apolloX: apollo-extended

apollo:

<sub><sup>Named after the greek god of knowledge, wisdom and intellect</sup></sub>

<details open>
  <summary>Dark theme</summary>
  
  ![blog-dark](apolloX-dark.png)
</details>

<details>
  <summary>Light theme</summary>
  
![blog-light](apolloX-light.png)
</details>

---

## Features

- [X] Pagination
- [X] Themes (light, dark, auto)
- [x] Social Links
- [x] Tags
- [ ] Navbar menu for smaller screen devices
- [ ] Search
- [ ] Categories

#### Removed:
~~-[X] Analytics using [GoatCounter](https://www.goatcounter.com/)~~


## Installation

1. Download the theme
```
git submodule add https://github.com/jarp0l/apolloX themes/apolloX
```

2. Add `theme = "apolloX"` to your `config.toml`
3. Copy the example content

```
cp -r themes/apolloX/content/* content
```

## Options

### Additional stylesheets

You can add stylesheets to override the theme:

```toml
[extra]
stylesheets = [
    "override.css",
    "something_else.css"
]
```

These filenames are relative to the root of the site. In this example, the two CSS files would be in the `static` folder.

## References

`apollo` theme is based on [archie-zola](https://github.com/XXXMrG/archie-zola/).

`apolloX` theme is based on [apollo](https://github.com/not-matthias/apollo), [Pascal's scribbles theme](https://deterministic.space/)  ([code](https://github.com/killercup/jekyll-theme-scribbles)) and [xypnox's xyBlag theme](https://www.xypnox.com/blag/) ([code](https://github.com/xypnox/blag)).

