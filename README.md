
simple-button-radios
==========
Simple button radios is a simple plugin for transform radio inputs into html buttons for css customize. High performance, keyboard support and preserve original input click/change events.

## Demos / Documentation
Demo and doc : [http://joelthorner.github.io/simple-button-radios/](http://joelthorner.github.io/simple-button-radios/)

## Getting Started

### Includes
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <link rel="stylesheet" href="path/to/simple-button-radios.css">
  </head>
  <body>

    <script src="path/to/jquery/3.x.x.min.js"></script>
    <script src="path/to/simple-button-radios.js"></script>
  </body>
</html>
```

### Js initialization
```javascript
//default options
$('input[type="radio"]').simpleButtonRadios({
  buttonClass: "sbr-default",
  checkedIcon : '<svg aria-hidden="true" xmlns="http://www.w3.org/2000/svg" viewBox="-725.53 115.775 1451.338 1451.338"><path d="M.141 376.731c-256.717 0-464.713 207.995-464.713 464.713 0 256.72 207.997 464.715 464.713 464.715 256.718 0 464.712-207.995 464.712-464.715 0-256.718-207.994-464.713-464.712-464.713z"/></svg>',
  nonCheckedIcon : '',
  // 'none' or 'input' or 'all'
  wrapContainer : 'none', 
  btnAttributes : {
    'type' : 'button'
  },
  onInit : null,
  onChange : null,
  changeCallback : null,
  onDestroy: null
});

//equivalent of
$('input[type="radio"]').simpleButtonRadios();
```

## Options and Methods
Options and Methods : [http://joelthorner.github.io/simple-button-radios/](http://joelthorner.github.io/simple-button-radios/)

## Checkbox plugin
[https://github.com/joelthorner/simple-button-checks](https://github.com/joelthorner/simple-button-checks)
