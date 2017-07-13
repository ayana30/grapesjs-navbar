# GrapesJS Navbar

Simple navbar component for GrapesJS editor

[Demo](http://grapesjs.com/demo.html)
<br/>


## Summary

* Plugin name: `gjs-navbar`
* Components: `burger-menu`
* Blocks: `h-navbar`



## Options

* `blocks` Which blocks to add, default: `['h-navbar']` (all),
* `defaultStyle` Add default style to blocks, default: 1,
* `navbarClsPfx` Navbar class prefix, default: 'navbar',
* `labelNavbar` Navbar label, default: 'Navbar',
* `labelNavbarContainer` Navbar container label, default: 'Navbar Container',
* `labelMenu` Menu label, default: 'Navbar Menu',
* `labelMenuLink` Menu link label, default: 'Menu link',
* `labelBurger` Burger menu label, default: 'Burger',
* `labelBurgerLine` Burger line label, default: 'Burger Line',
* `labelNavbarBlock` Navbar Block label, default: 'Navbar',
* `labelNavbarCategory` Navbar Block Category label, default: 'Extra',
* `labelHome` Home label, default: 'Home',
* `labelAbout` About label, default: 'About',
* `labelContact` Contact label, default: 'Contact',



## Download

* `npm i grapesjs-navbar` or `yarn add grapesjs-navbar`



## Usage

```html
<link href="path/to/grapes.min.css" rel="stylesheet"/>
<script src="path/to/grapes.min.js"></script>
<script src="path/to/grapesjs-navbar.min.js"></script>

<div id="gjs"></div>

<script type="text/javascript">
  var editor = grapesjs.init({
      container : '#gjs',
      plugins: ['gjs-navbar'],
      pluginsOpts: {
        'gjs-navbar': {/* ...options */}
      }
  });
</script>
```



## Development

Clone the repository

```sh
$ git clone https://github.com/artf/grapesjs-navbar.git
$ cd grapesjs-navbar
```

Install it

```sh
$ npm i
```

Start the dev server

```sh
$ npm start
```

Build before the commit. This will also increase the patch level version of the package

```sh
$ npm run build
```



## License

BSD 3-Clause
