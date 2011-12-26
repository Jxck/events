# event.js

event.js is a port of the Node.js standard events library for the browser.
The original code and tests are from Node.js, and have been modified to be browser compatible.

You can use EventEmitter on **both sides** (server-side and client-side) if you use this.


## run the same code on both sides

You can use the standard events module when running your code on Node.js.
And your code will running on browser to.


## how to use

```html
<script src="event.js"></script>
<script src="path/to/your/code.js"></script>
```

## running test of this library

### browser

open ```test/index.html``` in your browser,
and see the console.
(it depends on [assert](https://github.com/Jxck/assert))

### node.js

```shell
> cd test
> ./runtest.sh
```

## license

MIT (same as Node.js)