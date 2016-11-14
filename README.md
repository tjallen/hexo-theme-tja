# tja hexo theme

A simple portfolio-oriented theme for [Hexo](https://hexo.io/).

This is being developed for use on my [portfolio](http://thomjamesallen.com), but I'll attempt to make it as generic/customiseable as possible.

## Usage:
Get a Hexo site set up:
```
npm install -g hexo-cli
hexo init <directory>
```

Then install the theme:
```
git clone https://github.com/tjallen/hexo-theme-tja themes/tja
cd themes/tja
npm install
```

Install required dependencies:

```
cd <directory>
npm install hexo-renderer-scss
```

Finally, enable the theme in your config.yml:
```
theme: tja
```
