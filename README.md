# KC FAB

KC FAB is a jQuery plugin to create materialize floating action button easily.

### Version
1.0

### DEMO

- [jsfriddle demo]
- Thank you for [jqueryscript.net] to provide another usage [example] for my plugin


### How to use

First of all, you need to have a DOM element to hold action buttons:
e.g
```html
<div class="kc_fab_wrapper" ></div>
```
Then in your script, calling the kc_fab on your DOM element.
You can pass in an object array as option to tell the plugin the buttons style and the anchors' link.
```js
var links = [
                {   /* The first object will be the main button */
                    "bgcolor":"red",
                    "icon":"+"
                },
                /* Following are the hidden button list */
                {
                    "url":"http://www.example.com",
                    "bgcolor":"red",
                    "color":"#fffff",
                    "icon":"<i class='fa fa-phone'></i>",
                    "target":"_blank"
                },
                {
                    "url":"http://www.example.com",
                    "bgcolor":"black",
                    "color":"white",
                    "icon":"<i class='fa fa-music'></i>"
                }
            ]
$('.kc_fab_wrapper').kc_fab(links);
```

### Install by [Bower]
```nodejs
bower install kc_fab
```

License
----

Copyright (c) 2015 Mark Luk Licensed under the [MIT license].

[jsfriddle demo]: https://jsfiddle.net/katrinluk/8wxho9cw/3/
[jqueryscript.net]: http://www.jqueryscript.net/menu/Material-Design-Floating-Action-Button-with-jQuery-KC-FAB.html
[example]: http://www.jqueryscript.net/demo/Material-Design-Floating-Action-Button-with-jQuery-KC-FAB/
[Bower]: http://libraries.io/bower/kc_fab
[MIT license]: https://github.com/katrincwl/kc_fab/blob/master/LICENSE