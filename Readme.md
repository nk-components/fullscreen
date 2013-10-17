
# fullscreen

  Fullscreen api

## Installation

    $ component install nk-components/fullscreen

## Example

```js
var fullscreen = require('fullscreen');

fullscreen.on('change', function(full){
  console.log('changed to %s', full ? 'fullscreen' : 'regular');
});

setTimeout(function(){
  fullscreen();
}, 2000);
```

## Events

 - "change" (fullscreen) boolean

## API

### fullscreen([el])

  Display fullscreen document or `el`.

### fullscreen.exit()

  Exit fullscreen mode.

### fullscreen.supported

  Check if fullscreen is supported.

### fullscreen.isFullscreen

  If the window is displayed in full screen mode or not.

## License

  MIT
