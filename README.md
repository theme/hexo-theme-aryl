# Aryl

A simple theme for [Hexo].

- [Preview](http://)

## Installation

### Install

``` bash
$ git clone https://github.com/theme/hexo-theme-aryl.git themes/aryl
```

### Enable

Modify `theme` setting in `_config.yml` to `aryl`.
Then do `hexo g`
### Update

``` bash
cd themes/aryl
git pull
```

## Configuration

``` yml
# Header
menu:
  Home: /
  Archives: /archives
```

- **menu** - Navigation menu

## Features

### Fancybox

Landscape uses [Fancybox] to showcase your photos. You can use Markdown syntax or fancybox tag plugin to add your photos.

```
![img caption](img url)

{% fancybox img_url [img_thumbnail] [img_caption] %}
```

### Sidebar


## Development

### Requirements


[Hexo]: http://zespia.tw/hexo/
[Slate]: https://github.com/jasoncostello/slate
[Fancybox]: http://fancyapps.com/fancybox/
[Font Awesome]: http://fontawesome.io/
[favicon generator]: http://realfavicongenerator.net/
