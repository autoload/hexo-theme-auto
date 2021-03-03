# hexo-theme-auto
<h3>A modern stylish theme for Hexo.</h3>


### [Preview](https://autoload.github.io)

## Install

### For hexo < 5.0

``` shell
git clone https://github.com/Shen-Yu/hexo-theme-auto.git themes/auto
```

### For hexo >= 5.0

``` shell
npm i hexo-theme-ayer -S
```

- If this theme is newly installed, a `_config.auto.yml` file will be generated in the root directory after the installation is complete, and you can directly edit the `_config.auto.yml` file for configuration.
- If it is a theme upgrade, you can use the configuration method of hexo < 5.0, or you can move the original configuration file to the root directory and rename it to `_config.auto.yml`.

## Enable

Modify `theme` setting in `_config.yml` to `auto`

``` yml
theme: auto
```

## Update

``` bash
cd themes/auto
git pull
```

## Multi Language Support
zh-CN（Simplified Chinese） en（English） zh-TW（traditional Chinese） ja（Japanese） es（Spanish） de（German） fr（French） ru（Russian） ko（Korean） vi（Vietnamese） nl（Dutch） no（Norwegian） pt（Portuguese）

English is default languge, if you want to change, modify `language` option in `_config.yml` file in your blog's root folder.

## Configuration

``` yml
# Menu-Sidebar
menu:
  Home: /
  Archives: /archives
  Categories: /categories
  Tags: /tags
  About: /about

# Sidebar
sidebar: right
widgets:
- tag
- recent_posts
- category
- archive
```


---

<br/>

## License

MIT License

Copyright (c) 2020 David Wan

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


