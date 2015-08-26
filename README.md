# ngTouchstart
A angular module to add directive `ng-touchstart`.

# How to use it
You must include the ngTouchstart dependency on your angular module:
````
var app = angular.module("demoapp", ["ngTouchstart"]);
````
Then in your HTML you can use:
````
<div ng-touchstart="someFunction($event)"></div>
````

# See also
- [ngTouch](https://github.com/nglar/ngTouch)
- [ngTouchmove](https://github.com/nglar/ngTouchmove)
- [ngTouchend](https://github.com/nglar/ngTouchend)