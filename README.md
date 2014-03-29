# Joomla Isis template for Bootstrap 3   [![Analytics](https://ga-beacon.appspot.com/UA-48372917-1/joomla-bootstrap3-isis-template/readme)](https://github.com/igrigorik/ga-beacon)

This is Joomla!3 isis template but using Bootstrap 3 styles.

This template support both Bootstrap 2 & 3 syntax, by including the [Bootstrap 3 Adapter](https://github.com/asika32764/bootstrap3-adapter).

## Installation

[Download](https://github.com/asika32764/joomla-bootstrap3-isis-template/releases) package and install it in Joomla admin.

## Development

### Compiling CSS

If you want to change some less code, please install [NodeJS less](https://www.npmjs.org/package/less) first:

```
$ npm install -g less
```

Then cd to `{JOOMLA}/administrator/template/isis3/cli` and run:

```
$ lessc template.less ../css/template.css
```

Now you will get a compiled css file at `css/template.css`.

### LESS folders

```
less
  |
  |--- adapter    // Bootstrap3 adapter less files
  |
  |--- bootstrap2 // Old Joomla isis template less files
  |
  |--- bootstrap3 // Bootstrap 3 less files
```

## Screen shots

![admin-1](http://cl.ly/Ugpu/140328-0006.jpg)

![admin-2](http://cl.ly/UhDn/140328-0005.jpg)

