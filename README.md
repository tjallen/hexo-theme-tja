# tja hexo theme

A simple portfolio-oriented theme for [Hexo](https://hexo.io/).

This was developed for use on my [portfolio](http://thomjamesallen.com), but I've attempted to make it generic and customiseable.

## Usage:
Get a Hexo site set up:
```
npm install -g hexo-cli
hexo init YOUR_SITE_NAME
```

Install required dependencies:

```
npm install --save hexo-renderer-scss
```

Then install the theme:
```
git clone https://github.com/tjallen/hexo-theme-tja themes/tja
cd themes/tja
npm install
```

Finally, enable the theme in your config.yml:
```
theme: tja
```
