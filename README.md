# Chardin.js

**Simple overlay instructions for your apps.**

Chardin.js is a jQuery plugin that creates a simple overlay to display instructions on existent elements.

Based on [the original](http://heelhook.github.com/chardin.js/) by heelhook, this version was modified to use LESS and includes various fixes and improvements (i.e. performance, touch-support, old IE versions).

## Adding data for the instructions

Add the instructions to your elements:

`data-intro`: Text to show with the instructions  
`data-position`: (`left`, `top`, `right`, `bottom`), where to place the text with respect to the element

```HTML
<img src="img/chardin.png" data-intro="An awesome 18th-century painter, who found beauty in everyday, common things." data-position="right" />
```

## Running

Once you have your elements ready you can show instructions running

```Javascript
$('body').chardinJs('start')
```

If you would rather run ChardinJs confined to a particular container (instead of using the whole document) you can
change `body` to some other selector.

```Javascript
$('.container').chardinJs('start')
```

## Methods

### .chardinJs('start')

Start ChardinJs in the selector.

### .chardinJs('toggle')

Toggle ChardinJs.

### .chardinJs('stop')

Make your best guess. That's right! Stops ChardinJs in the selector.

## Events

### 'chardinJs:start'

Triggered when chardinJs is correctly started.

### 'chardinJs:stop'

Triggered when chardinJs is stopped.

## Original License

Copyright 2013 Pablo Fernandez

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

 [0]: https://github.com/heelhook/chardin.js/blob/master/chardinjs.css
 [1]: https://github.com/heelhook/chardin.js/blob/master/chardinjs.min.js
 [2]: https://github.com/heelhook
