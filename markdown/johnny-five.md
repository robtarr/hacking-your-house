
# johnny-five

![Johnny-Five](//johnny-five.io/img/static/johnny-five-fb.png) <!-- .element style="width: 800px;" -->

http://johnny-five.io

Johnny-Five intro based on slides from Mark West <!-- .element style="font-size: .5em;" -->
<br>http://creativecommons.org/licenses/by/4.0/


```
$ npm install johnny-five
```


# Make it blink!
```
const five = require('johnny-five');
const board = new five.Board();

board.on('ready', function() {
  const led = new five.Led(13);
  led.blink(500);
});
```
